---
title:  "Phân tích dữ liệu ô nhiễm không khí- giới thiệu R-package openair"
comments: true
date:   2020-04-08 00:00:00 -0000
layout: single
classes: wide
author_profile: true
header:
  teaser: /assets/images/onkk.ctw.png
---

## Phân tích dữ liệu ô nhiễm không khí bằng R-package Open air

Với sự phát triển trong công nghệ cảm biến chi phí thấp cùng với những dữ liệu đo đạc ngày một nhiều từ vệ tinh, 
thì chúng ta đang có bộ dữ liệu về khí quyển ngày càng lớn. Để phân tích dữ liệu như vậy thì những hiểu biết phân tích dữ liệu qua Python hoặc R là rất hữu ích trong việc nghiên cứu.

Xin chia sẻ với các anh chị thích phân tích dữ liệu ô nhiễm không khí cuốn sách updated về "openair" R-package của giáo sư Carslaw theo link dưới đây.
link sách: [https://bookdown.org/david_carslaw/openair/](https://bookdown.org/david_carslaw/openair/)

Theo tôi đây là tài liệu mà sinh viên ngành nghiên cứu ô nhiễm không khí nên có. Tài liệu có code viết rất rõ ràng, dễ hiểu và dễ thực hành. 
Package này sẽ giúp các bạn dễ dàn lấy dữ liệu về các chất ô nhiễm cũng như dữ liệu khí tượng từ nhiều nơi trên thế giới trong đó có Việt Nam.
Xa hơn nữa, các bạn có thể vận dụng để phác họa biểu đồ theo thời gian của bụi, hoặc các biểu đồ hoa gió cũng như sự vận chuyển từ xa của bụi.

## Thực hành cho dữ liệu từ VN
Cách đây mấy tháng tôi đã có 2 buổi hướng dẫn 1 số bạn sinh viên VN thực hành về package này cho dữ liệu các chất ô nhiễm không khí từ Việt Nam. 
Các bạn có thể tham khảo folder trong đó có code và hướng dẫn thực hành phân tích ONKK tại VN:
[https://github.com/tuanvvu/Atmospheric_science_VN](https://github.com/tuanvvu/Atmospheric_science_VN)

Hình dưới minh họa từ buổi thực hành:
Hình 1: Các cụm khối khí di chuyển tới Hà Nội trong các tháng khác nhau
Hình 2: Ảnh hưởng sự vận chuyển bụi từ xa tới Hà Nội
Các bạn cũng có thể đọc thêm tài liệu tham khảo: 
[The effects of meteorological conditions and long-range transport on PM2.5 levels in Hanoi revealed from multi-site measurement using compact sensors and machine learning approach](https://www.sciencedirect.com/science/article/pii/S0021850220302019)

![animation]({{ site.url }}/assets/images/onkk.backtraj.png) 

*Hình 1. Các cụm khối khí di chuyển tới Hà Nội trong các tháng khác nhau.*

![animation]({{ site.url }}/assets/images/onkk.ctw.png) 
*Hình 2. Ảnh hưởng sự vận chuyển bụi từ xa tới Hà Nội.*
