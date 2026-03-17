# Solution — Track B (Middle)

## 1. Risks or Pain Points Expected in a Product Like This

<!--
Describe the risks or pain points you expect in a SaaS product that connects online merchants with external services (shipping, payment, notifications, etc.)
-->

- **Risk/Pain Point 1:** Hệ thống có chịu được tải lớn khi số lượng người dùng và tích hợp tăng lên theo thời gian hoặc theo các sự kiện đặc biệt (ví dụ: mua sắm ngày lễ, chương trình giảm giá, số lượng người dùng đồng thời tăng đột biến, ...) không?

- **Risk/Pain Point 2:** Đôi khi dịch vụ bên thứ 3 không có độ ổn định/tin cậy cao hoặc không hỗ trợ việc API tích hợp.

- **Risk/Pain Point 3:** Việc tích hợp với nhiều dịch vụ bên thứ 3 có thể dẫn đến sự phức tạp trong việc quản lý và bảo trì hệ thống.

- **Risk/Pain Point 4:** Khi có nhiều dịch vụ bên thứ 3 được tích hợp, việc đồng bộ dữ liệu (data consistency) và xử lý lỗi có thể trở nên khó khăn, dẫn đến trải nghiệm người dùng không nhất quán hoặc dữ liệu không chính xác.

- **Risk/Pain Point 5:** Việc đảm bảo bảo mật và tuân thủ các quy định liên quan đến dữ liệu người dùng và giao dịch có thể là một thách thức, đặc biệt khi tích hợp với nhiều dịch vụ bên thứ 3 có tiêu chuẩn bảo mật khác nhau. Nếu không được quản lý tốt, điều này có thể dẫn đến rủi ro về bảo mật và mất lòng tin từ khách hàng.

- **Risk/Pain Point 6:** Việc tích hợp với nhiều dịch vụ bên thứ 3 có thể dẫn đến sự phụ thuộc vào các nhà cung cấp dịch vụ này. Khi có sự cố hoặc thay đổi từ phía nhà cung cấp dịch vụ, điều này có thể ảnh hưởng đến hoạt động của sản phẩm và trải nghiệm người dùng.

---

## 2. What I Would Prioritize Improving in the Next 2–3 Months

<!--
Describe what you would focus on improving and explain your reasoning clearly.
-->

- **Priority 1:** Xác định rõ ràng roadmap sản phẩm và các tích hợp ưu tiên dựa trên nhu cầu của khách hàng và thị trường.
  - Reasoning: Việc có một roadmap rõ ràng sẽ giúp đội ngũ tập trung vào những tích hợp quan trọng nhất, đảm bảo rằng nguồn lực được sử dụng hiệu quả và sản phẩm phát triển theo hướng đáp ứng nhu cầu thực tế của khách hàng. Điều này cũng sẽ giúp tạo ra giá trị nhanh chóng và thu hút khách hàng sớm, từ đó tạo đà cho sự phát triển tiếp theo của sản phẩm.

- **Priority 2:** Xác định & hiện thực các dịch vụ bên thứ 3 quan trọng nhất đối với khách hàng (ví dụ: dịch vụ thanh toán, dịch vụ vận chuyển). Song song với đó là đảm bảo về code quality và tính scalable, HA (high availability) của hệ thống.
  - Reasoning: Xác định product MVP với các tích hợp quan trọng nhất sẽ giúp nhanh chóng triển khai sản phẩm lên môi trường test/production, thu hút khách hàng và tạo ra giá trị thực tế. Kết hợp với việc thiết kế hệ thống linh hoạt để dễ dàng mở rộng và tích hợp các dịch vụ mới trong tương lai, việc tập trung vào các tích hợp này cũng sẽ giúp thu thập phản hồi từ người dùng sớm, từ đó cải thiện sản phẩm một cách hiệu quả hơn.

