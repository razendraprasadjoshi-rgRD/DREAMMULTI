# DREAMMULTI
dream-multipurpose-website │ ├── index.html ├── css/ │   └── style.css ├── images/ │   ├── hero.jpg │   ├── construction1.jpg │   ├── construction2.jpg │ └── README.md
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Dream Multipurpose and Suppliers Pvt. Ltd.</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header class="hero">
    <h1>Dream Multipurpose and Suppliers Pvt. Ltd.</h1>
    <p>Reliable Construction Contractor in Nepal Since 2077 B.S.</p>
    <a href="#contact" class="btn">Contact Us</a>
</header>

<section>
    <h2>About Us</h2>
    <p>
        Dream Multipurpose and Suppliers Pvt. Ltd. is a professional construction
        contractor based in Kathmandu, Nepal. Established in 2077 B.S., we deliver
        quality, safe, and timely construction services.
    </p>
</section>

<section>
    <h2>Our Services</h2>
    <ul>
        <li>Building Construction</li>
        <li>Road & Infrastructure Works</li>
        <li>Renovation & Maintenance</li>
        <li>Supply of Construction Materials</li>
        <li>Government & Private Projects</li>
    </ul>
</section>

<section>
    <h2>Projects</h2>
    <img src="images/construction1.jpg" alt="Construction Project">
    <img src="images/construction2.jpg" alt="Construction Project">
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>📍 Devkota Sadak, Kathmandu</p>
    <p>📞 9847965689</p>
    <p>📧 multipurposedream@gmail.com</p>
</section>

<footer>
    <p>© 2025 Dream Multipurpose and Suppliers Pvt. Ltd.</p>
</footer>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    line-height: 1.6;
}

.hero {
    background: url("../images/hero.jpg") center/cover no-repeat;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.btn {
    background: #0056b3;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
}

section {
    padding: 40px 20px;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 10px;
}
