# HCM-KS26-CNTT1_NhapMonCNTT_Session15_BTVN10
# BÀI 10: LỰA CHỌN NỀN TẢNG GIAO TIẾP NHÓM

**Họ và tên:** Phạm Thành Đạo  
**Lớp:** HCM-KS26-CNTT1  
**Môn học:** Nhập môn Công nghệ thông tin  
**Dự án:** CampusPay  
**Chủ đề:** Phân tích và lựa chọn nền tảng giao tiếp nhóm

---

# PHẦN 1: PHÂN TÍCH BÀI TOÁN

## 1.1. Xác định đầu vào (Input)

Để lựa chọn nền tảng giao tiếp phù hợp, cần xác định nhu cầu thực tế của nhóm CampusPay.

**A. Thông tin nhóm**

- Ban Kỹ thuật: 3 thành viên, phụ trách phát triển phần mềm và kiểm thử API.
- Ban Thiết kế: 2 thành viên, phụ trách thiết kế giao diện và tài sản đồ họa.
- Ban Kinh doanh: 2 thành viên, phụ trách kế hoạch kinh doanh và liên hệ đối tác.
- Trưởng nhóm: Quản lý tiến độ, phân công nhiệm vụ và theo dõi deadline.
- Quy mô: Khoảng 4–5 người theo yêu cầu bài toán, có thể mở rộng khi cần.

**B. Nhu cầu giao tiếp**

- Trao đổi công việc giữa các ban.
- Gửi thông báo quan trọng và hạn chế tình trạng tin nhắn bị trôi.
- Phân công nhiệm vụ, xác định người phụ trách và Deadline.
- Tìm kiếm lại các quyết định và tài liệu đã trao đổi trước đó.
- Hỗ trợ giao tiếp bất đồng bộ khi thành viên không trực tuyến cùng thời điểm.
- Giao tiếp với đối tác bên ngoài trường học.

**C. Các vấn đề hiện tại**

- Tin nhắn quan trọng dễ bị trôi trong nhóm chat.
- Khó theo dõi nhiệm vụ nếu chỉ giao việc bằng tin nhắn.
- Khó tìm lại quyết định kỹ thuật sau một thời gian dài.
- Thông tin công việc bị phân tán.
- Thành viên có lịch học và thời gian làm việc khác nhau.

## 1.2. Xác định đầu ra (Output)

Nền tảng giao tiếp được lựa chọn cần đáp ứng:

1. Phân loại nội dung trao đổi theo từng chủ đề và phòng ban.
2. Giữ thông báo quan trọng dễ tìm kiếm và theo dõi.
3. Hỗ trợ giao nhiệm vụ, phân công người phụ trách và đặt Deadline.
4. Tìm kiếm được lịch sử tin nhắn và tài liệu.
5. Hỗ trợ giao tiếp bất đồng bộ, hạn chế yêu cầu phản hồi ngay lập tức.
6. Có thể sử dụng trên cả máy tính và điện thoại.
7. Phù hợp với ngân sách và khả năng tiếp cận công nghệ của sinh viên.

## 1.3. Phân tích Giải pháp A – Zalo

### Ưu điểm

**1. Dễ sử dụng**

- Các thành viên đã quen với giao diện Zalo.
- Không cần dành nhiều thời gian đào tạo.
- Có thể bắt đầu trao đổi công việc ngay lập tức.

**2. Chi phí thấp**

- Có thể sử dụng các chức năng nhắn tin cơ bản miễn phí.
- Không cần đầu tư thêm nền tảng mới nếu nhóm đã sử dụng Zalo.

**3. Thuận tiện trên điện thoại**

- Thành viên có thể trao đổi khi đang ở trường hoặc di chuyển.
- Dễ gửi hình ảnh, file và tin nhắn.
- Phù hợp với những đối tác chỉ sử dụng Zalo.

**4. Giao tiếp nhanh**

- Phù hợp với những trao đổi ngắn.
- Có thể ghim tin nhắn quan trọng.
- Dễ dàng liên hệ cá nhân hoặc nhóm.

### Nhược điểm

**1. Tin nhắn dễ bị trôi**

- Khi có nhiều thành viên trao đổi cùng lúc, thông báo quan trọng có thể bị đẩy lên trên.
- Khó phân chia thảo luận theo từng chủ đề chuyên môn.

