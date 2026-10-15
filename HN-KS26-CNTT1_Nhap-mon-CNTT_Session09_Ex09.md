**Yêu cầu đầu ra**

**_Phần 1: Phân tích và thiết kế giải pháp_**

**1.** Phân tích bài toán (I/O): Xác định rõ Dữ liệu đầu vào (nội dung CLB cần trình bày) và Kết quả mong đợi (file README.md render ra trang hiển thị như thế nào).
-   Đầu vào: Tên CLB, mô tả, danh sách các ban, thông tin liên hệ, hướng dẫn gia nhập, checklist nhiệm vụ và các quy định.
    
-   Đầu ra: File README.md hiển thị trên GitHub với tiêu đề phân cấp rõ ràng, bảng thông tin, danh sách bước, checklist và phần lưu ý dễ đọc.

**2.** Đề xuất giải pháp: Mô tả ngắn gọn cách bạn tổ chức 5 phần trong file, cú pháp nào dùng cho phần nào.
-   Phần 1: Dùng Heading `#`, `##` và chữ in đậm để giới thiệu CLB.
    
-   Phần 2: Dùng bảng Markdown và link `mailto:` để liên hệ.
    
-   Phần 3: Dùng Ordered List và Code Block để hướng dẫn các lệnh Git.
    
-   Phần 4: Dùng Task List để theo dõi nhiệm vụ.
    
-   Phần 5: Dùng Blockquote để nhấn mạnh deadline và quy tắc.



**3.** Thiết kế các bước: Gạch đầu dòng tuần tự các thao tác bạn sẽ làm để tạo file (không cần mô tả từng ký tự, chỉ cần mô tả logic).
-   Bước 1: Tạo file `README.md` trong thư mục dự án.
    
-   Bước 2: Viết nội dung theo 5 phần đã xác định.
    
-   Bước 3: Kiểm tra cú pháp Markdown và các đường link.
    
-   Bước 4: Xem trước giao diện hiển thị trên GitHub.
    
-   Bước 5: Commit và push file lên repository của CLB

**_Phần 2: Triển khai và chống lỗi_**

**4.** Viết source file [README.md](http://README.md) hoàn chỉnh với đầy đủ 5 phần theo yêu cầu nghiệp vụ. Nội dung có thể tự đặt tên CLB và thành viên.
## CLB Lập trình PTIT

Chào mừng bạn đến với **CLB Lập trình PTIT**, nơi các thành viên cùng học hỏi, thực hành và phát triển kỹ năng lập trình.

### 1. Giới thiệu CLB

CLB hướng đến việc xây dựng cộng đồng lập trình viên năng động, hỗ trợ thành viên mới và thực hiện các dự án thực tế.

**Điểm nổi bật:** Học tập cùng nhau, chia sẻ kiến thức và phát triển kỹ năng làm việc nhóm.

### 2. Danh sách Ban

Tên Ban|Trưởng Ban|Liên hệ
|-|-|-
Ban Kỹ thuật|Mai Việt Dũng|[dung@ptit.edu.vn](mailto:dung@ptit.edu.vn)
Ban Truyền thông|Trần Thu Hà|[ha@ptit.edu.vn](mailto:ha@ptit.edu.vn)
Ban Nhân sự|Nguyễn Quang Huỳnh|[nqh@ptit.edu.vn](mailto:nqh@ptit.edu.vn)

## 3. Hướng dẫn gia nhập

1.  Tạo tài khoản GitHub và gửi thông tin cho Ban Kỹ thuật.
    
2.  Cài đặt Git trên máy tính.
    
3.  Sao chép repository của CLB về máy bằng lệnh:
    
    ```bash
    git clone https://github.com/ptit-club/club-wiki.git
    
    ```
    
4.  Di chuyển vào thư mục dự án:
    
    ```bash
    cd club-wiki
    
    ```
    
5.  Tạo nhánh mới để thực hiện thay đổi:
    
    ```bash
    git checkout -b ten-nhanh-moi
    
    ```
    

## 4. Checklist nhiệm vụ thành viên mới

- [x]  Đọc nội quy CLB.
    
- [x]  Tham gia nhóm trao đổi của CLB.
    
- [ ] Hoàn thiện thông tin thành viên.
    
-  [ ] Cài đặt Git và VS Code.
    
-  [ ] Đọc hướng dẫn đóng góp mã nguồn.
    
-  [ ] Tham gia buổi sinh hoạt đầu tiên.
    

## 5. Lưu ý quan trọng

> **Deadline:** Thành viên mới cần hoàn thành các nhiệm vụ trong tuần đầu tiên kể từ ngày gia nhập.
> 
> **Quy tắc ứng xử:** Tôn trọng mọi thành viên, trao đổi lịch sự, hỗ trợ nhau học tập và không tự ý sửa hoặc xóa dữ liệu chung khi chưa được phép.

**5.** Trả lời 2 bẫy dữ liệu đã nêu ở phần ràng buộc.
Bẫy 1: Email phải là link bấm được

Dùng cú pháp:

```
[dung@ptit.edu.vn](mailto:dung@ptit.edu.vn)
```

Khi bấm vào, hệ thống sẽ mở ứng dụng email mặc định để soạn thư gửi đến địa chỉ đó. Nếu chỉ ghi địa chỉ email thông thường thì chưa chắc tạo được liên kết gửi thư như mong muốn.

Bẫy 2: Thành viên paste URL không hợp lệ

Nếu URL sai hoặc không tồn tại, liên kết có thể dẫn đến trang lỗi hoặc trang không tìm thấy. Nếu URL không đúng cú pháp Markdown, nó có thể chỉ hiển thị dưới dạng văn bản thay vì liên kết bấm được.
