Bài 3 : Giảm chi phí vận hành Chatbot AI

Phần 1:

\- ưu thế Markdown 

Giảm tải số lượng Token bằng cách sử dụng cú pháp cực kỳ gọn như (\*\*) , (#) , (-).

\- Tốc độ xử lý của AI: LLM xử lý văn bản theo từng token (nhóm ký tự), markdown có token ít hơn html và markdown gần gũi với văn bản tự nhiên giúp AI xử lý nhanh hơn cú pháp html phức tạp.

Phần 2:So sánh \& Đánh giá

| Tiêu chí                | Markdown                                                            | HTML                                                                     |
| ----------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Số lượng ký tự \& Token | ngắn gọn, gần gũi văn bản tự nhiên Plain Text                       | Phức tạp (Nhiều thẻ đóng/mở rườm rà, lãng phí token)                     |
| Độ dễ đọc               | Dễ nhìn                                                             | Khó nhìn                                                                 |
| Hiệu quả xử lý của AI   | Tối ưu, LLM được huấn luyện sâu với Markdown nên ít lỗi cú pháp hơn | Kém hơn, dễ bị lỗi thiếu thẻ đóng như (</div>, </ul>) làm hỏng giao diện |
| Độ phức tạp cú pháp     | Đơn giản, dễ học và dễ chuyển đổi sang giao diện di động/Web        | Phức tạp, cần bộ phân tích cú pháp (Parser) nặng hơn ở phía client       |



Giải pháp tối ưu cho hệ thống "GreenTech"

**Giải pháp đề xuất:** Lựa chọn Markdown làm định dạng chính cho toàn bộ hệ thống đầu ra của "GreenTech"
Lập luận:
- Tiết kiệm chi phí token và tăng tốc độ xử lý của AI: sử dụng Markdown giúp giảm từ 20% đến 40% số lượng token đầu ra so với HTML và tối ưu LLM xử lý đưa câu trả lời nhanh hơn
- Phù hợp cho nông dân sử dụng vì Markdown giúp hiển thị thông tin trực quan,dễ nhìn 
- Độ ổn định cao cho AI: Markdown giúp AI dễ nhìn và xử lý và trả lời câu hỏi ổn định hơn HTML cú pháp phức tạp khiến AI dễ đưa ra câu trả lời bị thiếu cú pháp và lỗi cú pháp