# My-1st-demo-website
This is my 1st demo website which displays home page.

#languages used-
1.HTML
2.CSS

Source Code-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Zilla Parishad Style Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f4f6f9;
        }

        /*  HEADER  */
        header {
            background-color: #004a99;
            color: white;
            padding: 10px 20px;
        }

        .top-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        /*  NAVBAR */
        nav {
            background-color: #003366;
        }

        nav ul {
            display: flex;
            list-style: none;
            flex-wrap: wrap;
        }

        nav ul li {
            padding: 12px 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 14px;
        }

        nav ul li:hover {
            background-color: #005bb5;
        }

        /* BANNER  */
        .banner {
            background-color: #e6eef7;
            padding: 40px 20px;
            text-align: center;
        }

        .banner h1 {
            color: #003366;
            margin-bottom: 10px;
        }

        /*  MAIN CONTENT  */
        .container {
            display: flex;
            gap: 20px;
            padding: 20px;
        }

        .box {
            background: white;
            padding: 15px;
            border: 1px solid #ddd;
            flex: 1;
        }

        .box h2 {
            background-color: #004a99;
            color: white;
            padding: 8px;
            font-size: 16px;
            margin-bottom: 10px;
        }

        .box ul {
            list-style: none;
        }

        .box ul li {
            padding: 6px 0;
            border-bottom: 1px dashed #ccc;
            font-size: 14px;
        }

        /*  FOOTER  */
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
            font-size: 13px;
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            nav ul {
                flex-direction: column;
            }
        }
  </style>
</head>

<body>

<header>
    <div class="top-header">
        <div class="logo">Zilla Parishad Solapur</div>
        <div>Government of Maharashtra</div>
    </div>
</header>

<nav>
    <ul>
        <li><a href="#">मुख्यपृष्ठ</a></li>
        <li><a href="#">आमच्याबद्दल</a></li>
        <li><a href="#">विभाग</a></li>
        <li><a href="#">नागरिक सेवा</a></li>
        <li><a href="#">सूचना</a></li>
        <li><a href="#">फोटो गॅलरी</a></li>
        <li><a href="#">संपर्क</a></li>
    </ul>
</nav>

<section class="banner">
    <h1>Welcome to Zilla Parishad Portal</h1>
    <p>Official Information Platform for Citizens</p>
</section>

<section class="container">
    <div class="box">
        <h2>Latest Announcements</h2>
        <ul>
            <li>Recruitment Notice 2025</li>
            <li>New Government Scheme</li>
            <li>Tender Information</li>
            <li>Public Holiday Notice</li>
        </ul>
    </div>

  <div class="box">
        <h2>Important Links</h2>
        <ul>
            <li>RTI Information</li>
            <li>Online Services</li>
            <li>Grievance Portal</li>
            <li>Citizen Charter</li>
        </ul>
    </div>
</section>

<footer>
    © 2025 Zilla Parishad | Designed for Academic Purpose
</footer>

</body>
</html>
