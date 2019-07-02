CÁCH LẤY ACCESS TOKEN
Truy cập Link này:
https://b-graph.facebook.com/auth/login?email={tai-khoan}&method=POST&password={mat-khau}&access_token=350685531728%257C62f8ce9f74b12f84c123cc23437a4a32
Nhớ thay đoạn: {tai-khoan} và {mat-khau} thành tài khoản và mật khẩu Facebook tương ứng nhé. Access Token là đoạn nằm trong ngoặc kép sau "access_token" có dạng EAAAAU....
CÁCH XÓA ACCESS TOKEN SAU KHI SỬ DỤNG
Truy cập Link này:
https://api.facebook.com/restserver.php?method=auth.expireSession&format=json&access_token={access-token}
Nhớ thay đoạn {access-token} thành Access Token cần xóa nhé.
