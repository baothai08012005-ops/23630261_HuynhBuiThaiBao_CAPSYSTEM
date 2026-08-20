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
BƯỚC 5 – BUSINESS REQUIREMENT (BR)

Sau khi xác nhận yêu cầu với khách hàng, các Business Goal (BG) được chuyển thành các Business Requirement (BR) cụ thể.

5.1. Bảng Business Requirement
Mã & STT	Tên Business Requirement	Diễn giải
BR01	Tự động tìm kiếm tài xế	Hệ thống phải tự động tìm kiếm tài xế phù hợp với yêu cầu đặt xe của khách hàng, nhằm giảm thời gian chờ.
BR02	Tự động phân công tài xế	Hệ thống phải tự động phân công tài xế phù hợp cho chuyến xe, hạn chế việc nhân viên phải thực hiện thủ công.
BR03	Giảm thời gian chờ tài xế	Hệ thống phải tối ưu quá trình tìm kiếm và phân công để rút ngắn thời gian từ khi khách hàng tạo yêu cầu đến khi có tài xế xác nhận.
BR04	Quản lý yêu cầu đặt xe	Hệ thống phải tiếp nhận, lưu trữ và quản lý yêu cầu đặt xe của khách hàng trong suốt quá trình xử lý.
BR05	Quản lý thông tin tài xế	Hệ thống phải quản lý thông tin tài xế, trạng thái hoạt động và thông tin phương tiện để phục vụ việc tìm kiếm và phân công.
BR06	Thanh toán bằng tiền mặt	Hệ thống phải cho phép khách hàng lựa chọn thanh toán chuyến xe bằng tiền mặt.
BR07	Thanh toán trực tuyến	Hệ thống phải cho phép khách hàng thanh toán chuyến xe bằng phương thức thanh toán trực tuyến được doanh nghiệp hỗ trợ.
BR08	Quản lý trạng thái thanh toán	Hệ thống phải ghi nhận và quản lý trạng thái giao dịch như thành công, thất bại hoặc đang xử lý.
BR09	Thông báo trạng thái chuyến xe	Hệ thống phải thông báo cho khách hàng và tài xế về các trạng thái quan trọng của đặt xe và chuyến xe.
BR10	Đảm bảo thanh toán không làm gián đoạn hệ thống	Khi chức năng thanh toán gặp lỗi, lỗi đó không được làm toàn bộ hệ thống đặt xe ngừng hoạt động.
BR11	Bảo vệ thông tin người dùng	Hệ thống phải bảo vệ thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch.
BR12	Xác thực người dùng	Khách hàng và tài xế phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản.
BR13	Phân quyền quản trị	Hệ thống phải kiểm soát quyền truy cập đối với các chức năng quản trị.
BR14	Lưu vết hoạt động	Hệ thống phải lưu vết các thao tác quan trọng để phục vụ kiểm tra và xử lý sự cố.
BR15	Khả năng mở rộng hệ thống	Các thành phần của hệ thống phải có khả năng mở rộng độc lập khi tải tăng.
BR16	Triển khai chức năng từng phần	Hệ thống phải cho phép triển khai chức năng mới từng phần và hạn chế ảnh hưởng đến chức năng đang hoạt động.
BR17	Mở rộng loại dịch vụ	Kiến trúc phải cho phép bổ sung các loại dịch vụ CAB mới trong tương lai mà không phải xây dựng lại toàn bộ ứng dụng.
BR18	Thay đổi nhà cung cấp dịch vụ	Hệ thống phải cho phép bổ sung hoặc thay đổi nhà cung cấp thanh toán và thông báo mà hạn chế ảnh hưởng đến hệ thống hiện tại.
5.2. Liên kết BG → BR
Business Goal	Business Requirement hỗ trợ
BG01 – Giảm thời gian tìm và phân công tài xế	BR01, BR02, BR03, BR04, BR05
BG02 – Tự động hóa quy trình tìm tài xế	BR01, BR02, BR04, BR05
BG03 – Hỗ trợ thanh toán bằng tiền mặt hoặc trực tuyến	BR06, BR07, BR08, BR10
Tóm tắt Business Goal
Mã	Tên	Diễn giải
BG01	Giảm thời gian tìm và phân công tài xế	Rút ngắn thời gian khách hàng chờ được ghép với tài xế.
BG02	Tự động hóa tìm tài xế	Giảm thao tác thủ công bằng cách tự động tìm và phân công tài xế.
BG03	Hỗ trợ thanh toán linh hoạt	Cho phép khách hàng thanh toán bằng tiền mặt hoặc trực tuyến.

Quan hệ: BG (Business Goal) → BR (Business Requirement) → Functional Requirement (FR)
Tức là từ mục tiêu kinh doanh, ta xác định yêu cầu kinh doanh, sau đó mới phân rã thành yêu cầu chức năng cụ thể ở các bước tiếp theo.
BƯỚC 6 – XÂY DỰNG BUSINESS PROCESS ĐẶT CHUYẾN
6.1. Mục tiêu của Business Process

Xây dựng quy trình nghiệp vụ đặt chuyến CAB từ lúc khách hàng bắt đầu tạo chuyến cho đến khi tìm được tài xế và tài xế chấp nhận chuyến.

Quy trình này hỗ trợ trực tiếp:

BG01: Giảm thời gian tìm và phân công tài xế.
BG02: Tự động hóa quy trình tìm tài xế.
6.2. Business Process đặt chuyến
Quy trình tổng quát
┌──────────────────────┐
│      KHÁCH HÀNG      │
└──────────┬───────────┘
           │
           ▼
┌────────────────────────────┐
│ 1. Tạo yêu cầu đặt chuyến  │
└────────────┬───────────────┘
             │
             ▼
┌────────────────────────────┐
│ 2. Xác nhận điểm đón       │
│    và điểm đến             │
└────────────┬───────────────┘
             │
             ▼
┌────────────────────────────┐
│ 3. Hệ thống xác nhận       │
│    thông tin chuyến        │
└────────────┬───────────────┘
             │
             ▼
┌────────────────────────────┐
│ 4. Tìm tài xế phù hợp      │
└────────────┬───────────────┘
             │
             ▼
       ┌───────────────┐
       │ Tìm được      │
       │ tài xế?       │
       └───────┬───────┘
          Có   │   Không
               │
      ┌────────┘
      │
      ▼
┌──────────────────────────┐
│ Tiếp tục chờ / tìm kiếm  │
│ tài xế phù hợp           │
└──────────┬───────────────┘
           │
           └───────────────┐
                           │
                           ▼
                 ┌─────────────────────┐
                 │ Gửi yêu cầu cho     │
                 │ tài xế              │
                 └──────────┬──────────┘
                            │
                            ▼
                    ┌────────────────┐
                    │ Tài xế chấp    │
                    │ nhận chuyến?   │
                    └───────┬────────┘
                       Có   │   Không
                            │
               ┌────────────┘
               │
               ▼
      ┌─────────────────────┐
      │ Xác nhận tài xế     │
      │ và chuyến xe        │
      └──────────┬──────────┘
                 │
                 ▼
      ┌─────────────────────┐
      │ Khách hàng được     │
      │ thông báo           │
      └──────────┬──────────┘
                 │
                 ▼
      ┌─────────────────────┐
      │ Tài xế thực hiện    │
      │ chuyến đi           │
      └─────────────────────┘


Nếu tài xế KHÔNG chấp nhận:
          │
          ▼
┌─────────────────────────────┐
│ Thông báo/gửi yêu cầu đến   │
│ tài xế phù hợp tiếp theo    │
└──────────────┬──────────────┘
               │
               ▼
        Quay lại bước
        "Tài xế chấp nhận?"
6.3. Chi tiết Business Process
Bước	Tác nhân	Hoạt động	Kết quả
1	Khách hàng	Chọn chức năng đặt chuyến	Bắt đầu tạo chuyến
2	Khách hàng	Nhập/xác nhận điểm đón	Có điểm đón
3	Khách hàng	Nhập/xác nhận điểm đến	Có điểm đến
4	Hệ thống	Kiểm tra và xác nhận thông tin chuyến	Yêu cầu đặt chuyến hợp lệ
5	Hệ thống	Tìm kiếm tài xế phù hợp	Có hoặc chưa có tài xế
6	Hệ thống	Gửi yêu cầu đến tài xế	Tài xế nhận được yêu cầu
7	Tài xế	Xem và phản hồi yêu cầu	Chấp nhận hoặc từ chối
8A	Tài xế	Chấp nhận chuyến	Hệ thống xác nhận tài xế
9A	Hệ thống	Thông báo cho khách hàng	Khách hàng biết tài xế đã nhận
10A	Tài xế	Thực hiện chuyến	Chuyến bắt đầu
8B	Tài xế	Không chấp nhận chuyến	Hệ thống tìm tài xế khác
9B	Hệ thống	Gửi yêu cầu cho tài xế tiếp theo	Tiếp tục quá trình tìm tài xế
8C	Hệ thống	Chưa tìm được tài xế	Tiếp tục tìm/chờ tài xế phù hợp
6.4. Các nhánh xử lý chính
Trường hợp 1 – Tìm được tài xế và tài xế chấp nhận
Tìm tài xế
     ↓
Tìm được tài xế
     ↓
Gửi yêu cầu
     ↓
Tài xế chấp nhận
     ↓
Xác nhận chuyến
     ↓
Thông báo khách hàng
     ↓
Thực hiện chuyến
Trường hợp 2 – Tìm được tài xế nhưng tài xế không chấp nhận
Tìm tài xế
     ↓
Tìm được tài xế
     ↓
Gửi yêu cầu
     ↓
Tài xế không chấp nhận
     ↓
Tìm tài xế khác
     ↓
Gửi yêu cầu cho tài xế tiếp theo
     ↓
Chờ tài xế phản hồi
Trường hợp 3 – Chưa tìm được tài xế
Tìm tài xế
     ↓
Chưa tìm được
     ↓
Tiếp tục tìm kiếm
     ↓
Chờ tài xế phù hợp
     ↓
Tìm được tài xế?
     ↓
Có → Gửi yêu cầu cho tài xế
6.5. Business Process hoàn chỉnh
START
  │
  ▼
Khách hàng chọn "Đặt chuyến"
  │
  ▼
Nhập / xác nhận điểm đón
  │
  ▼
Nhập / xác nhận điểm đến
  │
  ▼
Hệ thống xác nhận yêu cầu
  │
  ▼
Tìm tài xế phù hợp
  │
  ▼
┌──────────────────────┐
│ Có tìm được tài xế?  │
└──────────┬───────────┘
       Không│       Có
            │        │
            ▼        ▼
     Tiếp tục tìm   Gửi yêu cầu
     / chờ tài xế   cho tài xế
            │        │
            │        ▼
            │   ┌───────────────────┐
            │   │ Tài xế chấp nhận? │
            │   └────────┬──────────┘
            │       Không│     Có
            │            │      │
            │            ▼      ▼
            │      Tìm tài xế  Xác nhận
            │         khác      chuyến
            │            │       │
            │            └───┐   ▼
            │                │ Thông báo
            │                │ khách hàng
            │                │   │
            └────────────────┘   ▼
                            Thực hiện chuyến
                                  │
                                  ▼
                                 END
