# PhotoGrow

<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PhotoGrow - Belajar Fotosintesis</title>

<style>
* {
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5fff5;
  color: #214b32;
}

header {
  background: #174d35;
  color: white;
  padding: 20px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

.logo {
  font-size: 27px;
  font-weight: bold;
}

.logo span {
  color: #b8e986;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 8px;
}

.hero {
  padding: 75px 8%;
  background: linear-gradient(135deg, #e6f8d8, #c7efce);
  text-align: center;
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  max-width: 650px;
  margin: 15px auto;
}

button {
  background: #28764c;
  color: white;
  border: none;
  border-radius: 9px;
  padding: 12px 18px;
  cursor: pointer;
  font-size: 15px;
}

button:hover {
  background: #174d35;
}

section {
  padding: 55px 8%;
}

h2 {
  font-size: 32px;
  color: #174d35;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: white;
  padding: 24px;
  border-radius: 15px;
  box-shadow: 0 4px 15px #00000010;
}

.icon {
  font-size: 40px;
}

.formula {
  background: #174d35;
  color: white;
  text-align: center;
  padding: 25px;
  border-radius: 15px;
  margin-top: 25px;
  font-size: 22px;
}

.process {
  background: #e9f7e8;
}

.lab {
  background: #174d35;
  color: white;
}

.lab h2 {
  color: #c7ef9e;
}

.lab-box {
  background: #ffffff12;
  border: 1px solid #ffffff30;
  border-radius: 18px;
  padding: 25px;
}

input[type="range"] {
  width: 100%;
  accent-color: #b8e986;
  margin: 12px 0;
}

.control {
  margin: 22px 0;
}

.control label {
  display: flex;
  justify-content: space-between;
  font-weight: bold;
}

.plant {
  font-size: 100px;
  text-align: center;
  margin: 15px;
  transition: transform 0.3s;
}

.plant.grow {
  transform: scale(1.15);
}

.result {
  text-align: center;
  font-size: 22px;
  font-weight: bold;
  color: #c7ef9e;
}

.progress {
  height: 14px;
  background: #ffffff35;
  border-radius: 20px;
  overflow: hidden;
  margin: 15px 0;
}

.progress-bar {
  height: 100%;
  width: 70%;
  background: #b8e986;
  transition: width 0.3s;
}

.quiz-box {
  background: white;
  padding: 25px;
  border-radius: 15px;
  max-width: 650px;
}

.answers {
  display: grid;
  gap: 10px;
}

.answers button {
  text-align: left;
  background: #edf7eb;
  color: #214b32;
  border: 1px solid #cfe4cb;
}

.answers button:hover {
  background: #d9f0d4;
}

#feedback {
  font-weight: bold;
  margin: 15px 0;
}

footer {
  background: #123d2b;
  color: white;
  text-align: center;
  padding: 25px;
}

@media (max-width: 600px) {
  header {
    gap: 15px;
  }

  .hero h1 {
    font-size: 36px;
  }

  nav a {
    display: inline-block;
    margin: 5px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">🌱 Photo<span>Grow</span></div>
  <nav>
    <a href="#materi">Materi</a>
    <a href="#proses">Proses</a>
    <a href="#simulasi">Simulasi</a>
    <a href="#kuis">Kuis</a>
  </nav>
</header>

<div class="hero">
  <h1>Discover the Power of Photosynthesis!</h1>
  <p>
    Pelajari bagaimana tumbuhan menggunakan cahaya matahari,
    air, dan karbon dioksida untuk menghasilkan makanan dan oksigen.
  </p>
  <a href="#simulasi">
    <button>Mulai Eksperimen 🌿</button>
  </a>
</div>

<section id="materi">
  <h2>🌿 Apa Itu Fotosintesis?</h2>
  <p>
    Fotosintesis adalah proses tumbuhan hijau membuat makanannya
    sendiri dengan bantuan energi cahaya matahari. Proses ini
    terutama berlangsung di kloroplas yang mengandung klorofil.
  </p>

  <div class="cards">
    <div class="card">
      <div class="icon">☀️</div>
      <h3>Cahaya Matahari</h3>
      <p>Sumber energi untuk menjalankan proses fotosintesis.</p>
    </div>

    <div class="card">
      <div class="icon">💧</div>
      <h3>Air</h3>
      <p>Diserap oleh akar dan digunakan sebagai bahan fotosintesis.</p>
    </div>

    <div class="card">
      <div class="icon">🌬️</div>
      <h3>Karbon Dioksida</h3>
      <p>Gas dari udara yang digunakan tumbuhan untuk membentuk gula.</p>
    </div>

    <div class="card">
      <div class="icon">🍃</div>
      <h3>Klorofil</h3>
      <p>Pigmen hijau yang menyerap energi cahaya matahari.</p>
    </div>
  </div>

  <div class="formula">
    <h3>Rumus Fotosintesis</h3>
    6CO₂ + 6H₂O + cahaya → C₆H₁₂O₆ + 6O₂
    <p>Karbon dioksida + Air → Glukosa + Oksigen</p>
  </div>
</section>

<section class="process" id="proses">
  <h2>🔬 Bagaimana Fotosintesis Terjadi?</h2>

  <div class="cards">
    <div class="card">
      <h3>1. Menangkap Cahaya</h3>
      <p>Klorofil menyerap energi dari matahari.</p>
    </div>

    <div class="card">
      <h3>2. Menyerap Air</h3>
      <p>Akar mengambil air dari tanah dan mengalirkannya ke daun.</p>
    </div>

    <div class="card">
      <h3>3. Mengambil CO₂</h3>
      <p>Karbon dioksida masuk ke daun terutama melalui stomata.</p>
    </div>

    <div class="card">
      <h3>4. Menghasilkan Gula</h3>
      <p>Tumbuhan menghasilkan glukosa dan melepaskan oksigen.</p>
    </div>
  </div>
</section>

<section class="lab" id="simulasi">
  <h2>🧪 Interactive Photosynthesis Lab</h2>
  <p>
    Atur kondisi di bawah ini dan amati perubahan laju
    fotosintesis tanaman virtual!
  </p>

  <div class="lab-box">
    <div class="control">
      <label>
        ☀️ Cahaya Matahari
        <span id="lightValue">70%</span>
      </label>
      <input type="range" id="light" min="0" max="100" value="70">
    </div>

    <div class="control">
      <label>
        💧 Ketersediaan Air
        <span id="waterValue">70%</span>
      </label>
      <input type="range" id="water" min="0" max="100" value="70">
    </div>

    <div class="control">
      <label>
        🌬️ Karbon Dioksida
        <span id="co2Value">70%</span>
      </label>
      <input type="range" id="co2" min="0" max="100" value="70">
    </div>

    <div class="plant" id="plant">🌿</div>

    <div class="result">
      <span id="rate">70</span>/100
      <p style="font-size:15px">Indeks fotosintesis simulasi</p>
    </div>

    <div class="progress">
      <div class="progress-bar" id="progressBar"></div>
    </div>

    <p id="status" style="text-align:center">
      Kondisi cukup baik untuk fotosintesis!
    </p>

    <button onclick="resetLab()">↻ Reset Eksperimen</button>
  </div>

  <p>
    Catatan: Simulasi ini menggunakan model edukasi sederhana,
    bukan pengukuran biologis nyata.
  </p>
</section>

<section id="kuis">
  <h2>🎯 Kuis Fotosintesis</h2>
  <p>Uji pemahamanmu dengan menjawab pertanyaan berikut!</p>

  <div class="quiz-box">
    <h3 id="question">Apa sumber energi utama fotosintesis?</h3>

    <div class="answers" id="answers"></div>

    <p id="feedback"></p>

    <button onclick="nextQuestion()" id="next">
      Pertanyaan Berikutnya →
    </button>
  </div>
</section>

<footer>
  <h3>🌱 PhotoGrow</h3>
  <p>Learn, Explore, and Grow with Science.</p>
  <p>Website edukasi tentang fotosintesis tumbuhan.</p>
</footer>

<script>
// SIMULASI FOTOSINTESIS

const light = document.getElementById("light");
const water = document.getElementById("water");
const co2 = document.getElementById("co2");

function updateLab() {
  const values = [
    Number(light.value),
    Number(water.value),
    Number(co2.value)
  ];

  document.getElementById("lightValue").textContent =
    values[0] + "%";

  document.getElementById("waterValue").textContent =
    values[1] + "%";

  document.getElementById("co2Value").textContent =
    values[2] + "%";

  // Model sederhana: faktor terendah membatasi proses.
  const rate = Math.round(
    Math.min(...values) * 0.7 +
    (values.reduce((a, b) => a + b, 0) / 3) * 0.3
  );

  document.getElementById("rate").textContent = rate;

  document.getElementById("progressBar").style.width =
    rate + "%";

  const plant = document.getElementById("plant");

  if (rate < 25) {
    plant.textContent = "🥀";
  } else if (rate < 55) {
    plant.textContent = "🌱";
  } else if (rate < 80) {
    plant.textContent = "🌿";
  } else {
    plant.textContent = "🪴";
  }

  plant.classList.toggle("grow", rate >= 75);

  const status = document.getElementById("status");

  if (rate < 25) {
    status.textContent =
      "Salah satu faktor sangat terbatas. Fotosintesis tidak optimal.";
  } else if (rate < 55) {
    status.textContent =
      "Fotosintesis berlangsung, tetapi ada faktor pembatas.";
  } else if (rate < 80) {
    status.textContent =
      "Kondisi cukup baik. Coba tingkatkan faktor terendah!";
  } else {
    status.textContent =
      "Kondisi sangat mendukung dalam model simulasi ini!";
  }
}

light.addEventListener("input", updateLab);
water.addEventListener("input", updateLab);
co2.addEventListener("input", updateLab);

function resetLab() {
  light.value = 70;
  water.value = 70;
  co2.value = 70;
  updateLab();
}

updateLab();

// KUIS INTERAKTIF

const questions = [
  {
    question: "Apa sumber energi utama fotosintesis?",
    answers: [
      "Air dari tanah",
      "Cahaya matahari",
      "Oksigen dari udara"
    ],
    correct: 1
  },
  {
    question: "Gas apa yang digunakan tumbuhan untuk fotosintesis?",
    answers: [
      "Oksigen",
      "Helium",
      "Karbon dioksida"
    ],
    correct: 2
  },
  {
    question: "Apa salah satu hasil fotosintesis?",
    answers: [
      "Oksigen",
      "Pasir",
      "Asap"
    ],
    correct: 0
  },
  {
    question: "Di mana fotosintesis terutama berlangsung?",
    answers: [
      "Akar",
      "Kloroplas",
      "Dinding sel"
    ],
    correct: 1
  }
];

let currentQuestion = 0;
let answered = false;

function showQuestion() {
  const q = questions[currentQuestion];

  answered = false;

  document.getElementById("question").textContent =
    q.question;

  document.getElementById("feedback").textContent = "";

  const answers = document.getElementById("answers");
  answers.innerHTML = "";

  q.answers.forEach((answer, index) => {
    const button = document.createElement("button");
    button.textContent = answer;

    button.onclick = function() {
      if (answered) return;
      answered = true;

      if (index === q.correct) {
        button.style.background = "#b9edb1";
        document.getElementById("feedback").textContent =
          "Benar! Jawabanmu tepat! 🌟";
      } else {
        button.style.background = "#ffd7c7";
        document.getElementById("feedback").textContent =
          "Belum tepat. Coba pelajari materinya lagi!";
      }
    };

    answers.appendChild(button);
  });

  document.getElementById("next").textContent =
    currentQuestion === questions.length - 1
      ? "Ulangi Kuis ↻"
      : "Pertanyaan Berikutnya →";
}

function nextQuestion() {
  currentQuestion =
    (currentQuestion + 1) % questions.length;

  showQuestion();
}

showQuestion();
</script>

</body>
</html>
