Hệ thống phải hoạt động ổn định vào các thời điểm nhu cầu tăng cao. Doanh nghiệp không muốn một lỗi xảy ra ở chức năng thanh toán hoặc thông báo làm cho toàn bộ hệ thống đặt xe ngừng hoạt động. Các thành phần của hệ thống cần có khả năng mở rộng độc lập khi tải tăng. Doanh nghiệp cũng yêu cầu các chức năng mới có thể được triển khai từng phần mà hạn chế ảnh hưởng đến các chức năng đang hoạt động.
Về bảo mật, khách hàng và tài xế phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. Các thao tác quản trị phải được kiểm soát quyền truy cập. Thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch phải được bảo vệ. Doanh nghiệp cần lưu vết các thao tác quan trọng để phục vụ kiểm tra khi có sự cố.
Doanh nghiệp hiện chưa chốt toàn bộ chi tiết về cách tính cước, tiêu chí ưu tiên tài xế, thời gian tài xế phải phản hồi, chính sách hủy chuyến, cách xử lý khi mất kết nối mạng, cũng như thời gian lưu trữ dữ liệu. Khách hàng mong muốn Business Analyst làm rõ các vấn đề này với các bên liên quan trước khi nhóm phát triển xây dựng giải pháp. Ngoài ra, doanh nghiệp muốn hệ thống có kiến trúc đủ linh hoạt để trong tương lai có thể bổ sung các loại dịch vụ mới, thêm phương thức thanh toán, thêm nhà cung cấp thông báo hoặc thay đổi một số thành phần kỹ thuật mà không phải xây dựng lại toàn bộ ứng dụng.
Kỳ vọng của khách hàng
Khách hàng không chỉ muốn một ứng dụng đặt xe đơn thuần mà muốn một nền tảng CAB có thể phát triển lâu dài. Hệ thống cần đáp ứng tốt quy trình từ khi khách hàng tạo yêu cầu, tìm và phân công tài xế, thực hiện chuyến, tính cước, thanh toán, thông báo đến đánh giá sau chuyến. Các bộ phận trong doanh nghiệp phải có thể phối hợp thông qua hệ thống và có đủ dữ liệu để theo dõi hoạt động. Trong giai đoạn phân tích, Business Analyst được kỳ vọng xác định rõ phạm vi, tác nhân, quy trình nghiệp vụ, yêu cầu chức năng, yêu cầu phi chức năng, các quy tắc nghiệp vụ, các trường hợp ngoại lệ và những điểm còn chưa rõ cần xác nhận với khách hàng.
BƯỚC 1 – ĐỌC VÀ PHÂN TÍCH YÊU CẦU SƠ KHỞI CỦA KHÁCH HÀNG Ở GIAI ĐOẠN 1
1. Tổng quan yêu cầu

Qua yêu cầu sơ khởi, có thể xác định khách hàng muốn xây dựng một hệ thống CAB – nền tảng đặt xe không chỉ phục vụ việc đặt xe mà còn có khả năng vận hành ổn định, bảo mật, mở rộng và phát triển lâu dài.

Hệ thống cần hỗ trợ toàn bộ quy trình nghiệp vụ:

Khách hàng tạo yêu cầu → Tìm kiếm/phân công tài xế → Tài xế phản hồi → Thực hiện chuyến → Tính cước → Thanh toán → Thông báo → Đánh giá sau chuyến.

Ngoài ra, hệ thống phải cho phép các bộ phận trong doanh nghiệp phối hợp và theo dõi hoạt động thông qua dữ liệu được lưu trữ trên hệ thống.

2. Phân tích mục tiêu của khách hàng
Mục tiêu	Phân tích yêu cầu
Ổn định	Hệ thống phải hoạt động ổn định ngay cả khi nhu cầu đặt xe tăng cao.
Chịu lỗi	Nếu chức năng thanh toán hoặc thông báo gặp lỗi, toàn bộ hệ thống đặt xe không được ngừng hoạt động.
Khả năng mở rộng	Các thành phần của hệ thống phải có khả năng mở rộng độc lập khi tải tăng.
Triển khai linh hoạt	Chức năng mới có thể triển khai từng phần mà hạn chế ảnh hưởng đến chức năng đang hoạt động.
Bảo mật	Khách hàng và tài xế phải được xác thực trước khi sử dụng chức năng yêu cầu tài khoản.
Phân quyền	Các thao tác quản trị phải được kiểm soát quyền truy cập.
Bảo vệ dữ liệu	Thông tin cá nhân, phương tiện, vị trí và giao dịch phải được bảo vệ.
Theo dõi sự cố	Các thao tác quan trọng phải được lưu vết để phục vụ kiểm tra và xử lý sự cố.
Phát triển lâu dài	Kiến trúc phải đủ linh hoạt để bổ sung dịch vụ, phương thức thanh toán và nhà cung cấp trong tương lai.
3. Phân tích phạm vi hệ thống
Phạm vi chính của hệ thống CAB

