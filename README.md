Dự án: Hệ thống Chấm điểm Thi Tự động (Grade the Exams)

📌 Giới thiệu:  Dự án này là một chương trình Python giúp tự động hóa quy trình chấm điểm các bài thi trắc nghiệm từ các tệp văn bản (.txt). Chương trình sử dụng thư viện Pandas và NumPy để xử lý dữ liệu lớn một cách tối ưu và nhanh chóng.

🚀 Các Tính năng Chính: Chương trình được chia thành 4 nhiệm vụ chính (Tasks):
Kiểm tra tệp đầu vào (Task 1):  Yêu cầu người dùng nhập tên lớp và kiểm tra sự tồn tại của tệp bằng xử lý ngoại lệ (try/except).

Phân tích & Lọc dữ liệu (Task 2): * Kiểm tra định dạng mã số sinh viên (bắt đầu bằng 'N' và có 8 chữ số).Đảm bảo mỗi dòng dữ liệu có đủ 26 giá trị (1 ID + 25 câu trả lời).Báo cáo chi tiết các dòng dữ liệu không hợp lệ.

Chấm điểm & Thống kê (Task 3):Áp dụng quy tắc: Đúng (+4), Bỏ qua (0), Sai (-1).Sử dụng kỹ thuật Vectorization của NumPy để tính toán điểm số cho toàn bộ lớp cùng lúc.Tính toán các chỉ số thống kê: Điểm trung bình, Cao nhất, Thấp nhất, Miền giá trị và Trung vị (Median).

Xuất kết quả (Task 4): Lưu kết quả điểm số của từng sinh viên vào một tệp mới có hậu tố _grades.txt.

🛠 Yêu cầu Hệ thống
    Python 3.x
    Thư viện Pandas
    Thư viện NumPy
Cài đặt nhanh các thư viện cần thiết:pip install pandas numpy

📂 Cấu trúc Dự ánPlaintext.
├── class1.txt                  # Dữ liệu mẫu lớp 1
├── class2.txt                  # Dữ liệu mẫu lớp 2
├── class3.txt                  # Dữ liệu mẫu lớp 3
├── class4.txt                  # Dữ liệu mẫu lớp 4
├── class5.txt                  # Dữ liệu mẫu lớp 5
├── class6.txt                  # Dữ liệu mẫu lớp 6
├── class7.txt                  # Dữ liệu mẫu lớp 7
├── class8.txt                  # Dữ liệu mẫu lớp 8
├── lastname_firstname_grade_the_exams.py   # File mã nguồn chính
└── README.md                               # Hướng dẫn dự án

📖 Hướng dẫn Sử dụng
    1.Đặt file mã nguồn .py và các file dữ liệu .txt vào cùng một thư mục.
    2.Chạy chương trình bằng lệnh:python lastname_firstname_grade_the_exams.py
    3.Nhập tên lớp khi được yêu cầu (ví dụ: class1).
    4.Xem báo cáo phân tích trên màn hình và kiểm tra file kết quả class1_grades.txt được tạo ra trong thư mục.

📊 Quy tắc Chấm điểm
    Chương trình sử dụng bộ đáp án chuẩn:B,A,D,D,C,B,D,A,C,C,D,B,A,B,A,C,B,D,A,C,A,A,B,D,D
    Loại câu trả lời
        Điểm:
            Đúng+4
            Sai-1
            Bỏ trống0
            
📝 Thông tin Sinh viên
Họ và tên: Trần Thái Minh
Mã số sinh viên: 202416568
