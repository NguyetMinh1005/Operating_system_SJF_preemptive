# Operating_system_SJF_preemptive
Chào mọi người! Đây là tài liệu hướng dẫn quy trình làm việc nhóm trên GitHub. Dự án của chúng ta code bằng Python.
Để tránh mất code và đè code của nhau, TUYỆT ĐỐI KHÔNG CODE VÀ PUSH TRỰC TIẾP LÊN NHÁNH main HOẶC develop. Mỗi người sẽ làm việc trên một nhánh (branch) đã được tạo sẵn.

---
PHẦN 1: THAO TÁC CHUNG (AI CŨNG PHẢI LÀM LẦN ĐẦU)
Đây là thao tác để tải toàn bộ dự án từ GitHub về máy tính cá nhân của bạn. Chỉ làm 1 lần duy nhất lúc mới bắt đầu.

Bước 1: Mở Terminal (hoặc Git Bash, Terminal trong VS Code) tại thư mục bạn muốn lưu dự án.
Bước 2: Gõ lệnh sau để tải code về:

Bash
git clone https://github.com/NguyetMinh1005/Operating_system_SJF_preemptive.git
Bước 3: Di chuyển vào trong thư mục dự án vừa tải:

Bash
cd Operating_system_SJF_preemptive

PHẦN 2: HƯỚNG DẪN DÀNH CHO TỪNG NHIỆM VỤ
Leader đã tạo sẵn 3 nhánh riêng cho 3 người. Hãy tìm đến đúng tên của mình, chuyển sang nhánh đó và bắt đầu code.

🧑‍💻 Người 1: Xây dựng cấu trúc dữ liệu (Data Model)
Nhiệm vụ: Viết class Process trong file process.py.
Thao tác thực hiện:

Chuyển vào nhánh làm việc của bạn:

Bash
git checkout feature/data-model
Mở VS Code, tạo file process.py và bắt đầu viết code.

Sau khi code xong (hoặc xong một phần muốn lưu lại), gõ lần lượt 3 lệnh sau để đẩy lên GitHub:

Bash
git add .
git commit -m "Hoàn thành class Process" 
git push origin feature/data-model
🧑‍💻 Người 2: Viết logic thuật toán (Core Algorithm)
Nhiệm vụ: Viết hàm lập lịch SJF Preemptive trong file scheduler.py.
Thao tác thực hiện:

Chuyển vào nhánh làm việc của bạn:

Bash
git checkout feature/core-algorithm
Mở VS Code, tạo file scheduler.py và bắt đầu viết code (có thể thỏa thuận trước với Người 1 về các thuộc tính của Process để code song song).

Sau khi code xong, gõ lần lượt 3 lệnh sau để đẩy lên GitHub:

Bash
git add .
git commit -m "Hoàn thành thuật toán SJF" 
git push origin feature/core-algorithm
🧑‍💻 Người 3: Xử lý dữ liệu & Test (Utils & Testing)
Nhiệm vụ: Viết file utils.py (nhập/xuất dữ liệu dạng bảng) và main.py (chạy 3 bộ Test Case).
Thao tác thực hiện:

Chuyển vào nhánh làm việc của bạn:

Bash
git checkout feature/utils-test
Mở VS Code, tạo các file cần thiết và bắt đầu viết code.

Sau khi test xong, gõ lần lượt 3 lệnh sau để đẩy lên GitHub:

Bash
git add .
git commit -m "Hoàn thành format bảng và test cases" 
git push origin feature/utils-test
PHẦN 3: CÁCH NỘP CODE (TẠO PULL REQUEST)
Khi bạn đã hoàn thành nhiệm vụ và gõ lệnh git push thành công, bạn cần "nộp" code để Leader duyệt và ghép vào dự án chung.

Lên trang web GitHub của dự án: Link dự án

Bạn sẽ thấy một dòng thông báo màu xanh lá cây có nút Compare & pull request. Hãy bấm vào đó.

Kiểm tra xem hướng mũi tên ghép code đã đúng là từ nhánh của bạn trỏ vào develop chưa. (Ví dụ: base: develop <--- compare: feature/data-model).

Ghi một vài dòng mô tả bạn đã làm được những gì và bấm Create pull request.

Nhắn tin vào group thông báo để Leader vào duyệt (Merge) code.

Chúc team hoàn thành đồ án xuất sắc và không bị bug!
