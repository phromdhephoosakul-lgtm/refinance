<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>รีไฟแนนซ์บ้าน - Refinace Homeloan</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@400;600;700&display=swap" rel="stylesheet">
  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    :root {
      --primary-red: #E30613;
      --dark-red: #A3040D;
      --light-red: #FFEBEC;
      --text-dark: #2D2D2D;
      --white: #FFFFFF;
      --blue: #0070C0;      
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Kanit', sans-serif;
    }

    body {
      background-color: var(--gray);
      color: var(--text-dark);
      line-height: 1.6;
    }

    /* Header */
    header {
      background: linear-gradient(135deg, var(--primary-red), var(--dark-red));
      color: var(--white);
      padding: 30px 20px;
      text-align: left;
      border-bottom-left-radius: 40px;
      border-bottom-right-radius: 40px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.15);
    }

    header h1 {
      font-size: 2rem;
      margin-bottom: 5px;
      font-weight: 700;
      letter-spacing: 1px;
    }

    header h2 {
      font-size: 1.5rem;
      opacity: 0.9;
    }

    header p {
      font-size: 1rem;
      opacity: 0.9;
    }

    /* Container */
    .container {
      padding: 20px;
      max-width: 600px;
      margin: auto;
    }

    .section-title {
      color: var(--primary-red);
      font-size: 1.3rem;
      font-weight: 600;
      margin: 30px 0 20px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .section-title i {
      color: var(--dark-red);
    }

    /* Card */
    .card {
      background: var(--white);
      border-radius: 20px;
      padding: 20px;
      margin-bottom: 25px;
      border: 1px solid #eee;
      box-shadow: 0 6px 15px rgba(0,0,0,0.08);
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.12);
    }

    .card-header {
      font-weight: bold;
      font-size: 1.2rem;
      color: var(--primary-red);
      margin-bottom: 10px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .benefit-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
      margin-top: 15px;
    }

    .benefit-item {
      background: var(--light-red);
      padding: 12px;
      border-radius: 12px;
      text-align: center;
    }

    .benefit-item2 {
      background: var(--light-red);
      padding: 12px;
      border-radius: 12px;
      text-align: left;
    }

    .benefit-label {
      font-size: 0.8rem;
      color: #666;
    }

    .benefit-value {
      font-size: 1rem;
      font-weight: bold;
      color: var(--dark-red);
    }

    .card a {
      display: inline-block;
      margin-top: 15px;
      font-size: 0.85rem;
      color: var(--blue);
      text-decoration: none;
      font-weight: 600;
    }

    .card a:hover {
      text-decoration: underline;
    }

    /* Badge */
    .badge {
      background: var(--primary-red);
      color: var(--white);
      padding: 3px 10px;
      border-radius: 12px;
      font-size: 0.7rem;
    }

    /* CTA Button */
    .cta-btn {
      background: var(--primary-red);
      color: var(--white);
      text-align: center;
      padding: 15px;
      border-radius: 50px;
      display: block;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.2rem;
      margin: 30px auto;
      max-width: 300px;
      box-shadow: 0 6px 20px rgba(227, 6, 19, 0.3);
      transition: background 0.3s ease, transform 0.2s ease;
    }

    .cta-btn:hover {
      background: var(--dark-red);
      transform: scale(1.05);
    }

    /* Disclaimer */
    .disclaimer {
      font-size: 0.8rem;
      color: #555;
      padding: 20px;
      background: #fafafa;
      border-left: 4px solid var(--primary-red);
      margin-top: 30px;
      border-radius: 10px;
    }

    /* Footer / Note */
    .footer{
      font-size: 0.75rem;
      color: #777;
      padding: 20px;
      background: #eee;
      margin-top: 20px;
    }
    
    .footer1{
      font-size: 0.75rem;
      color: #777;
      padding: 10px;
      background: #eee;
      margin-top: 10px;
    }

    .footer2{
      font-size: 0.75rem;
      color: #777;
      padding: 20px;
      background: #eee;
      margin-top: -10px;
    }
    
  </style>
</head>
<body>

<header>
  <h2>สินเชื่อรีไฟแนนซ์บ้าน</h2>
  <h1>REFINANCE HOMELOAN</h1>
  <p>ช่วยลดดอกเบี้ยที่จ่ายกับที่เดิมให้น้อยลง ลดเงินต้นได้มากขึ้น เพื่อเป็นเจ้าของบ้านได้เร็วขึ้น </p>
</header>

