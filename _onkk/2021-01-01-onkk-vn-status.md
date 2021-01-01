---
title:  "Nghiên cứu ô nhiễm không khí ở Việt Nam: Chặng đường phía trước"
comments: true
date:   2021-01-01 00:00:00 -0000
layout: single
classes: wide
author_profile: true
header:
  teaser: /assets/images/onkk.source.traffic.png
---

### Lời dẫn

Khi tôi viết những dòng này, Luân Đôn chuẩn bị bước qua những khoảnh khắc cuối cùng của năm 2020 trong giá lạnh và sự cô lập.
Thành phố đang trải qua lệnh phong tỏa lần thứ hai để ngăn chặn sự lây nhiễm siêu nhanh của virus biến thể mới. 
Hồi đầu năm tôi thực sự không ngờ rằng Covid sẽ đảo lộn cuộc sống của tôi ghê gớm đến thế.
Ở lần phong tỏa này tôi có lẽ cảm thấy bình tâm hơn để sống theo tình hình mới, thay cho những bàng hoàng ở lần phong tỏa đầu. 

Cuộc sống có thể sẽ còn lâu mới trở bình thường nhưng nó không ngừng vận động. 
Những vấn đề ô nhiễm không khí (ONKK) còn dang dở khiến tôi luôn cảm thấy bận rộn. 
Hiện tôi đang dành rất nhiều thời gian để phát triển một mô hình tích hợp tính toán mức độ phơi nhiễm ONKK
cho 2 dự án khá lớn của thành phố Luân Đôn (*). 
Tuy vậy như nhiều người Việt xa quê hương, 
tôi cũng dành thời gian cập nhật tình hình nghiên cứu trong nước với mong muốn được đóng góp chút hiểu biết hạn hẹp của mình. 

Năm rồi tôi có cơ duyên làm quen với các anh chị nghiên cứu trong nước.
Tôi rất vui khi cùng các anh chị tìm hiểu một số vấn đề (đây đều là những dự án cá nhân mà tôi làm ngoài giờ làm việc).
Những trao đổi quý báu cùng các anh chị đã giúp tôi có cái nhìn rõ ràng hơn với bức tranh nghiên cứu ONKK ở quê nhà. 
Tôi viết bài này như là để tổng kết lại những quan sát và 
suy nghĩ của tôi về tình hình nghiên cứu ONKK trong nước năm qua và ý kiến của tôi cho chặng đường nghiên cứu phía trước.

Tôi cũng xin thú nhận là tôi chưa từng làm nghiên cứu cũng như chưa tham gia một dự án nào ở trong nước,
do đó tôi hiểu những nghĩ suy này của tôi sẽ không tránh khỏi sự cảm tính, 
thiên kiến và thiếu chính xác.
Vì vậy, tôi rất mong nhận được sự góp ý của các anh chị (xin vui lòng inbox hoặc gửi vào hòm thư của tôi).

## Thực trạng nghiên cứu ONKK ở Việt Nam

Những năm gần đây, vấn đề ONKK đã nhận được sự quan tâm nhiều hơn từ các nhà khoa học, người dân, và các cấp chính quyền.
Sự đầu tư cho mạng lưới quan trắc không khí ở Việt Nam là việc làm rất đáng hoan nghênh. 
Cộng với sự góp mặt của cổng thông tin quan trắc môi trường, mạng lưới quan trắc môi trường thủ đô cũng như sự góp sức của
mạng lưới cảm biến từ PamAir hiện nay, bức tranh về mức độ ô nhiễm bụi mịn ở Hà Nội đã hiện ra khá rõ ràng.
Năm qua đã có thêm dự án dành cho việc kiểm thải và phân tích đặc trưng của bụi.
Theo tôi là những bước đi cần thiết để có thể định lượng đóng góp từng nguồn ô nhiễm. 

Một điểm rất sáng không thể không kể đến là về công bố khoa học.
Các nhà khoa học không những đã có thêm những công bố chất lượng trên tạp san uy tín,
mà chủ đề nghiên cứu cũng được mở rộng như đo đạc nồng độ ô nhiễm và lượng phát thải, 
phân tích đặc trưng bụi, phát triển mô hình mô phỏng, ứng dụng dữ liệu vệ tinh và tính toán sự phơi nhiễm. 
Cũng đã có thêm một số công bố liên ngành với sự tham gia của các chuyên gia bên kỹ thuật xử lý,
cũng như các chuyên gia về năng lượng, y tế và kinh tế. 
Tôi xin được chúc mừng các anh chị đồng nghiệp vì những nỗ lực nghiên cứu không mệt mỏi trong điều kiện tài trợ rất eo hẹp.