Hệ thống dự kiến bao gồm các nghiệp vụ chính:

Quản lý khách hàng
Quản lý tài xế
Quản lý thông tin phương tiện
Đặt xe
Tìm kiếm và phân công tài xế
Quản lý chuyến xe
Tính cước
Thanh toán
Gửi thông báo
Đánh giá sau chuyến
Quản trị và phân quyền
Theo dõi, lưu vết hoạt động
Theo dõi dữ liệu phục vụ quản lý và vận hành
4. Phân tích yêu cầu chức năng
4.1. Đặt xe

Khách hàng cần có khả năng tạo yêu cầu đặt xe trên hệ thống.

Quy trình cơ bản:

Khách hàng nhập yêu cầu → Hệ thống tiếp nhận → Tìm tài xế phù hợp → Phân công tài xế → Tài xế phản hồi.

4.2. Tìm kiếm và phân công tài xế

Hệ thống cần có chức năng tìm và phân công tài xế cho yêu cầu đặt xe.

Tuy nhiên, tiêu chí ưu tiên tài xế hiện chưa được khách hàng xác định, vì vậy đây là yêu cầu cần BA làm rõ.

Ví dụ các vấn đề cần xác nhận:

Ưu tiên tài xế gần nhất?
Ưu tiên tài xế có trạng thái sẵn sàng?
Có xét loại phương tiện không?
Có xét đánh giá của tài xế không?
4.3. Phản hồi yêu cầu chuyến

Tài xế cần có khả năng phản hồi yêu cầu chuyến.

Khách hàng hiện chưa chốt:

Tài xế phải phản hồi trong bao lâu?
Nếu tài xế không phản hồi thì hệ thống xử lý như thế nào?
Nếu tài xế từ chối thì hệ thống tìm tài xế khác như thế nào?

→ Đây là yêu cầu cần xác nhận.

4.4. Thực hiện và quản lý chuyến xe

Hệ thống cần quản lý trạng thái của chuyến từ lúc được tạo đến khi hoàn thành hoặc hủy.

Ví dụ:

Chờ tìm tài xế → Đã phân công → Tài xế xác nhận → Đang thực hiện → Hoàn thành / Hủy.

4.5. Tính cước

Hệ thống cần có chức năng tính cước cho chuyến xe.

Tuy nhiên, cách tính cước chưa được doanh nghiệp chốt.

BA cần xác nhận:

Giá cơ bản.
Giá theo khoảng cách.
Giá theo thời gian.
Phụ phí.
Khuyến mãi/giảm giá.
Quy tắc làm tròn.
Thời điểm xác định giá.
4.6. Thanh toán

Hệ thống cần hỗ trợ thanh toán cho chuyến xe.

Yêu cầu đặc biệt:

Nếu chức năng thanh toán gặp lỗi, lỗi đó không được làm toàn bộ hệ thống đặt xe ngừng hoạt động.

Ngoài ra cần xác định:

Các phương thức thanh toán.
Xử lý giao dịch thất bại.
Xử lý giao dịch bị gián đoạn.
Đối soát giao dịch.
4.7. Thông báo

Hệ thống cần gửi thông báo cho người dùng trong các sự kiện quan trọng của chuyến xe.

Ví dụ:

Đặt xe thành công.
Đã tìm thấy tài xế.
Tài xế nhận chuyến.
Chuyến xe bắt đầu.
Chuyến xe hoàn thành.
Thanh toán.
Hủy chuyến.

Hệ thống phải có khả năng thay đổi nhà cung cấp thông báo trong tương lai.

4.8. Đánh giá

Sau khi chuyến xe hoàn thành, khách hàng cần có khả năng đánh giá dịch vụ/tài xế.