<div class="container">

  <div class="section-title">
    <i class="fas fa-star"></i> เลือกโปรโมชั่นที่ใช่สำหรับคุณ
  </div>

  <!-- Option 1 -->
  <div class="card">
    <div class="card-header">รีไฟแนนซ์ตามยอดหนี้ที่เหลือ<br>ไม่ขอวงเงินเพิ่ม <span class="badge">ยอดฮิต</span></div>
    <p style="font-size: 0.9rem; ">
      <ul style="margin-left: 40px;">
      <li>พนักงานประจำ รายได้ > 20,000 บาท</li>
      <li>เจ้าของกิจการ รายได้ > 30,000 บาท</li>
      <li>มียอดจำนองกับธนาคารเดิม > 2 ล้านบาท<br>และมีเงินต้นเหลือ > 1 ล้านบาท</li>
      </ul>
    </p>
    <div class="benefit-grid">
      <div class="benefit-item">
        <div class="benefit-label">อัตราดอกเบี้ยเริ่มต้น</div>
        <div class="benefit-value">1.59% - 3.19% ต่อปี</div>
      </div>
      <div class="benefit-item">
        <div class="benefit-label">วงเงินกู้ตามยอดเงินต้น<br>ล่าสุด</div>
        <div class="benefit-value">85% - 110%<br>ของราคาประเมิน</div>
      </div>
    </div>
    <a href="https://www.cimbthai.com/content/dam/cimbth/personal/documents/loan/refinance/2026/%E0%B8%94%E0%B8%AD%E0%B8%81%E0%B9%80%E0%B8%9A%E0%B8%B5%E0%B9%89%E0%B8%A2%20Generic%20-%20%E0%B8%A3%E0%B8%B5%E0%B9%84%E0%B8%9F%E0%B9%81%E0%B8%99%E0%B8%99%E0%B8%8B%E0%B9%8C2-Th_261268.pdf" target="_blank" rel="noopener noreferrer">ดูรายละเอียดเพิ่มเติม ></a>
  </div>

  <!-- Option 2 -->
  <div class="card">
    <div class="card-header">รีไฟแนนซ์และขอวงเงินเพิ่ม</div>
    <p style="font-size: 0.9rem; ">
      <ul style="margin-left: 40px;">
      <li>พนักงานประจำ รายได้ > 15,000 บาท</li>
      <li>เจ้าของกิจการ รายได้ > 30,000 บาท</li>
      </ul>
    </p>
    <div class="benefit-grid">
      <div class="benefit-item2">
        <div class="benefit-label">รีไฟแนนซ์ : ดอกเบี้ยเริ่มต้น</div>
        <div class="benefit-value">3.09% - 3.53% ต่อปี</div>
        <div class="benefit-label">ส่วนกู้เพิ่ม : ดอกเบี้ยเริ่มต้น</div>
        <div class="benefit-value">5.39% - 5.59% ต่อปี</div>
      </div>
      <div class="benefit-item">
        <div class="benefit-label">วงเงินกู้สูงสุด</div>
        <div class="benefit-value">70% - 95%<br>ของราคาประเมิน</div>
      </div>
    </div>
    <a href="https://www.cimbthai.com/content/dam/cimbth/personal/documents/loan/refinance/2026/%E0%B8%94%E0%B8%AD%E0%B8%81%E0%B9%80%E0%B8%9A%E0%B8%B5%E0%B9%89%E0%B8%A2%20Generic%20-%20%E0%B8%A3%E0%B8%B5%E0%B9%84%E0%B8%9F%E0%B9%81%E0%B8%99%E0%B8%99%E0%B8%8B%E0%B9%8C1-Th_261268.pdf" target="_blank" rel="noopener noreferrer">ดูรายละเอียดเพิ่มเติม ></a>
  </div>

    <a href="https://drive.google.com/file/d/1ZUAgyIfJB2y1T07PHI-OZi9kkqktwBlH/view?usp=sharing" target="_blank" rel="noopener noreferrer" class="cta-btn">เอกสารประกอบการสมัคร</a>
</div>

<div class="footer1">
    <strong>หมายเหตุ :</strong>
<div class="footer2">
    <li>วงเงินกู้ขึ้นอยู่กับประเภทของหลักประกัน อาชีพ รายได้ ความต้องการของลูกค้า และหลักเกณฑ์ของธนาคาร</li>
    <li>การพิจารณาอนุมัติสินเชื่อเป็นไปตามหลักเกณฑ์และเงื่อนไขของธนาคาร ทั้งนี้ ธนาคารขอสงวนสิทธิ์ในการเปลี่ยนแปลงอัตราดอกเบี้ยรวมทั้งหลักเกณฑ์และเงื่อนไข โปรดตรวจสอบโปรโมชั่นส่งเสริมการขายกับเจ้าหน้าที่ก่อนการตัดสินใจ</li>
</div>
</div>

</body>
</html>