**2. Quản lý công việc còn hạn chế**

- Không có quy trình chuyển tin nhắn thành Task có người phụ trách và Deadline tích hợp như mô hình nhóm đang cần.
- Thành viên phải tự ghi nhớ hoặc sử dụng thêm công cụ quản lý công việc.

**3. Tìm kiếm lịch sử chưa thuận tiện cho quản lý dự án**

- Có thể tìm kiếm tin nhắn, nhưng việc theo dõi một quyết định qua nhiều cuộc trao đổi vẫn dễ bị phân tán.
- Khó quản lý tập trung lịch sử công việc theo từng chủ đề.

**4. Giao tiếp bất đồng bộ chưa có cấu trúc rõ ràng**

- Nội dung trao đổi thường tập trung trong một dòng hội thoại chung.
- Khó phân biệt thông báo, câu hỏi, báo lỗi và nhiệm vụ.

**Kết luận:** Zalo phù hợp với giao tiếp nhanh và liên hệ đối tác, nhưng chưa phải lựa chọn tối ưu để quản lý toàn bộ quy trình làm việc nội bộ của CampusPay.

## 1.4. Phân tích Giải pháp B – Lark Suite

### Ưu điểm

**1. Phân chia Channel theo chủ đề**

- Có thể tạo các Channel riêng cho từng ban.
- Thông tin kỹ thuật, thiết kế và kinh doanh được phân loại rõ ràng.
- Thành viên dễ tìm đúng nội dung cần trao đổi.

**2. Reply in Thread**

- Các câu trả lời được giữ trong từng luồng thảo luận.
- Hạn chế tình trạng nhiều chủ đề bị trộn lẫn.
- Giúp khung chat chính gọn gàng hơn.

**3. Quản lý công việc**

- Có thể chuyển nội dung trao đổi thành Task theo quy trình được hỗ trợ.
- Phân công người thực hiện.
- Đặt Deadline và theo dõi trạng thái công việc.

**4. Tìm kiếm lịch sử**

- Có thể tìm kiếm tin nhắn và tài liệu theo từ khóa, người gửi hoặc nội dung.
- Thuận tiện khi cần tìm lại quyết định kiến trúc hoặc thông tin kỹ thuật từ trước.

**5. Tích hợp nhiều công cụ**

- Có thể kết hợp Chat, Calendar, Docs và Video Call.
- Giảm việc phải chuyển đổi giữa nhiều nền tảng.
- Hỗ trợ quản lý công việc tập trung.

**6. Hỗ trợ thiết bị di động**

- Lark có ứng dụng dành cho điện thoại.
- Thành viên không có laptop vẫn có thể tham gia Channel, đọc thông báo và trao đổi công việc.
- Phù hợp với thành viên Ban Kinh doanh chỉ sử dụng điện thoại.

### Nhược điểm

**1. Cần thời gian làm quen**

- Thành viên chưa quen với cách tổ chức Channel và Thread.
- Cần hướng dẫn cách tạo Task và sử dụng Calendar.
- Có thể mất khoảng 1–2 ngày để cả nhóm làm quen theo giả định của bài toán.

**2. Phụ thuộc vào Internet**

- Muốn nhận thông báo và đồng bộ công việc cần có kết nối mạng.
- Khi mạng không ổn định, quá trình trao đổi có thể bị gián đoạn.

**3. Cần thống nhất quy trình sử dụng**

- Nếu không có quy định rõ ràng, Channel có thể bị tạo quá nhiều.
- Thành viên có thể đăng sai nơi hoặc lạm dụng tính năng nhắc tên.
- Cần người quản lý duy trì không gian làm việc.

**4. Khó thay thế hoàn toàn công cụ của đối tác**

- Một số đối tác bên ngoài chỉ quen sử dụng Zalo.
- Việc yêu cầu tất cả đối tác chuyển sang Lark có thể gây bất tiện.

**Kết luận:** Lark phù hợp hơn với nhu cầu quản lý dự án và giao tiếp nội bộ, nhưng cần thời gian đào tạo và quy định sử dụng thống nhất.

---

# PHẦN 2: SO SÁNH VÀ LỰA CHỌN

