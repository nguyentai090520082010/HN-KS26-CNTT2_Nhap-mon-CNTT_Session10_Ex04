# Bài 4 : Thiết kế Prompt tối ưu cho AI Assistant
## Phần 1: **Thiết kế Kiến trúc:** Bản Prompt hoàn chỉnh viết bằng Markdown theo đúng công thức 3 phần.
# 1. Bối cảnh
Bạn là một gia sư AI thân thiện, có kỹ năng sư phạm xuất sắc trong việc chuyển đổi các khái niệm công nghệ - kỹ thuật phức tạp thành nội dung cực kỳ đơn giản, trực quan và dễ hiểu. 
Đối tượng học viên là sinh viên năm 1 ngành Công nghệ Thông tin, chưa có kinh nghiệm thực tế về nông nghiệp thông minh cũng như các hệ thống tự động hóa nâng cao.

## 2. Nội dung
Hãy giải thích khái niệm **"Mô hình IPO (Input - Process - Output) trong trang trại thông minh (Smart Farm)"**. 
Để sinh viên dễ hình dung, hãy phân tích mô hình này thông qua một ví dụ thực tế cụ thể: **Hệ thống tưới cây tự động dựa trên độ ẩm của đất**.

## 3. Yêu cầu & Ràng buộc
 **Ngôn ngữ & Thuật ngữ**: Sử dụng 100% tiếng Việt tự nhiên, diễn đạt trong sáng. Tránh lạm dụng thuật ngữ tiếng Anh chuyên ngành. Nếu bắt buộc phải sử dụng thuật ngữ tiếng Anh (như Input, Process, Output), phải giải thích nghĩa tiếng Việt ngay trong ngoặc đơn bên cạnh.
 **Độ dài & Định dạng**: Câu trả lời ngắn gọn, cô đọng, tổng độ dài dưới 400 từ. Sử dụng danh sách gạch đầu dòng và định dạng bôi đậm để tăng tính trực quan.
 **Cấu trúc nội dung**:
  1. Định nghĩa ngắn gọn mô hình IPO.
  2. Phân tích ví dụ hệ thống tưới cây theo 3 bước Input - Process - Output.
  3. Kết luận về ý nghĩa cốt lõi của mô hình đối với sinh viên CNTT.


---

## Phần 2: Sản phẩm (Câu trả lời của AI sau khi áp dụng Prompt)

# Giải thích Mô hình IPO trong Trang Trại Thông Minh

Chào bạn! Là một sinh viên năm 1, việc tiếp cận các hệ thống tự động hóa ban đầu có thể thấy hơi trừu tượng. Tuy nhiên, mọi hệ thống thông minh — dù phức tạp đến đâu — đều hoạt động dựa trên một nguyên lý cốt lõi rất đơn giản: **Mô hình IPO**.

---

### 1. Mô hình IPO là gì?
**IPO** là viết tắt của 3 từ tiếng Anh mô tả luồng xử lý thông tin:
* **Input (Đầu vào):** Dữ liệu hoặc thông tin mà hệ thống thu thập được từ môi trường xung quanh.
* **Process (Xử lý):** "Bộ não" của hệ thống phân tích dữ liệu đầu vào và đưa ra quyết định dựa trên các quy tắc đã được cài đặt sẵn.
* **Output (Đầu ra):** Hành động thực tế hoặc kết quả được tạo ra sau khi hệ thống đưa ra quyết định.

---

### 2. Ví dụ thực tế: Hệ thống tưới cây tự động

Hãy tưởng tượng bạn lắp đặt một hệ thống tưới rau tự động trong trang trại thông minh. Hệ thống này vận hành theo mô hình IPO như sau:

* **Input (Đầu vào):** 
  * Cảm biến cắm dưới đất liên tục đo mức độ ẩm của đất. 
  * *Ví dụ:* Cảm biến ghi nhận độ ẩm hiện tại là **20%** (đất đang rất khô).

* **Process (Xử lý):** 
  * Bộ điều khiển trung tâm tiếp nhận con số **20%** và so sánh với mức cài đặt chuẩn (ví dụ: độ ẩm tối thiểu phải là **50%**).
  * Do $20\% < 50\%$, bộ điều khiển đưa ra quyết định: **"Cần phải tưới nước ngay lập tức!"**

* **Output (Đầu ra):** 
  * Bộ điều khiển phát tín hiệu kích hoạt **máy bơm nước tự động bật lên** để tưới cho luống rau. 
  * Khi độ ẩm đạt đủ 50%, máy bơm sẽ **tự động tắt**.

---

### 3. Tóm lại
Mô hình IPO giúp bạn tư duy logic khi xây dựng bất kỳ phần mềm hay hệ thống nào: **Hệ thống nhận dữ liệu gì? (Input) $\rightarrow$ Phân tích ra sao? (Process) $\rightarrow$ Thực hiện hành động gì? (Output)**. Đây chính là bước khởi đầu quan trọng nhất cho một kỹ sư công nghệ tương lai!