Những công bố khoa học này là những mảnh ghép quan trọng để chúng ta có thể hiểu sâu sắc hơn về thực trạng ONKK
và có những giải pháp đúng đắn. Tuy nhiên, theo tôi còn rất vấn đề nghiên cứu quan trọng liên quan tới ONKK ở 
Việt Nam đặt ra chưa được giải quyết. 
Với thực trạng ONKK hiện này, thì sự đầu tư của nhà nước và 
chính quyền địa phương cho việc nghiên cứu về ONKK còn rất khiêm tốn. 
Sự đầu tư này rõ rang là quá nhỏ bé so với lợi ích từ việc giảm thiểu ONKK như 
giảm chi phí gánh nặng bệnh tật, sự ổn định xã hội, và nhiều lợi ích kinh tế khác. 

## Cần đầu tư nhiều hơn cho nghiên cứu ONKK 

Theo kinh nghiệm của tôi thì việc đầu tư cho nghiên cứu ONKK cần được đầu tư một cách liên tục và bài bản.
Sự biến động về các nguồn ví dụ như sự gia tăng sản xuất công nghiệp, 
các loại phương tiện giao thông mới hay sư phát triển nóng của các khu đô thị 
mới có thể dẫn tới sự đóng góp của các nguồn theo từng thời gian khác nhau. 
Do đó, việc kiểm thải các nguồn ô nhiễm theo định kỳ là cần thiết. Hiện nay việc đầu tư cho thống kê 
kiểm thải các nguồn ô nhiễm ở Việt Nam còn nhiều khoảng trống, dẫn tới sự yếu kém trong việc phát các 
mô hình mô phỏng và dự báo kịch bản ô nhiễm.

Ngoài việc thu thập dữ liệu bụi mịn, chúng ta cũng thiếu nhiều dữ liệu về 
thành phần hóa học của bụi cũng như nhiều các chất khí cơ bản như NOx. 
Một số dự án gần đây được sự tài trợ của nước ngoài đã phân tích thành phần hóa học của bụi,
tuy nhiên dữ liệu đó theo thời gian dự án và không liên tục.
Sự thiếu một bộ dữ liệu đồng bộ và liên tục sẽ cản trợ sự phân tích xu thế ô nhiễm cũng như
khó có thể đưa ra một bức tranh tổng thể về tình hình ô nhiễm. Do đó ngoài đầu tư liên tục 
chúng ta cần đầu tư một cách có bài bản với những lộ trình thích hợp.

### Cần một chương nghiên cứu ONKK trọng điểm của quốc gia?

Hiện nay đầu tư nghiên cứu ONKK với số tiền tài trợ nhỏ và riêng lẻ có thể dẫn tới sự thiếu hiệu quả. 
Đặc thù của ngành môi trường nói chung và ONKK là đòi hỏi sự hợp tác chặt chẽ giữa các
nhà khoa học từ cùng một chuyên ngành hoặc liên ngành. 
Thí dụ, để thu mẫu và thực hiện các chiến dịch thu mẫu là rất tốn kém, 
do đó nếu gộp các dự án nhỏ lại 1 chương trình nghiên cứu lớn hơn, các nhà nghiên cứu có thể chia sẻ lẫn nhau các mẫu 
và thiết bị nghiên cứu và cũng như dữ liệu và kết quả nghiên cứu. 
Sự đồng bộ của dữ liệu về mặt thời gian cũng rất quan trong để có thể đánh giá và xác nhận độ chính xác của những mô hình mô phỏng,
từ đó cho chúng ta một bức tranh tổng thể về tình hình ONKK.  

Tôi đã đọc một số đề tài nghiên cứu về ONKK do Nafosted tài trợ, 
và tôi nhận thấy có thể gộp một vài đề tài đấy thành một đề tài lớn hơn với sự tham gia cùng lúc của nhiều nhóm nghiên cứu khác nhau. 
Theo tôi chúng ta cần có một chương trình nghiên cứu về ONKK với một sự tài trợ lớn và dài hơi. 
Các nhóm nghiên cứu cần hợp tác để kết hợp cùng nộp những đề tài nổi bật (hightlight topics) 
để các nhà tài trợ có thể đưa lựa chọn một hoặc hai chủ đề lớn nghiên cứu cần ưu tiên trong năm. 
Tất nhiên bên cạnh các đề tài trọng điểm quốc gia thì các địa phương cũng cần phải có những 
tài trợ nhỏ hơn để nghiên cứu tình hình ONKK trên địa bàn. 
Thí dụ thành phố Hà Nội có thể tài trợ cho đề tài về mô hình cảnh bảo sớm ONKK cũng dự dự đoán các đợt bụi kéo dài ở Hà Nội.