5. Phân tích yêu cầu phi chức năng
Nhóm yêu cầu	Yêu cầu phi chức năng
Hiệu năng	Hệ thống phải đáp ứng tốt khi nhu cầu đặt xe tăng cao.
Khả năng mở rộng	Các thành phần có thể mở rộng độc lập khi tải tăng.
Tính sẵn sàng	Hệ thống tiếp tục hoạt động khi một thành phần gặp lỗi.
Khả năng chịu lỗi	Lỗi thanh toán/thông báo không làm toàn bộ hệ thống ngừng hoạt động.
Khả năng triển khai	Có thể triển khai chức năng mới từng phần.
Bảo mật	Người dùng phải được xác thực trước khi sử dụng chức năng yêu cầu tài khoản.
Phân quyền	Chỉ người có quyền mới được thực hiện thao tác quản trị.
Bảo vệ dữ liệu	Bảo vệ thông tin cá nhân, phương tiện, vị trí và giao dịch.
Audit/Logging	Lưu vết các thao tác quan trọng.
Khả năng bảo trì	Có thể thay đổi một số thành phần kỹ thuật mà không phải xây dựng lại toàn bộ hệ thống.
Khả năng mở rộng nghiệp vụ	Có thể bổ sung loại dịch vụ mới trong tương lai.
Khả năng tích hợp	Có thể bổ sung phương thức thanh toán và nhà cung cấp thông báo mới.
6. Phân tích yêu cầu bảo mật

Khách hàng đặc biệt quan tâm đến bảo mật.

6.1. Xác thực

Khách hàng và tài xế phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản.

6.2. Phân quyền

Các thao tác quản trị phải được kiểm soát dựa trên quyền của người dùng.

6.3. Bảo vệ dữ liệu

Các loại dữ liệu cần được bảo vệ gồm:

Thông tin cá nhân khách hàng.
Thông tin cá nhân tài xế.
Thông tin phương tiện.
Dữ liệu vị trí.
Dữ liệu giao dịch.
6.4. Lưu vết

Các thao tác quan trọng phải được ghi nhận để:

Kiểm tra khi xảy ra sự cố.
Xác định người thực hiện thao tác.
Hỗ trợ điều tra.
Hỗ trợ kiểm toán.
7. Phân tích khả năng mở rộng và phát triển lâu dài

Đây là một yêu cầu quan trọng trong định hướng của khách hàng.

Hệ thống phải có kiến trúc cho phép:

Bổ sung loại dịch vụ CAB mới.
Bổ sung phương thức thanh toán mới.
Thay đổi nhà cung cấp thanh toán.
Thay đổi nhà cung cấp thông báo.
Thay đổi một số thành phần kỹ thuật.
Mở rộng từng thành phần khi tải tăng.
Triển khai chức năng mới mà hạn chế ảnh hưởng đến chức năng hiện tại.

→ Điều này cho thấy khách hàng không muốn xây dựng một ứng dụng chỉ đáp ứng nhu cầu hiện tại mà muốn xây dựng một nền tảng có khả năng phát triển lâu dài.

8. Các yêu cầu chưa rõ cần BA xác nhận

Đây là phần quan trọng nhất trong giai đoạn phân tích sơ khởi.

STT	Nội dung chưa rõ	Cần xác nhận với
1	Cách tính cước	Doanh nghiệp, Tài chính, Vận hành
2	Tiêu chí ưu tiên tài xế	Doanh nghiệp, Vận hành
3	Thời gian tài xế phải phản hồi	Doanh nghiệp, Vận hành, Tài xế
4	Chính sách hủy chuyến	Doanh nghiệp, CSKH, Vận hành
5	Xử lý khi mất kết nối mạng	Doanh nghiệp, IT, Developer
6	Thời gian lưu trữ dữ liệu	Doanh nghiệp, IT, Pháp chế
7	Phương thức thanh toán	Doanh nghiệp, Tài chính
8	Quy tắc xử lý thanh toán thất bại	Tài chính, IT, Nhà cung cấp thanh toán
9	Quy tắc gửi thông báo	Vận hành, CSKH
10	Quyền của từng loại tài khoản	Doanh nghiệp, Admin, IT
11	Các loại dịch vụ có thể bổ sung	Doanh nghiệp
12	Các trường hợp ngoại lệ của chuyến xe	Doanh nghiệp, Vận hành, CSKH
9. Các trường hợp ngoại lệ cần phân tích

BA cần xác định cách hệ thống xử lý các trường hợp:

Không tìm thấy tài xế.
Tài xế không phản hồi.
Tài xế từ chối chuyến.
Tài xế hủy chuyến.
Khách hàng hủy chuyến.
Mất kết nối mạng.
Thanh toán thất bại.
Nhà cung cấp thanh toán không hoạt động.
Nhà cung cấp thông báo gặp lỗi.
Lượng người dùng tăng đột biến.
Một thành phần của hệ thống bị lỗi.
Người dùng cố thực hiện chức năng không được cấp quyền.
10. Kết quả phân tích yêu cầu sơ khởi

