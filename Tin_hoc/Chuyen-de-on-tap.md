# 📚 Chuyên đề ôn tập Olympic Tin học NEU

Dưới đây là các nhóm kiến thức nên ưu tiên khi chuẩn bị cho Olympic Tin học cấp Đại học Kinh tế Quốc dân.

> Lưu ý: Đây là nội dung định hướng ôn tập, không phải đề cương chính thức của kỳ thi.

## 1. Lập trình cơ bản và mô phỏng

Cần nắm chắc các kiến thức nền tảng như biến, kiểu dữ liệu, câu lệnh điều kiện, vòng lặp, hàm, nhập/xuất dữ liệu và xử lý số cơ bản.

Bên cạnh đó, nên luyện các bài mô phỏng — tức là đọc yêu cầu đề bài và thực hiện đúng từng bước xử lý được mô tả.

Ví dụ:
- Tính điểm theo quy tắc
- Thay đổi trạng thái qua nhiều bước
- Xử lý từng phần tử theo thứ tự
- Mô phỏng một quá trình hoặc hệ thống đơn giản

## 2. Mảng, dãy, chuỗi và ma trận

Đây là nhóm kiến thức xuất hiện rất thường xuyên trong các bài thi lập trình.

Nên luyện:
- Duyệt mảng và dãy
- Tìm max, min
- Đếm phần tử thỏa điều kiện
- Tính tổng và xử lý đoạn
- Prefix Sum
- Xử lý chuỗi ký tự
- Đếm tần suất ký tự
- Duyệt ma trận, hàng, cột và các ô lân cận

## 3. Sắp xếp và tìm kiếm

Cần sử dụng thành thạo các kỹ thuật:
- `sort`
- Tìm kiếm tuyến tính
- Binary Search
- `lower_bound`
- `upper_bound`

Điểm quan trọng là biết khi nào nên sắp xếp dữ liệu trước để giảm số lần duyệt và tối ưu thời gian chạy.

## 4. Thuật toán tham lam – Greedy

Greedy thường xuất hiện trong các bài yêu cầu chọn phương án tốt nhất tại từng bước.

Một số dạng nên luyện:
- Chọn phần tử
- Chọn khoảng
- Sắp xếp rồi lựa chọn
- Tối đa hóa hoặc tối thiểu hóa kết quả

Cần chú ý rằng không phải bài toán nào cũng có thể giải bằng Greedy, vì vậy nên tập nhận biết khi nào lựa chọn cục bộ có thể dẫn đến kết quả tối ưu.

## 5. Quy hoạch động – Dynamic Programming

Đây là một trong những chuyên đề quan trọng hơn trong competitive programming.

Nên hiểu:
- Trạng thái DP
- Công thức chuyển
- Trường hợp cơ sở
- Thứ tự tính

Một số dạng phổ biến:
- DP một chiều
- DP hai chiều cơ bản
- Bài toán chọn / không chọn
- Bài toán chia tổng
- Knapsack cơ bản
- DP trên dãy

## 6. Đồ thị cơ bản

Nên nắm các kiến thức:
- Biểu diễn đồ thị bằng danh sách kề
- BFS
- DFS
- Thành phần liên thông
- Duyệt lưới bằng BFS/DFS

BFS thường dùng cho các bài đường đi ngắn nhất trên đồ thị không trọng số, còn DFS thường được dùng để duyệt đồ thị và xác định các thành phần liên thông.

## 7. Cấu trúc dữ liệu cơ bản

Nên biết cách sử dụng:
- Stack
- Queue
- Set
- Map
- Priority Queue

Các cấu trúc này giúp xử lý dữ liệu hiệu quả hơn và thường xuyên xuất hiện trong các bài lập trình thi đấu.

## 8. Độ phức tạp và tối ưu thuật toán

Ngoài việc tìm được cách giải đúng, cần chú ý đến thời gian chạy của chương trình.

Nên phân biệt các mức độ phức tạp như:
- `O(1)`
- `O(log n)`
- `O(n)`
- `O(n log n)`
- `O(n²)`

Khi đọc đề, nên xem giới hạn dữ liệu trước để ước lượng thuật toán nào đủ nhanh.

## 🗺️ Thứ tự ôn tập gợi ý

Nếu chưa có nhiều kinh nghiệm, có thể học theo thứ tự:

**Mảng / Chuỗi → Mô phỏng → Sắp xếp / Tìm kiếm → Prefix Sum → Greedy → Dynamic Programming → BFS / DFS → Cấu trúc dữ liệu**

> Không cần học quá nhiều thuật toán nâng cao ngay từ đầu. Quan trọng hơn là nắm chắc nền tảng, luyện nhiều bài và biết phân tích độ phức tạp của lời giải.