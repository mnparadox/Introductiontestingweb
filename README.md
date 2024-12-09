<html lang="en">
  <meta charset="UTF-8">
  <title>Nhóm 4 - Trang Web Chính Thức</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      text-align: center;
      background-color: #4CAF50;
      padding: 20px;
      color: white;
    }
    .banner img {
      width: 100%;
      height: auto;
    }
    .nav-icons {
      text-align: center;
      margin: 20px 0;
    }
    .nav-icons a {
      margin: 0 10px;
      text-decoration: none;
      display: inline-block;
      text-align: center;
      width: 80px;
      height: 80px;
      background-color: #f2f2f2;
      border: 2px solid #4CAF50;
      border-radius: 50%;
      overflow: hidden;
      transition: transform 0.3s, background-color 0.3s;
    }
    .nav-icons a:hover {
      transform: scale(1.1);
      background-color: #4CAF50;
    }
    .nav-icons img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
    section {
      padding: 20px;
      margin: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      background-color: #f9f9f9;
    }
    .donate-form {
      width: 50%;
      margin: 20px auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      background-color: #f9f9f9;
    }
    .donate-form input, .donate-form button {
      width: calc(100% - 22px);
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .donate-form button {
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    .donate-form button:hover {
      background-color: #45a049;
    }
  </style>
<body>

<header>
  <h1>CHÀO MỪNG ĐẾN VỚI NHÓM 4</h1>
</header>

<div class="nav-icons">
  <a href="ngocngan.html" title="Phạm Ngọc Ngân">
    <img src="ngocngan-icon.jpg" alt="Ngọc Ngân">
  </a>
  <a href="kimnguyen.html" title="Lữ Ngọc Kim Nguyên">
    <img src="KimNguyen.jpg" alt="Kim Nguyên">
  </a>
  <a href="mynhan.html" title="Ngô Mỹ Nhàn">
    <img src="mynhan-icon.jpg" alt="Mỹ Nhàn">
  </a>
  <a href="thanhhieu.html" title="Nguyễn Thành Hiếu">
    <img src="thanhhieu-icon.jpg" alt="Thành Hiếu">
  </a>
</div>

<section>
  <h2>Giới thiệu về Nhóm 4</h2>
  <p>
    Nhóm 4 là một đội ngũ gồm bốn thành viên tài năng và nhiệt huyết: 
    Phạm Ngọc Ngân, Lữ Ngọc Kim Nguyên, Ngô Mỹ Nhàn, và Nguyễn Thành Hiếu. 
    Chúng tôi đến từ lớp 12 Lý của trường THPT Chuyên Bến Tre và cùng nhau xây dựng trang web này với mục đích:
  </p>
  <ul>
    <li>Chia sẻ thông tin học tập và kinh nghiệm thú vị từ các thành viên.</li>
    <li>Tạo nền tảng kết nối và giao lưu giữa học sinh trong trường.</li>
    <li>Gây quỹ để thực hiện các dự án học tập và hoạt động xã hội.</li>
  </ul>
  <p>
    Trang web này không chỉ là nơi để mọi người tham khảo thông tin về nhóm, mà còn là một biểu tượng cho sự đoàn kết, sáng tạo và nỗ lực không ngừng. 
    Nhóm 4 cam kết mang lại giá trị thiết thực và khích lệ tinh thần học tập trong cộng đồng học sinh.
  </p>
</section>

<section>
  <h2>Donate Cho Nhóm 4</h2>
  <form class="donate-form">
    <label for="name">Họ và Tên:</label>
    <input type="text" id="name" name="name" placeholder="Nhập tên của bạn" required>

  <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Nhập email của bạn" required>

  <label for="amount">Số tiền (VNĐ):</label>
    <input type="number" id="amount" name="amount" placeholder="Nhập số tiền" min="1000" required>

  <button type="submit">Donate ngay</button>
  </form>
  <p align="center">Số tài khoản nhận tiền: <b>0918167809</b> - BIDV</p>
</section>

</body>
</html>