Sau khi đọc và phân tích yêu cầu, có thể xác định:

Phạm vi chính

Hệ thống CAB hỗ trợ toàn bộ vòng đời của một chuyến xe:

Đặt xe → Tìm tài xế → Phân công → Thực hiện chuyến → Tính cước → Thanh toán → Thông báo → Đánh giá.

Yêu cầu trọng tâm

1. Tính ổn định và chịu lỗi
Không để lỗi của một chức năng làm sập toàn bộ hệ thống.

2. Khả năng mở rộng
Các thành phần có thể mở rộng độc lập.

3. Bảo mật
Xác thực, phân quyền và bảo vệ dữ liệu.

4. Khả năng phát triển lâu dài
Có thể bổ sung dịch vụ, phương thức thanh toán và nhà cung cấp mới.

5. Khả năng vận hành
Các bộ phận doanh nghiệp có thể phối hợp và theo dõi hoạt động thông qua hệ thống.

Những vấn đề cần xác nhận trước khi phát triển

Đặc biệt cần làm rõ:

Cách tính cước + ưu tiên tài xế + thời gian phản hồi + chính sách hủy + mất kết nối + thời gian lưu trữ dữ liệu + các trường hợp ngoại lệ.
BƯỚC 2 – XÁC ĐỊNH VÀ XÁC NHẬN CÁC STAKEHOLDER
2.1. Danh sách Stakeholder và vai trò
Tên Stakeholder	Vai trò của Stakeholder trong hệ thống
1. Khách hàng (Customer)	Người sử dụng chính của hệ thống. Tạo yêu cầu đặt xe, cung cấp thông tin chuyến đi, theo dõi chuyến, thanh toán và đánh giá sau chuyến.
2. Tài xế (Driver)	Người trực tiếp cung cấp dịch vụ vận chuyển. Nhận yêu cầu chuyến, phản hồi yêu cầu, thực hiện chuyến và cập nhật trạng thái chuyến.
3. Doanh nghiệp / Chủ hệ thống CAB	Chủ sở hữu hệ thống, xác định mục tiêu kinh doanh, phạm vi, ngân sách, yêu cầu và định hướng phát triển lâu dài của nền tảng.
4. Ban quản lý	Quản lý và giám sát hoạt động của hệ thống, theo dõi dữ liệu, hiệu quả vận hành và đưa ra quyết định kinh doanh.
5. Business Analyst (BA)	Thu thập, phân tích và làm rõ yêu cầu; xác định stakeholder, quy trình nghiệp vụ, quy tắc nghiệp vụ và các vấn đề chưa được xác nhận.
6. Đội phát triển (Developer)	Thiết kế, xây dựng, tích hợp, kiểm thử và triển khai các chức năng của hệ thống theo yêu cầu đã được xác nhận.
7. Đội IT / Vận hành hệ thống	Giám sát, vận hành, bảo trì hệ thống; đảm bảo hệ thống ổn định khi tải cao và xử lý sự cố kỹ thuật.
8. Quản trị viên (Admin)	Quản lý tài khoản, phân quyền, cấu hình hệ thống và thực hiện các thao tác quản trị được cấp quyền.
9. Bộ phận Chăm sóc khách hàng (CSKH)	Tiếp nhận và xử lý khiếu nại, hỗ trợ khách hàng/tài xế và giải quyết các vấn đề phát sinh trong quá trình sử dụng dịch vụ.
10. Bộ phận Vận hành	Theo dõi hoạt động đặt xe, tình trạng tài xế/chuyến xe và xử lý các tình huống nghiệp vụ phát sinh.
11. Bộ phận Tài chính / Kế toán	Theo dõi giao dịch, thanh toán, doanh thu, đối soát và các vấn đề liên quan đến tài chính.
12. Nhà cung cấp dịch vụ thanh toán	Cung cấp nền tảng/API thanh toán, xử lý giao dịch và trả kết quả giao dịch về hệ thống CAB.
13. Nhà cung cấp dịch vụ thông báo	Cung cấp SMS, Email, Push Notification hoặc các dịch vụ thông báo khác cho hệ thống.
14. Cơ quan quản lý / Pháp luật	Đưa ra các quy định mà hệ thống phải tuân thủ, đặc biệt liên quan đến vận tải, dữ liệu cá nhân, giao dịch và bảo mật thông tin.
2.2. Stakeholder Matrix
Tiêu chí đánh giá
Mức độ ảnh hưởng (Influence): Khả năng stakeholder tác động đến quyết định, phạm vi, hoạt động hoặc kết quả của hệ thống.
Mức độ quan trọng (Importance): Mức độ cần thiết của stakeholder đối với việc hệ thống hoạt động và đạt mục tiêu.
Ma trận Stakeholder
MỨC ĐỘ ẢNH HƯỞNG ↓ / MỨC ĐỘ QUAN TRỌNG →	THẤP	CAO
🔴 CAO	Cơ quan quản lý / Pháp luật
Có quyền tác động thông qua các quy định và yêu cầu tuân thủ.	Doanh nghiệp / Chủ hệ thống CAB
Ban quản lý
Có quyền quyết định mục tiêu, phạm vi, ngân sách và định hướng phát triển hệ thống.
🟢 THẤP	Nhà cung cấp thanh toán
Nhà cung cấp thông báo
Là các dịch vụ bên ngoài, có khả năng thay thế bằng nhà cung cấp khác.	Khách hàng
Tài xế
Admin
IT / Vận hành
CSKH
Bộ phận Vận hành
Tài chính / Kế toán
Đây là các bên có vai trò trực tiếp hoặc thiết yếu đối với hoạt động của hệ thống.
	THẤP	CAO
