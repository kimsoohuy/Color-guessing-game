# Game Nhận Diện Màu Sắc với Cấp Độ và Lưu Điểm

## Mô tả

Đây là một trò chơi đơn giản giúp người chơi rèn luyện khả năng nhận diện và phân biệt các màu sắc tương tự. Trò chơi sẽ hiển thị một màu trong `colorBox` và người chơi phải chọn màu đúng trong các lựa chọn. Trò chơi cũng có các cấp độ khó tăng dần và lưu trữ điểm cao nhất của người chơi.

## Các thành phần chính

- **Giao diện đăng nhập:** Người chơi nhập tên để bắt đầu trò chơi.
- **Màn chơi chính:** Hiển thị ô màu `colorBox`, các lựa chọn màu, điểm và cấp độ hiện tại.
- **Bảng điểm cao:** Lưu trữ và hiển thị 5 điểm cao nhất.

## Cấu trúc

- **HTML:** Cấu trúc của trang web, bao gồm các phần chính là phần đăng nhập, phần chơi chính, và bảng điểm cao.
- **CSS:** Định dạng nút, ô nhập tên, và các phần khác, cùng với hiệu ứng hover.
- **JavaScript:** Chứa logic trò chơi, bao gồm các chức năng bắt đầu trò chơi, tạo màu tương tự, kiểm tra đáp án, và lưu điểm.

## Cách chơi

1. Người chơi nhập tên vào ô đăng nhập và nhấn nút **Bắt đầu**.
2. Ở mỗi vòng chơi, trò chơi sẽ hiển thị một màu trong `colorBox`.
3. Người chơi chọn một trong các nút màu bên dưới `colorBox` để đoán màu đúng.
4. Nếu chọn đúng, người chơi sẽ được cộng điểm và chuyển sang vòng tiếp theo. Sau mỗi 5 điểm, cấp độ sẽ tăng lên và màu sắc sẽ khó phân biệt hơn.
5. Nếu chọn sai, trò chơi kết thúc và lưu lại điểm nếu điểm của người chơi nằm trong top 5.

## Tính năng

- **Điều chỉnh độ khó tự động:** Độ khó tăng dần khi người chơi đạt nhiều điểm, với các màu sắc ngày càng khó phân biệt.
- **Lưu điểm cao:** Sử dụng `localStorage` để lưu 5 điểm cao nhất của người chơi và hiển thị chúng trong bảng điểm.
- **Thiết lập lại trò chơi:** Trò chơi sẽ khởi động lại nếu người chơi chọn sai hoặc chọn **Chơi lại**.

## Hướng dẫn triển khai

1. Lưu tệp HTML trên máy tính của bạn.
2. Mở tệp bằng trình duyệt bất kỳ.
3. Trò chơi có thể được chơi offline mà không cần kết nối mạng.

## Ghi chú kỹ thuật

- Trò chơi sử dụng `localStorage` để lưu dữ liệu bảng điểm cao, vì vậy dữ liệu này sẽ không bị mất khi người dùng làm mới trang hoặc thoát khỏi trang.

## Mở rộng

- Thêm các tính năng bổ sung như âm thanh khi chọn đúng hoặc sai.
- Tích hợp thêm các loại màu sắc mới hoặc các chế độ chơi để tăng tính hấp dẫn.
- Tùy chọn chia sẻ điểm số lên mạng xã hội.
  
Chúc bạn chơi vui vẻ và đạt điểm cao!
