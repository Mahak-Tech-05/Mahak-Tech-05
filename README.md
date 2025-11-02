<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MahakTech - Innovating the Future</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

<style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}
    body{background:#0a0f24;color:#fff;}

    /* Hero Section */
    header{
        height:100vh;
        display:flex;
        justify-content:center;
        align-items:center;
        flex-direction:column;
        text-align:center;
        padding:20px;
        background:linear-gradient(135deg,#0f172a,#1e293b,#334155);
        animation:bgMove 8s infinite alternate;
    }
    @keyframes bgMove{0%{background-position:left}100%{background-position:right}}

    h1{font-size:3.2rem;font-weight:700;}
    h2{font-size:1.4rem;font-weight:300;opacity:.9;margin:10px 0 20px;}

    .btn{
        padding:12px 30px;
        background:#1e90ff;
        border:none;
        border-radius:40px;
        font-size:1rem;
        cursor:pointer;
        transition:.3s;
        font-weight:600;
    }
    .btn:hover{background:#005eb8;transform:scale(1.05);}

    /* Sections */
    section{padding:70px 12%;}
    h3{text-align:center;font-size:2.2rem;margin-bottom:35px;}

    /* Services */
    .services{
        display:grid;
        grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
        gap:25px;
    }
    .box{
        background:#111a33;
        padding:25px;
        border-radius:18px;
        text-align:center;
        transition:.4s;
        border:1px solid transparent;
    }
    .box:hover{
        transform:translateY(-8px);
        border-color:#1e90ff;
        box-shadow:0 0 25px rgba(30,144,255,0.3);
    }
    .box i{font-size:2.2rem;margin-bottom:10px;color:#1e90ff;}

    /* Contact */
    .contact{
        text-align:center;
        margin-top:30px;
    }
    .contact a{
        display:inline-block;
        background:#1e90ff;
        padding:12px 18px;
        margin:0 10px;
        border-radius:50%;
        color:#fff;
        font-size:1.3rem;
        transition:.3s;
    }
    .contact a:hover{background:#005eb8;transform:scale(1.15);}

    footer{
        text-align:center;
        padding:25px;
        background:#08101c;
        font-size:.9rem;
        margin-top:40px;
    }
</style>
</head>

<body>

<!-- Hero -->
<header>
    <h1>MahakTech</h1>
    <h2>Innovating with Respect for Tradition</h2>
    <button class="btn" onclick="document.querySelector('#services').scrollIntoView({behavior:'smooth'});">
        Discover Our Work
    </button>
</header>

<!-- Services -->
<section id="services">
    <h3>Our Services</h3>
    <div class="services">
        <div class="box">
            <i class="fa-solid fa-globe"></i>
            <h4>Web Development</h4>
            <p>High-quality websites built with care and future-ready standards.</p>
        </div>
        <div class="box">
            <i class="fa-solid fa-mobile-screen"></i>
            <h4>App Development</h4>
            <p>Android and iOS apps designed for performance and simplicity.</p>
        </div>
        <div class="box">
            <i class="fa-solid fa-microchip"></i>
            <h4>AI & Automation</h4>
            <p>Solutions that make life easier without losing the human touch.</p>
        </div>
        <div class="box">
            <i class="fa-solid fa-headset"></i>
            <h4>Tech Support</h4>
            <p>Reliable help whenever you need it — because trust matters.</p>
        </div>
    </div>
</section>

<!-- Contact -->
<section>
    <h3>Contact Us</h3>
    <div class="contact">
        <a href="mailto:saxenamahak612@gmail.com"><i class="fa-solid fa-envelope"></i></a>
        <a href="https://github.com/Mahak-0101" target="_blank"><i class="fa-brands fa-github"></i></a>
        <a href="https://www.linkedin.com" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
    </div>
</section>

<footer>
    © 2025 MahakTech | Tradition + Innovation
</footer>

</body>
</html>