Sơ đồ 2×2
                         STAKEHOLDER MATRIX
                  MỨC ĐỘ QUAN TRỌNG CỦA STAKEHOLDER
                         THẤP                  CAO
                    ┌──────────────────┬────────────────────────┐
                    │                  │                        │
                    │  CƠ QUAN QUẢN   │  DOANH NGHIỆP / CHỦ    │
                    │  LÝ / PHÁP LUẬT │  HỆ THỐNG CAB           │
       ẢNH HƯỞNG    │                  │  BAN QUẢN LÝ            │
          CAO       │                  │                        │
                    ├──────────────────┼────────────────────────┤
                    │                  │                        │
                    │  NHÀ CUNG CẤP    │  KHÁCH HÀNG             │
                    │  THANH TOÁN      │  TÀI XẾ                 │
                    │                  │  ADMIN                  │
       ẢNH HƯỞNG    │  NHÀ CUNG CẤP    │  IT / VẬN HÀNH          │
          THẤP      │  THÔNG BÁO       │  CSKH                   │
                    │                  │  BỘ PHẬN VẬN HÀNH       │
                    │                  │  TÀI CHÍNH / KẾ TOÁN    │
                    └──────────────────┴────────────────────────┘
                         THẤP                  CAO
2.3. Phân tích mức độ ảnh hưởng và quan trọng
Nhóm	Stakeholder	Mức ảnh hưởng	Mức quan trọng	Cách quản lý
1	Doanh nghiệp / Chủ CAB	Cao	Cao	Quản lý chặt chẽ
2	Ban quản lý	Cao	Cao	Quản lý chặt chẽ
3	Cơ quan quản lý	Cao	Thấp	Duy trì hài lòng
4	Khách hàng	Thấp	Cao	Cập nhật và thu thập phản hồi
5	Tài xế	Thấp	Cao	Cập nhật và thu thập phản hồi
6	IT / Vận hành	Thấp	Cao	Phối hợp thường xuyên
7	Admin	Thấp	Cao	Phối hợp thường xuyên
8	CSKH	Thấp	Cao	Cập nhật thường xuyên
9	Bộ phận Vận hành	Thấp	Cao	Cập nhật thường xuyên
10	Tài chính / Kế toán	Thấp	Cao	Cập nhật thường xuyên
11	Nhà cung cấp thanh toán	Thấp	Thấp	Theo dõi
12	Nhà cung cấp thông báo	Thấp	Thấp	Theo dõi
Vị trí của BA và Developer

BA và Developer là stakeholder của dự án, nhưng nên phân biệt với stakeholder nghiệp vụ:

BA: ảnh hưởng cao trong giai đoạn phân tích và xác nhận yêu cầu; vai trò quan trọng đối với việc chuyển nhu cầu thành yêu cầu hệ thống.
Developer: ảnh hưởng cao trong việc lựa chọn và triển khai giải pháp kỹ thuật.
Tuy nhiên, BA và Developer không phải bên quyết định cuối cùng về yêu cầu kinh doanh; quyết định thuộc về doanh nghiệp và các stakeholder có thẩm quyền.

Vì vậy, nếu giảng viên yêu cầu “stakeholder của toàn bộ dự án”, nên đưa BA và Developer vào danh sách stakeholder; nếu yêu cầu “stakeholder của hệ thống CAB”, trọng tâm là khách hàng, tài xế, doanh nghiệp, quản lý, các bộ phận vận hành và các hệ thống bên ngoài.
BƯỚC 3 – XÁC ĐỊNH BUSINESS GOAL

