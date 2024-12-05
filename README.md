<html>
    <style>
        h1 {color : white;
	background-color: pink;
	border : 70px solid pink
	}
        .container {
        display: flex;
	background-color: pink; 
        }
        .item {
            flex: 1;
            border: 1px solid pink;
            padding: 10px;
	    color: black;
        }
    </style>
<body>
  <h1>Nhóm 1-Lớp 12 L-Trường THPT Chuyên Bến Tre </h1>
  <p>Xin chào! Chúng tôi là học sinh lớp 12 Chuyên Lý</p>
<p><a href="https://thptchuyenbentre.edu.vn/"> trường THPT Chuyên Bến Tre.</a></p>
   <title>Bố cục ngang</title>
    <div class="container">
        <div class="item">Trang chủ </div>
        <div class="item"><a href="qnhu.html">Quỳnh Như</a></div>
        <div class="item"><a href="ttam.html">Trúc Tâm</a></div>
        <div class="item"><a href="nthy.html">Nhã Thy</a></div>
	<div class="item"><a href="thang.html">Thúy Hằng</a></div>
	<div class="item"><a href="ny.html">Như Ý</a></div>
    </div>
<table border="1">
 <caption>Lịch học của 12 Lý</caption>
 <tr style="border:1px solid">
    	<th rowspan="2">Bộ môn</th>
        <th rowspan="2">GV phụ trách</th>
        <th colspan="6">Ngày</th>
 </tr>
   <tr>
    	<th>Thứ 2</th>
        <th>Thứ 3</th>
        <th>Thứ 4</th>
        <th>Thứ 5</th>
        <th>Thứ 6</th>
        <th>Thứ 7</th>
   </tr>
   <tr>
    	<td>Toán</td>
        <td>Cô Quyền</td>
        <td>X</td>
        <td></td>
        <td>X</td>
        <td></td>
        <td></td>
        <td>X</td>
   </tr>
   <tr>
    	<td>Lí</td>
        <td>Thầy Huy</td>
        <td></td>
        <td>X</td>
        <td></td>
        <td></td>
        <td>X</td>
        <td></td>
   </tr>
   <tr>
    	<td>Hóa</td>
        <td>Thầy Phú</td>
        <td></td>
        <td></td>
        <td>X</td>
        <td></td>
        <td></td>
        <td>X</td>
   </tr>
   <tr>
    	<td>Anh</td>
        <td>Cô Thảo</td>
        <td>X</td>
        <td></td>
        <td></td>
        <td>X</td>
        <td></td>
        <td></td>
   </tr>
   <tr>
    	<td>Văn</td>
        <td>Cô Thoa</td>
        <td>X</td>
        <td>X</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
   </tr>
<p>Dưới đây là một số hình ảnh về chúng tôi</p>
<img src="img/quynhnhu.png" width="700" height="500" alt="Ảnh lớp 12L">
<video src="video/lop.mp4" width="700" height="500" alt="3"></video>
<video src="video/12l.mp4" width="700" height="500" alt="3"><video>
<h2>Hãy để chúng tôi biết thêm về sở thích của bạn</h2>
  <form>
    <fieldset>
	<label for="hoten">Họ và tên</label>
	<input id="hoten" type="text"><br/><br/>
	<label for="ngaysinh">Ngày sinh</label>
	<input id="ngaysinh" type="date"><br/><br/>
	<label for="Gioitinh">Giới tính</label>
	<input type="radio" name="gioitinh" value="Nam">Nam
	<input type="radio" name="gioitinh" value="Nu">Nữ<br/><br/>
	<label for="monan">Món ăn yêu thích</label><br/>
	<input type="checkbox" name="monan" value="Com">Cơm
	<input type="checkbox" name="monan" value="Bun">Bún
	<input type="checkbox" name="monan" value="Banhmi">Bánh mì<br/><br/> <label for="thich">Thích</label>
	<select id="thich" name="Thích">
	<option value="anvat">Ăn vặt</option>
	<option value="monlau">Món lẩu</option>
	<option value="monnuong">Món nướng</option>
	<option value="cacloainuoc">Các loại nước</option>
	</select><br/><br/>
	<input type="submit" value="Gửi thông tin">
   </fieldset>
</body>
</html>