6.6. Kết quả của Business Process

Quy trình đặt chuyến phải đảm bảo:

Khách hàng xác định được điểm đón và điểm đến.
Hệ thống tự động tìm tài xế.
Nếu tìm được tài xế → gửi yêu cầu để tài xế xác nhận.
Nếu tài xế chấp nhận → xác nhận chuyến và bắt đầu thực hiện.
Nếu tài xế không chấp nhận → hệ thống chuyển sang tài xế khác.
Nếu chưa tìm được tài xế → hệ thống tiếp tục tìm kiếm/chờ tài xế phù hợp.
Khách hàng được thông báo về trạng thái chuyến.

Đây là Business Process cốt lõi của hệ thống CAB và trực tiếp hiện thực hóa BR01 – Tự động tìm kiếm tài xế, BR02 – Tự động phân công tài xế và BR03 – Giảm thời gian chờ tài xế.
BƯỚC 7 – PHÂN RÃ BUSINESS REQUIREMENT THÀNH FUNCTIONAL REQUIREMENT

Ở bước này, các Business Requirement (BR) được phân rã thành các Functional Requirement (FR) cụ thể để mô tả hệ thống phải làm những gì.

BR → FR → Chức năng cụ thể của hệ thống

Đối với hệ thống CAB, phần quan trọng nhất là phân rã BR01 – Tự động tìm kiếm tài xế, BR02 – Tự động phân công tài xế và BR03 – Giảm thời gian chờ tài xế.

7.1. Phân rã BR01 – Tự động tìm kiếm tài xế

BR01: Hệ thống phải tự động tìm kiếm tài xế phù hợp với yêu cầu đặt xe của khách hàng.

Mã FR	Tên Functional Requirement	Diễn giải
FR01	Xác định vị trí khách hàng	Hệ thống phải xác định vị trí hiện tại của khách hàng dựa trên vị trí được cung cấp để làm cơ sở tìm tài xế.
FR02	Xác định điểm đón	Hệ thống phải cho phép khách hàng nhập hoặc xác nhận điểm đón của chuyến xe.
FR03	Xác định điểm đến	Hệ thống phải cho phép khách hàng nhập điểm đến của chuyến xe.
FR04	Lọc tài xế đang Online	Hệ thống phải lọc và chỉ lựa chọn những tài xế đang ở trạng thái Online/Sẵn sàng nhận chuyến.
FR05	Lọc tài xế theo vị trí	Hệ thống phải xác định các tài xế đang ở trong phạm vi phù hợp với điểm đón của khách hàng.
FR06	Lựa chọn loại xe	Hệ thống phải cho phép khách hàng lựa chọn loại xe phù hợp với nhu cầu.
FR07	Lọc tài xế theo loại xe	Hệ thống phải lựa chọn các tài xế có phương tiện phù hợp với loại xe mà khách hàng yêu cầu.
FR08	Ưu tiên tài xế có đánh giá cao	Hệ thống có thể ưu tiên các tài xế có mức đánh giá tốt khi lựa chọn tài xế phù hợp.
FR09	Xác định danh sách tài xế phù hợp	Hệ thống phải tạo danh sách các tài xế đáp ứng các tiêu chí tìm kiếm.
FR10	Xác định tài xế ưu tiên	Hệ thống phải xác định tài xế phù hợp nhất dựa trên các tiêu chí đã được doanh nghiệp xác nhận.
7.2. Phân rã BR02 – Tự động phân công tài xế

BR02: Hệ thống phải tự động phân công tài xế phù hợp cho chuyến xe.

Mã FR	Tên Functional Requirement	Diễn giải
FR11	Gửi yêu cầu nhận chuyến	Hệ thống phải gửi yêu cầu nhận chuyến đến tài xế được lựa chọn.
FR12	Hiển thị yêu cầu cho tài xế	Hệ thống phải hiển thị thông tin chuyến xe cho tài xế.
FR13	Tài xế chấp nhận chuyến	Hệ thống phải ghi nhận phản hồi khi tài xế chấp nhận chuyến.
FR14	Tài xế từ chối chuyến	Hệ thống phải ghi nhận phản hồi khi tài xế từ chối chuyến.
FR15	Tìm tài xế tiếp theo	Nếu tài xế từ chối, hệ thống phải tiếp tục tìm và gửi yêu cầu đến tài xế phù hợp tiếp theo.
FR16	Xác nhận tài xế	Khi tài xế chấp nhận, hệ thống phải xác nhận tài xế cho chuyến xe.
FR17	Thông báo cho khách hàng	Hệ thống phải thông báo cho khách hàng khi tài xế được xác nhận.
FR18	Cập nhật trạng thái chuyến	Hệ thống phải cập nhật trạng thái chuyến sau khi tài xế được phân công.
7.3. Phân rã BR03 – Giảm thời gian chờ tài xế

BR03: Hệ thống phải tối ưu quá trình tìm kiếm và phân công để giảm thời gian khách hàng chờ tài xế.

Mã FR	Tên Functional Requirement	Diễn giải
FR19	Tự động tìm kiếm liên tục	Hệ thống phải tiếp tục tìm tài xế khi chưa tìm được tài xế phù hợp.
FR20	Chuyển sang tài xế khác	Khi tài xế được gửi yêu cầu không phản hồi hoặc từ chối, hệ thống phải chuyển sang tài xế phù hợp khác.
FR21	Cập nhật trạng thái tìm tài xế	Hệ thống phải cập nhật trạng thái để khách hàng biết hệ thống đang tìm tài xế.
FR22	Thông báo kết quả tìm kiếm	Hệ thống phải thông báo cho khách hàng khi tìm được hoặc chưa tìm được tài xế.
FR23	Xử lý thời gian phản hồi	Hệ thống phải xử lý trường hợp tài xế không phản hồi trong khoảng thời gian được doanh nghiệp quy định.
7.4. Phân rã BR04 – Quản lý yêu cầu đặt xe

BR04: Hệ thống phải tiếp nhận và quản lý yêu cầu đặt xe.

Mã FR	Tên Functional Requirement	Diễn giải
FR24	Tạo yêu cầu đặt xe	Khách hàng có thể tạo yêu cầu đặt chuyến.
FR25	Kiểm tra thông tin đặt xe	Hệ thống kiểm tra các thông tin bắt buộc trước khi tạo chuyến.
FR26	Lưu thông tin chuyến	Hệ thống lưu điểm đón, điểm đến, loại xe và thông tin liên quan.
FR27	Cập nhật trạng thái chuyến	Hệ thống cập nhật trạng thái của yêu cầu đặt xe trong quá trình xử lý.
FR28	Hủy yêu cầu đặt xe	Hệ thống cho phép hủy chuyến theo chính sách hủy đã được doanh nghiệp xác nhận.
7.5. Phân rã BR05 – Quản lý thông tin tài xế

BR05: Hệ thống phải quản lý thông tin tài xế và phương tiện.

Mã FR	Tên Functional Requirement	Diễn giải
FR29	Quản lý thông tin tài xế	Hệ thống lưu trữ thông tin cần thiết của tài xế.
FR30	Quản lý thông tin phương tiện	Hệ thống lưu thông tin phương tiện của tài xế.
FR31	Quản lý trạng thái tài xế	Hệ thống phải ghi nhận tài xế đang Online, Offline hoặc đang thực hiện chuyến.
FR32	Quản lý đánh giá tài xế	Hệ thống lưu và cập nhật điểm đánh giá của tài xế.
7.6. Phân rã BR06 & BR07 – Thanh toán
BR06 – Thanh toán tiền mặt
Mã FR	Tên Functional Requirement	Diễn giải
FR33	Lựa chọn thanh toán tiền mặt	Khách hàng có thể chọn tiền mặt làm phương thức thanh toán.
FR34	Ghi nhận thanh toán tiền mặt	Hệ thống ghi nhận trạng thái thanh toán sau khi chuyến hoàn thành.
BR07 – Thanh toán trực tuyến
Mã FR	Tên Functional Requirement	Diễn giải
FR35	Lựa chọn thanh toán trực tuyến	Khách hàng có thể lựa chọn phương thức thanh toán trực tuyến.
FR36	Xử lý giao dịch trực tuyến	Hệ thống gửi và nhận kết quả giao dịch từ nhà cung cấp thanh toán.
FR37	Cập nhật trạng thái giao dịch	Hệ thống cập nhật giao dịch thành công, thất bại hoặc đang xử lý.
7.7. Sơ đồ phân rã BR → FR
BR01 – Tự động tìm kiếm tài xế
│
├── FR01 – Xác định vị trí khách hàng
├── FR02 – Xác định điểm đón
├── FR03 – Xác định điểm đến
├── FR04 – Lọc tài xế Online
├── FR05 – Lọc theo vị trí
├── FR06 – Lựa chọn loại xe
├── FR07 – Lọc theo loại xe
├── FR08 – Ưu tiên tài xế đánh giá cao
├── FR09 – Danh sách tài xế phù hợp
└── FR10 – Xác định tài xế ưu tiên




BR02 – Tự động phân công tài xế
│
├── FR11 – Gửi yêu cầu nhận chuyến
├── FR12 – Hiển thị yêu cầu
├── FR13 – Tài xế chấp nhận
├── FR14 – Tài xế từ chối
├── FR15 – Tìm tài xế tiếp theo
├── FR16 – Xác nhận tài xế
├── FR17 – Thông báo khách hàng
└── FR18 – Cập nhật trạng thái chuyến




BR03 – Giảm thời gian chờ tài xế
│
├── FR19 – Tự động tìm kiếm liên tục
├── FR20 – Chuyển sang tài xế khác
├── FR21 – Cập nhật trạng thái tìm kiếm
├── FR22 – Thông báo kết quả
└── FR23 – Xử lý thời gian phản hồi




BR04 – Quản lý yêu cầu đặt xe
│
├── FR24 – Tạo yêu cầu
├── FR25 – Kiểm tra thông tin
├── FR26 – Lưu thông tin chuyến
├── FR27 – Cập nhật trạng thái
└── FR28 – Hủy yêu cầu




BR05 – Quản lý tài xế
│
├── FR29 – Quản lý thông tin tài xế
├── FR30 – Quản lý phương tiện
├── FR31 – Quản lý trạng thái
└── FR32 – Quản lý đánh giá
7.8. Ví dụ luồng Functional Requirement tìm tài xế
Khách hàng tạo chuyến
        ↓
FR01: Xác định vị trí khách hàng
        ↓
FR02: Xác nhận điểm đón
        ↓
FR03: Xác nhận điểm đến
        ↓
FR06: Chọn loại xe
        ↓
FR04: Lọc tài xế Online
        ↓
