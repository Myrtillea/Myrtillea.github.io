# Myrtillea.github.io
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Class 12D4-K68 Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    /* Reset */
    body, h1, h2, h3, h4, p, ul, li, a, form, input, textarea, button, table, th, td, div {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Global Styles */
    body {
      background: linear-gradient(to bottom, #dceefb, #c6e0f5);
      font-family: 'Roboto', sans-serif;
      color: #333;
      line-height: 1.6;
      padding-top: 20px;
      transition: background 0.5s ease;
    }
html {
  scroll-behavior: smooth;
}
    h1, h2, h3, h4 {
      font-family: 'Roboto', sans-serif;
    }

    /* Container */
    #container {
      width: 90%;
      max-width: 1000px;
      overflow: hidden;
      margin: 50px auto;
      background: white;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      padding: 20px;
      transition: transform 0.3s ease;
    }

    /* Header */
    header {
      text-align: center;
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 3.5rem;
      color: #232d63;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #666;
    }

    /* Navigation Bar */
    nav {
      position: sticky;
      top: 0;
      background: #232d63;
      padding: 15px;
      text-align: center;
      z-index: 10;
    }

    nav a {
      font-size: 1.1rem;
      text-decoration: none;
      color: white;
      margin: 0 15px;
      padding: 10px 20px;
      border: 2px solid white;
      border-radius: 5px;
      transition: background-color 0.3s, color 0.3s;
    }

    nav a:hover {
      background-color: white;
      color: #232d63;
    }

    /* Photo Banner */
    .photobanner {
      height: 300px;
      display: flex;
      overflow: hidden;
      position: relative;
      margin-bottom: 30px;
      border-radius: 10px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
    }

    .photobanner img {
      height: 100%;
      animation: bannermove 30s linear infinite;
      object-fit: cover;
    }

    @keyframes bannermove {
      0% { transform: translateX(0); }
      100% { transform: translateX(-3000px); }
    }

    /* Content Sections */
    .content {
      margin-bottom: 30px;
    }

    h2 {
  color: #2a4d85;
  margin-bottom: 10px;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-size: 2rem;
}

    .content ul {
      margin-left: 20px;
    }

    .content ul li {
      margin-bottom: 10px;
      font-size: 1.1rem;
    }

    /* Section Cards */
    .card {
      background: #fff;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card img {
      width: 100%;
      height: auto;
      max-width: 100%;
      display: block;
      border-radius: 8px;
    }
    .card video {
      width: 100%; /* Make the video take up the full width of the card */
      height: auto; /* Maintain aspect ratio */
      border-radius: 8px; /* Same rounded corners as the card */
      box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1); /* Optional: Add a shadow for consistency */
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0px 6px 10px rgba(0, 0, 0, 0.2);
    }

    /* Table */
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      border-radius: 8px;
      overflow: hidden;
    }

    th, td {
      padding: 15px;
      text-align: center;
      border: 1px solid #ddd;
    }

    th {
      background-color: #f4f4f4;
      font-weight: bold;
    }

    td {
      background-color: #f9f9f9;
    }
    #comment-section {
    margin-top: 30px;
    padding: 20px;
    background-color: #f9f9f9;
    border-radius: 10px;
}

#comment-form textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
    resize: none;
}

#comment-form button {
    background-color: #232d63;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1rem;
}

#comment-form button:hover {
    background-color: #1e2554;
}

#comments-list {
    list-style-type: none;
    padding: 0;
}

#comments-list li {
    background: #fff;
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

    /* Footer */
    footer {
      text-align: center;
      margin-top: 50px;
      font-size: 1.1rem;
      color: #666;
    }

    footer p {
      margin-bottom: 10px;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .content h2 {
        font-size: 1.5rem;
      }

      nav a {
        font-size: 1rem;
        margin: 0 10px;
      }

      .card {
        padding: 15px;
      }
    }

  </style>
