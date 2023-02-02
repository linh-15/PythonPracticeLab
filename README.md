- Clone git repository về

```
git clone https://github.com/oguriedu/PythonPracticeLab.git
```

- Tạo nhánh mới từ `main` cho bài tập trong lab theo format: `<tên-lớp-msv>` - đây sẽ là **nhánh chính** của bạn. Ví dụ:

```
git checkout -b NgoQuangDai-DHTI10A1HN-1122334455
```

- Push nhánh chính của bạn lên remote repository. Ví dụ:

```
git push origin NgoQuangDai-DHTI10A1HN-1122334455
```

- Tạo nhánh mới theo lab mà bạn đang làm từ nhánh chính. Ví dụ:

```
git checkout -b NgoQuangDai-DHTI10A1HN-1122334455/lab1
```

- Làm việc trên nhánh theo lab, `add` thay đổi, `commit` rồi push lên remote repository

```
git add .

git commit -m "thuc hanh lab1 bai1/bai2/bai3"

git push origin NgoQuangDai-DHTI10A1HN-1122334455/lab1
```

- Tạo Pull request merge vào **nhánh chính** của bạn. Ghi rõ nội dung của thay đổi ở Pull Request Title.

- Thầy và các bạn cùng khóa sẽ review code và comment góp ý. **Comment "Done"** sau khi đã fix xong comment.

- Trường hợp có thay đổi như fix comment, update source code trên feature hiện tại, commit rồi push tiếp lên, không tạo pull request mới.

- Học thêm về git:
  - https://git-scm.com/book/en/v2
  - https://learngitbranching.js.org/?locale=vi