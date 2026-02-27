# digital-safety-site
<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>คู่มือรู้ทันภัยออนไลน์</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
  <h1>คู่มือรู้ทันภัยออนไลน์</h1>
  <p>Digital Safety Guide for Everyone</p>
  <nav>
    <a href="#home">Home</a>
    <a href="#scam">Scam Guide</a>
    <a href="#tips">Protection Tips</a>
    <a href="#quiz">Self Check</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home">
  <h2>ภัยออนไลน์คืออะไร</h2>
  <p>
    ภัยออนไลน์คือการหลอกลวงผ่านอินเทอร์เน็ต เช่น หลอกโอนเงิน ฟิชชิง 
    หรือการปลอมตัวเป็นเจ้าหน้าที่รัฐ ซึ่งสร้างความเสียหายจำนวนมากในปัจจุบัน
  </p>
</section>

<section id="scam">
  <h2>ประเภทสแกมที่พบบ่อย</h2>
  <ul>
    <li>หลอกโอนเงิน (Fake call center)</li>
    <li>หลอกลงทุนผลตอบแทนสูง</li>
    <li>ฟิชชิงขโมยรหัสผ่าน</li>
    <li>ร้านค้าออนไลน์ปลอม</li>
  </ul>
</section>

<section id="tips">
  <h2>วิธีป้องกันภัยออนไลน์</h2>
  <ul>
    <li>อย่าให้ข้อมูลส่วนตัวกับคนแปลกหน้า</li>
    <li>ตรวจสอบ URL ก่อนกรอกข้อมูล</li>
    <li>ตั้งรหัสผ่านที่คาดเดายาก</li>
    <li>เปิดการยืนยันตัวตน 2 ชั้น</li>
  </ul>
</section>

<section id="quiz">
  <h2>แบบประเมินความเสี่ยง</h2>
  <p>คุณเคยกดลิงก์จากข้อความแปลกหรือไม่?</p>
  <button onclick="showAlert()">เคย</button>
  <button onclick="showAlert()">ไม่เคย</button>
</section>

<section id="contact">
  <h2>ช่องทางขอความช่วยเหลือ</h2>
  <p>สายด่วนอาชญากรรมออนไลน์: 1441</p>
  <p>แจ้งความออนไลน์: www.thaipoliceonline.go.th</p>
</section>

<footer>
  <p>© 2026 Digital Safety Guide | เว็บไซต์เพื่อสาธารณประโยชน์</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  line-height: 1.6;
  background: #f4f6f8;
}

header {
  background: #1565c0;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 12px;
  text-decoration: none;
  font-weight: bold;
}

section {
  background: white;
  margin: 20px;
  padding: 20px;
  border-radius: 8px;
}

button {
  padding: 10px 20px;
  margin: 10px;
  border: none;
  background: #1565c0;
  color: white;
  border-radius: 6px;
  cursor: pointer;
}

footer {
  background: #263238;
  color: white;
  text-align: center;
  padding: 12px;
}
function showAlert() {
  alert("ขอบคุณสำหรับการประเมินความเสี่ยงออนไลน์");
}