</head>
<body>
  <div id="container">
    <!-- Header -->
    <header>
      <h1>CHÀO MỪNG MỌI NGƯỜI ĐÃ ĐẾN VỚI LỚP 12D4-K68</h1>
      <p>Trường Trung Học Phổ Thông Vũng Tàu</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
      <a href="#">Mục lục:</a>
      <a href="#Giới thiệu chung">Giới thiệu chung</a>
      <a href="#Thành viên lớp">Thành viên lớp</a>
      <a href="#Học tập">Học tập</a>
      <a href="#Văn nghệ & Kỷ niệm">Văn nghệ & Kỷ niệm</a>
    </nav>

    <!-- Photo Banner -->
    <div class="photobanner">
      <img src="C:/Users/ASUS/Downloads/truong.jpg" alt="School Image" />
      <img src="C:/Users/ASUS/Documents/Zalo Received Files/anh_lop.jpg" alt="Class Image" />
      <img src="C:/Users/ASUS/Documents/Zalo Received Files/anh_lop2.jpg" alt="Class Image 2" />
      <img src="C:/Users/ASUS/Documents/Zalo Received Files/anhlop3.jpg" alt="Class Image 3" />
      <img src="C:\Users\ASUS\Documents\Zalo Received Files\anh lop.jpg" alt="Class Image 4" />
      
    </div>

    <!-- Main Content -->
    <div class="content">

      <div id="Giới thiệu chung"class="card">
        <h2>Giới thiệu chung</h2>
        <p>Chúng tớ là học sinh lớp 12D4 thuộc <em>trường THPT Vũng Tàu</em> là tập thể gồm 40 đàn con của thầy chủ nhiệm <3</p>
        <p>Niên khoá: 2022-2025</p>
        <p>Giáo viên chủ nhiệm: Vũ Đình Quyết</p>
      </div>
      <div id="Thành viên lớp"class="card">
        <h2>Thành viên lớp</h2>
        <ol type="1">
          <li>Bùi Diệu Anh</li>
          <li>Đỗ Minh Anh</li>
          <li>Lê Vũ Quỳnh Anh</li>
          <li>Nguyễn Bình Phương Anh</li>
          <li>Nguyễn Hà Anh</li>
          <li>Phạm Phương Anh</li>
          <li>Võ Hồng Ân <strong>(Lớp phó học tập)</strong></li>
          <li>Trịnh Y Bình</li>
          <li>Nguyễn Minh Châu</li>
          <li>Trần Thị Diệu Châu</li>
          <li>Vũ Bảo Châu</li>
          <li>Nguyễn Huỳnh Ngọc Diệp</li>
          <li>Đào Thùy Dương</li>
          <li>Hoàng Quỳnh Giao</li>
          <li>Mai Thị Thanh Hiền <strong>(Lớp trưởng)</strong></li>
          <li>Lê Hoàng Huy</li>
          <li>Nguyễn Lê Khanh</li>
          <li>Đỗ Trần Thụy Khuê<strong>(Lớp phó lao động)</strong></li>
          <li>Dương Vũ Thảo Linh</li>
          <li>Lê Mai Khánh Linh</li>
          <li>Trần Khánh Linh</li>
          <li>Trần Thị Thùy Linh</li>
          <li>Vũ Thùy Linh</li>
          <li>Nguyễn Vũ Minh Lộc</li>
          <li>Đặng Nguyễn Khánh Ly</li>
          <li>Trần Khánh Ly</li>
          <li>Hoàng Xuân Mai</li>
          <li>Nguyễn Hà My</li>
          <li>Ong Huỳnh Phương Nghi</li>
          <li>Phạm Minh Nguyên</li>
          <li>Cao Hạnh Nhi</li>
          <li>Nguyễn Phương Nhi</li>
          <li>Nguyễn Bảo Như</li>
          <li>Hoàng Minh Sang</li>
          <li>Lý Hoàng Anh Thảo</li>
          <li>Nguyễn Thị Phương Thảo</li>
          <li>Đào Quỳnh Trang</li><strong>(Lớp phó văn thể mỹ)</strong>
          <li>Tạ Nguyễn Hiền Trang</li>
          <li>Chu Vũ Khánh Vy</li>
          <li>Kim Nguyễn Yoon</li>
        </ol>
      </div>

      <div id="Học tập"class="card">
        <h2>Học tập</h2>
        <h3>Thời khoá biểu</h3>
        <table>
          <tr>
            <th>Thứ 2</th>
            <th>Thứ 3</th>
            <th>Thứ 4</th>
            <th>Thứ 5</th>
            <th>Thứ 6</th>
            <th>Thứ 7</th>
          </tr>
          <tr>
            <td>Chào cờ</td>
            <td>Toán</td>
            <td>Anh văn</td>
            <td>GDKT-PL</td>
            <td>Tin học</td>
            <td>Địa lí</td>
          </tr>
          <tr>
            <td>Ngữ văn</td>
            <td>Ngữ văn</td>
            <td>Anh văn</td>
            <td>Thể dục</td>
            <td>GDQP</td>
            <td>Địa lí</td>
          </tr>
          <tr>
                <td>Toán</td>
                <td>Ngữ văn</td>
                <td>Địa lí</td>
                <td>Anh văn</td>
                <td>Toán</td>
                <td>Lịch sử</td>
            </tr>
            <tr>
                <td>Anh văn</td>
                <td>Anh văn</td>
                <td>Địa lí</td>
                <td>Ngữ văn</td>
                <td>Lịch sử</td>
                <td>Thể dục</td>
            </tr>
            <tr>
                <td>Tin học</td>
                <td>GDKT-PL</td>
                <td> </td>
                <td>Toán</td>
                <td>Sinh học</td>
                <td>Sinh hoạt lớp</td>
            </tr>
        </table>
        <h3>Thành tựu đạt được của lớp </h3> 
        <dl>
          <dt><b>Lớp 10</b></dt>
          <dd>Giải khuyến khích HSG Anh Văn cấp tỉnh</dd>
          <dt><b>Lớp 11</b></dt>
          <dd>Giải ba HSG Ngữ Văn cấp tỉnh</dd> 
          <dd>Giải khuyến khích HSG Anh Văn cấp tỉnh</dd>
          </dl> 
      </div>

      <div id="Văn nghệ & Kỷ niệm"class="card">
        <h2>Văn nghệ</h2>
        <h3>Văn nghệ dịp 20/11 lớp 11:</h3>
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\van nghe 11.jpg">
        <h3>Văn nghệ dịp 26/03 lớp 11:</h3> 
        <img src="C:\Users\ASUS\Downloads\hoi trai 11.jpg">
        <h3>Văn nghệ dịp 20/11 lớp 12:</h3>  
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\van nghe 12.jpg"> 
      </div>
      <div class="card">
        <h2>Kỷ niệm</h2>
        <h3>Mừng Ngày Boy's Day 19/11</h3>
        <p>Lớp 11:</p>
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\19_11.jpg"> 
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\19_11_lop11(1).jpg"> 
        <p>Lớp 12:</p> 
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\19_11 lop 12.jpg">
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\19_11 lop 12 (1).jpg">
        <h3>Mừng Ngày Nhà Giáo Việt Nam 20/11</h3>
        <p>Lớp 11:</p>
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\20_11_lop11.jpg" alt="Mô tả ảnh">
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\20_11_lop11(1).jpg" alt="Mô tả ảnh">
        <p>Lớp 12:</p> 
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\20_11_lop12.jpg"> 
        <h3>Giải bóng ném</h3>
        <video width="320" height="240" controls>
        <source src="C:\Users\ASUS\Documents\Zalo Received Files\bong nem 12.mp4" type="video/mp4">
        </video>
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\bong nem 12 (1).jpg"> 
        <h3>Thi gói bánh chưng dịp Tết</h3>
        <video width="320" height="240" controls>
        <source src="C:\Users\ASUS\Documents\Zalo Received Files\banh chung 11.mp4" type="video/mp4">
        </video>
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\banh_chung(1).jpg">
        <img src="C:\Users\ASUS\Documents\Zalo Received Files\banh chung 11(2).jpg"> 
      </div>
    </div>
      <div class="card">
        <h2>Đôi lời gửi gắm</h2> 
        <h3>Với giáo viên bộ môn Tin Học:</h3> 
        <p>Đây đã là năm thứ 2 lớp chúng em có vinh dự được gắn bó và chỉ bảo bởi cô Ngọc Anh. Đối với em, cô luôn là người luôn tạo được nhiều niềm cảm hứng đến với môn học tưởng chừng như khô khan này. Từ một đứa hiếu kì với việc được lập trình cùng máy tính, cô đã luôn ở bên chỉ bảo và dạy cho chúng em những điều hay ho ở cả những bài học trên lớp lẫn những lời hay lẽ phải để tụi em có thể trở thành những người có đạo đức trong xã hội. Vì bây giờ chúng em đã là những học sinh lớp 12, chúng em mong muốn sẽ cùng ghi nhiều dấu ấn với cô nhất có thể trong suốt năm học cuối này. Em và lớp chân thành cảm ơn sự cống hiến hết mình của cô.</p>
        <h3>Với lớp:</h3>
        <p>Lớp ơi chưa gì ta lại sắp trôi qua một nửa hành trình năm học này rồi. Vì là năm cuối nên ai cũng sẽ cố gắng dành thời gian chăm chỉ học hành hơn cho những kì thi sắp tới và quan trọng nhất là cho kì thi TNTHPTQG.Tuy vậy mọi người cũng đừng quên chăm sóc cho cả bản thân mình nhé, học thì học nhưng mà cũng không nên quên ăn uống ngủ nghỉ cho đủ giấc. Tớ mong lớp mình đều sẽ đậu được NV1 và vào các trường mà mình mong muốn, nên mọi người hãy cố lên nhe <3</p>
        </div> 
        <div id="comment-section" class="card">
    <h2>Hòm thư bày tỏ & góp ý</h2>
    <form id="comment-form">
        <label for="comment">Góp ý của bạn:</label>
        <textarea id="comment" name="comment" rows="5" cols="50" placeholder="Hãy bày tỏ ở đây nhé..." required></textarea>
        <br>
        <button type="submit">Nhấn gửi ở đây nheee!!!!!!!</button>
</div>
</div>
    <!-- Footer -->
    <footer>
      <p>&copy; 2024 Class 12D4-K68. All rights reserved.</p>
    </footer>
  </div>
      </form>
</body>
</html>
