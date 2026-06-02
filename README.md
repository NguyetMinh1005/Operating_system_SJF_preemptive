# Operating_system_SJF_preemptive
Đồ án môn Hệ điều hành - Nhóm [9]. Cài đặt và mô phỏng giải thuật lập lịch CPU SJF Preemptive (SRTF)
⚠️** ĐỌC PHẦN NÀY TRƯỚC KHI LÀM: HƯỚNG DẪN GIT CHI TIẾT**
Để tránh mất code và xung đột sát deadline, TẤT CẢ THÀNH VIÊN team Code phải làm theo đúng 5 bước sau đây. KHÔNG push code trực tiếp vào nhánh main và develop.
_Bước 1_: Lấy dự án về máy (Chỉ làm 1 lần duy nhất)
- Mở Terminal (hoặc Git Bash / Terminal trong VS Code) tại thư mục bạn muốn lưu dự án, gõ lệnh:
Bash
git clone <Link_Github_Của_Dự_Án_Vừa_Tạo>
cd Operating_system_SJF_preemptive

_Bước 2_: Cập nhật & Tạo nhánh làm việc riêng (Làm mỗi khi bắt đầu code)
- Luôn lấy dữ liệu mới nhất từ nhánh develop trước khi làm việc:
Bash
git checkout develop
git pull origin develop

- Tạo nhánh mới cho nhiệm vụ của bạn (Xem tên nhánh ở bảng phân công phía dưới) và chuyển sang nhánh đó:
Bash
git checkout -b <tên_nhánh_của_bạn>
Ví dụ: git checkout -b feature/gui

_Bước 3_: Lưu lại code sau khi làm xong
- Sau khi code xong và test chạy ổn trên máy cá nhân, gõ lệnh:
Bash
# Thêm tất cả file code vừa thay đổi vào Git
git add .

# Ghi chú công việc vừa làm (Ghi tiếng Việt không dấu hoặc tiếng Anh)
git commit -m "Hoan thanh logic tinh toan Waiting Time"

_Bước 4_: Đẩy nhánh của bạn lên GitHub
- Đưa nhánh làm việc của bạn lên kho lưu trữ chung:
Bash
git push origin <tên_nhánh_của_bạn>

_Bước 5_: Tạo Pull Request (Yêu cầu gộp code)
- Lên trang GitHub của dự án.
- Nhấn vào nút màu xanh/vàng "Compare & pull request".
- Cấu hình gộp nhánh
    + Base (Nhận): Chọn nhánh develop.
    + Compare (Gửi): Chọn nhánh feature/... của bạn.
- Viết mô tả ngắn gọn bạn đã upload/sửa những gì.
  VD: "Add file code <tên file code>"
- Nhấn Create pull request và tag Leader vào kiểm tra, duyệt code.

📁 QUY ĐỊNH NỘP FILE
Kho GitHub này CHỈ DÀNH CHO CODE.
✅ Những file nộp lên Git:
1. File mã nguồn Python: .py
2. File cấu hình môi trường: requirements.txt
3. File dữ liệu test: .json, .csv (nếu có).

❌ Những file TUYỆT ĐỐI KHÔNG đẩy lên Git:
1. File tài liệu: .docx (Word), .xlsx (Excel), .pptx (PowerPoint).
2. File đóng gói: .exe
3. Thư mục môi trường ảo và bộ nhớ đệm: venv/, env/, __pycache__/

👉 Lưu ý đối với Team Nội Dung & Slide (TV2, TV3, TV8): Các bạn không cần thao tác với GitHub. Khi hoàn thành báo cáo Word, bảng Excel so sánh hoặc Slide PPT, vui lòng gửi trực tiếp file qua Zalo Group hoặc upload lên thư mục Google Drive chung của nhóm để Leader tổng hợp.