Dựa trên yêu cầu sơ khởi của hệ thống CAB, các Business Goal (BG) nên được xác định từ mục tiêu kinh doanh của doanh nghiệp, không chỉ mô tả chức năng của hệ thống.

Mã BG	Business Goal	Mục đích / Ý nghĩa
BG01	Giảm thời gian tìm và phân công tài xế	Tự động hóa quá trình tìm kiếm và phân công tài xế phù hợp, giúp khách hàng nhanh chóng được ghép với tài xế và giảm thời gian chờ.
BG02	Tự động hóa quy trình tìm tài xế	Xây dựng chức năng tự động tìm kiếm tài xế dựa trên các tiêu chí phù hợp, giảm sự can thiệp thủ công của nhân viên vận hành.
BG03	Hỗ trợ nhiều phương thức thanh toán	Cho phép khách hàng thanh toán chuyến xe bằng tiền mặt hoặc thanh toán trực tuyến, đáp ứng nhu cầu đa dạng của khách hàng.
Giải thích cụ thể

BG01 – Giảm thời gian tìm và phân công tài xế

Mục tiêu kinh doanh là rút ngắn thời gian từ lúc khách hàng tạo yêu cầu đặt xe đến lúc được xác nhận tài xế, từ đó nâng cao trải nghiệm khách hàng và hiệu quả vận hành.

BG02 – Tự động hóa việc tìm tài xế

Hệ thống cần có chức năng tự động tìm tài xế phù hợp thay vì phụ thuộc hoàn toàn vào nhân viên. Điều này giúp giảm công việc thủ công và tăng khả năng xử lý nhiều yêu cầu đặt xe cùng lúc.

BG03 – Hỗ trợ thanh toán linh hoạt

Hệ thống cho phép khách hàng lựa chọn thanh toán bằng tiền mặt hoặc thanh toán trực tuyến, giúp tăng tính thuận tiện và đáp ứng nhiều nhu cầu sử dụng dịch vụ.

Mối quan hệ giữa Business Goal và chức năng
BUSINESS GOAL
     │
     ├── BG01: Giảm thời gian tìm tài xế
     │       ↓
     │   Chức năng tự động tìm & phân công tài xế
     │
     ├── BG02: Tự động hóa tìm tài xế
     │       ↓
     │   Hệ thống tự động xác định tài xế phù hợp
     │
     └── BG03: Thanh toán linh hoạt
             ↓
         Thanh toán tiền mặt
         Thanh toán trực tuyến

Lưu ý: BG01 và BG02 khá gần nhau. Nếu bài yêu cầu Business Goal phải khác nhau rõ ràng, mình khuyên dùng:

BG01: Giảm thời gian khách hàng chờ được tìm tài xế.
BG02: Tự động hóa quy trình tìm và phân công tài xế.
BG03: Cung cấp phương thức thanh toán linh hoạt bằng tiền mặt và trực tuyến.

Như vậy sẽ dễ phân biệt “kết quả kinh doanh muốn đạt được” (BG01) với “định hướng cải tiến hoạt động” (BG02).
BƯỚC 4 – XÁC ĐỊNH PHẠM VI YÊU CẦU ĐỂ THỰC HIỆN

Dựa trên các yêu cầu và Business Goal đã xác định ở các bước trước, phạm vi của hệ thống CAB – hệ thống đặt xe được xác định như sau.

4.1. Phạm vi tổng thể

Hệ thống tập trung vào việc hỗ trợ toàn bộ quy trình đặt xe:

Khách hàng đặt xe → Hệ thống tìm tài xế → Phân công tài xế → Tài xế thực hiện chuyến → Tính cước → Thanh toán → Thông báo → Đánh giá

Mục tiêu của phạm vi là xây dựng một hệ thống đủ chức năng để vận hành dịch vụ đặt xe, nhưng không mở rộng sang những chức năng chưa cần thiết ở giai đoạn đầu.

