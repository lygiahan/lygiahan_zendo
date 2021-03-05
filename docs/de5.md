## Tiêu đề : xây dựng một trang collection mới*
Giới thiệu :

## Yêu cầu 1

- setting ảnh trong admin hiển thị ra ngoài trang web

## Yêu cầu 2

### Tính năng 1:
* Thiết lập menu, mỗi menu item trỏ về collection tương ứng
* Dùng liquid để get menu --> Search linklist trong cheatsheet liquid để biết cách sử dụng: http://cheat.markdunkley.com/
* Lúc này sẽ lấy được title và link menu tương ứng với collection được thiết lập (link.title, link.url)

* Ưu điểm: Không bị giới hạn nhóm sản phẩm được thiết lập, khi cần tạo thêm tab collection thì chỉ cần vào phần thiết lập menu, tạo thêm menu là xong
* Nhược điểm: Tốn nhiều thời gian để triển khai. Chỉ phù hợp với nhu cầu thực tế cần tạo nhiều collection

### Tính năng 2:

* filter các loại sản phẩm gửi lên api, đợi api trả về rồi get ra ngoài trang chủ, nhưng chưa get ra ngoài được tạm thời để đó

### Tính năng 3:

* Để lấy hình ảnh của variant, search variant.image trong checklist http://cheat.markdunkley.com/


### Tính năng 4:

* Tra google....