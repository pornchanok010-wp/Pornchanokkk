<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #17131F;
            color: #E8E1F2;
            line-height: 1.8;
        }

        /* ส่วนหัว */
        header {
            background: #241D30;
            color: #C5A8F5;
            text-align: center;
            padding: 50px 20px;
            border-bottom: 2px solid #55416F;
        }

        header h1 {
            font-size: 36px;
        }

        /* เมนู */
        nav {
            background: #201929;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav a {
            color: #C5A8F5;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: white;
        }

        /* กล่องเนื้อหา */
        section {
            max-width: 900px;
            margin: 30px auto;
            padding: 30px;
            background: #241D30;
            border-radius: 12px;
            border: 1px solid #49385F;
        }

        h2 {
            color: #B99AEF;
            margin-bottom: 15px;
            border-bottom: 2px solid #55416F;
            padding-bottom: 8px;
        }

        /* รูปโปรไฟล์ */
        .profile {
            text-align: center;
        }

        .profile img {
            width: 170px;
            height: 170px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #8F70BD;
            margin-bottom: 15px;
        }

        .profile h3 {
            color: #C5A8F5;
            margin-top: 10px;
        }

        /* กล่องข้อมูล */
        .card {
            background: #30263F;
            padding: 15px;
            margin: 12px 0;
            border-radius: 10px;
            border-left: 4px solid #9B7ACB;
        }

        .card h3 {
            color: #C5A8F5;
        }

        /* ติดต่อ */
        a {
            color: #C5A8F5;
        }

        /* ท้ายเว็บไซต์ */
        footer {
            background: #241D30;
            color: #C5A8F5;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            border-top: 2px solid #55416F;
        }

        /* รองรับโทรศัพท์ */
        @media (max-width: 600px) {
            header h1 {
                font-size: 28px;
            }

            nav a {
                display: inline-block;
                margin: 5px;
                font-size: 13px;
            }

            section {
                margin: 15px;
                padding: 20px;
            }
        }
    </style>
</head>

<body>

    <nav>
        <a href="#about">เกี่ยวกับฉัน</a>
        <a href="#education">การศึกษา</a>
        <a href="#contact">ติดต่อ</a>
    </nav>

    <header>
        <h1>MY PORTFOLIO</h1>
        <p>Welcome to my Portfolio</p>
    </header>

    <section id="about" class="profile">
        <h2>ประวัติส่วนตัว</h2>

        <p>
            สวัสดีค่ะ ชื่อพรชนก ไกรนัย ชื่อเล่นโบว์
            มีความสนใจด้านเทคโนโลยี ชอบเรียนรู้สิ่งใหม่ ๆ
            และสนใจการออกแบบเว็บไซต์ค่ะ
        </p>

        <br>

        <img src="S__11730948.jpg" alt="รูปโปรไฟล์">

        <h3>ชื่อ - นามสกุล : นางสาว พรชนก ไกรนัย</h3>
        <p>ชื่อเล่น : โบว์</p>
        <p>วันเกิด : 25 มกราคม พ.ศ. 2553</p>
        <p>อายุ : 16 ปี</p>
        <p>งานอดิเรก : ฟังเพลง</p>
    </section>

    <section id="education">
        <h2>ประวัติการศึกษา</h2>

        <div class="card">
            <h3>ระดับมัธยมศึกษา</h3>
            <p>โรงเรียน : วัดพรหมสาคร</p>
        </div>

    </section>

    <section id="contact">
        <h2>ช่องทางการติดต่อ</h2>

        <p>
            Email :
            <a href="mailto:pornchanok08a@gmail.com">
                pornchanok08a@gmail.com
            </a>
        </p>

        <p>
            Instagram :
            <a href="https://instagram.com/p.ornchanok_00"
               target="_blank">
                instagram.com/p.ornchanok_00
            </a>
        </p>
    </section>

    <footer>
        <p>© 2026 My Portfolio</p>
        <p>Designed by Bow</p>
    </footer>

</body>
</html>
```
