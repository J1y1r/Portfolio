[Sumcio.html](https://github.com/user-attachments/files/26463103/Sumcio.html)
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Jayar Sumcio Resume</title>

    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom, #3674B5, #493D9E);
            background-attachment: fixed;
            background-size: cover;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 20px;
            background-color: #F2EFE7;
            border-radius: 15px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        .header {
            background-color: #C4D9FF;
            color: #09122C;
            padding: 20px;
            text-align: center;
            border-top-left-radius: 15px;
            border-top-right-radius: 15px;
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #ffffff;
            margin-bottom: 15px;
            transition: transform 0.3s ease;
        }
        .profile-pic:hover {
            transform: scale(1.1);
        }
        h1 {
            font-size: 30px;
            margin: 10px 0 5px;
        }
        p.tagline {
            font-size: 16px;
            margin: 0;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
        }
        .card {
            flex: 1;
            min-width: 300px;
            background-color: #FFDAB3;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .card h2 {
            font-size: 22px;
            color: #4B164C;
            margin-bottom: 15px;
        }
        .card p, .card ul {
            font-size: 16px;
            color: #493D9E;
            line-height: 1.6;
        }
        .card ul {
            list-style: none;
            padding: 0;
        }
        .card ul li {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }
        .card ul li::before {
            content: "⭑";
            color: #780C28;
            font-size: 18px;
            margin-right: 10px;
        }
        a {
            color: #780C28;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .divider {
            width: 100%;
            height: 3px;
            background: linear-gradient(to right, #ffb6c1, #ff9f9f);
            margin: 30px 0;
            border-radius: 5px;
        }

        /* Floating Widgets */
        .contact-btn, .phone-btn, .email-btn {
            position: fixed;
            right: 20px;
            bottom: 20px;
            background-color: #ffb6c1;
            color: white;
            padding: 15px 20px;
            border-radius: 50%;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .contact-btn:hover, .phone-btn:hover, .email-btn:hover {
            background-color: #ff6f91;
        }

        .phone-btn {
            right: 80px; 
            bottom: 20px;
        }

        /* Hover Animation */
        .phone-btn:hover {
            transform: scale(1.1);
        }
        .email-btn:hover {
            transform: scale(1.1);
        }

        /* Skill Progress Bar */
        .progress-bar {
            width: 100%;
            background-color: #fce4ec;
            border-radius: 20px;
            margin-top: 20px;
        }
        .progress-bar div {
            height: 20px;
            border-radius: 20px;
            text-align: center;
            color: rgb(1, 18, 0);
            padding: 5px;
        }
        .communication {
            width: 90%;
            background-color: #ffb6c1;
        }
        .time-management {
            width: 85%;
            background-color: #d1c4e9;
        }
        .leadership {
            width: 80%;
            background-color: #ffc1e3;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://yt3.googleusercontent.com/ytc/AGIKgqPpkXZFDOLcQTlqL4HsUTwZ1tbH3wkp1AzeiBhQ=s900-c-k-c0x00ffffff-no-rj" alt="Mark Reynold Valeriano" class="profile-pic">
	  <h1>Jayar Sumcio</h1>

            
        </div>

        <!-- Content Section -->
        <div class="content">
            <!-- Personal Information -->
            <div class="box">
                <h2>Personal Information</h2>
                <p><span class="icon">📞</span><strong>Phone:</strong> 09208538461</p>
                <p><span class="icon">📧</span><strong>Email:</strong> <a href="mailto:babsiandfriends@gmail.com">babsiandfriends@gmail.com</a></p>
                <p><span class="icon">🌐</span><strong>Facebook:</strong> <a href="https://www.facebook.com/jayarsumcio31" target="_blank">Jayar Sumcio</a></p>
                
            </div>

            <div class="card">
                <h2>Education</h2>
                <ul>
                    <li><strong>Primary:</strong> Likha Molino Elem</li>
                    <li><strong>Secondary:</strong> BNHS</li>
                    <li><strong>Senior High School:</strong>University of Perpetual Help Molino</li>
                    <li><strong>Tertiary:</strong>University of Perpetual Help Molino (2022 - Present)</li>
                </ul>
            </div>

            <div class="card">
                <h2>Hobbies</h2>
                <ul>
                    <li>Basketball</li>
                    <li>Cooking</li>
		<li>Play Online Game</li>
                </ul>
            </div>
        </div>
		 </div>
    </div>

    <!-- Floating Widgets -->
    <div class="phone-btn">
        <a href="tel:09208538461" style="color: rgb(44, 208, 240);">📞</a>
    </div>
    <div class="email-btn">
        <a href="omarkreynold@gmail.com" style="color: rgb(156, 34, 231);">✉</a>
    </div>
    <div class="contact-btn">
        <a href="omarkreynold@gmail.com" style="color: rgb(240, 21, 83);">✉</a>
    </div>
</body>
</video>       
</html>
<video controls="controls" autoplay="autoplay" width="600" heigth="400" loop>
	<source src="nba highlights" type="video/mp4" />
	</video>


