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
- Tạo nhánh: git switch -c "namebranch" or checkout -b -> git push -u origin namebranch (để ghi nhớ tên newbranch mới cho lần use sau)
- Chuyển sang nhành đã tồn tại: git checkout/switch namebranch
## Về Merge và Full Request
- Full Request: xin cho phép nhập vô main
- Merge: lệnh cho phép nhập vô main
- lức đầu mk đẩy commit lên branch cá nhân -> full request vào main -> Merge để đẩy vô main
- Full Request: Base: kho và compare: hàng gửi vào kho
