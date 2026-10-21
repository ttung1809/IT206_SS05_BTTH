# BÀI TỔNG HỢP: QUẢN LÝ PRODUCT BACKLOG CHO CHƯƠNG TRÌNH GREENMART LOYALTY

## Phần A — Thiết kế vận hành Scrum

### 1. Lựa chọn độ dài Sprint

Chọn Sprint 2 tuần, toàn dự án kéo dài 8 tuần, tương ứng 4 Sprint. Độ dài này giúp đội Hoa có đủ thời gian phát triển, kiểm thử và bàn giao từng phần chức năng, đồng thời nhận phản hồi sớm để điều chỉnh Product Backlog mà không làm gián đoạn Sprint đang chạy.

### 2. Phân công 3 vai trò Scrum

| Vai trò            | Người/nhóm phụ trách                                            | Trách nhiệm trong dự án                                                                                                                                               |
| ------------------ | --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Product Owner (PO) | Đại diện nghiệp vụ, phối hợp Marketing và Kế toán               | Xác định mục tiêu sản phẩm; thu thập yêu cầu; sắp xếp Product Backlog theo giá trị, rủi ro và mức độ cần thiết; quyết định thứ tự ưu tiên.                            |
| Scrum Master (SM)  | Người phụ trách vận hành Scrum kiêm BA                          | Hướng dẫn đội thực hiện Scrum; tổ chức các sự kiện Scrum; loại bỏ trở ngại; hỗ trợ làm rõ yêu cầu và Acceptance Criteria; đảm bảo thay đổi được xử lý đúng quy trình. |
| Development Team   | Đội Hoa gồm lập trình viên, kiểm thử và các thành viên kỹ thuật | Tự tổ chức công việc; thiết kế, phát triển, kiểm thử và tích hợp chức năng; đánh giá năng lực Sprint; đảm bảo Increment đáp ứng Definition of Done.                   |

Lưu ý: Trong Scrum, Scrum Master và Product Owner là hai trách nhiệm khác nhau. Dù người thực hiện có thể kiêm BA, việc ưu tiên Product Backlog vẫn thuộc trách nhiệm của PO.

### 3. Sự kiện Scrum quan trọng nhất

Chọn Sprint Review.

Sprint Review giúp đội Hoa cùng PO và các bên liên quan kiểm tra kết quả thực tế của Sprint, đối chiếu với nhu cầu của Marketing, Kế toán và khách hàng. Sự kiện này thể hiện rõ trụ cột Thanh tra (Inspection) vì các bên đánh giá Increment, đồng thời hỗ trợ Thích nghi (Adaptation) khi kết quả hoặc yêu cầu thay đổi dẫn đến việc cập nhật Product Backlog.

## Phần B — Product Backlog và ưu tiên hóa bằng MoSCoW

### 1. Tiêu chí ưu tiên

Để tránh phân loại theo cảm tính, đội Hoa thống nhất các tiêu chí sau:

- Must have: Chức năng bắt buộc để chương trình Loyalty vận hành đúng nghiệp vụ, đảm bảo tính chính xác của điểm hoặc tính minh bạch giao dịch.
- Should have: Chức năng quan trọng giúp nâng cao trải nghiệm hoặc hiệu quả vận hành, nhưng có thể hoàn thành sau mà không làm mất khả năng vận hành cốt lõi.
- Could have: Chức năng bổ sung, tăng tiện ích nhưng chưa ảnh hưởng trực tiếp đến hoạt động chính.
- Won't have this time: Chưa thực hiện trong phạm vi 8 tuần; có thể xem xét ở giai đoạn sau.

### 2. Bảng Product Backlog