Những chủ đề lớn ví dụ như xác định nguồn ONKK ở Hà Nội:
các đề tại hiện tại mới đang tìm hiểu một vài khía cạnh như xác định hóa học của bụi 
sau đó dùng mô hình điểm tiếp nhận để tìm nguồn ô nhiễm. 
Tuy nhiên để có thể hiểu sâu và chính xác hơn về nguồn ONKK,
chúng ta cần kết hợp nhiều kỹ thuật phân tích khác nhau,
so sánh các mô hình mô phỏng cũng như các khía cạnh khác như cơ chế lan chuyền và hình thành các chất ô nhiễm.
Một số câu hỏi quan trọng khác mà tôi chưa có được câu trả lời như: đặc trưng hóa lý (source profiles)
và hệ số phát thải của bụi từ các nguồn ô khác nhau, 
cơ chế hình thành các đợt bụi kéo dài ở Hà Nội, các quá trình xảy ra trong khí quyển Hà Nội, 
hay nguồn nào đóng góp nhiều nhất cho sự phơi nhiễm ONKK. 

### Đầu tư thiết bị đo đạc và phân tích

Để thực hiện được nghiên cứu trên, tôi cho rằng các trường/ viện cũng các quỹ tài
trợ cần đầu tư mạnh mẽ cơ sở vật chất đặc biệt là các thiết bị đo đạc. 
Theo tôi quan sát thì các thiệt bị đo ô nhiễm không khí ngoài các trạm quan trắc, 
các thiết bị thu bụi và một số các cảm biến quang học thì chúng ta hầu như không có gì. 
Trong khi các trường viện mà tôi có dịp tới làm việc trên thế giới đã và đang đầu tư nhiều các thiết bị đo đạc hiện đại. 

Một sự thiếu hụt nghiêm trọng là về các thiết bị đo đạc theo thời gian thực (online instruments).
Các thiết bị hiện nay có thể đo những thành phần cơ bản của bụi như nông độ kim loại, ion, carbon đen,
tổng hàm lượng carbon và một số các chất hữu cơ cũng như các khí theo từng giờ, thậm chí từng phút. 
Những thiết bị đo đạc này rất hữu ích trong việc xác định nhanh nguyên nhân ô nhiễm cũng như cảnh báo ô nhiễm. 
Ví dụ như đợt cháy nhà máy Rạng Đông hồi năm 2019, nếu chúng ta có các thiệt bị này, chúng ta có thể có những 
cảnh báo nhanh và thiết thực về mức độ ô nhiễm.

Sự thiếu hụt các thiết bị đặc trưng lý tính của bụi như phân bố kích cỡ bụi, 
hình dáng cấu tạo, mật độ trọng lượng, cũng độ háo nước của bụi cũng làm hạn chế những nghiên cứu chuyên sâu về cơ chế hình thành
và lan truyền bụi. Xây dựng một siêu trạm quan trắc (supersite) bao gồm các thiết bị quan trắc hiện đại là điều tôi 
mong ước cần chúng ta hướng tới.

  
Một sự thiếu hụt đáng tiếc nữa là về các thiết bị phân tích thành phần hóa học.
Hiện các lab tiên tiến trên thế giới có trang bị những thiết bị hiện đại cũng như phát triển
những kỹ thuật phân tích mới như thiết bị sắc kí khí 2 chiều, có thể phân tích hàng ngàn các
hợp chất hữu cơ trong bụi cùng lúc. Tuy nhiên, khi đọc một số bài báo nghiên cứu tôi thấy có những 
phân tích đơn giản như hàm lượng ion và tổng lượng carbon trong bụi mà chúng ta vẫn gửi mẫu sang nước 
ngoài phân tích. 

