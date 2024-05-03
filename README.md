# Usage Instructions
1. cách clone 1 repository từ github về máy
    "git clone https://github.com/user/repo.git"
    - "git pull origin master" cập nhật những thay đổi ở branch "master".
2. các bước đẩy 1 dự án lên repository
    - đầu tiên "git init" để tạo 1 repo Git mới.
    - sau đó "git add ." để thêm tất cả các thay đổi của thư mục hiện tại vào repo.
    - "git commit -m "Commit message" sử dụng để lưu các thay đổi đã được thêm ở trên với thông điệp "Commit message".
    - "git push origin master" đẩy các thay đổi đã commit lên nhánh "master"
3. ngoài ra còn có các câu lệnh khác như
    - "git branch branch-name" tạo một nhánh mới với "branch-name" là tên nhánh của bạn.
    - "git checkout branch-name" chuyển đổi sang 1 nhanh khác.
    - "git merge branch-name" merge một nhánh vào nhánh hiện tại.
    - "git status" xem trạng thái của repo.
    - "git log" xem lịch sử commit. 