- **Priority 3:** Hoàn thiện & đảm bảo quy trình kiểm thử và giám sát hiệu quả cho các tích hợp của ưu tiên 2.
  - Reasoning: Việc kiểm thử và giám sát hiệu quả sẽ giúp phát hiện sớm các vấn đề, giảm rủi ro lỗi và đảm bảo trải nghiệm người dùng ổn định. Việc này cũng sẽ giúp xây dựng niềm tin với khách hàng khi họ thấy rằng sản phẩm hoạt động ổn định và đáng tin cậy.

---

## 3. One Decision or Improvement I Would Intentionally Postpone, and Why

<!--
Describe one thing you would deliberately delay and explain your reasoning.
-->

- **What I would postpone:** Việc tích hợp với các dịch vụ bên thứ 3 có độ ưu tiên thấp hơn (ví dụ: dịch vụ thông báo, dịch vụ phân tích, v.v.)
- **Why:**
  - Việc tập trung vào các tích hợp quan trọng nhất sẽ giúp nhanh chóng triển khai sản phẩm và thu hút khách hàng sớm, tạo đà cho sự phát triển tiếp theo của sản phẩm. Nếu cố gắng tích hợp quá nhiều dịch vụ cùng một lúc -> đội ngũ có thể bị phân tán và không đủ nguồn lực để đảm bảo chất lượng và hiệu suất của các tích hợp quan trọng.
  - Tránh việc xây dựng các tính năng hoặc tích hợp mà khách hàng không thực sự cần hoặc sử dụng, từ đó tối ưu hóa nguồn lực và tập trung vào việc tạo ra giá trị thực tế cho khách hàng.

---

## AI Usage & Critical Thinking

### AI-Generated Suggestion

> "To build a scalable SaaS product, start with a strong architecture and add all necessary infrastructure early so you don't need to rewrite later."

### Do I Agree or Disagree?

<!--
Briefly state your position.
-->

- [ ] Đồng ý (Agree)
- [x] Đồng ý một phần (Partially Agree)
- [ ] Không đồng ý (Disagree)

Explanation: Tôi đồng ý ở việc bắt đầu dự án với một kiến trúc tốt "strong architecture", đây là một trong những yếu tố quan trọng để đảm bảo rằng sản phẩm có thể mở rộng và phát triển theo thời gian. Tuy nhiên, về quan điểm "add all necessary infrastructure early", tôi cho rằng việc này có thể không hoàn toàn thực tế hoặc cần thiết trong giai đoạn đầu của một project. Việc xây dựng tất cả các thành phần hạ tầng ngay từ đầu có thể dẫn đến việc lãng phí nguồn lực và thời gian nếu thành phần đó không thực sự cần thiết hoặc không được sử dụng trong giai đoạn đầu của sản phẩm.

### Why This Advice Could Be Risky or Incomplete

<!--
Explain one reason why this advice could be risky or incomplete in a real business.
-->

- **Reason 1:** Việc xây dựng tất cả các thành phần hạ tầng ngay từ đầu có thể dẫn đến việc lãng phí nguồn lực và thời gian nếu thành phần đó không thực sự cần thiết hoặc không được sử dụng trong giai đoạn đầu của sản phẩm. Điều này có thể làm chậm tiến độ phát triển và tăng chi phí, đặc biệt đối với các startup hoặc dự án có nguồn lực hạn chế. Thay vào đó, việc áp dụng nguyên tắc "build the minimum viable product (MVP)" và sau đó mở rộng dần dần khi có nhu cầu thực tế sẽ giúp tối ưu hóa nguồn lực và tập trung vào việc tạo ra giá trị cho khách hàng một cách hiệu quả hơn.

---

## AI Usage Disclosure

<!--
Briefly mention how you used AI during this assignment, if applicable.
-->

- **Tool(s) used:** Github Copilot
- **How I used it:** Sử dụng để gợi ý cấu trúc và cách diễn đạt cho phần giải pháp.
- **What I wrote myself:** Viết ý tưởng ban đầu. Sau đó xem xét, chỉnh sửa và hoàn thiện nội dung để đảm bảo tính chính xác và rõ ràng.
