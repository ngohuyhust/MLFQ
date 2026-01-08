**# OS-project**
**Multilevel Feedback Queue Scheduling**
Đây là chương trình mô phỏng thuật toán lập lịch Multi-Level Feedback Queue (MLFQ) được viết bằng ngôn ngữ Python. Thuật toán này giúp tối ưu hóa thời gian phản hồi cho các tiến trình ngắn và ngăn chặn tình trạng "đói" (starvation) của các tiến trình dài thông qua cơ chế phản hồi và thay đổi độ ưu tiên linh hoạt.

**Tính năng chính**
Đa hàng đợi (Multiple Queues): Hệ thống bao gồm nhiều mức hàng đợi với các chiến lược lập lịch khác nhau (thường là Round Robin cho các mức cao và FCFS cho mức thấp nhất).

Cấp phát Quantum thời gian (Time Quantum): Mỗi hàng đợi có một khoảng thời gian chạy (Time Quantum) riêng biệt, tăng dần theo các mức thấp hơn.

Cơ chế Phản hồi (Feedback Mechanism): Tiến trình tự động bị hạ bậc nếu sử dụng hết quantum thời gian mà chưa hoàn thành.

Cơ chế Tăng bậc (Priority Boost/Aging): Ngăn chặn tình trạng đói tiến trình bằng cách định kỳ đưa các tiến trình ở hàng đợi thấp lên hàng ưu tiên cao hơn.

Báo cáo kết quả: Tính toán và hiển thị các thông số quan trọng: Waiting Time, Turnaround Time, Response Time.
