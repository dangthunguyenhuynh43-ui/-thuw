# -thuw
<!DOCTYPE html>
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
    background: url('THƯ.jpd')
                no-repeat center/cover;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
  }

  /* Lớp mờ */
  body::before{
    content:"";
    position:absolute; inset:0;
    background:rgba(0,0,0,0.45);
    backdrop-filter:blur(5px);
  }

  /* CARD GIỚI THIỆU */
  .card{
    position:relative;
    width:360px;
    padding:28px;
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

  h2{font-size:26px;font-weight:700;}
  p.bio{margin-top:10px;line-height:1.6;font-size:15px;color:#f1f1f1;}

  /* Social buttons */
  .social{
    margin-top:18px;
    display:flex;
    justify-content:center;
    gap:12px;
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
  <img src="Đăng Thư.png" class="avatar" alt="avatar">

  <h2>Nguyễn Huỳnh Đăng Thư</h2>
  <p class="bio">
    Xin chào! Mình là học sinh lớp 12 Văn, yêu thích thể thao, du lịch, xem phim, công nghệ và thiết kế. Mình thích thực hiện những thứ yêu thích và mới mẻ✨  
  </p>

  <div class="social">
    <a href="#">https://www.facebook.com/share/17oGvZN4PS/?mibextid=wwXIfr</a>
    <a href="#">dangthu_nguyenhuynh</a>
    <a href="#">dangthunguyenhuynh43@gmail.com</a>
  </div>
</div>

</body>
</html>