## 2.1. Bảng so sánh 5 tiêu chí nghiệp vụ

Quy ước đánh giá:

- ✅ Tốt: Đáp ứng tốt nhu cầu.
- ⚠️ Trung bình: Có hỗ trợ nhưng còn hạn chế.
- ❌ Kém: Chưa đáp ứng tốt yêu cầu nghiệp vụ.

| Tiêu chí | Zalo | Lark Suite |
|---|---|---|
| 1. Ngăn chặn tin nhắn bị trôi | ⚠️ Có ghim tin nhắn nhưng khó phân loại nhiều chủ đề. | ✅ Channel và Thread giúp tổ chức thảo luận rõ ràng. |
| 2. Quản lý công việc | ❌ Chủ yếu giao việc qua tin nhắn, cần công cụ khác để theo dõi Task. | ✅ Hỗ trợ quản lý Task, người phụ trách và Deadline. |
| 3. Miễn phí và dễ cài đặt | ✅ Quen thuộc, dễ sử dụng, ít thời gian làm quen. | ⚠️ Có thể bắt đầu với gói miễn phí phù hợp, nhưng cần thời gian học cách sử dụng. |
| 4. Tìm kiếm lịch sử | ⚠️ Có tìm kiếm nhưng thông tin trao đổi dễ phân tán trong hội thoại. | ✅ Tìm kiếm theo từ khóa, người gửi và nội dung trong Workspace. |
| 5. Giao tiếp bất đồng bộ | ⚠️ Có thể gửi tin nhắn dài nhưng khó tổ chức và theo dõi phản hồi theo chủ đề. | ✅ Thread, Channel và Task hỗ trợ trao đổi có ngữ cảnh, không cần phản hồi tức thì. |

**Nhận xét:**

- Zalo nổi bật ở tính đơn giản, dễ tiếp cận và chi phí triển khai thấp.
- Lark nổi bật ở khả năng tổ chức thông tin, quản lý nhiệm vụ và cộng tác theo quy trình.
- Với nhóm CampusPay, những vấn đề cần giải quyết không chỉ là nhắn tin mà còn là quản lý tiến độ và hạn chế thất lạc thông tin.

## 2.2. Chốt lựa chọn nền tảng

**Em lựa chọn giải pháp lai: Lark Suite kết hợp Zalo.**

Trong đó:

- Lark Suite là nền tảng giao tiếp và quản lý công việc chính của nội bộ CampusPay.
- Zalo được giữ lại để liên hệ với đối tác bên ngoài hoặc những người chưa sử dụng Lark.

### Lý do lựa chọn

**Thứ nhất: Giải quyết vấn đề quản lý nội bộ**

Lark có Channel, Thread và Task giúp các thành viên theo dõi công việc rõ ràng hơn. Khi có lỗi kỹ thuật, nhóm có thể trao đổi, phân công và đặt Deadline ngay trong môi trường làm việc.

**Thứ hai: Hạn chế thất lạc thông tin**

Các thông báo và quyết định quan trọng được đưa vào đúng Channel. Thành viên có thể tìm lại nội dung theo chủ đề thay vì phải đọc lại toàn bộ nhóm chat.

**Thứ ba: Không gây gián đoạn giao tiếp bên ngoài**

Nhóm vẫn duy trì Zalo để trao đổi với những đối tác chỉ sử dụng nền tảng này. Không cần bắt buộc đối tác phải cài thêm ứng dụng mới.

---

# PHẦN 3: GIẢI QUYẾT 3 BẪY DỮ LIỆU

## 3.1. Bẫy 1 – Thành viên Ban Kinh doanh không có laptop

**Tình huống:**

Một thành viên Ban Kinh doanh chỉ sử dụng điện thoại, không có laptop nhưng vẫn cần tham gia hoạt động của nhóm.

**Giải pháp:**

Sử dụng ứng dụng Lark trên điện thoại.

**Cách giải quyết:**

- Cài đặt ứng dụng Lark từ App Store hoặc Google Play.
- Đăng nhập bằng tài khoản được cấp.
- Tham gia các Channel cần thiết.
- Nhận thông báo và phản hồi tin nhắn.
- Theo dõi Task và Deadline.
- Tham gia cuộc họp trực tuyến khi cần.