FR05: Lọc tài xế theo vị trí
        ↓
FR07: Lọc theo loại xe
        ↓
FR08: Ưu tiên tài xế đánh giá cao
        ↓
FR10: Xác định tài xế ưu tiên
        ↓
FR11: Gửi yêu cầu nhận chuyến
        ↓
     ┌──────────────────┐
     │ Tài xế phản hồi? │
     └────────┬─────────┘
          Có  │  Không
              │
       ┌──────┴──────┐
       ↓             ↓
   Chấp nhận       Không phản hồi
       ↓             │
 Xác nhận chuyến     ↓
       │         FR20: Tìm tài xế khác
       ↓             │
 Thông báo KH        └──────→ Gửi yêu cầu mới

Kết quả của Bước 7: Từ các BR01–BR07, hệ thống đã được phân rã thành các FR01–FR37. Các FR này là cơ sở để sang bước tiếp theo thiết kế Use Case, giao diện, dữ liệu và quy trình xử lý chi tiết.
BƯỚC 8 – THIẾT KẾ BUSINESS RULE VÀ ACCESS/ASSIGNMENT RULE

Dựa trên các Business Requirement (BR) và Functional Requirement (FR) ở bước 7, bước này xác định các quy tắc nghiệp vụ (Business Rule) để hệ thống biết khi nào được thực hiện, điều kiện nào phải thỏa mãn và khi nào chuyển sang bước tiếp theo.

Trong ví dụ của bạn, “access” nên hiểu là accept/acceptance – tài xế chấp nhận chuyến; còn việc hệ thống giao chuyến cho tài xế là assignment – phân công.

8.1. Business Rule tổng quát
Mã	Tên Business Rule	Điều kiện / Quy tắc	Kết quả
BRULE01	Tài xế phải sẵn sàng	Chỉ tài xế có trạng thái Online/Sẵn sàng mới được đưa vào danh sách tìm kiếm.	Tài xế Offline không được nhận chuyến.
BRULE02	Tài xế phải phù hợp loại xe	Tài xế phải có loại xe phù hợp với loại xe khách hàng yêu cầu.	Chỉ tài xế phù hợp được lựa chọn.
BRULE03	Ưu tiên tài xế gần khách hàng	Trong danh sách tài xế phù hợp, hệ thống ưu tiên tài xế có khoảng cách gần điểm đón hơn.	Giảm thời gian chờ của khách hàng.
BRULE04	Ưu tiên tài xế có đánh giá cao	Khi các tài xế có điều kiện tương đương, hệ thống ưu tiên tài xế có đánh giá cao hơn.	Tăng chất lượng dịch vụ.
BRULE05	Một tài xế chỉ nhận một chuyến tại một thời điểm	Tài xế đang thực hiện hoặc đã nhận một chuyến không được nhận thêm chuyến khác.	Tránh trùng lịch/chuyến.
BRULE06	Tài xế phải phản hồi trong thời hạn	Tài xế phải chấp nhận hoặc từ chối yêu cầu trong khoảng thời gian được quy định.	Nếu hết thời gian → chuyển sang tài xế tiếp theo.
BRULE07	Tài xế từ chối chuyến	Nếu tài xế từ chối yêu cầu, hệ thống không tiếp tục gửi yêu cầu đó cho tài xế này.	Hệ thống tìm tài xế khác.
BRULE08	Tài xế không phản hồi	Nếu tài xế không phản hồi trước thời hạn, hệ thống xem yêu cầu là hết hạn.	Chuyển sang tài xế tiếp theo.
BRULE09	Chưa tìm được tài xế	Nếu chưa có tài xế phù hợp, hệ thống tiếp tục tìm kiếm/chờ tài xế.	Yêu cầu vẫn ở trạng thái đang tìm tài xế.
BRULE10	Tài xế chấp nhận chuyến	Khi tài xế chấp nhận trong thời hạn, hệ thống phải xác nhận tài xế cho chuyến.	Chuyến được phân công cho tài xế.
BRULE11	Không phân công trùng tài xế	Một chuyến chỉ được xác nhận với một tài xế tại một thời điểm.	Tránh hai tài xế cùng nhận một chuyến.
BRULE12	Thông báo kết quả	Khi tài xế được xác nhận, hệ thống phải thông báo cho khách hàng.	Khách hàng biết tài xế đã nhận chuyến.
BRULE13	Hủy yêu cầu tìm tài xế	Nếu khách hàng hủy yêu cầu trước khi có tài xế xác nhận, hệ thống dừng quá trình tìm tài xế.	Chuyến chuyển sang trạng thái đã hủy.
BRULE14	Tài xế không còn Online	Nếu tài xế chuyển Offline trước khi chấp nhận, hệ thống không được gửi yêu cầu mới cho tài xế đó.	Chọn tài xế khác.
BRULE15	Bảo đảm trạng thái chuyến	Hệ thống phải cập nhật trạng thái chuyến sau mỗi sự kiện quan trọng.	Trạng thái luôn phản ánh đúng quá trình xử lý.
8.2. Quy tắc Assignment – Phân công tài xế
Quy trình lựa chọn tài xế
Khách hàng tạo chuyến
        ↓
Xác định điểm đón + điểm đến
        ↓
Xác định loại xe
        ↓
Lấy danh sách tài xế
        ↓
┌──────────────────────────────┐
│ Tài xế đang Online/Sẵn sàng? │
└──────────────┬───────────────┘
               │ Có
               ↓
┌──────────────────────────────┐
│ Có đúng loại xe yêu cầu?     │
└──────────────┬───────────────┘
               │ Có
               ↓
┌──────────────────────────────┐
│ Tính mức độ phù hợp          │
│ - Khoảng cách                │
│ - Loại xe                    │
│ - Đánh giá                   │
└──────────────┬───────────────┘
               ↓
       Xếp hạng tài xế
               ↓
       Chọn tài xế ưu tiên
               ↓
       Gửi yêu cầu nhận chuyến
8.3. Quy tắc Accept – Tài xế chấp nhận chuyến

Tài xế chỉ được xem là đã nhận chuyến khi:

Tài xế Online
      +
Tài xế phù hợp loại xe
      +
Chưa có chuyến đang thực hiện
      +
Phản hồi trong thời hạn
      +
Chấp nhận yêu cầu
      ↓
XÁC NHẬN NHẬN CHUYẾN

Nếu thiếu một trong các điều kiện trên, hệ thống không xác nhận tài xế.

8.4. Quy tắc hết thời gian phản hồi

Đây là quy tắc quan trọng trong hệ thống.

Trường hợp tài xế không phản hồi
Gửi yêu cầu cho tài xế
          ↓
     Bắt đầu đếm giờ
          ↓
   ┌──────────────────┐
   │ Tài xế phản hồi? │
   └────────┬─────────┘
       Có   │   Không
            │
      ┌─────┴─────┐
      ↓           ↓
 Chấp nhận      Hết thời gian
      ↓           ↓
 Xác nhận       Đánh dấu
 chuyến         "Timeout"
                  ↓
           Tìm tài xế tiếp theo
                  ↓
           Gửi yêu cầu mới
Business Rule

BRULE06: Tài xế phải phản hồi yêu cầu trong thời gian quy định.

BRULE08: Nếu tài xế không phản hồi trước thời hạn, hệ thống tự động chuyển sang tài xế phù hợp tiếp theo.

Lưu ý: Thời gian cụ thể, ví dụ 15 giây, 30 giây..., phải được khách hàng xác nhận trước khi đưa thành yêu cầu chính thức.

8.5. Trường hợp tài xế từ chối
Gửi yêu cầu
     ↓
Tài xế từ chối
     ↓
Cập nhật trạng thái = REJECTED
     ↓
Loại tài xế khỏi yêu cầu hiện tại
     ↓
Tìm tài xế tiếp theo
     ↓
Gửi yêu cầu mới
Quy tắc

BRULE07: Khi tài xế từ chối chuyến, hệ thống phải tự động tìm tài xế phù hợp tiếp theo.

8.6. Trường hợp chưa tìm được tài xế
Tìm tài xế
     ↓
Không có tài xế phù hợp
     ↓
Trạng thái = SEARCHING
     ↓
Tiếp tục tìm kiếm
     ↓
Có tài xế phù hợp?
     │
   ┌─┴─┐
 Không Có
   │    │
   │    ↓
   │  Gửi yêu cầu
   │  cho tài xế
   │
   └──→ Tiếp tục chờ
Quy tắc

BRULE09: Nếu chưa tìm được tài xế, yêu cầu đặt xe vẫn ở trạng thái SEARCHING và hệ thống tiếp tục tìm kiếm theo chính sách đã xác định.

8.7. Quy tắc trạng thái tài xế
Trạng thái	Có được nhận chuyến mới?	Giải thích
ONLINE	✅ Có	Tài xế đang sẵn sàng nhận chuyến.
OFFLINE	❌ Không	Không tham gia tìm kiếm tài xế.
BUSY	❌ Không	Đang thực hiện chuyến khác.
ACCEPTING	❌ Không	Đang xử lý một yêu cầu nhận chuyến.
ON_TRIP	❌ Không	Đang thực hiện chuyến.
8.8. Quy tắc trạng thái chuyến
Trạng thái	Ý nghĩa
REQUESTED	Khách hàng vừa tạo yêu cầu.
SEARCHING	Hệ thống đang tìm tài xế.
OFFERED	Hệ thống đã gửi yêu cầu cho tài xế.
ACCEPTED	Tài xế đã chấp nhận chuyến.
DRIVER_ASSIGNED	Tài xế đã được phân công chính thức.
ON_TRIP	Chuyến đang được thực hiện.
COMPLETED	Chuyến đã hoàn thành.
CANCELLED	Chuyến đã bị hủy.
8.9. Tổng hợp Business Rule cho quy trình tìm tài xế
                    TẠO CHUYẾN
                        │
                        ▼
                SEARCHING
                        │
                        ▼
             Lọc tài xế ONLINE
                        │
                        ▼
              Lọc theo loại xe
                        │
                        ▼
            Lọc theo khoảng cách
                        │
                        ▼
          Ưu tiên đánh giá cao
                        │
                        ▼
             Chọn tài xế ưu tiên
                        │
                        ▼
              Gửi yêu cầu nhận
                        │
                 ┌──────┴──────┐
                 │             │
              CHẤP NHẬN      TỪ CHỐI/
                 │           TIMEOUT
                 ▼             │
             ACCEPTED          ▼
                 │       Tìm tài xế tiếp
                 ▼             │
         DRIVER_ASSIGNED ◄─────┘
                 │
                 ▼
              ON_TRIP
                 │
                 ▼
             COMPLETED
8.10. Các Business Rule cần khách hàng xác nhận

Một số quy tắc chưa nên tự quyết định vì yêu cầu ban đầu chưa xác định rõ:

Nội dung cần xác nhận	Ví dụ
Thời gian tài xế phản hồi	15 giây / 30 giây / 60 giây
Phạm vi tìm tài xế	1 km / 3 km / 5 km
Tiêu chí ưu tiên	Khoảng cách hay đánh giá cao hơn?
Tỷ trọng đánh giá	Đánh giá có quan trọng hơn khoảng cách không?
Số tài xế được gửi cùng lúc	1 tài xế hay nhiều tài xế?
Số lần tìm lại	Tìm liên tục hay giới hạn số lần?
Khi không có tài xế	Tiếp tục chờ hay thông báo không có tài xế?
Khi tài xế mất kết nối	Có tự động chuyển sang tài xế khác không?
Chính sách hủy	Khách hàng có thể hủy ở trạng thái nào?
Kết luận Bước 8

Business Rule cốt lõi: Chỉ tài xế Online/Sẵn sàng và phù hợp mới được đưa vào quá trình phân công. Hệ thống ưu tiên tài xế theo các tiêu chí đã được doanh nghiệp xác nhận. Khi tài xế chấp nhận trong thời hạn, chuyến được xác nhận. Nếu tài xế từ chối hoặc hết thời gian phản hồi, hệ thống tự động chuyển sang tài xế phù hợp tiếp theo. Nếu chưa có tài xế, hệ thống tiếp tục ở trạng thái SEARCHING cho đến khi tìm được hoặc áp dụng chính sách kết thúc tìm kiếm.
BƯỚC 9 – XÂY DỰNG DATA MODELING VÀ MÔ HÌNH ERD

Dựa trên các Business Requirement (BR), Functional Requirement (FR) và Business Process đã xây dựng ở các bước trước, ta xác định các thực thể (Entity), thuộc tính và mối quan hệ giữa chúng.

9.1. Xác định các thực thể chính
Mã	Thực thể	Vai trò
E01	CUSTOMER	Lưu thông tin khách hàng sử dụng dịch vụ đặt xe.
E02	DRIVER	Lưu thông tin tài xế và trạng thái hoạt động.
E03	VEHICLE	Lưu thông tin phương tiện của tài xế.
E04	TRIP	Lưu thông tin chuyến xe do khách hàng tạo.
E05	DRIVER_ASSIGNMENT	Quản lý quá trình hệ thống tìm và phân công tài xế cho chuyến.
E06	PAYMENT	Lưu thông tin thanh toán của chuyến xe.
E07	NOTIFICATION	Lưu các thông báo gửi cho khách hàng/tài xế.
E08	REVIEW	Lưu đánh giá của khách hàng sau chuyến.
E09	LOCATION	Lưu thông tin vị trí phục vụ tìm kiếm và theo dõi.
E10	VEHICLE_TYPE	Danh mục loại xe mà khách hàng có thể lựa chọn.
E11	AUDIT_LOG	Lưu vết các thao tác quan trọng trong hệ thống.
9.2. Chi tiết các thực thể
CUSTOMER
Thuộc tính	Ý nghĩa
customer_id (PK)	Mã khách hàng
full_name	Họ tên
phone	Số điện thoại
email	Email
password_hash	Mật khẩu đã mã hóa
status	Trạng thái tài khoản
created_at	Ngày tạo
DRIVER
Thuộc tính	Ý nghĩa
driver_id (PK)	Mã tài xế
full_name	Họ tên
phone	Số điện thoại
email	Email
password_hash	Mật khẩu đã mã hóa
status	ONLINE, OFFLINE, BUSY
rating	Điểm đánh giá
created_at	Ngày tạo
VEHICLE
Thuộc tính	Ý nghĩa
vehicle_id (PK)	Mã phương tiện
driver_id (FK)	Tài xế sở hữu
vehicle_type_id (FK)	Loại xe
license_plate	Biển số xe
brand	Hãng xe
model	Model xe
status	Trạng thái phương tiện
VEHICLE_TYPE
Thuộc tính	Ý nghĩa
vehicle_type_id (PK)	Mã loại xe
name	Tên loại xe
description	Mô tả
status	Trạng thái

Ví dụ:

CAB 4 chỗ
CAB 7 chỗ
Các loại xe khác trong tương lai
TRIP
Thuộc tính	Ý nghĩa
trip_id (PK)	Mã chuyến
customer_id (FK)	Khách hàng đặt chuyến
vehicle_type_id (FK)	Loại xe yêu cầu
pickup_location_id (FK)	Điểm đón
destination_location_id (FK)	Điểm đến
status	Trạng thái chuyến
fare	Cước chuyến
requested_at	Thời gian tạo yêu cầu
completed_at	Thời gian hoàn thành
DRIVER_ASSIGNMENT

Đây là thực thể rất quan trọng đối với bài toán tìm tài xế.

Nó lưu lại quá trình:

Tìm tài xế → Gửi yêu cầu → Tài xế chấp nhận/từ chối/timeout → Nếu thất bại thì tìm tài xế tiếp theo.

Thuộc tính	Ý nghĩa
assignment_id (PK)	Mã lần phân công
trip_id (FK)	Mã chuyến
driver_id (FK)	Tài xế được gửi yêu cầu
status	OFFERED, ACCEPTED, REJECTED, TIMEOUT
sent_at	Thời gian gửi yêu cầu
responded_at	Thời gian tài xế phản hồi
expired_at	Thời gian hết hạn
priority	Thứ tự ưu tiên

Ví dụ:

Trip #T001
   │
   ├── Driver A → REJECTED
   │
   ├── Driver B → TIMEOUT
   │
   └── Driver C → ACCEPTED

Nhờ DRIVER_ASSIGNMENT, hệ thống có thể lưu lại lịch sử tìm tài xế thay vì chỉ lưu tài xế cuối cùng.

9.3. Quan hệ giữa các thực thể
Các quan hệ chính
CUSTOMER 1 ─────── N TRIP


TRIP 1 ─────────── N DRIVER_ASSIGNMENT


DRIVER 1 ───────── N DRIVER_ASSIGNMENT


DRIVER 1 ───────── N VEHICLE


VEHICLE_TYPE 1 ─── N VEHICLE


VEHICLE_TYPE 1 ─── N TRIP


TRIP 1 ─────────── 1 PAYMENT


TRIP 1 ─────────── N REVIEW


CUSTOMER 1 ─────── N REVIEW


DRIVER 1 ───────── N REVIEW


CUSTOMER 1 ─────── N NOTIFICATION


DRIVER 1 ───────── N NOTIFICATION


TRIP 1 ─────────── N NOTIFICATION


TRIP 1 ─────────── N LOCATION
9.4. ERD bằng Mermaid

Có thể sử dụng đoạn code Mermaid dưới đây để vẽ Entity Relationship Diagram:

