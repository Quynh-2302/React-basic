## SSR AND CSR
SSR (Server-Side Rendering) và CSR (Client-Side Rendering) là hai phương pháp khác nhau để xây dựng và hiển thị giao diện người dùng trong ứng dụng web.

1, Server-Side Rendering (SSR):

* SSR là quá trình xây dựng và hiển thị giao diện trên phía máy chủ.
* Khi một yêu cầu được gửi từ trình duyệt đến máy chủ, máy chủ sẽ thực hiện xử lý dữ liệu và tạo ra giao diện HTML hoàn chỉnh.
* Giao diện HTML được trả về cho trình duyệt và hiển thị ngay lập tức.
* Dữ liệu được tải lần đầu từ máy chủ và cung cấp cho giao diện ngay từ đầu.
* SSR thường có thời gian phản hồi nhanh hơn cho người dùng ban đầu, vì họ nhận được giao diện hoàn chỉnh từ máy chủ.
* Một số framework phổ biến hỗ trợ SSR là Next.js (dựa trên React) và Nuxt.js (dựa trên Vue.js).

2, Client-Side Rendering (CSR):

* CSR là quá trình xây dựng và hiển thị giao diện trên phía máy khách (trình duyệt).
* Khi một yêu cầu được gửi từ trình duyệt đến máy chủ, máy chủ chỉ trả về một tài liệu HTML rỗng hoặc một trang tĩnh ban đầu.
* Mã JavaScript được tải xuống máy khách và chạy trên trình duyệt để xây dựng và điều khiển giao diện.
* Dữ liệu được tải xuống từ máy chủ sau khi giao diện đã được hiển thị và sau đó được sử dụng để cập nhật giao diện mà không cần tải lại toàn bộ trang.
* CSR thường có trải nghiệm tương tác tốt, vì dữ liệu được tải và hiển thị theo yêu cầu của người dùng.
* React và Vue.js là hai framework phổ biến hỗ trợ CSR.

👉 Cả SSR và CSR đều có ưu điểm và hạn chế riêng, và lựa chọn phù hợp phụ thuộc vào yêu cầu cụ thể của ứng dụng. SSR thường được sử dụng cho các trang web có nội dung tĩnh, đòi hỏi SEO tốt và thời gian tải nhanh ban đầu. CSR thường được sử dụng cho các ứng dụng động, tương tác cao và trải nghiệm người dùng mượt mà.