| ID     | Product Backlog Item (PBI)                               | Giá trị nghiệp vụ / lý do                                                                    | MoSCoW               |
| ------ | -------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------- |
| PBI-01 | Tự động tích điểm sau khi đơn hàng thanh toán thành công | Là chức năng cốt lõi; áp dụng tỷ lệ 10.000đ = 1 điểm, tạo nền tảng cho chương trình Loyalty. | Must                 |
| PBI-02 | Thu hồi điểm khi đơn hàng bị hủy hoặc hoàn               | Đảm bảo số dư điểm phản ánh giao dịch thực tế, tránh khách nhận điểm không hợp lệ.           | Must                 |
| PBI-03 | Đổi điểm lấy ưu đãi                                      | Cho phép khách sử dụng điểm theo tỷ lệ 100 điểm = 20.000đ và quy tắc không cộng dồn ưu đãi.  | Must                 |
| PBI-04 | Xem số dư điểm và lịch sử tích/đổi điểm                  | Giúp khách hàng và Kế toán đối chiếu giao dịch, tăng tính minh bạch.                         | Must                 |
| PBI-05 | Tự động trừ điểm khi hết hạn 12 tháng                    | Đảm bảo chương trình tuân thủ quy tắc hiệu lực điểm đã công bố.                              | Must                 |
| PBI-06 | Thông báo điểm sắp hết hạn                               | Giúp khách chủ động sử dụng điểm, cải thiện trải nghiệm và khả năng giữ chân khách hàng.     | Should               |
| PBI-07 | Báo cáo tổng hợp điểm và giao dịch cho Marketing/Kế toán | Hỗ trợ theo dõi hiệu quả chương trình và đối soát dữ liệu.                                   | Should               |
| PBI-08 | Cá nhân hóa ưu đãi theo lịch sử mua hàng                 | Có thể tăng mức độ tương tác nhưng không cần thiết để vận hành chức năng Loyalty cốt lõi.    | Could                |
| PBI-09 | Xây dựng ứng dụng Loyalty độc lập với hệ thống riêng     | Phạm vi lớn, có thể kéo dài thời gian triển khai và không cần thiết trong giai đoạn đầu.     | Won't have this time |

Giải thích: PBI-01 đến PBI-05 được xếp Must vì chúng tạo thành chuỗi nghiệp vụ cơ bản: phát sinh điểm đúng, điều chỉnh điểm khi giao dịch thay đổi, sử dụng điểm, tra cứu và xử lý điểm hết hạn. Nếu thiếu một trong các chức năng này, số dư hoặc việc sử dụng điểm có thể sai lệch so với quy tắc chương trình.

### 3. Danh sách đưa vào Sprint 1

Sprint 1 chỉ đủ nguồn lực để hoàn thành toàn bộ nhóm Must và tối đa 2 hạng mục Should. Vì vậy, đội Hoa chốt như sau:

| PBI    | Hạng mục                                | Ưu tiên | Quyết định             |
| ------ | --------------------------------------- | ------- | ---------------------- |
| PBI-01 | Tích điểm sau thanh toán thành công     | Must    | Đưa vào Sprint 1       |
| PBI-02 | Thu hồi điểm khi hủy/hoàn đơn           | Must    | Đưa vào Sprint 1       |
| PBI-03 | Đổi điểm lấy ưu đãi                     | Must    | Đưa vào Sprint 1       |
| PBI-04 | Xem số dư và lịch sử giao dịch điểm     | Must    | Đưa vào Sprint 1       |
| PBI-05 | Tự động trừ điểm hết hạn                | Must    | Đưa vào Sprint 1       |
| PBI-06 | Thông báo điểm sắp hết hạn              | Should  | Đưa vào Sprint 1       |
| PBI-07 | Báo cáo giao dịch cho Marketing/Kế toán | Should  | Đưa vào Sprint 1       |
| PBI-08 | Cá nhân hóa ưu đãi                      | Could   | Chưa đưa vào Sprint 1  |
| PBI-09 | Ứng dụng Loyalty độc lập                | Won't   | Ngoài phạm vi hiện tại |

Kết luận Sprint 1: Chọn 5 hạng mục Must và 2 hạng mục Should, đúng giới hạn nguồn lực. Trong Sprint Planning, Development Team cần xác nhận khối lượng công việc có khả thi hay không; nếu không đủ năng lực thực tế, PO và đội cần thống nhất phạm vi Sprint phù hợp, không cam kết vượt quá khả năng.

## Phần C — Acceptance Criteria và Definition of Done

### 1. Hạng mục được chọn

PBI-01: Tự động tích điểm sau khi đơn hàng thanh toán thành công.

Quy tắc nghiệp vụ áp dụng:

- Cứ 10.000đ giá trị đơn hàng hợp lệ được tính 1 điểm.
- Chỉ đơn hàng thanh toán thành công mới được tích điểm.
- Điểm đã tích phải được thu hồi khi đơn bị hủy hoặc hoàn.
- Để tránh tính điểm sai, hệ thống cần xác định rõ cách xử lý phần giá trị đơn hàng chưa đủ 10.000đ.

