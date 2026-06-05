<h1 align="center">Hi <picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4aa/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4aa/512.gif" alt="💪" width="32" height="32">
</picture>, I'm Porpa</h1>
<h3 align="center">A passionate frontend developer from Thailand</h3>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 60" width="100%" height="60">
  <style>
    .text-typing {
      font-family: 'Courier New', Courier, monospace; /* ใช้ฟอนต์สไตล์พิมพ์ดีด */
      font-weight: bold;
      font-size: 24px;
      fill: #ef454a; /* สีแดงแบบโค้ดดั้งเดิมของคุณ */
    }

    .cursor {
      fill: #ff9123; /* เส้นเคอร์เซอร์สีส้มวิบวับ */
      animation: blink 0.8s infinite;
    }

    .letter {
      opacity: 0;
      animation: type 0.1s forwards;
    }

    /* ไล่เวลา (Delay) ให้ตัวอักษรพิมพ์เรียงตัวกันออกมา */
    .l1  { animation-delay: 0.2s; }
    .l2  { animation-delay: 0.4s; }
    .l3  { animation-delay: 0.6s; }
    .l4  { animation-delay: 0.8s; }
    .l5  { animation-delay: 1.0s; }
    .l6  { animation-delay: 1.2s; }
    .l7  { animation-delay: 1.4s; }
    .l8  { animation-delay: 1.6s; }
    .l9  { animation-delay: 1.8s; }
    .l10 { animation-delay: 2.0s; }
    .l11 { animation-delay: 2.2s; }
    .l12 { animation-delay: 2.4s; }
    .l13 { animation-delay: 2.6s; }
    .l14 { animation-delay: 2.8s; }
    .l15 { animation-delay: 3.0s; }

    /* ขยับเส้นเคอร์เซอร์ตามตัวอักษรที่พิมพ์ออกมา */
    @keyframes type {
      to { opacity: 1; }
    }

    @keyframes blink {
      50% { opacity: 0; }
    }

    @keyframes move-cursor {
      /* ย้ายตำแหน่งตัวเคอร์เซอร์ไปข้างหลังตามจังหวะพิมพ์ */
      0%, 4% { transform: translateX(0px); }
      5% { transform: translateX(15px); }
      10% { transform: translateX(30px); }
      15% { transform: translateX(45px); }
      20% { transform: translateX(60px); }
      25% { transform: translateX(75px); }
      30% { transform: translateX(90px); }
      35% { transform: translateX(105px); }
      40% { transform: translateX(120px); }
      45% { transform: translateX(135px); }
      50% { transform: translateX(150px); }
      55% { transform: translateX(165px); }
      60% { transform: translateX(180px); }
      65% { transform: translateX(195px); }
      70% { transform: translateX(210px); }
      75%, 100% { transform: translateX(225px); }
    }

    .cursor-move {
      animation: move-cursor 3.5s steps(1) infinite;
    }
    
    /* ให้ข้อความทั้งหมดหายไปเพื่อเริ่มพิมพ์ใหม่รอบถัดไป */
    .loop-wrap {
      animation: reset-loop 4.5s infinite;
    }
    @keyframes reset-loop {
      0%, 85% { opacity: 1; }
      90%, 100% { opacity: 0; }
    }
  </style>

  <g class="loop-wrap">
    <text x="10" y="35" class="text-typing">
      <tspan class="letter l1">H</tspan>
      <tspan class="letter l2">E</tspan>
      <tspan class="letter l3">L</tspan>
      <tspan class="letter l4">L</tspan>
      <tspan class="letter l5">O</tspan>
      <tspan class="letter l6">,</tspan>
      <tspan class="letter l7"> </tspan> <tspan class="letter l8">W</tspan>
      <tspan class="letter l9">O</tspan>
      <tspan class="letter l10">R</tspan>
      <tspan class="letter l11">L</tspan>
      <tspan class="letter l12">D</tspan>
      <tspan class="letter l13">!</tspan>
      <tspan class="letter l14">!</tspan>
      <tspan class="letter l15">!</tspan>
    </text>

    <g class="cursor-move">
      <rect x="25" y="15" width="12" height="24" class="cursor" />
    </g>
  </g>
</svg>

