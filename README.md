<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NGUYỄN HUỲNH ĐĂNG THƯ</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins', sans-serif;}

  body{
    background: url('THƯ.jpg') no-repeat center/cover;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
  }

  .card{
    position:relative;
    width:440px;
    padding:28px 32px;
    border-radius:20px;
    text-align:center;
    background:rgba(255,255,255,0.13);
    backdrop-filter:blur(14px);
    border:1px solid rgba(255,255,255,0.3);
    color:#fff;
    box-shadow:0 8px 30px rgba(0,0,0,0.3);
    animation:fadeIn .8s ease;
  }

  .avatar{
    width:120px;
    height:120px;
    border-radius:50%;
    object-fit:cover;
    border:4px solid rgba(255,255,255,0.7);
    margin-bottom:18px;
  }

  h2{font-size:26px;font-weight:700; margin-bottom:6px;}

  .profile-section{
    margin-top:14px;
    margin-bottom:10px;
    text-align:left;
  }

  .profile-section h3{
    font-size:17px;
    color:#ffecec;
    font-weight:600;
  }

  .profile-section p{
    font-size:14.5px;
    line-height:1.5;
    color:#f7f7f7;
  }

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

  .back-home{
    display:inline-block;
    padding:10px 16px;
    margin-top:18px;
    text-decoration:none;
    border:1px solid #ccc;
    border-radius:6px;
    font-size:16px;
    color:white;
    transition:0.3s;
  }

  .back-home:hover{
    background:white;
    color:black;
  }

</style>

</head>
<body>

<div class="card">
  <img src="ĐT.jpg" class="avatar" alt="avatar">

  <h2>Nguyễn Huỳnh Đăng Thư</h2>

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

  <div class="social">
    <a href="#">Facebook</a>
    <a href="#">Instagram</a>
    <a href="#">Gmail</a>
  </div>

  <!-- ⭐ Nút quay lại trang chủ -->
  <a class="back-home" href="https://nt4620567-byte.github.io/Nhom4-12van/">
    ← Quay lại trang chủ
  </a>

</div>

</body>
</html>

