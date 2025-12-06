<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NGUYỄN HUỲNH ĐĂNG THƯ</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins', sans-serif;}

  /* Nền */
  body{
    background: url('THƯ.jpg') no-repeat center/cover;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
  }

  /* CARD GIỚI THIỆU */
  .card{
    position:relative;
    width:440px;            /* ⭐ rộng ngang hơn  */
    padding:28px 32px;      /* ⭐ mở rộng padding ngang */
    border-radius:20px;
    text-align:center;
    background:rgba(255,255,255,0.13);
    backdrop-filter:blur(14px);
    border:1px solid rgba(255,255,255,0.3);
    color:#fff;
    box-shadow:0 8px 30px rgba(0,0,0,0.3);
    animation:fadeIn .8s ease;
  }

  /* Avatar */
  .avatar{
    width:120px;
    height:120px;
    border-radius:50%;
    object-fit:cover;
    border:4px solid rgba(255,255,255,0.7);
    margin-bottom:18px;
    box-shadow:0 4px 12px rgba(0,0,0,0.4);
  }

  h2{font-size:26px;font-weight:700; margin-bottom:6px;}

  /* ⭐ Phần hồ sơ chuyên nghiệp */
  .profile-section{
    margin-top:14px;
    margin-bottom:10px;
    text-align:left;
  }

  .profile-section h3{
    font-size:17px;
    margin-bottom:4px;
    color:#ffecec;
    font-weight:600;
  }

  .profile-section p{
    font-size:14.5px;
    line-height:1.5;
    color:#f7f7f7;
  }

  /* Social buttons */
  .social{
    margin-top:18px;
    display:flex;
    justify-content:center;
    gap:12px;
    flex-wrap:wrap;
  }

  .social a{
    padding:10px 14px;
    background:rgba(255,255,255,0.2);
    border-radius:12px;
    color:white;
    text-decoration:none;
    font-weight:500;
    transition:.25s;
    font-size:14px;
  }

  .social a:hover{
    background:white;
    color:#222;
    transform:translateY(-3px);
  }

  @keyframes fadeIn{
    from{opacity:0; transform:translateY(20px);}
    to{opacity:1; transform:translateY(0);}
  }
</style>

</head>
<body>

<div class="card">
  <img src="ĐT.jpg" class="avatar" alt="avatar">

  <h2>Nguyễn Huỳnh Đăng Thư</h2>

  <!-- 🔹 BẮT ĐẦU: Thông tin hồ sơ chuyên nghiệp -->
  <div class="profile-section">
    <h3>Giới thiệu</h3>
    <p>Mình là Nguyễn Huỳnh Đăng Thư, học sinh lớp 12 Văn. Công việc mình muốn trong tương lai là Event Producer.</p>
  </div>

  <div class="profile-section">
    <h3>Sở thích</h3>
    <p>• Thể thao<br>
       • Du lịch<br>
       • Xem phim</p>
  </div>

  <div class="profile-section">
    <h3>Tính cách</h3>
    <p>Mình là người hoà đồng, năng động, thích trải nghiệm và thử thách bản thân ✨</p>
  </div>
  <!-- 🔹 KẾT THÚC: Thông tin hồ sơ chuyên nghiệp -->

  <div class="social">
    <a href="#">https://www.facebook.com/share/17oGvZN4PS/?mibextid=wwXIfr</a>
    <a href="#">dangthu_nguyenhuynh</a>
    <a href="#">dangthunguyenhuynh43@gmail.com</a>
  </div>

</body>
</html>
  <a href="https://nt4620567-byte.github.io/Nhom4-12van/"style="
  display:inline-block;
  padding:10px 16px;
  text-decoration:none;
  border:1px solid #ccc;
  border-radius:6px;
  font-size:16px;
">
  ← Quay lại trang chủ
</a>