**Ảnh hưởng đến quyết định:**

Việc thành viên không có laptop không phải lý do bắt buộc phải loại bỏ Lark vì nền tảng có ứng dụng di động.

Tuy nhiên, những công việc cần chỉnh sửa tài liệu phức tạp hoặc xử lý bảng tính lớn có thể thuận tiện hơn trên máy tính.

**Kết luận:** Vẫn có thể chọn Lark làm công cụ nội bộ, đồng thời bố trí công việc phù hợp với khả năng sử dụng điện thoại của thành viên.

## 3.2. Bẫy 2 – Nhóm mất 1–2 ngày để học Lark khi sắp đến Deadline

**Tình huống:**

Nhóm sắp đến hạn nộp bài, nếu chuyển ngay sang Lark thì phải dành 1–2 ngày để làm quen.

**Giải pháp: Triển khai theo từng giai đoạn.**

**Giai đoạn 1 – Làm quen nhanh**

- Tạo Workspace và các Channel cần thiết.
- Hướng dẫn thành viên cách gửi tin nhắn.
- Hướng dẫn Reply in Thread.
- Hướng dẫn tạo và cập nhật Task.

**Giai đoạn 2 – Áp dụng vào công việc**

- Chuyển các thông báo quan trọng sang Lark.
- Giao nhiệm vụ mới qua Task.
- Sử dụng Thread để trao đổi các vấn đề kỹ thuật.
- Duy trì Zalo trong giai đoạn chuyển đổi nếu cần liên hệ nhanh.

**Đánh giá chi phí học tập:**

Nếu Deadline chỉ còn một ngày, việc chuyển toàn bộ hoạt động sang nền tảng mới có thể làm tăng rủi ro chậm tiến độ.

Nếu còn đủ thời gian và nhóm có thể dành 1–2 ngày làm quen thì chi phí này có thể chấp nhận được vì lợi ích lâu dài trong quản lý dự án.

**Kết luận:** Không nên chuyển đổi đột ngột khi đang sát Deadline. Nên triển khai thử nghiệm trước, sau đó chuyển dần các công việc nội bộ sang Lark.

## 3.3. Bẫy 3 – Đối tác bên ngoài chỉ sử dụng Zalo

**Tình huống:**

Một số đối tác của CampusPay không sử dụng Lark và chỉ quen trao đổi qua Zalo.

**Giải pháp: Tiếp tục sử dụng Zalo cho giao tiếp bên ngoài.**

**Quy trình thực hiện:**

1. Nhân viên Ban Kinh doanh liên hệ đối tác qua Zalo.
2. Tiếp nhận thông tin, yêu cầu và phản hồi từ đối tác.
3. Tổng hợp nội dung quan trọng.
4. Chuyển thông tin cần xử lý vào Channel tương ứng trên Lark.
5. Tạo Task nếu phát sinh công việc có Deadline.
6. Cập nhật kết quả xử lý cho đối tác qua Zalo.

**Ví dụ:**

Đối tác yêu cầu thay đổi phương thức thanh toán. Nhân viên Ban Kinh doanh tiếp nhận yêu cầu qua Zalo, sau đó đăng nội dung vào Channel `#kinh-doanh` trên Lark để các thành viên liên quan thảo luận và phân công xử lý.

**Lưu ý bảo mật:**

Không gửi API Keys, mật khẩu hoặc dữ liệu khách hàng nhạy cảm qua nhóm Zalo thông thường. Chỉ chuyển tiếp những thông tin cần thiết cho công việc và sử dụng kênh được tổ chức phê duyệt đối với dữ liệu mật.

**Kết luận:** Giữ Zalo để giao tiếp với đối tác giúp tránh gián đoạn hợp tác và không bắt buộc bên ngoài thay đổi thói quen sử dụng công nghệ.

---

# PHẦN 4: THIẾT KẾ CẤU TRÚC CHANNEL TRÊN LARK

## 4.1. Nguyên tắc thiết kế

Em đề xuất tạo các Channel theo chức năng và nhóm công việc để tránh tình trạng thông tin bị trộn lẫn.

Mỗi Channel có mục đích riêng, thành viên biết nơi cần đăng bài và người chịu trách nhiệm quản lý.