Tôi biết đầu tư thiết bị phân tích và nâng cao khả năng phân tích rất tốn kém 
nhưng theo tôi điều đó mang lại những lợi ích lớn và dài lâu vì không những có thể phục vụ cho ngành ONKK mà còn 
các ngành khác như nghiên cứu về đất/nước, dược phẩm, thực phẩm và vật liệu đề rất cần. 
Những máy phân tích cơ bản như sắc kí khí (GC/MS) ở nhóm tôi dùng đã 25 năm nay mà vẫn còn chạy tốt.

### Đào tạo chuyên gia nghiên cứu

Tất nhiên để thực hiện nghiên cứu, thì không thể bỏ qua yếu tố con người. 
Tôi bắt đầu quan sát nhiều hơn về tình hình nghiên cứu ở VN nhiều hơn từ hè rồi bằng cách sưu tầm 
các bài báo khoa học đăng trên các tạp chí trong nước và ngoài nước. 
Thú thật, tôi khá bất ngờ với số lượng các anh chị đang làm về ONKK. 
Số lượng các nhà nghiên cứu nhiều hơn tôi nghĩ trước đó nhiều. 

Tuy vậy nếu so sánh với các nước khác như UK và với nhu cầu thực tế thì đội ngũ này còn rất mỏng. 
Theo tôi biết chúng ta đã và đang xây dựng các nhóm nghiên cứu mạnh- một việc làm hết sức cần thiết.
Việc đào tạo các sinh viên giỏi là việc không thể thiếu trong quá trình xây dựng các nhóm nghiên cứu đó.
Vì vậy chúng ta cần khuyến khích nhiều bạn trẻ tham gia nghiên cứu cũng như khuyến khích các em tự xin những học bổng nước ngoài. 
Về ngành khí quyển học tôi thấy có khá nhiều học bổng (từ trang này: [https://www.lists.rdg.ac.uk/archives/met-jobs/]( https://www.lists.rdg.ac.uk/archives/met-jobs/)). 

Bên cạnh đó chúng ta cũng cần nâng cao  khả năng đào tạo sinh viên và chuyên gia nghiên cứu trong nước.
Hè rồi tôi đã có 2 buổi training cho các em về phân tích dữ liệu ONKK và bản thân tôi cũng từng tốt nghiệp đại học ở ĐHQG, 
tôi cho rằng sinh viên Việt Nam có tiềm năng nhưng chưa được phát huy hết một phần do thiếu những tài liệu giảng dạy hiện đại.
Tôi có may mắn được đào tạo tiến sĩ từ chương trình H2O2 của EU về ô nhiễm không khí. 
Tôi sẵn sàng chia sẻ những kinh nghiệm học tập cũng những chương trình đào tạo. 

Tôi hi vọng sẽ có nhiều bạn trẻ tham gia vào nghiên cứu ô nhiễm khí quyển hơn. 
Trong 3 năm qua tôi có tham gia dạy khóa thạc sĩ về ONKK ở trường đại học Birmingham và King’s College London, 
có rất nhiều các sinh viên tới từ các nước có vấn đề ONKK như Việt Nam, tiếc là lớp tôi không có em sinh Việt nào.

## Lời kết

Tóm lại, tôi cho rằng chúng ta còn một chặng đường rất dài để có thể nâng cao chất lượng không khí theo được tiêu chuẩn của WHO. 
Nghiên cứu một cách bài bản về tình hình ONKK sẽ giúp chúng ta có những chính sách phù hợp để rút ngắn đáng kể chặng đường đó. 
Để đạt được điều đó, chúng ta cần đầu tư một cách mạnh mẽ trong việc tài trợ thiết bị nghiên cứu và các 
đề tài đủ lớn để giải quyết trọn vẹn từng vấn đề quan trọng và cần xây dựng một lộ trình thích hợp 
cho các chương trình nghiên cứu cũng như đào tạo các các chuyên gia mới.

*PS1: Bài này hơi dài, tôi hi vọng không làm lãng phí thời gian của các anh chị. 
Chúc các anh chị một năm 2021 an lành.*


*PS2:* (*) *Tới các anh chị nào quan tâm tới nghiên cứu hiện tại của tôi. 
Hai dự án chính tôi đang tham gia là: 1) [“An Air Pollution Exposure model 
to integrate protection of vulnerable groups into the UK Clean Air Programme"-£1.4 mil by UKRI-NERC](https://gtr.ukri.org/project/6D2FF57F-BE97-4070-B074-685CC802D05F) và 
2) [“Cognitive DeveLopment in the Urban Environment”-£0.6 mil by MRC](https://gtr.ukri.org/projects?ref=MR%2FR00322X%2F1)*
