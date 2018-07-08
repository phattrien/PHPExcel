# PHPExcel-Plugin-Msexcel-Shops
Plugin thêm tính năng Nhập/xuất sản phẩm từ MS Excel cho module shops (NukeViet 4)

## Hướng dẫn cài đặt
### Cài đặt PHPEXCEL
Để cài đặt thư viện PHPExcel, bạn thực hiện một trong hai phương án sau đây

**Phương án 1: Cài đặt PHPExcel qua composer (khuyến khích dùng)**

Hãy bỏ qua nếu bạn không hiểu composer là gì
```
composer require phpoffice/phpexcel
```
 

**Phương án 2: Cài đặt qua mã nguồn**
- Truy cập https://github.com/PHPOffice/PHPExcel/releases và tải về phiên bản mới nhất
- Giải nén, copy thư mục `Classes` vào `includes` (nukeviet)
- Đổi tên thư mục `Classes` vừa copy thành `class`. Chúng ta sẽ có `includes/class/PHPExcel.php`

### Cài đặt gói plugin
- Downnload giải nén ba thư mục `includes`, `modules` và `themes` (chỉ ba thư mục này) vào thư mục tương ứng
- **Truy cập ACP / Sản phẩm**. Lúc này xẽ xuất hiện thêm menu **Nhập / xuất Excel**

## Thông tin khác
- **Kho ứng dụng:** https://github.com/NukeVietCMS/
- **Diễn đàn hỗ trợ:** https://mynukeviet.net/hoi-dap/Ho-tro-su-dung-NukeViet/Ho-tro-plugin-nhap-xuat-san-pham-qua-Excel-259/