4.2. Các chức năng nằm trong phạm vi
STT	Chức năng	Mô tả
1	Quản lý khách hàng	Đăng ký, đăng nhập, xác thực, quản lý thông tin cá nhân và lịch sử chuyến đi.
2	Quản lý tài xế	Đăng nhập, xác thực, quản lý thông tin tài xế, trạng thái hoạt động và thông tin phương tiện.
3	Quản lý đặt xe	Khách hàng tạo yêu cầu đặt xe, nhập điểm đón, điểm đến và thông tin chuyến.
4	Tìm kiếm tài xế	Hệ thống tự động tìm tài xế phù hợp với yêu cầu của khách hàng.
5	Phân công tài xế	Hệ thống phân công tài xế cho chuyến xe.
6	Quản lý chuyến xe	Theo dõi trạng thái chuyến: tạo → xác nhận → đang thực hiện → hoàn thành/hủy.
7	Tính cước	Xác định số tiền khách hàng cần thanh toán theo quy tắc kinh doanh.
8	Thanh toán	Hỗ trợ thanh toán tiền mặt và thanh toán trực tuyến.
9	Thông báo	Gửi thông báo về trạng thái đặt xe, tài xế, chuyến xe và thanh toán.
10	Đánh giá	Khách hàng đánh giá tài xế/chuyến xe sau khi hoàn thành.
11	Quản trị hệ thống	Quản lý tài khoản, quyền truy cập và cấu hình hệ thống.
12	Bảo mật & phân quyền	Xác thực người dùng, kiểm soát quyền và bảo vệ dữ liệu.
13	Logging/Audit	Lưu vết các thao tác quan trọng để kiểm tra khi có sự cố.
14	Báo cáo cơ bản	Cung cấp dữ liệu để doanh nghiệp theo dõi hoạt động của hệ thống.
4.3. Xác định các mô-đun cơ bản

Hệ thống CAB có thể được chia thành các mô-đun sau:

                         HỆ THỐNG CAB
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
  QUẢN LÝ NGƯỜI DÙNG    QUẢN LÝ ĐẶT XE       THANH TOÁN
        │                     │                     │
    ┌───┴───┐             ┌───┴────┐           ┌────┴────┐
    │       │             │        │           │         │
 Khách   Tài xế         Đặt xe   Tìm tài xế   Tiền mặt  Online
 hàng                 Phân công
        │                     │
        └─────────────────────┼─────────────────────┐
                              │                     │
                       QUẢN LÝ CHUYẾN          THÔNG BÁO
                              │                     │
                         TÍNH CƯỚC              ĐÁNH GIÁ
                              │
                         QUẢN TRỊ
                              │
                     BẢO MẬT / PHÂN QUYỀN
                              │
                       LOGGING / AUDIT
Danh sách mô-đun
Mã	Mô-đun	Chức năng chính
M01	Quản lý khách hàng	Tài khoản, thông tin cá nhân, lịch sử chuyến
M02	Quản lý tài xế	Tài khoản, trạng thái, phương tiện
M03	Đặt xe	Tạo và quản lý yêu cầu đặt xe
M04	Tìm & phân công tài xế	Tự động tìm và phân công tài xế
M05	Quản lý chuyến	Quản lý trạng thái và thông tin chuyến
M06	Tính cước	Tính số tiền phải thanh toán
M07	Thanh toán	Tiền mặt và trực tuyến
M08	Thông báo	Gửi thông báo cho khách hàng/tài xế
M09	Đánh giá	Đánh giá sau chuyến
M10	Quản trị	Quản lý tài khoản, quyền và cấu hình
M11	Bảo mật	Xác thực, phân quyền, bảo vệ dữ liệu
M12	Logging/Audit	Lưu vết thao tác quan trọng
M13	Báo cáo	Theo dõi hoạt động và dữ liệu cơ bản
4.4. Xác định MVP

MVP (Minimum Viable Product) là phiên bản đầu tiên có đủ chức năng cốt lõi để hệ thống CAB có thể vận hành và kiểm chứng nhu cầu thực tế.

Các chức năng MVP
Mã	Chức năng	Ưu tiên
MVP01	Đăng ký/đăng nhập khách hàng	🔴 Bắt buộc
MVP02	Đăng nhập/xác thực tài xế	🔴 Bắt buộc
MVP03	Tạo yêu cầu đặt xe	🔴 Bắt buộc
MVP04	Tự động tìm tài xế	🔴 Bắt buộc
MVP05	Phân công tài xế	🔴 Bắt buộc
MVP06	Tài xế nhận/phản hồi chuyến	🔴 Bắt buộc
MVP07	Quản lý trạng thái chuyến	🔴 Bắt buộc
MVP08	Tính cước cơ bản	🔴 Bắt buộc
MVP09	Thanh toán tiền mặt	🔴 Bắt buộc
MVP10	Thanh toán trực tuyến	🔴 Bắt buộc
MVP11	Thông báo cơ bản	🔴 Bắt buộc
MVP12	Đánh giá sau chuyến	🟡 Nên có
MVP13	Quản trị & phân quyền	🔴 Bắt buộc
MVP14	Logging/Audit	🔴 Bắt buộc
MVP phải đáp ứng 3 Business Goal chính
BG01
Giảm thời gian tìm tài xế
        ↓
