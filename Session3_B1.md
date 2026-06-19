Đáp án: B.

Phương án B là lựa chọn tối ưu vì đáp ứng đầy đủ 5 thành phần cốt lõi của Prompt. Role: “Java Developer chuyên nghiệp” giúp AI xác định đúng vai trò. Goal: yêu cầu viết lớp UserService với hàm registerUser, mục tiêu rõ ràng. Context: chỉ rõ dự án sử dụng Java 17 và Spring Boot 3.x, giúp AI sinh mã phù hợp môi trường. Constraint: quy định kiểm tra email bằng userRepository.existsByEmail(), nếu trùng thì ném DuplicateEmailException, đồng thời mã hóa mật khẩu bằng PasswordEncoder, đảm bảo đúng nghiệp vụ. Format: yêu cầu xuất mã nguồn Java sạch, chuẩn OOP và có chú thích tiếng Việt ở từng bước, giúp kết quả dễ đọc, ít cần chỉnh sửa.

Phương án A chỉ nêu mục tiêu chung và một phần ràng buộc, thiếu Role, Context và Format. Vì vậy AI có thể chọn sai phiên bản Spring Boot, cấu trúc code không thống nhất hoặc thiếu chú thích.

Phương án C có Goal, một phần Constraint và Format, nhưng thiếu Role, thiếu Context (Java 17, Spring Boot 3.x) và chưa nêu yêu cầu mã hóa mật khẩu. Điều này dễ khiến AI bỏ sót nghiệp vụ hoặc sinh mã không đúng chuẩn dự án.