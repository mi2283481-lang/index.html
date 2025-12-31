# index.html
for you
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Malam Tahun Baru</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: radial-gradient(circle at top, #1a1a2e, #000);
      color: #fff;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      overflow: hidden;
    }
    .container {
      padding: 25px;
      max-width: 360px;
      animation: fadeIn 2s ease;
    }
    h1 {
      font-size: 1.8em;
      margin-bottom: 15px;
    }
    p {
      font-size: 0.95em;
      line-height: 1.7;
      opacity: 0.9;
    }
    .hint {
      margin-top: 25px;
      font-size: 0.8em;
      opacity: 0.6;
    }
    .star {
      position: absolute;
      background: white;
      width: 2px;
      height: 2px;
      border-radius: 50%;
      animation: twinkle 3s infinite alternate;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes twinkle {
      from { opacity: 0.2; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>✨ Selamat Tahun Baru ✨</h1>
    <p>
      sayangggggggg,<br><br>
      tahun baru akhirnya datang juga. rasanya campur aduk—antara senang, haru, dan sedikit takut. tapi semua perasaan itu jadi jauh lebih tenang karena ada adek di sisi kakak. kakak bersyukur, karena di antara banyak hal yang berubah, adek masih di sini, masih memilih bertahan bersama kakak.<br><br>

      terima kasih sudah bertahan sejauh ini sama kakak, dengan segala cerita, cape, dan perasaan yang kadang nggak selalu mudah. kakak menjadi kakak, dan adek menjadi adek yang selalu sabar menghadapi kakak. meskipun kakak sering banget bikin adek kecewa, bikin adek sedih, bahkan bikin adek capek, tapi adek tetap bertahan dan memilih untuk mengerti. itu nggak pernah kakak anggap hal kecil.<br><br>

      adek adalah salah satu alasan kenapa tahun kemarin terasa berarti, meskipun nggak selalu sempurna. terima kasih sudah menjadi obat luka, terima kasih karena adek yang perlahan menyembuhkan kakak dari kisah masa lalu yang sempat membuat kakak takut untuk percaya lagi. kehadiran adek bikin kakak merasa lebih utuh, lebih tenang, dan lebih hidup.<br><br>

      di tahun yang baru ini, kakak nggak minta hal yang berlebihan. kakak cuma pengin kakak dan adek tetap saling genggam, saling jujur, dan saling pulang. semoga kakak dan adek bisa jadi lebih sabar, lebih dewasa, dan lebih mengerti satu sama lain. kalau nanti ada hari yang berat, semoga kakak dan adek selalu ingat alasan kenapa memilih bertahan, bukan alasan untuk menyerah.<br><br>

      selamat tahun baru, sayanggggg.<br>
      terima kasih sudah jadi rumah, tempat kakak merasa aman dan dicintai. semoga di tahun ini kakak dan adek masih bersama, masih saling memilih, dan masih jatuh cinta dengan orang yang sama—adek 🤍✨
    </p>
    <div class="hint">
      Dibuat dengan tulus, di malam pergantian tahun 🌙
    </div>
  </div>

  <script>
    for(let i = 0; i < 40; i++){
      const star = document.createElement('div');
      star.className = 'star';
      star.style.top = Math.random() * 100 + '%';
      star.style.left = Math.random() * 100 + '%';
      star.style.animationDuration = (Math.random() * 3 + 2) + 's';
      document.body.appendChild(star);
    }
  </script>

</body>
</html>
