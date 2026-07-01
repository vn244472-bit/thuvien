# 📚 Hệ thống Quản lý Thư viện CLI (C++17)

Đồ án phân tích cấu trúc dữ liệu ứng dụng thực tế để quản lý sách, độc giả và quy trình mượn trả tự động hóa. Đảm bảo viết thủ công các node liên kết không lạm dụng STL Container.

## 🛠️ Cấu trúc dữ liệu áp dụng
* **Binary Search Tree (BST):** Lưu trữ danh mục sách giúp tối ưu hóa việc tìm kiếm từ dữ liệu lớn chỉ mất $O(\log n)$.
* **Queue (Hàng đợi đơn):** Lưu hàng chờ của độc giả khi một đầu sách mong muốn đã bị mượn hết sạch.
* **Stack (Ngăn xếp):** Theo vết lịch sử hành vi để cung cấp tính năng Undo (Hoàn tác).
* **Linked List:** Danh sách liên kết tuyến tính giúp quản lý danh sách độc giả động một cách mềm dẻo.

## 🚀 Hướng dẫn Biên dịch & Chạy ứng dụng

### Biên dịch Chương trình chính:
Chạy lệnh sau trên terminal/cmd tại thư mục `src/`:
```bash
g++ -std=c++17 main.cpp functions.cpp -o library_app