erDiagram
    DRIVER_ASSIGNMENT {
        int assignment_id PK
        int trip_id FK
        int driver_id FK
        string status
        int priority
        datetime sent_at
        datetime responded_at
        datetime expired_at
    }


    PAYMENT {
        int payment_id PK
        int trip_id FK
        decimal amount
        string payment_method
        string payment_status
        string transaction_id
        datetime paid_at
    }


    NOTIFICATION {
        int notification_id PK
        int customer_id FK
        int driver_id FK
        int trip_id FK
        string type
        string title
        string message
        string status
        datetime created_at
    }


    REVIEW {
        int review_id PK
        int trip_id FK
        int customer_id FK
        int driver_id FK
        int rating
        string comment
        datetime created_at
    }


    AUDIT_LOG {
        int log_id PK
        int customer_id FK
        int driver_id FK
        string action
        string entity_type
        int entity_id
        string ip_address
        datetime created_at
    }


    CUSTOMER ||--o{ TRIP : "creates"


    DRIVER ||--o{ VEHICLE : "owns"


    VEHICLE_TYPE ||--o{ VEHICLE : "classifies"


    VEHICLE_TYPE ||--o{ TRIP : "requested"


    LOCATION ||--o{ TRIP : "pickup"


    LOCATION ||--o{ TRIP : "destination"


    TRIP ||--o{ DRIVER_ASSIGNMENT : "has"


    DRIVER ||--o{ DRIVER_ASSIGNMENT : "receives"


    TRIP ||--o| PAYMENT : "has"


    CUSTOMER ||--o{ REVIEW : "writes"


    DRIVER ||--o{ REVIEW : "receives"


    TRIP ||--o| REVIEW : "has"


    CUSTOMER ||--o{ NOTIFICATION : "receives"


    DRIVER ||--o{ NOTIFICATION : "receives"


    TRIP ||--o{ NOTIFICATION : "generates"


    CUSTOMER ||--o{ AUDIT_LOG : "performs"


    DRIVER ||--o{ AUDIT_LOG : "performs"
9.5. Giải thích luồng dữ liệu đặt chuyến

Mô hình dữ liệu trên phản ánh đúng Business Process ở Bước 6:

CUSTOMER
    │
    │ tạo yêu cầu
    ▼
TRIP
    │
    ├── Điểm đón ───────► LOCATION
    │
    ├── Điểm đến ───────► LOCATION
    │
    └── Loại xe ────────► VEHICLE_TYPE
             │
             ▼
    DRIVER_ASSIGNMENT
             │
       ┌─────┼─────┐
       ▼     ▼     ▼
    Driver A  B    C
    Reject   Timeout Accept
                    │
                    ▼
                  TRIP
                    │
          ┌─────────┼─────────┐
          ▼         ▼         ▼
       PAYMENT  NOTIFICATION REVIEW
9.6. Tại sao cần DRIVER_ASSIGNMENT?

Đây là điểm quan trọng nhất của Data Modeling cho bài này.

Không nên chỉ đặt:

TRIP
 └── driver_id

vì cách này không lưu được quá trình tìm tài xế.

Ví dụ:

Chuyến T001
   │
   ├── Tài xế A → Từ chối
   ├── Tài xế B → Timeout
   ├── Tài xế C → Từ chối
   └── Tài xế D → Chấp nhận

Vì vậy cần:

TRIP
  │
  └── DRIVER_ASSIGNMENT
          ├── Driver A – REJECTED
          ├── Driver B – TIMEOUT
          ├── Driver C – REJECTED
          └── Driver D – ACCEPTED

Điều này giúp hệ thống:

Theo dõi lịch sử tìm tài xế.
Biết tài xế nào đã từ chối.
Biết tài xế nào không phản hồi.
Tự động chuyển sang tài xế tiếp theo.
Phục vụ Audit/Logging.
Phân tích hiệu quả của thuật toán phân công tài xế.
9.7. Kết quả của Bước 9
Các thực thể cốt lõi

CUSTOMER → TRIP → DRIVER_ASSIGNMENT → DRIVER → VEHICLE

Các thực thể hỗ trợ

VEHICLE_TYPE → LOCATION → PAYMENT → NOTIFICATION → REVIEW → AUDIT_LOG

Luồng dữ liệu chính

Khách hàng tạo TRIP → hệ thống xác định LOCATION và VEHICLE_TYPE → tìm DRIVER → ghi nhận quá trình vào DRIVER_ASSIGNMENT → tài xế ACCEPTED → thực hiện chuyến → PAYMENT → REVIEW/NOTIFICATION.

Mô hình này là nền tảng để bước tiếp theo có thể xây dựng Database Schema, Use Case chi tiết và API/Service cho hệ thống CAB.
BƯỚC 10 – XÁC ĐỊNH NON-FUNCTIONAL REQUIREMENT (NFR)

Non-Functional Requirement (NFR) là các yêu cầu mô tả hệ thống phải hoạt động như thế nào, thay vì hệ thống phải thực hiện chức năng gì.

Ví dụ:

FR: Hệ thống tìm tài xế.
NFR: Hệ thống phải tìm tài xế trong tối đa 5 giây trong điều kiện tải bình thường.

Dựa trên yêu cầu sơ khởi của khách hàng, ta xác định các NFR sau:

10.1. Bảng Non-Functional Requirement
Mã	Nhóm NFR	Tên yêu cầu	Diễn giải
NFR01	Performance	Thời gian phản hồi	Hệ thống phải phản hồi các thao tác chính trong thời gian phù hợp để không gây cảm giác chậm cho khách hàng.
NFR02	Performance	Thời gian tìm tài xế	Hệ thống phải tối ưu thời gian tìm và phân công tài xế nhằm giảm thời gian khách hàng chờ.
NFR03	Scalability	Khả năng mở rộng	Hệ thống phải có khả năng mở rộng khi số lượng khách hàng, tài xế và yêu cầu đặt xe tăng cao.
NFR04	Scalability	Mở rộng độc lập	Các thành phần như tìm tài xế, thanh toán, thông báo phải có khả năng mở rộng độc lập khi tải tăng.
NFR05	Availability	Tính sẵn sàng	Hệ thống phải hoạt động ổn định, đặc biệt trong thời điểm nhu cầu đặt xe tăng cao.
NFR06	Reliability	Khả năng chịu lỗi	Lỗi ở một thành phần như thanh toán hoặc thông báo không được làm toàn bộ hệ thống đặt xe ngừng hoạt động.
NFR07	Reliability	Khôi phục sau sự cố	Hệ thống phải có khả năng phát hiện và khôi phục sau các lỗi hoặc sự cố phù hợp với mức độ quan trọng của dịch vụ.
NFR08	Security	Xác thực	Người dùng phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản.
NFR09	Security	Phân quyền	Hệ thống phải kiểm soát quyền truy cập đối với các chức năng quản trị.
NFR10	Security	Bảo vệ dữ liệu cá nhân	Thông tin khách hàng, tài xế và các dữ liệu nhạy cảm phải được bảo vệ khỏi truy cập trái phép.
NFR11	Security	Bảo vệ dữ liệu vị trí	Dữ liệu vị trí của khách hàng và tài xế phải được bảo vệ và chỉ sử dụng cho mục đích được cấp quyền.
NFR12	Security	Bảo vệ dữ liệu giao dịch	Thông tin liên quan đến giao dịch thanh toán phải được bảo vệ khỏi truy cập và thay đổi trái phép.
NFR13	Auditability	Lưu vết hoạt động	Hệ thống phải ghi nhận các thao tác quan trọng để phục vụ kiểm tra và điều tra khi xảy ra sự cố.
NFR14	Maintainability	Khả năng bảo trì	Hệ thống phải được thiết kế để dễ dàng bảo trì, sửa lỗi và nâng cấp.
NFR15	Maintainability	Triển khai từng phần	Chức năng mới có thể được triển khai từng phần mà hạn chế ảnh hưởng đến các chức năng đang hoạt động.
NFR16	Flexibility	Khả năng mở rộng dịch vụ	Kiến trúc phải cho phép bổ sung các loại dịch vụ CAB mới mà không phải xây dựng lại toàn bộ ứng dụng.
NFR17	Flexibility	Mở rộng phương thức thanh toán	Hệ thống phải có khả năng bổ sung phương thức thanh toán mới trong tương lai.
NFR18	Flexibility	Thay đổi nhà cung cấp	Có thể thay đổi nhà cung cấp thanh toán hoặc thông báo mà hạn chế ảnh hưởng đến các thành phần khác.
NFR19	Usability	Dễ sử dụng	Giao diện đặt xe phải đơn giản, dễ hiểu để khách hàng có thể tạo chuyến mà không cần nhiều thao tác.
NFR20	Compatibility	Khả năng tương thích	Hệ thống phải có khả năng tích hợp với các dịch vụ bên ngoài như bản đồ, thanh toán và thông báo.
10.2. Các NFR quan trọng nhất của hệ thống CAB

Từ yêu cầu khách hàng, có thể chia thành 6 nhóm chính:

                    NON-FUNCTIONAL
                     REQUIREMENT
                          │
       ┌──────────────────┼──────────────────┐
       │                  │                  │
       ▼                  ▼                  ▼
 Performance         Availability        Security
       │                  │                  │
       │                  │                  ├─ Authentication
       ├─ Response time   ├─ Stability      ├─ Authorization
       ├─ Driver search   └─ Fault tolerance └─ Data protection
       └─ Scalability
       │
       ├──────────────────┐
       ▼                  ▼
 Maintainability      Flexibility
       │                  │
       ├─ Easy update     ├─ New services
       ├─ Partial deploy  ├─ New payment
       └─ Easy maintain   └─ New providers
10.3. Performance – Hiệu năng
NFR01 – Thời gian phản hồi

Hệ thống phải phản hồi nhanh đối với các thao tác quan trọng như:

Tạo chuyến.
Xác nhận điểm đón/điểm đến.
Tìm tài xế.
Gửi yêu cầu cho tài xế.
Cập nhật trạng thái chuyến.

Lưu ý: Con số cụ thể như ≤ 2 giây hoặc ≤ 5 giây cần được khách hàng xác nhận trước khi trở thành tiêu chuẩn chính thức.

NFR02 – Tìm tài xế

Hệ thống phải tối ưu quá trình tìm tài xế để đáp ứng mục tiêu giảm thời gian chờ của khách hàng.

10.4. Scalability – Khả năng mở rộng

Đây là yêu cầu rất quan trọng vì khách hàng nói rõ:

Hệ thống phải hoạt động ổn định vào thời điểm nhu cầu tăng cao.

Do đó:

              TẢI TĂNG
                 │
        ┌────────┼─────────┐
        ▼        ▼         ▼
     Booking   Driver    Payment
        │        │         │
        ▼        ▼         ▼
    Scale     Scale     Scale
   độc lập   độc lập   độc lập

Ví dụ:

Khi lượng đặt xe tăng → mở rộng Booking/Trip Service.
Khi lượng tài xế tăng → mở rộng Driver/Matching Service.
Khi giao dịch tăng → mở rộng Payment Service.

Không bắt buộc phải mở rộng toàn bộ hệ thống cùng lúc.

10.5. Availability & Reliability
NFR05 – Availability

Hệ thống phải duy trì khả năng phục vụ ngay cả khi nhu cầu tăng cao.

NFR06 – Fault Tolerance

Một lỗi ở một thành phần không được làm toàn bộ hệ thống ngừng hoạt động.

Ví dụ:

Booking
   │
   ├──────────► Driver Matching
   │
   ├──────────► Payment
   │                 ❌ ERROR
   │
   └──────────► Notification

Nếu Payment lỗi:

Payment ❌
   │
   └── Không được làm
       Booking ❌
       Driver Matching ❌

Hệ thống đặt xe vẫn phải có khả năng tiếp tục xử lý trong phạm vi nghiệp vụ cho phép.

10.6. Security – Bảo mật

Hệ thống phải đảm bảo:

Authentication
      ↓
Authorization
      ↓
Data Protection
      ↓
Audit Logging
Bao gồm:
Xác thực khách hàng.
Xác thực tài xế.
Phân quyền quản trị viên.
Bảo vệ thông tin cá nhân.
Bảo vệ thông tin phương tiện.
Bảo vệ dữ liệu vị trí.
Bảo vệ dữ liệu giao dịch.
Lưu vết các thao tác quan trọng.
10.7. Maintainability – Khả năng bảo trì

Hệ thống phải dễ:

Sửa lỗi.
Nâng cấp.
Thêm chức năng.
Thay đổi thành phần.
Triển khai phiên bản mới.

Đặc biệt:

Chức năng mới phải có thể triển khai từng phần và hạn chế ảnh hưởng đến chức năng đang hoạt động.

10.8. Flexibility – Khả năng mở rộng trong tương lai

Kiến trúc phải cho phép:

Hệ thống hiện tại
       │
       ├── Thêm dịch vụ CAB mới
       │
       ├── Thêm phương thức thanh toán
       │
       ├── Thêm nhà cung cấp thông báo
       │
       └── Thay đổi thành phần kỹ thuật

Mà không phải xây dựng lại toàn bộ ứng dụng.

10.9. Những yêu cầu CHƯA NÊN CHỐT

Theo yêu cầu khách hàng ở giai đoạn đầu, một số NFR vẫn cần được BA xác nhận thêm:

Nội dung	Chưa xác định
Thời gian phản hồi tối đa	Chưa có con số cụ thể
Số lượng người dùng đồng thời	Chưa xác định
Số chuyến/giây cần xử lý	Chưa xác định
Mức Availability	Chưa xác định
Thời gian khôi phục sau sự cố	Chưa xác định
Thời gian lưu Audit Log	Chưa xác định
Thời gian lưu dữ liệu	Khách hàng chưa chốt
Thời gian tài xế phải phản hồi	Chưa chốt
Chính sách khi mất mạng	Chưa chốt
10.10. Tổng kết Bước 10

Có thể nhóm NFR của hệ thống CAB thành:

Nhóm	Các yêu cầu chính
Performance	NFR01, NFR02
Scalability	NFR03, NFR04
Availability & Reliability	NFR05, NFR06, NFR07
Security	NFR08 → NFR13
Maintainability	NFR14, NFR15
Flexibility	NFR16 → NFR18
Usability	NFR19
Compatibility	NFR20
Điểm quan trọng

FR trả lời câu hỏi:

“Hệ thống phải làm gì?”

Ví dụ: FR01 – Tìm vị trí khách hàng.

NFR trả lời câu hỏi:

“Hệ thống phải làm việc đó như thế nào?”

Ví dụ: NFR01 – Hệ thống phải phản hồi nhanh và ổn định khi số lượng yêu cầu tăng cao.
BƯỚC 11–12: XÁC ĐỊNH, VẼ VÀ ĐẶC TẢ USE CASE

Dựa trên các bước trước, ta xác định các Actor và Use Case (UC) của hệ thống CAB.

Quy ước mã: UC01, UC02, UC03...
Ví dụ: UC01 – Đăng ký tài khoản, UC02 – Đăng nhập.

11.1. Xác định Actor
Mã	Actor	Vai trò
A01	Customer	Người đặt chuyến, theo dõi chuyến, thanh toán và đánh giá tài xế.
A02	Driver	Người nhận chuyến, thực hiện chuyến và cập nhật trạng thái chuyến.
A03	Admin	Quản lý khách hàng, tài xế, chuyến xe và theo dõi hoạt động hệ thống.
A04	Payment Gateway	Hệ thống bên ngoài hỗ trợ thanh toán trực tuyến.
A05	Map/Location Service	Cung cấp vị trí, bản đồ và hỗ trợ xác định khoảng cách.
A06	Notification Service	Cung cấp dịch vụ gửi thông báo cho khách hàng và tài xế.
11.2. Danh sách Use Case
Customer
Mã	Use Case
UC01	Customer – Đăng ký tài khoản
UC02	Customer – Đăng nhập
UC03	Customer – Tạo yêu cầu đặt chuyến
UC04	Customer – Xác định điểm đón
UC05	Customer – Xác định điểm đến
UC06	Customer – Chọn loại xe
UC07	Customer – Theo dõi trạng thái tìm tài xế
UC08	Customer – Xem thông tin tài xế
UC09	Customer – Hủy chuyến
UC10	Customer – Chọn phương thức thanh toán
UC11	Customer – Thanh toán chuyến
UC12	Customer – Đánh giá tài xế
Driver
Mã	Use Case
UC13	Driver – Đăng nhập
UC14	Driver – Chuyển trạng thái Online/Offline
UC15	Driver – Nhận yêu cầu chuyến
UC16	Driver – Chấp nhận chuyến
UC17	Driver – Từ chối chuyến
UC18	Driver – Thực hiện chuyến
UC19	Driver – Cập nhật trạng thái chuyến
UC20	Driver – Xem lịch sử chuyến
Admin
Mã	Use Case
UC21	Admin – Đăng nhập quản trị
UC22	Admin – Quản lý khách hàng
UC23	Admin – Quản lý tài xế
UC24	Admin – Quản lý phương tiện
UC25	Admin – Quản lý chuyến xe
UC26	Admin – Theo dõi hoạt động hệ thống
UC27	Admin – Xem Audit Log
Hệ thống bên ngoài
Mã	Use Case
UC28	Payment Gateway – Xử lý thanh toán trực tuyến
UC29	Map Service – Xác định vị trí/khoảng cách
UC30	Notification Service – Gửi thông báo
11.3. Use Case quan trọng nhất: Đặt chuyến

Đối với bài toán CAB, UC03 – Customer – Tạo yêu cầu đặt chuyến là Use Case trung tâm.

Nó liên kết với:

UC03 – Customer: Tạo yêu cầu đặt chuyến
             │
             ├── UC04: Xác định điểm đón
             ├── UC05: Xác định điểm đến
             ├── UC06: Chọn loại xe
             │
             └── Hệ thống tìm tài xế
                       │
                       ├── Lọc tài xế Online
                       ├── Lọc theo loại xe
                       ├── Ưu tiên tài xế phù hợp
                       ├── Gửi yêu cầu
                       └── Chờ tài xế chấp nhận
11.4. Use Case Diagram bằng Mermaid
flowchart LR


    Customer["A01 - Customer"]
    Driver["A02 - Driver"]
    Admin["A03 - Admin"]
    Payment["A04 - Payment Gateway"]
    Map["A05 - Map / Location Service"]
    Notify["A06 - Notification Service"]


    subgraph CAB["CAB SYSTEM"]


        UC01["UC01 - Đăng ký tài khoản"]
        UC02["UC02 - Đăng nhập"]


        UC03["UC03 - Tạo yêu cầu đặt chuyến"]
        UC04["UC04 - Xác định điểm đón"]
        UC05["UC05 - Xác định điểm đến"]
        UC06["UC06 - Chọn loại xe"]
        UC07["UC07 - Theo dõi tìm tài xế"]
        UC08["UC08 - Xem thông tin tài xế"]
        UC09["UC09 - Hủy chuyến"]
        UC10["UC10 - Chọn phương thức thanh toán"]
        UC11["UC11 - Thanh toán chuyến"]
        UC12["UC12 - Đánh giá tài xế"]


        UC13["UC13 - Driver đăng nhập"]
        UC14["UC14 - Online / Offline"]
        UC15["UC15 - Nhận yêu cầu chuyến"]
        UC16["UC16 - Chấp nhận chuyến"]
        UC17["UC17 - Từ chối chuyến"]
        UC18["UC18 - Thực hiện chuyến"]
        UC19["UC19 - Cập nhật trạng thái chuyến"]
        UC20["UC20 - Xem lịch sử chuyến"]


        UC21["UC21 - Admin đăng nhập"]
        UC22["UC22 - Quản lý khách hàng"]
        UC23["UC23 - Quản lý tài xế"]
        UC24["UC24 - Quản lý phương tiện"]
        UC25["UC25 - Quản lý chuyến xe"]
        UC26["UC26 - Theo dõi hoạt động"]
        UC27["UC27 - Xem Audit Log"]


        UC28["UC28 - Xử lý thanh toán trực tuyến"]
        UC29["UC29 - Xác định vị trí / khoảng cách"]
        UC30["UC30 - Gửi thông báo"]
    end


    Customer --> UC01
    Customer --> UC02
    Customer --> UC03
    Customer --> UC07
    Customer --> UC08
    Customer --> UC09
    Customer --> UC10
    Customer --> UC11
    Customer --> UC12


    UC03 --> UC04
    UC03 --> UC05
    UC03 --> UC06
    UC03 --> UC29


    Driver --> UC13
    Driver --> UC14
    Driver --> UC15
    Driver --> UC16
    Driver --> UC17
    Driver --> UC18
    Driver --> UC19
    Driver --> UC20


    Admin --> UC21
    Admin --> UC22
    Admin --> UC23
    Admin --> UC24
    Admin --> UC25
    Admin --> UC26
    Admin --> UC27


    UC11 --> UC28
    Payment --> UC28


    Map --> UC29
    Notify --> UC30


    UC03 --> UC30
    UC16 --> UC30
    UC17 --> UC30
BƯỚC 12 – ĐẶC TẢ USE CASE

Để tránh đặc tả quá dài cho tất cả 30 UC, ta đặc tả các Use Case nghiệp vụ cốt lõi trước. Các UC còn lại có thể đặc tả theo cùng mẫu.

UC01 – Customer: Đăng ký tài khoản
Thuộc tính	Nội dung
Mã	UC01
Tên	Customer – Đăng ký tài khoản
Actor chính	Customer
Mục tiêu	Tạo tài khoản để sử dụng hệ thống
Tiền điều kiện	Customer chưa có tài khoản
Hậu điều kiện	Tài khoản được tạo thành công
Luồng chính
1. Customer chọn Đăng ký.
2. Hệ thống hiển thị form đăng ký.
3. Customer nhập thông tin.
4. Hệ thống kiểm tra dữ liệu.
5. Hệ thống tạo tài khoản.
6. Hệ thống thông báo đăng ký thành công.
Ngoại lệ
Số điện thoại đã tồn tại → thông báo lỗi.
Thông tin không hợp lệ → yêu cầu nhập lại.
Lỗi hệ thống → không tạo tài khoản.
UC02 – Customer: Đăng nhập
Thuộc tính	Nội dung
Mã	UC02
Actor	Customer
Mục tiêu	Xác thực khách hàng
Tiền điều kiện	Customer đã có tài khoản
Hậu điều kiện	Customer đăng nhập thành công
Luồng chính
1. Customer nhập số điện thoại/email và mật khẩu.
2. Hệ thống kiểm tra thông tin.
3. Thông tin hợp lệ.
4. Hệ thống xác thực.
5. Customer đăng nhập thành công.
Ngoại lệ
Sai tài khoản/mật khẩu → thông báo lỗi.
Tài khoản bị khóa → từ chối đăng nhập.
UC03 – Customer: Tạo yêu cầu đặt chuyến
Thuộc tính	Nội dung
Mã	UC03
Actor chính	Customer
Actor phụ	Map Service, Notification Service
Mục tiêu	Tạo một yêu cầu đặt chuyến
Tiền điều kiện	Customer đã đăng nhập
Hậu điều kiện	Yêu cầu chuyến được tạo và hệ thống bắt đầu tìm tài xế
Luồng chính
1. Customer chọn "Đặt chuyến".
2. Hệ thống xác định vị trí hiện tại.
3. Customer xác nhận điểm đón.
4. Customer nhập điểm đến.
5. Customer chọn loại xe.
6. Hệ thống kiểm tra thông tin.
7. Hệ thống tạo yêu cầu chuyến.
8. Trạng thái chuyến = SEARCHING.
9. Hệ thống bắt đầu tìm tài xế.
10. Hệ thống thông báo trạng thái cho Customer.
Ngoại lệ
Không xác định được vị trí → yêu cầu Customer nhập điểm đón.
Điểm đến không hợp lệ → yêu cầu nhập lại.
Không có tài xế → tiếp tục tìm/chờ theo Business Rule.
UC04 – Customer: Xác định điểm đón
Thuộc tính	Nội dung
Mã	UC04
Actor	Customer
Mục tiêu	Xác định vị trí đón khách
Tiền điều kiện	Customer đang tạo chuyến
Hậu điều kiện	Điểm đón được lưu vào yêu cầu chuyến
Luồng chính
1. Hệ thống lấy vị trí hiện tại.
2. Hiển thị vị trí trên bản đồ.
3. Customer xác nhận hoặc điều chỉnh vị trí.
4. Hệ thống lưu điểm đón.
UC05 – Customer: Xác định điểm đến
Thuộc tính	Nội dung
Mã	UC05
Actor	Customer
Mục tiêu	Xác định điểm đến
Tiền điều kiện	Customer đang tạo chuyến
Hậu điều kiện	Điểm đến được lưu
Luồng chính
1. Customer nhập điểm đến.
2. Hệ thống tìm kiếm địa điểm.
3. Hệ thống hiển thị kết quả.
4. Customer chọn điểm đến.
5. Hệ thống lưu điểm đến.
UC06 – Customer: Chọn loại xe
Thuộc tính	Nội dung
Mã	UC06
Actor	Customer
Mục tiêu	Chọn loại xe phù hợp
Tiền điều kiện	Đã có điểm đón và điểm đến
Hậu điều kiện	Loại xe được lưu vào chuyến
Luồng chính
1. Hệ thống hiển thị các loại xe.
2. Customer chọn loại xe.
3. Hệ thống ghi nhận lựa chọn.
4. Hệ thống sử dụng loại xe để tìm tài xế phù hợp.
UC07 – Customer: Theo dõi tìm tài xế
Mã	UC07
Actor	Customer
Mục tiêu	Theo dõi quá trình hệ thống tìm tài xế
Tiền điều kiện	Chuyến đang ở trạng thái SEARCHING
Hậu điều kiện	Customer biết trạng thái tìm tài xế
Luồng chính
1. Hệ thống hiển thị "Đang tìm tài xế".
2. Hệ thống thực hiện tìm tài xế.
3. Nếu tìm được → hiển thị thông tin tài xế.
4. Nếu chưa tìm được → tiếp tục chờ/tìm.
5. Khi tài xế chấp nhận → cập nhật trạng thái.
UC15 – Driver: Nhận yêu cầu chuyến
Mã	UC15
Actor	Driver
Mục tiêu	Nhận yêu cầu từ hệ thống
Tiền điều kiện	Driver đang Online và phù hợp
Hậu điều kiện	Driver có thể chấp nhận hoặc từ chối
Luồng chính
1. Hệ thống tìm Driver phù hợp.
2. Hệ thống gửi yêu cầu.
3. Driver nhận thông báo.
4. Driver xem thông tin chuyến.
5. Driver chọn:
   - Chấp nhận
   - Từ chối
UC16 – Driver: Chấp nhận chuyến
Mã	UC16
Actor	Driver
Mục tiêu	Chấp nhận yêu cầu chuyến
Tiền điều kiện	Driver Online và yêu cầu chưa hết hạn
Hậu điều kiện	Driver được phân công cho chuyến
Luồng chính
1. Driver nhận yêu cầu.
2. Driver chọn "Chấp nhận".
3. Hệ thống kiểm tra yêu cầu còn hiệu lực.
4. Hệ thống xác nhận Driver.
5. Trip → ACCEPTED.
6. Trip → DRIVER_ASSIGNED.
7. Hệ thống thông báo cho Customer.
Ngoại lệ
Yêu cầu đã hết hạn
       ↓
Không cho phép nhận
       ↓
Tìm Driver tiếp theo
UC17 – Driver: Từ chối chuyến
Mã	UC17
Actor	Driver
Mục tiêu	Từ chối yêu cầu
Tiền điều kiện	Driver đã nhận yêu cầu
Hậu điều kiện	Hệ thống tìm Driver khác
Luồng chính
1. Driver nhận yêu cầu.
2. Driver chọn "Từ chối".
3. Hệ thống cập nhật Assignment = REJECTED.
4. Hệ thống loại Driver khỏi yêu cầu hiện tại.
5. Hệ thống tìm Driver tiếp theo.
6. Hệ thống gửi yêu cầu mới.
UC18 – Driver: Thực hiện chuyến
Mã	UC18
Actor	Driver
Mục tiêu	Thực hiện chuyến đã nhận
Tiền điều kiện	Driver đã được phân công
Hậu điều kiện	Chuyến hoàn thành
Luồng
Driver được phân công
        ↓
Đến điểm đón
        ↓
Đón Customer
        ↓
Bắt đầu chuyến
        ↓
Di chuyển đến điểm đến
        ↓
Kết thúc chuyến
        ↓
Trip = COMPLETED
UC10 – Customer: Chọn phương thức thanh toán
Mã	UC10
Actor	Customer
Mục tiêu	Chọn phương thức thanh toán
Tiền điều kiện	Có chuyến cần thanh toán
Hậu điều kiện	Phương thức thanh toán được ghi nhận
Các lựa chọn
Phương thức thanh toán
        │
        ├── Tiền mặt
        │
        └── Trực tuyến
UC11 – Customer: Thanh toán chuyến
Mã	UC11
Actor chính	Customer
Actor phụ	Payment Gateway
Mục tiêu	Thanh toán cước chuyến
Tiền điều kiện	Chuyến đã hoàn thành hoặc đến trạng thái cần thanh toán
Hậu điều kiện	Giao dịch được ghi nhận
Thanh toán trực tuyến
Customer
   ↓
Chọn thanh toán Online
   ↓
Hệ thống tạo giao dịch
   ↓
Payment Gateway
   ↓
Thanh toán
   ↓
Kết quả giao dịch
   ↓
Hệ thống cập nhật Payment
Thanh toán tiền mặt
Customer
   ↓
Chọn tiền mặt
   ↓
Hoàn thành chuyến
   ↓
Ghi nhận thanh toán tiền mặt
UC12 – Customer: Đánh giá tài xế
Mã	UC12
Actor	Customer
Mục tiêu	Đánh giá chất lượng chuyến đi
Tiền điều kiện	Chuyến đã hoàn thành
Hậu điều kiện	Đánh giá được lưu
Luồng chính
1. Customer mở chuyến đã hoàn thành.
2. Hệ thống hiển thị chức năng đánh giá.
3. Customer chọn số sao.
4. Customer nhập nhận xét (nếu có).
5. Hệ thống lưu Review.
6. Hệ thống cập nhật điểm đánh giá của Driver.
UC22 – Admin: Quản lý khách hàng
Mã	UC22
Actor	Admin
Mục tiêu	Quản lý tài khoản khách hàng
Tiền điều kiện	Admin đã đăng nhập và có quyền
Hậu điều kiện	Thông tin khách hàng được cập nhật
Chức năng
Quản lý Customer
      │
      ├── Xem thông tin
      ├── Tìm kiếm
      ├── Cập nhật
      ├── Khóa tài khoản
      └── Mở khóa tài khoản
UC23 – Admin: Quản lý tài xế
Mã	UC23
Actor	Admin
Mục tiêu	Quản lý tài xế
Tiền điều kiện	Admin có quyền
Hậu điều kiện	Thông tin Driver được cập nhật
Chức năng
Quản lý Driver
      │
      ├── Xem thông tin
      ├── Tìm kiếm
      ├── Quản lý trạng thái
      ├── Quản lý hồ sơ
      └── Khóa / mở khóa
12.1. Quy trình Use Case đặt chuyến hoàn chỉnh
Customer
   │
   ▼
UC03 – Tạo yêu cầu đặt chuyến
   │
   ├── UC04 – Điểm đón
   │
   ├── UC05 – Điểm đến
   │
   └── UC06 – Chọn loại xe
            │
            ▼
      Hệ thống tìm Driver
            │
            ▼
      Driver Online?
        │          │
       Không       Có
        │          │
        │          ▼
        │    Gửi yêu cầu
        │          │
        │          ▼
        │    UC15 – Nhận yêu cầu
        │          │
        │     ┌────┴────┐
        │     ▼         ▼
        │ UC16       UC17
        │ Chấp nhận  Từ chối
        │     │         │
        │     ▼         ▼
        │  Gán xe    Tìm Driver khác
        │     │
        └─────┤
              ▼
       UC07 – Theo dõi
              │
              ▼
       UC08 – Xem tài xế
              │
              ▼
       UC18 – Thực hiện chuyến
              │
              ▼
       UC11 – Thanh toán
              │
              ▼
       UC12 – Đánh giá
12.2. Mối quan hệ giữa các bước đã làm
BG
│
▼
BR
│
▼
FR
│
▼
Business Rule
│
▼
Data Model / ERD
│
▼
USE CASE
│
▼
Use Case Specification

Ví dụ với chức năng tìm tài xế:

BG01
Giảm thời gian tìm tài xế
        ↓
BR01
Tự động tìm kiếm tài xế
        ↓
FR01 – Xác định vị trí
FR04 – Lọc tài xế Online
FR05 – Lọc theo vị trí
FR06 – Chọn loại xe
FR08 – Ưu tiên đánh giá cao
        ↓
Business Rule
Chỉ tài xế Online và phù hợp
mới được nhận yêu cầu
        ↓
UC03 – Tạo yêu cầu đặt chuyến
        ↓
UC15 – Nhận yêu cầu
        ↓
UC16 – Chấp nhận
        ↓
UC17 – Từ chối
        ↓
Tìm tài xế tiếp theo

Như vậy, Bước 11 xác định và vẽ Use Case, còn Bước 12 đặc tả chi tiết cách từng Use Case hoạt động. Hai bước này được thực hiện liên tục và có thể truy vết ngược về BG → BR → FR → Business Rule.
BƯỚC 13 – ACCEPTANCE CRITERIA (TIÊU CHÍ CHẤP NHẬN)
13.1. Acceptance Criteria là gì?

Acceptance Criteria (AC) – Tiêu chí chấp nhận là tập hợp các điều kiện cụ thể mà hệ thống hoặc một chức năng phải đáp ứng để khách hàng xác nhận chức năng đó đã hoàn thành và có thể nghiệm thu.

Nói đơn giản:

Acceptance Criteria trả lời câu hỏi: “Làm thế nào để biết yêu cầu này đã làm đúng và có thể nghiệm thu?”

Acceptance Criteria phải:

Rõ ràng.
Có thể kiểm thử.
Có thể xác định Đạt / Không đạt.
Gắn với Business Requirement hoặc Functional Requirement.
Không gây hiểu nhầm giữa khách hàng, BA, Developer và Tester.
13.2. Mục đích của Acceptance Criteria
Mục đích	Ý nghĩa
Xác định điều kiện hoàn thành	Biết chính xác khi nào một chức năng được xem là hoàn thành.
Làm cơ sở nghiệm thu	Khách hàng dựa vào AC để xác nhận sản phẩm đạt yêu cầu.
Hỗ trợ kiểm thử	Tester sử dụng AC để xây dựng Test Case.
Tránh hiểu sai yêu cầu	BA, Developer, Tester và Customer có cùng cách hiểu.
Kiểm soát phạm vi	Không tự ý thêm các chức năng ngoài yêu cầu.
Đánh giá chất lượng	Xác định chức năng có đáp ứng yêu cầu nghiệp vụ hay không.
13.3. Cấu trúc Acceptance Criteria

Một Acceptance Criteria nên có:

Requirement
     ↓
Điều kiện ban đầu
     ↓
Hành động
     ↓
Kết quả mong đợi
     ↓
Đạt / Không đạt
     ↓
Nghiệm thu

Có thể sử dụng mẫu:

Given – When – Then

Given: Điều kiện ban đầu
When: Người dùng thực hiện hành động
Then: Hệ thống phải tạo ra kết quả mong muốn
13.4. Acceptance Criteria cho hệ thống CAB
Mã AC	Use Case / Requirement	Tiêu chí chấp nhận	Kết quả mong đợi
AC01	UC01 – Đăng ký	Khách hàng nhập đầy đủ thông tin hợp lệ	Tài khoản được tạo thành công
AC02	UC02 – Đăng nhập	Nhập đúng tài khoản và mật khẩu	Đăng nhập thành công
AC03	UC02 – Đăng nhập	Nhập sai thông tin	Hệ thống từ chối và hiển thị thông báo
AC04	UC03 – Đặt chuyến	Nhập điểm đón, điểm đến và loại xe hợp lệ	Yêu cầu chuyến được tạo
AC05	UC04 – Điểm đón	Xác định được vị trí khách hàng	Điểm đón được lưu chính xác
AC06	UC05 – Điểm đến	Khách hàng chọn điểm đến hợp lệ	Điểm đến được lưu
AC07	UC06 – Loại xe	Khách hàng chọn loại xe	Loại xe được ghi nhận
AC08	Tìm tài xế	Có tài xế Online phù hợp	Hệ thống gửi yêu cầu nhận chuyến
AC09	Tìm tài xế	Không có tài xế phù hợp ngay lập tức	Hệ thống tiếp tục tìm/chờ theo Business Rule
AC10	UC16 – Chấp nhận	Tài xế Online và chấp nhận trong thời hạn	Tài xế được phân công cho chuyến
AC11	UC17 – Từ chối	Tài xế từ chối	Hệ thống tìm tài xế tiếp theo
AC12	Timeout	Tài xế không phản hồi hết thời gian	Hệ thống tự động chuyển sang tài xế tiếp theo
AC13	UC09 – Hủy	Khách hàng hủy chuyến ở trạng thái được phép	Chuyến chuyển sang CANCELLED
AC14	UC11 – Thanh toán	Thanh toán tiền mặt	Giao dịch được ghi nhận là tiền mặt
AC15	UC11 – Thanh toán	Thanh toán trực tuyến thành công	Payment chuyển sang PAID
AC16	UC11 – Thanh toán	Thanh toán trực tuyến thất bại	Giao dịch chuyển FAILED và không làm hệ thống đặt xe dừng
AC17	UC12 – Đánh giá	Chuyến đã hoàn thành	Khách hàng có thể đánh giá
AC18	Security	Người chưa đăng nhập truy cập chức năng yêu cầu tài khoản	Hệ thống yêu cầu đăng nhập
AC19	Authorization	Người không có quyền truy cập chức năng quản trị	Hệ thống từ chối truy cập
AC20	Audit	Thực hiện thao tác quan trọng	Hệ thống tạo Audit Log
AC21	Reliability	Một thành phần bị lỗi	Các chức năng không liên quan vẫn tiếp tục hoạt động trong phạm vi thiết kế
AC22	Scalability	Tải hệ thống tăng	Thành phần cần thiết có thể mở rộng mà không phải mở rộng toàn bộ hệ thống
AC23	Notification	Có sự kiện cần thông báo	Hệ thống gửi thông báo theo cấu hình
AC24	Trip	Tài xế hoàn thành chuyến	Trip chuyển sang COMPLETED
AC25	Nghiệm thu	Tất cả AC bắt buộc đều đạt	Chức năng được đề xuất nghiệm thu
13.5. Đặc tả Acceptance Criteria cho chức năng Đặt chuyến

Đây là Acceptance Criteria quan trọng nhất vì đặt chuyến là nghiệp vụ trung tâm.

AC-BOOKING-01 – Tạo chuyến thành công

Given

Customer đã đăng nhập.
Customer có điểm đón hợp lệ.
Customer có điểm đến hợp lệ.
Customer đã chọn loại xe.

When

Customer nhấn “Đặt chuyến”.

Then

Hệ thống tạo TRIP.
Trạng thái chuyến = SEARCHING.
Hệ thống bắt đầu quá trình tìm tài xế.
AC-BOOKING-02 – Tìm tài xế

Given

Chuyến đang ở trạng thái SEARCHING.

When

Hệ thống thực hiện tìm tài xế.

Then

Chỉ tài xế đang ONLINE/sẵn sàng mới được xét.
Tài xế phải phù hợp với loại xe.
Hệ thống áp dụng tiêu chí ưu tiên đã được doanh nghiệp xác nhận.
Hệ thống gửi yêu cầu nhận chuyến.
AC-BOOKING-03 – Tài xế chấp nhận

Given

Tài xế đang Online.
Yêu cầu nhận chuyến chưa hết hạn.

When

Tài xế nhấn “Chấp nhận”.

Then

Assignment = ACCEPTED
Trip       = DRIVER_ASSIGNED
Customer nhận được thông báo.
Không tài xế khác được xác nhận cho cùng chuyến.
AC-BOOKING-04 – Tài xế từ chối

Given

Tài xế nhận được yêu cầu.

When

Tài xế chọn “Từ chối”.

Then

Assignment = REJECTED
Tài xế được loại khỏi lần tìm kiếm hiện tại.
Hệ thống tìm tài xế tiếp theo.
AC-BOOKING-05 – Tài xế không phản hồi

Given

Hệ thống đã gửi yêu cầu cho tài xế.

When

Tài xế không phản hồi trước thời hạn.

Then

Assignment = TIMEOUT
Hệ thống tự động chuyển sang tài xế phù hợp tiếp theo.
Customer tiếp tục nhận trạng thái đang tìm tài xế.

Thời gian timeout cụ thể cần được khách hàng xác nhận.

13.6. Acceptance Criteria cho thanh toán
AC-PAYMENT-01 – Tiền mặt
Given:
Customer chọn phương thức "Tiền mặt"


When:
Chuyến hoàn thành


Then:
Hệ thống ghi nhận phương thức thanh toán = CASH
và lưu giao dịch.
AC-PAYMENT-02 – Thanh toán Online thành công
Given:
Customer chọn thanh toán Online


When:
Payment Gateway trả kết quả thành công


Then:
Payment = PAID
Trip được ghi nhận đã thanh toán.
AC-PAYMENT-03 – Thanh toán thất bại
Given:
Customer thanh toán Online


When:
Payment Gateway trả kết quả thất bại


Then:
Payment = FAILED
Hệ thống thông báo cho Customer
và hệ thống đặt chuyến không bị dừng toàn bộ.
13.7. Acceptance Criteria cho bảo mật
AC-SECURITY-01 – Authentication
Given:
Người dùng chưa đăng nhập


When:
Truy cập chức năng yêu cầu tài khoản


Then:
Hệ thống yêu cầu đăng nhập
và không cho phép thực hiện chức năng.
AC-SECURITY-02 – Authorization
Given:
Customer không có quyền Admin


When:
Customer truy cập chức năng quản trị


Then:
Hệ thống từ chối truy cập.
AC-SECURITY-03 – Audit Log
Given:
Người dùng thực hiện thao tác quan trọng


When:
Thao tác được thực hiện


Then:
Hệ thống lưu Audit Log gồm:
- Người thực hiện
- Thao tác
- Đối tượng tác động
- Thời gian
13.8. Acceptance Criteria cho Non-Functional Requirement
Mã	NFR	Acceptance Criteria
AC-NFR01	Performance	Thời gian phản hồi phải đạt ngưỡng do khách hàng thống nhất.
AC-NFR02	Scalability	Hệ thống có thể mở rộng thành phần chịu tải cao độc lập.
AC-NFR03	Availability	Hệ thống đáp ứng mức Availability đã thống nhất.
AC-NFR04	Reliability	Lỗi một thành phần không làm toàn bộ hệ thống ngừng hoạt động.
AC-NFR05	Security	Các chức năng yêu cầu tài khoản phải được xác thực.
AC-NFR06	Authorization	Chức năng quản trị phải được phân quyền.
AC-NFR07	Audit	Các thao tác quan trọng phải được ghi log.
AC-NFR08	Maintainability	Có thể triển khai chức năng mới mà hạn chế ảnh hưởng chức năng đang hoạt động.
AC-NFR09	Flexibility	Có thể bổ sung phương thức thanh toán/notification provider mà không phải xây dựng lại toàn bộ hệ thống.

Các con số cụ thể như response time, số người dùng đồng thời, Availability %, thời gian timeout... chỉ nên đưa vào AC chính thức sau khi được khách hàng xác nhận.

13.9. Quy trình kiểm tra Acceptance Criteria
flowchart TD
    A["Business Requirement / Functional Requirement"] --> B["Xác định Acceptance Criteria"]
    B --> C["Developer triển khai"]
    C --> D["Tester kiểm thử"]
    D --> E{"Tất cả AC đạt?"}
    
    E -- "Không" --> F["Ghi nhận lỗi / Gap"]
    F --> C
    
    E -- "Có" --> G["BA kiểm tra nghiệp vụ"]
    G --> H["Customer kiểm tra"]
    H --> I{"Khách hàng chấp nhận?"}
    
    I -- "Không" --> J["Feedback / Điều chỉnh"]
    J --> C
    
    I -- "Có" --> K["Nghiệm thu"]
    K --> L["Đóng Requirement / Release"]
13.10. Khi nào được xem là hoàn thành và nghiệm thu?

Một Use Case/Requirement được xem là hoàn thành để nghiệm thu khi:

Requirement đã triển khai
        ↓
Tất cả Acceptance Criteria bắt buộc
        ↓
Đã kiểm thử
        ↓
Không còn lỗi nghiêm trọng
        ↓
BA xác nhận đúng nghiệp vụ
        ↓
Customer xác nhận đạt
        ↓
       DONE
        ↓
     NGHIỆM THU
Definition of Acceptance

Có thể quy định:

100% Acceptance Criteria bắt buộc đạt.
Không còn lỗi Critical/Blocker chưa xử lý.
Các lỗi còn lại phải được khách hàng chấp thuận nếu cho phép release.
Chức năng đáp ứng đúng Business Requirement.
BA xác nhận kết quả đúng nghiệp vụ.
Khách hàng/UAT xác nhận chấp nhận.
Có đầy đủ bằng chứng kiểm thử/nghiệm thu.
13.11. Ma trận truy vết Requirement → Acceptance Criteria

Để quản lý toàn bộ yêu cầu, có thể nối các bước từ đầu đến cuối:

Business Goal	BR	FR	UC	AC
BG01 – Giảm thời gian tìm tài xế	BR01 – Tự động tìm tài xế	FR tìm vị trí, lọc Driver Online, ưu tiên Driver	UC03, UC07, UC15, UC16, UC17	AC08–AC12
BG02 – Hỗ trợ đặt chuyến	BR02 – Quản lý quy trình đặt chuyến	FR tạo Trip, chọn điểm đón/đến, chọn xe	UC03–UC09	AC04–AC13
BG03 – Hỗ trợ thanh toán	BR03 – Thanh toán tiền mặt/Online	FR xử lý Payment	UC10, UC11	AC14–AC16
BG04 – Bảo vệ hệ thống	BR04 – Authentication/Authorization	FR đăng nhập, phân quyền	UC02, UC21	AC18–AC20
BG05 – Nền tảng có khả năng phát triển	BR05 – Mở rộng độc lập	FR/Architecture hỗ trợ mở rộng	Các UC liên quan	AC21–AC23
Kết luận Bước 13

Acceptance Criteria chính là “điểm chốt” của yêu cầu.

flowchart LR
    BG["BG - Business Goal"]
    BR["BR - Business Requirement"]
    FR["FR - Functional Requirement"]
    UC["UC - Use Case"]
    AC["AC - Acceptance Criteria"]
    TEST["Test / UAT"]
    ACCEPT["Customer Acceptance"]


    BG --> BR
    BR --> FR
    FR --> UC
    UC --> AC
    AC --> TEST
    TEST --> ACCEPT

BG xác định doanh nghiệp muốn đạt gì → BR xác định doanh nghiệp cần gì → FR xác định hệ thống phải làm gì → UC mô tả người dùng tương tác thế nào → AC xác định điều kiện để kết luận “làm đúng” → Test/UAT kiểm tra → Customer nghiệm thu.