## 4.2. Cấu trúc Channel

```text
CAMPUSPAY WORKSPACE
│
├── #00-thong-bao
│
├── #01-tien-do-du-an
│
├── #02-ky-thuat
│
├── #03-thiet-ke
│
├── #04-kinh-doanh
│
├── #05-bug-reports
│
└── #06-giao-tiep-chung
```

## 4.3. Bảng mô tả Channel và quyền đăng bài

| Channel | Mục đích | Người có quyền đăng bài |
|---|---|---|
| #00-thong-bao | Thông báo chính thức, Deadline và quy định nhóm. | Trưởng nhóm; thành viên chỉ phản hồi theo quy định. |
| #01-tien-do-du-an | Cập nhật tiến độ, nhiệm vụ và tình trạng công việc. | Tất cả thành viên. |
| #02-ky-thuat | Trao đổi code, API, lỗi hệ thống và giải pháp kỹ thuật. | Ban Kỹ thuật; các ban khác được tham gia khi liên quan. |
| #03-thiet-ke | Trao đổi UI/UX, prototype và tài sản đồ họa. | Ban Thiết kế; các ban khác được góp ý. |
| #04-kinh-doanh | Business Plan, đối tác và chiến lược kinh doanh. | Ban Kinh doanh; trưởng nhóm được tham gia quản lý. |
| #05-bug-reports | Báo lỗi, phân tích nguyên nhân và theo dõi xử lý. | Tất cả thành viên có thể báo lỗi; Ban Kỹ thuật phụ trách xử lý. |
| #06-giao-tiep-chung | Trao đổi các vấn đề chung và giao lưu. | Tất cả thành viên. |

**Quy định:** Quyền đăng bài thực tế cần được thiết lập theo khả năng phân quyền của loại Channel và phiên bản Lark đang sử dụng. Với Channel thông báo, trưởng nhóm có thể giới hạn người đăng nếu Workspace hỗ trợ; các Channel còn lại cho phép thành viên liên quan tham gia trao đổi.

## 4.4. Quy tắc phòng tránh Spam @all – Quy tắc cờ đỏ

Để hạn chế việc lạm dụng @all gây phiền nhiễu cho các thành viên, nhóm áp dụng quy tắc cờ đỏ.

**Quy tắc 1 – Chỉ sử dụng @all khi thực sự cần thiết**

Chỉ dùng @all trong những trường hợp:

- Có thay đổi Deadline quan trọng.
- Có sự cố nghiêm trọng ảnh hưởng đến toàn bộ dự án.
- Có thông báo khẩn cấp cần tất cả thành viên biết.

**Quy tắc 2 – Không sử dụng @all cho việc thông thường**

Không dùng @all khi:

- Hỏi một câu hỏi kỹ thuật.
- Nhắc một thành viên hoàn thành nhiệm vụ.
- Gửi tài liệu tham khảo.
- Thông báo tiến độ cá nhân.

Thay vào đó, sử dụng @tên người phụ trách hoặc đăng vào Channel phù hợp.

**Quy tắc 3 – Quy tắc cờ đỏ**

Nếu một thành viên sử dụng @all không đúng mục đích:

- Lần 1: Nhắc nhở và giải thích quy định.
- Lần 2: Cảnh báo trong nhóm.
- Lần 3: Trưởng nhóm xem xét giới hạn quyền đăng thông báo hoặc quyền nhắc toàn nhóm nếu nền tảng hỗ trợ.

**Quy tắc 4 – Tôn trọng thời gian cá nhân**

- Không yêu cầu phản hồi ngay lập tức khi không khẩn cấp.
- Không gửi thông báo hàng loạt vào ban đêm nếu không có sự cố.
- Ghi rõ Deadline và mức độ ưu tiên trong nội dung công việc.

## 4.5. Ví dụ giao tiếp bất đồng bộ

**Tình huống:** Ban Kỹ thuật phát hiện lỗi API thanh toán.

Tin nhắn mẫu:

```text
[BUG REPORT] API thanh toán trả về lỗi 500

Người phụ trách: Nguyễn Văn A
Mức độ ưu tiên: High

Mô tả:
Khi gửi yêu cầu thanh toán, hệ thống trả về
HTTP 500 thay vì kết quả giao dịch.

Ảnh hưởng:
Người dùng không thể hoàn tất thanh toán.

Yêu cầu:
1. Kiểm tra log máy chủ.
2. Kiểm tra kết nối cơ sở dữ liệu.
3. Xác định nguyên nhân.
4. Đề xuất phương án sửa lỗi.

Deadline: 17:00 ngày mai.

Tài liệu:
[Link tài liệu kiểm thử API]

Sau khi xử lý, cập nhật kết quả vào Task.
```

Sau khi đăng tin nhắn:

- Thành viên trao đổi chi tiết trong Thread.
- Trưởng nhóm chuyển nội dung thành Task.
- Người phụ trách cập nhật tiến độ.
- Khi hoàn thành, nhóm kiểm thử lại và chuyển Task sang Done.

Cách làm này giúp thành viên đọc nội dung vào thời gian phù hợp mà vẫn hiểu rõ vấn đề, người phụ trách và thời hạn xử lý.

---

# PHẦN 5: KẾ HOẠCH TRIỂN KHAI GIẢI PHÁP LAI

## 5.1. Phân chia mục đích sử dụng

| Nền tảng | Mục đích | Đối tượng |
|---|---|---|
| Lark Suite | Giao tiếp nội bộ, Channel, Thread, Task và Calendar. | Các thành viên CampusPay. |
| Zalo | Liên hệ đối tác bên ngoài và trao đổi nhanh khi cần. | Đối tác, khách hàng và người chưa sử dụng Lark. |

## 5.2. Quy trình vận hành

1. Thành viên trao đổi công việc nội bộ trên Lark.
2. Các vấn đề chuyên môn được đăng vào Channel tương ứng.
3. Các cuộc thảo luận chi tiết sử dụng Reply in Thread.
4. Công việc phát sinh được chuyển thành Task có Deadline.
5. Ban Kinh doanh tiếp nhận yêu cầu đối tác qua Zalo.
6. Những yêu cầu liên quan đến dự án được tổng hợp và đưa vào Lark.
7. Trưởng nhóm theo dõi tiến độ và kiểm tra kết quả.

## 5.3. Lợi ích của giải pháp lai

- Không phải loại bỏ ngay công cụ mà các thành viên đã quen thuộc.
- Tận dụng được khả năng quản lý dự án của Lark.
- Giữ được khả năng giao tiếp với đối tác sử dụng Zalo.
- Giảm nguy cơ thất lạc thông tin.
- Có thể mở rộng quy trình khi nhóm phát triển lớn hơn.

---

# PHẦN 6: KẾT LUẬN

Qua bài tập Lựa chọn Nền tảng Giao tiếp Nhóm, em đã phân tích hai giải pháp Zalo và Lark Suite dựa trên năm tiêu chí nghiệp vụ quan trọng: khả năng ngăn chặn tin nhắn bị trôi, quản lý công việc, chi phí và độ dễ sử dụng, tìm kiếm lịch sử và giao tiếp bất đồng bộ.

Kết quả cho thấy:

- Zalo phù hợp với giao tiếp nhanh, đơn giản và liên hệ đối tác.
- Lark Suite phù hợp với quản lý công việc, tổ chức thông tin và cộng tác nội bộ.
- Giải pháp lai giúp CampusPay tận dụng ưu điểm của cả hai nền tảng.

**Lựa chọn cuối cùng:** Sử dụng Lark Suite làm nền tảng giao tiếp và quản lý công việc chính trong nội bộ CampusPay, đồng thời duy trì Zalo để liên hệ với đối tác bên ngoài.

Đây là giải pháp cân bằng giữa hiệu quả công việc, chi phí triển khai, khả năng tiếp cận của thành viên và yêu cầu thực tế của một startup sinh viên.

**Kết luận chung:** Công cụ giao tiếp tốt không nhất thiết phải là công cụ có nhiều tính năng nhất mà phải là công cụ phù hợp với quy mô, quy trình và khả năng sử dụng của nhóm. Việc lựa chọn đúng nền tảng sẽ giúp CampusPay phối hợp hiệu quả hơn, hạn chế thất lạc thông tin và nâng cao khả năng hoàn thành dự án đúng Deadline.
