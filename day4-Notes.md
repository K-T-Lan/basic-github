## Phân biệt Git với GitHub
- chạy trên app - web
- Quản lý phiên bản - Lưu trữ và chia sẻ
- Dùng terminal - Có giao diện
## Cách kết nối repo với vs code của mình
- ... -> terminal -> new terminal -> dấu + -> Git Bash -> nhập git clone "linh HTTTPS" ở ô xanh dương của "Code" -> enter -> repo trở thành một thư mục trong máy bạn -> Mở file và sửa -> ctrl S
- Sau khi lưu thay đổi trên VS Code -> thao tác Terminal: 
+ git status: file đỏ = chưa commit
-> git add .
-> git commit -m"add..."
-> git push origin main (đẩu code lên github)
## Quá trình đẩy code vào GitHub: luồng chuẩn
- VS Code (trên máy) -> git ad . -> git commit -m".." ->  push branch -> GitHub tạo Full Request -> Merge vào nhánh main
- Tạo nhánh: git switch -c "namebranch" or checkout -b
- Base: kho và compare: hàng gửi vào kho
