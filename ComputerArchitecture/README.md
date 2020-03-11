Chúng ta đang sống trong thời đại mà công nghệ phát triển nhanh hơn bao giờ hết. Vào những năm 40 của thập kỷ trước, xuất hiện chiếc máy tính thương mại đầu tiên, chiếc máy tính ấy có kích cỡ bằng một căn phòng, rất tốn kém và dường như chỉ là những thứ đồ chơi xa xỉ, 70 năm sau đó, máy tính đã trở thành một công cụ không thể thay thế trong cuộc sống hàng ngày. Hiệu năng tính toán của máy tính đã tăng lên gấp rất nhiều lần so với chiếc máy tính thương mại đầu tiên, điều đó đã đưa con người vào một kỷ nguyên mới, đó là kỷ nguyên số. Cho đến năm nay, những bộ vi xử lý mới đã có hiệu năng tính toán cực cao mà 10 năm trước dường như đạt được điều này chỉ là giấc mơ. Dưới đây là một vài bộ xử lý mới có clockspeed đáng kể.
```
AMD Ryzen 9 3900X  				    clock: 3.8 - 4.6GHz
Intel Core i9-9900KS			       clock: 4.0 - 5.0GHz
AMD Ryzen 5 2600X				      clock: 3.6 - 4.3GHz
AMD Ryzen 3 2200G				      clock: 3.5 - 3.7GHz
```

Tuy nhiên, dường như sự phát triển của tốc độ của bộ xử lý đang chậm lại và đạt đến giới hạn, đó là 5.0GHz. Những giới hạn đó là gì?
  

Trong thực tế, có 2 yếu tố chính dẫn giới hạn tốc độ của một bộ vi xử lý, đó là lượng nhiệt năng sản sinh ra và độ trễ truyền (transmission delay). Tuy nhiên, yếu tố cản trở chủ yếu là yếu tố nhiệt năng tỏa ra.

  

Các bộ xử lý hiện nay được sản xuất sử dụng công nghệ CMOS. Cứ mỗi một clock cycle thì sẽ có một lượng nhiệt tỏa ra, điều đó dẫn đến việc tốc độ xung clock càng cao thì lượng nhiệt năng tỏa ra càng cao. Biểu đồ ở dưới là thể hiện sự tương quan giữa tốc độ xung clock (clockspeed ở cột ngang) và điện năng tiêu thụ (power-consumption ở cột dọc).

<center><img src="https://i.stack.imgur.com/daciI.png" width="650"></center>
<div style="font-size: 13px;"><center><b>Figure 1</b>. <i>Biểu đồ thể hiện mối quan hệ giữa tốc độ xung clock và điện năng tiêu thụ.</i></center></div>

Để đối phó với lượng nhiệt tản ra, các nhà sản xuất cố gắng để thiết kế ra các bóng bán dẫn (transistors) với kích thước nhỏ. Vào năm 2000, chúng ta có 130 nanometer process; vào năm 2017 con số đó giảm còn 10 nanometer.  Tuy nhiên vẫn có một giới hạn đối với việc chúng ta có thể làm ra các bóng bán dẫn nhỏ đến đâu. Khi bóng bán dẫn trở nên quá nhỏ, electron có thể dịch chuyển qua các bóng bán dẫn thông qua quy trình xuyên hầm lượng tử (quantum tunneling), điều đó có nghĩa rằng một bóng bán dẫn đang trong trạng thái tắt (trạng thái 0) có thể chuyển sang trạng thái bật (trạng thái 1) một cách ngẫu nhiên.

  

Thêm nữa, như ở trên đã trình bày, các bộ xử lý có tốc độ càng cao thì tỏa nhiệt càng nhiều. Mặc dù công nghệ tản nhiệt hiện nay cũng đã có nhiều tiến bộ, nhưng bộ xử lý vẫn có thể trở nên rất nóng, khiến cho các bộ phận nhạy cảm trong bộ xử lý có thể bị tan chảy dẫn đến hư hỏng.