Giả định đặc tả: Điểm được tính bằng phần nguyên của giá trị đơn hàng hợp lệ chia cho 10.000đ; phần dư không được làm tròn lên. Giá trị dùng để tính điểm là số tiền đủ điều kiện tích điểm theo quy định nghiệp vụ.

### 2. Acceptance Criteria (Given – When – Then)

#### AC-01: Tích điểm với đơn hàng thanh toán thành công

- Given: Khách hàng có một đơn hàng trị giá 250.000đ và đơn chưa được ghi nhận tích điểm trước đó.
- When: Hệ thống nhận xác nhận thanh toán thành công.
- Then: Hệ thống cộng 25 điểm vào tài khoản khách hàng và lưu lại giao dịch tích điểm gắn với đơn hàng đó.

#### AC-02: Không tích điểm khi thanh toán thất bại

- Given: Khách hàng có một đơn hàng trị giá 250.000đ nhưng giao dịch thanh toán thất bại.
- When: Hệ thống nhận kết quả thanh toán thất bại.
- Then: Hệ thống không cộng điểm vào tài khoản khách hàng và không ghi nhận giao dịch tích điểm thành công.

#### AC-03: Không tích điểm trùng khi nhận thông báo thanh toán lặp lại

- Given: Đơn hàng trị giá 250.000đ đã thanh toán thành công và khách hàng đã được cộng 25 điểm.
- When: Hệ thống nhận lại thông báo thanh toán thành công của cùng đơn hàng.
- Then: Hệ thống không cộng thêm điểm lần thứ hai và số dư điểm của khách hàng không thay đổi.

#### AC-04: Thu hồi điểm khi đơn hàng bị hủy sau khi đã tích điểm

- Given: Khách hàng đã nhận 25 điểm từ đơn hàng 250.000đ.
- When: Đơn hàng được xác nhận hủy hoặc hoàn toàn bộ theo quy trình nghiệp vụ.
- Then: Hệ thống thu hồi 25 điểm đã cấp từ đơn hàng đó, lưu giao dịch điều chỉnh và không xóa mất lịch sử tích điểm ban đầu.

AC-04 là tình huống ngoại lệ quan trọng: Nếu không thu hồi điểm, khách hàng có thể giữ điểm từ một đơn hàng không còn hợp lệ.

### 3. Definition of Done (DoD) cho Sprint 1

DoD áp dụng chung cho các PBI hoàn thành trong Sprint 1:

1. Chất lượng mã nguồn: Mã nguồn được kiểm tra, tuân thủ quy ước lập trình của đội và được ít nhất một thành viên khác review.
2. Kiểm thử và tích hợp: Các kiểm thử phù hợp được thực hiện; kiểm thử hồi quy không phát hiện lỗi nghiêm trọng mới trong phạm vi chức năng liên quan.
3. Tài liệu: Tài liệu kỹ thuật và hướng dẫn sử dụng liên quan được cập nhật, đủ để thành viên khác hiểu và vận hành chức năng.
4. Triển khai thử nghiệm: Chức năng được tích hợp vào môi trường kiểm thử chung và có thể trình diễn trong Sprint Review.
5. Quản lý lỗi: Không còn lỗi nghiêm trọng hoặc lỗi chặn việc sử dụng chức năng trong phạm vi đã thống nhất; các lỗi còn lại được ghi nhận và đánh giá rõ ràng.

Phân biệt AC và DoD: AC xác định một hạng mục cụ thể cần làm gì để đáp ứng yêu cầu nghiệp vụ; DoD là tiêu chuẩn chất lượng chung mà Increment hoặc hạng mục hoàn thành phải đáp ứng.

## Phần D — Xử lý tình huống thay đổi giữa Sprint

### 1. Quy trình tiếp nhận thay đổi mà không phá vỡ Sprint hiện tại

Marketing đề nghị đổi tỷ lệ đổi điểm từ 100 điểm = 20.000đ sang 100 điểm = 25.000đ.

Đội Hoa xử lý như sau:

1. Ghi nhận yêu cầu: Scrum Master/BA làm rõ lý do thay đổi, thời điểm áp dụng, phạm vi khách hàng, các chương trình khuyến mãi liên quan và tác động đến giao dịch đã phát sinh.
2. PO đánh giá và ưu tiên: Product Owner đánh giá giá trị kinh doanh, rủi ro tài chính, ảnh hưởng đến khách hàng và cập nhật thứ tự ưu tiên trong Product Backlog.
3. Không tự ý thay đổi Sprint Backlog: Development Team tiếp tục theo đuổi Sprint Goal hiện tại. Yêu cầu mới được đưa vào Product Backlog để xem xét cho Sprint tiếp theo, trừ khi PO và Development Team cùng xác định rằng có thể điều chỉnh phạm vi Sprint mà không gây nguy hiểm cho Sprint Goal.
4. Làm rõ quy tắc trước khi triển khai: PO cần xác nhận thời điểm có hiệu lực, cách xử lý giao dịch cũ, mã ưu đãi đã phát hành và quy tắc không cộng dồn.
5. Đưa vào kế hoạch phù hợp: Nếu thay đổi quan trọng hơn các hạng mục chưa thực hiện, PO sắp xếp lại Product Backlog để đội xem xét trong Sprint kế tiếp. Nếu Sprint Goal trở nên lỗi thời, PO có thể hủy Sprint theo Scrum Guide; đây là biện pháp ngoại lệ, không phải cách xử lý mặc định.

### 2. Ảnh hưởng đến Product Backlog, AC và DoD

#### a. Product Backlog

PBI-03 cần được cập nhật từ:

- Quy tắc cũ: 100 điểm = 20.000đ.
- Quy tắc mới: 100 điểm = 25.000đ.

PO cần cập nhật mô tả nghiệp vụ, Acceptance Criteria, ví dụ tính toán, thứ tự ưu tiên nếu thay đổi làm tăng rủi ro hoặc giá trị kinh doanh. Các hạng mục liên quan đến đổi điểm, hiển thị giá trị điểm, mã giảm giá và báo cáo đối soát cũng cần được rà soát.

#### b. Acceptance Criteria

AC của PBI-03 cần cập nhật theo quy tắc mới. Ví dụ:

AC mới — Đổi điểm theo tỷ lệ khuyến mãi

- Given: Khách hàng có ít nhất 100 điểm hợp lệ và chương trình áp dụng tỷ lệ quy đổi mới.
- When: Khách hàng đổi 100 điểm.
- Then: Hệ thống trừ 100 điểm và áp dụng giá trị ưu đãi 25.000đ; giao dịch được ghi nhận đầy đủ trong lịch sử điểm.

Bổ sung thêm kịch bản kiểm thử cho các trường hợp:

- Chương trình chưa đến thời điểm áp dụng thì vẫn dùng tỷ lệ cũ.
- Chương trình đã áp dụng thì dùng tỷ lệ mới.
- Khách không đủ điểm thì hệ thống từ chối giao dịch.
- Ưu đãi không được cộng dồn nếu không có xác nhận cho phép từ hệ thống.

#### c. Definition of Done

DoD không cần thay đổi chỉ vì tỷ lệ quy đổi thay đổi, vì đây là tiêu chuẩn chất lượng chung, không phải nơi định nghĩa quy tắc nghiệp vụ. Tuy nhiên, đội cần áp dụng DoD hiện tại để xác nhận các cập nhật mới đã được review, kiểm thử, tích hợp và có tài liệu phù hợp.

Nếu thay đổi phát sinh yêu cầu chất lượng mới có tính áp dụng chung — ví dụ cần kiểm toán bắt buộc mọi lần thay đổi tỷ lệ quy đổi — đội có thể thảo luận cập nhật DoD một cách minh bạch và thống nhất, thay vì thay đổi riêng cho một PBI mà không có sự đồng thuận.

## Kết luận

Bộ tài liệu trên thiết lập cách vận hành GreenMart Loyalty trong 8 tuần với 4 Sprint, ưu tiên các chức năng đảm bảo tính đúng đắn của điểm và tính minh bạch giao dịch. MoSCoW giúp đội Hoa lựa chọn phạm vi Sprint 1 theo giá trị và mức độ bắt buộc; Acceptance Criteria giúp kiểm chứng nghiệp vụ; DoD đảm bảo chất lượng chung; còn quy trình quản lý thay đổi cho phép Marketing đề xuất điều chỉnh mà không mặc định làm gián đoạn Sprint đang chạy.