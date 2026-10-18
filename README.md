# Thực hành CSS: flex-wrap

## Nội dung
Trang thực hành minh họa bốn giá trị của `flex-wrap`:
- `nowrap`: giữ các Flex Item trên một dòng.
- `wrap`: cho phép các item xuống dòng.
- `wrap-reverse`: cho phép nhiều dòng và đảo hướng của cross axis.
- `initial`: trả thuộc tính về giá trị ban đầu, tương đương `nowrap`.

## Chạy bài
1. Giải nén thư mục nếu tải file ZIP.
2. Mở `index.html` bằng trình duyệt.
3. Dùng danh sách lựa chọn để đổi giá trị `flex-wrap` và quan sát sáu item.
4. Trên điện thoại, khung demo có thể cuộn ngang khi dùng `nowrap` hoặc `initial`.

## Cấu trúc
- `index.html`: trang thực hành tương tác.
- `style.css`: định dạng giao diện và Flexbox.
- `screenshots/`: ảnh chụp từng trạng thái và ảnh giao diện mobile.

## Ghi chú
Bản demo dùng `flex: 0 0 180px` cho item để tránh co nhỏ, giúp sự khác nhau giữa `nowrap` và `wrap` dễ quan sát hơn. Chiều rộng vùng flex là 600px trên desktop; khung ngoài có thể cuộn ngang khi nội dung vượt khung.