Tự động tìm & phân công tài xế




BG02
Tự động hóa việc tìm tài xế
        ↓
Mô-đun tìm kiếm và phân công tài xế




BG03
Hỗ trợ thanh toán linh hoạt
        ↓
┌──────────────────┐
│ Thanh toán tiền mặt │
│ Thanh toán online   │
└──────────────────┘
4.5. IN SCOPE – Những gì sẽ thực hiện
Người dùng
Quản lý khách hàng.
Quản lý tài xế.
Quản lý thông tin phương tiện.
Đăng nhập và xác thực.
Phân quyền người dùng.
Quy trình đặt xe
Tạo yêu cầu đặt xe.
Tìm tài xế.
Phân công tài xế.
Tài xế phản hồi.
Quản lý trạng thái chuyến.
Hoàn thành/hủy chuyến.
Thanh toán
Tính cước.
Thanh toán tiền mặt.
Thanh toán trực tuyến.
Theo dõi trạng thái giao dịch.
Hỗ trợ
Thông báo.
Đánh giá.
Quản trị.
Logging/Audit.
Báo cáo cơ bản.
Bảo mật dữ liệu.
4.6. OUT OF SCOPE – Những gì không nên làm ở giai đoạn đầu

Để tránh Scope Creep (phạm vi dự án bị mở rộng không kiểm soát), các chức năng sau không nên đưa vào MVP:

Chức năng	Lý do
AI dự đoán nhu cầu đặt xe	Không cần thiết cho chức năng đặt xe cơ bản.
AI tự động tối ưu giá	Quy tắc tính cước hiện chưa được xác định.
Chương trình tích điểm nâng cao	Không thuộc quy trình đặt xe cốt lõi.
Hệ thống thành viên VIP phức tạp	Có thể phát triển ở giai đoạn sau.
Quảng cáo trên ứng dụng	Không phục vụ trực tiếp mục tiêu đặt xe.
Phân tích Big Data nâng cao	Chưa cần thiết khi hệ thống mới triển khai.
Chatbot AI	Có thể bổ sung sau khi hệ thống cốt lõi ổn định.
Quá nhiều loại dịch vụ CAB	Nên tập trung vào dịch vụ chính trước.
Tích hợp quá nhiều cổng thanh toán	Chỉ cần các phương thức đã được doanh nghiệp xác nhận.
Tích hợp nhiều nhà cung cấp thông báo cùng lúc	Chỉ cần thiết kế kiến trúc có khả năng thay đổi nhà cung cấp.
Các chức năng không liên quan đến đặt xe	Làm tăng chi phí và thời gian phát triển.
4.7. Các vấn đề chưa đưa vào phạm vi chính thức

Một số yêu cầu khách hàng chưa chốt, do đó BA không nên tự ý quyết định mà cần xác nhận:

STT	Nội dung cần xác nhận
1	Cách tính cước
2	Tiêu chí ưu tiên tài xế
3	Thời gian tài xế phải phản hồi
4	Chính sách hủy chuyến
5	Xử lý khi mất kết nối mạng
6	Thời gian lưu trữ dữ liệu
7	Quyền của từng loại người dùng
8	Phương thức thanh toán trực tuyến cụ thể
9	Nhà cung cấp thanh toán
10	Nhà cung cấp thông báo
11	Các loại dịch vụ CAB sẽ bổ sung trong tương lai
4.8. Tóm tắt phạm vi
IN SCOPE

Quản lý khách hàng → Quản lý tài xế → Đặt xe → Tìm tài xế → Phân công → Quản lý chuyến → Tính cước → Thanh toán tiền mặt/online → Thông báo → Đánh giá → Quản trị → Bảo mật → Logging.

OUT OF SCOPE

AI nâng cao → Quảng cáo → Big Data → Loyalty nâng cao → Chatbot AI → Quá nhiều dịch vụ mới → Các chức năng không trực tiếp phục vụ quy trình đặt xe.

Trọng tâm của MVP

MVP = Đặt xe + Tự động tìm tài xế + Phân công tài xế + Quản lý chuyến + Tính cước + Thanh toán tiền mặt/online + Thông báo + Quản trị cơ bản.

Như vậy, Bước 4 đã xác định được rõ phạm vi thực hiện, các mô-đun cơ bản, MVP, In Scope và Out of Scope, đồng thời tách riêng những yêu cầu chưa đủ thông tin để triển khai.

