
<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Misi Pemulihan - Kata Adjektif Pancaindera</title>

<style>
* { box-sizing: border-box; }

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #fff7ed;
    color: #334155;
}

header {
    background: linear-gradient(135deg,#fb923c,#f472b6);
    color: white;
    text-align: center;
    padding: 30px 15px;
    border-radius: 0 0 30px 30px;
}

header h1 { font-size: 28px; }
header p { font-size: 16px; }

.container {
    max-width: 850px;
    margin: 25px auto;
    padding: 15px;
}

.card {
    background: white;
    padding: 22px;
    border-radius: 18px;
    margin-bottom: 22px;
    box-shadow: 0 4px 12px #00000010;
}

h2 { color: #ea580c; }

button {
    background: #f97316;
    color: white;
    border: none;
    border-radius: 10px;
    padding: 12px 18px;
    cursor: pointer;
    font-size: 15px;
    margin: 5px;
}

button:hover { background: #c2410c; }

button:disabled {
    background: #cbd5e1;
    cursor: not-allowed;
}

.nav {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 8px;
    margin: 20px 0;
}

.nav button { background: #7c3aed; }

.section { display: none; }
.section.active { display: block; }

.senses {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 12px;
}

.sense-box {
    background: #fff7ed;
    border: 2px solid #fed7aa;
    border-radius: 15px;
    padding: 15px;
}

.sense-box h3 { color: #ea580c; }

.word-card {
    background: #ffedd5;
    border: 2px solid #fdba74;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    cursor: pointer;
    min-height: 110px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    transition: .2s;
}

.word-card:hover {
    transform: translateY(-3px);
    background: #fed7aa;
}

.word-card .word {
    font-size: 23px;
    font-weight: bold;
    color: #c2410c;
}

.word-card .meaning {
    font-size: 14px;
    margin-top: 8px;
}

.cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(140px,1fr));
    gap: 12px;
    margin-top: 18px;
}

.flip-card {
    height: 125px;
    background: #8b5cf6;
    color: white;
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 22px;
    font-weight: bold;
    cursor: pointer;
    text-align: center;
    padding: 10px;
}

.flip-card.open {
    background: #fef3c7;
    color: #92400e;
    border: 2px solid #fbbf24;
}

.flip-card.matched {
    background: #dcfce7;
    color: #166534;
    cursor: default;
}

.question {
    background: #fff7ed;
    padding: 16px;
    border-radius: 12px;
    margin: 15px 0;
}

.option {
    display: block;
    background: white;
    border: 2px solid #fed7aa;
    border-radius: 10px;
    padding: 12px;
    margin: 8px 0;
    cursor: pointer;
}

.option:hover { background: #ffedd5; }

.option.selected {
    background: #fed7aa;
    border-color: #f97316;
}

.feedback {
    padding: 12px;
    border-radius: 10px;
    margin-top: 12px;
    display: none;
}

.good { background: #dcfce7; color: #166534; }
.bad { background: #fee2e2; color: #991b1b; }

.progress {
    background: #e2e8f0;
    height: 12px;
    border-radius: 20px;
    overflow: hidden;
    margin: 15px 0;
}

.progress-bar {
    height: 100%;
    background: #22c55e;
    width: 0%;
}

footer {
    text-align: center;
    padding: 20px;
    color: #64748b;
}

</style>
</head>

<body>

<header>
    <div style="font-size:45px;">👁️ 👂 👃 👅 ✋</div>
    <h1>🌟 MISI PEMULIHAN 🌟</h1>
    <h2 style="color:white;">Kata Adjektif Pancaindera</h2>
    <p>Jom belajar sambil bermain!</p>
</header>

<div class="container">

<div class="nav">
    <button onclick="showSection('learn')">📚 Misi 1: Kad Imbas</button>
    <button onclick="showSection('game')">🎮 Misi 2: Flip & Match</button>
    <button onclick="showSection('quiz')">📝 Misi 3: Uji Minda</button>
</div>

<!-- MISI 1 -->

<section id="learn" class="section active">
<div class="card">
    <h2>📚 MISI 1: KAD IMBAS PINTAR</h2>
    <p>Arahan: Klik pada kad untuk melihat contoh kata adjektif dan maksudnya. Mari kenali lima deria kita!</p>

    <div class="senses">

        <div class="sense-box">
            <h3>👁️ Deria Pandang</h3>
            <p>Kita menggunakan mata untuk melihat warna, bentuk dan saiz.</p>
            <div class="cards-grid">
                <div class="word-card" onclick="flipWord(this,'Cantik','Sangat menarik apabila dilihat.')">
                    <span class="word">Cantik</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Comel','Kecil dan menarik dipandang.')">
                    <span class="word">Comel</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Indah','Cantik dan menarik dipandang.')">
                    <span class="word">Indah</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Buruk','Tidak cantik dipandang.')">
                    <span class="word">Buruk</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Molek','Elok dan cantik dipandang.')">
                    <span class="word">Molek</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Kacak','Tampan dan menarik dipandang.')">
                    <span class="word">Kacak</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
            </div>
        </div>

        <div class="sense-box">
            <h3>👂 Deria Dengar</h3>
            <p>Kita menggunakan telinga untuk mendengar bunyi, muzik dan suara manusia.</p>
            <div class="cards-grid">
                <div class="word-card" onclick="flipWord(this,'Bising','Bunyi yang kuat dan mengganggu.')">
                    <span class="word">Bising</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Nyaring','Bunyi yang kuat dan tinggi.')">
                    <span class="word">Nyaring</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Senyap','Tidak kedengaran bunyi.')">
                    <span class="word">Senyap</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Merdu','Bunyi atau suara yang sedap didengar.')">
                    <span class="word">Merdu</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Riuh','Bunyi ramai orang bercakap.')">
                    <span class="word">Riuh</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Garau','Suara yang rendah dan kasar.')">
                    <span class="word">Garau</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
            </div>
        </div>

        <div class="sense-box">
            <h3>👃 Deria Bau</h3>
            <p>Kita menggunakan hidung untuk menghidu bau.</p>
            <div class="cards-grid">
                <div class="word-card" onclick="flipWord(this,'Harum','Bau yang menyenangkan.')">
                    <span class="word">Harum</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Wangi','Bau yang sangat menyenangkan.')">
                    <span class="word">Wangi</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Busuk','Bau yang tidak menyenangkan.')">
                    <span class="word">Busuk</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Hanyir','Bau seperti bau ikan mentah.')">
                    <span class="word">Hanyir</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Nyaman','Bau yang segar dan menyenangkan.')">
                    <span class="word">Nyaman</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Basi','Bau makanan yang sudah rosak.')">
                    <span class="word">Basi</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
            </div>
        </div>

        <div class="sense-box">
            <h3>👅 Deria Rasa</h3>
            <p>Kita menggunakan lidah untuk merasa makanan.</p>
            <div class="cards-grid">
                <div class="word-card" onclick="flipWord(this,'Lemak','Rasa yang berkrim dan berlemak.')">
                    <span class="word">Lemak</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Lazat','Makanan yang sangat enak.')">
                    <span class="word">Lazat</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Pedas','Rasa seperti cili.')">
                    <span class="word">Pedas</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Manis','Rasa seperti gula atau madu.')">
                    <span class="word">Manis</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Masin','Rasa seperti garam.')">
                    <span class="word">Masin</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Sedap','Rasa makanan yang enak.')">
                    <span class="word">Sedap</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
            </div>
        </div>

        <div class="sense-box">
            <h3>✋ Deria Sentuh</h3>
            <p>Kita menggunakan tangan dan kulit untuk merasa tekstur dan suhu.</p>
            <div class="cards-grid">
                <div class="word-card" onclick="flipWord(this,'Keras','Tidak mudah ditekan atau dibengkokkan.')">
                    <span class="word">Keras</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Halus','Permukaan yang lembut dan licin.')">
                    <span class="word">Halus</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Kasar','Permukaan yang tidak rata.')">
                    <span class="word">Kasar</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Licin','Permukaan yang rata dan mudah digerakkan.')">
                    <span class="word">Licin</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Lembut','Mudah ditekan dan tidak keras.')">
                    <span class="word">Lembut</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
                <div class="word-card" onclick="flipWord(this,'Kesat','Permukaan yang tidak licin.')">
                    <span class="word">Kesat</span>
                    <span class="meaning">Klik untuk belajar</span>
                </div>
            </div>
        </div>

    </div>

    <button onclick="showSection('game')">Seterusnya: Misi 2 ➜</button>
</div>
</section>

<!-- MISI 2 -->

<section id="game" class="section">
<div class="card">
    <h2>🎮 MISI 2: PERMAINAN FLIP & MATCH</h2>
    <p>Arahan: Klik dua kad untuk mencari pasangan kata adjektif yang sama.</p>
    <p>Contoh: Harum ↔ Harum</p>

    <div class="progress">
        <div class="progress-bar" id="gameProgress"></div>
    </div>

    <p id="gameScore">Pasangan dijumpai: 0 / 5</p>

    <div class="cards-grid" id="gameCards"></div>

    <div id="gameFeedback" class="feedback"></div>

    <button onclick="startGame()">🔄 Main Semula</button>
    <button onclick="showSection('quiz')">Seterusnya: Misi 3 ➜</button>
</div>
</section>

<!-- MISI 3 -->

<section id="quiz" class="section">
<div class="card">
    <h2>📝 MISI 3: UJI MINDA</h2>
    <p>Arahan: Pilih jawapan yang betul berdasarkan soalan.</p>

    <div id="quizQuestions"></div>

    <button onclick="checkQuiz()">Semak Jawapan</button>
    <button onclick="resetQuiz()" style="background:#64748b;">Cuba Semula</button>

    <div id="quizResult" class="feedback"></div>
</div>
</section>

<div class="card" style="text-align:center;background:#fff7ed;">
    <h2>🌟 Syabas!</h2>
    <p>Anda telah belajar tentang lima deria dan kata adjektif pancaindera.</p>
    <p>Teruskan belajar dan jangan berputus asa!</p>
    <div style="font-size:40px;">🏆 ⭐ 🎉</div>
</div>

</div>

<footer>
Misi Pemulihan Bahasa Melayu | Selamat Belajar!
</footer>

<script>

// NAVIGASI

function showSection(id) {
    document.querySelectorAll('.section').forEach(s => {
        s.classList.remove('active');
    });
    document.getElementById(id).classList.add('active');
    window.scrollTo({top:0,behavior:'smooth'});
}

// KAD IMBAS

function flipWord(card,word,meaning) {
    card.querySelector('.word').textContent = word;
    card.querySelector('.meaning').textContent = meaning;
}

// PERMAINAN FLIP & MATCH

const gameWords = [
    "Cantik","Cantik",
    "Merdu","Merdu",
    "Harum","Harum",
    "Manis","Manis",
    "Lembut","Lembut"
];

let firstCard = null;
let secondCard = null;
let locked = false;
let matched = 0;

function startGame() {
    firstCard = null;
    secondCard = null;
    locked = false;
    matched = 0;

    const shuffled = [...gameWords].sort(() => Math.random() - 0.5);
    const board = document.getElementById('gameCards');

    board.innerHTML = '';

    shuffled.forEach((word,index) => {
        const card = document.createElement('div');
        card.className = 'flip-card';
        card.textContent = '?';
        card.dataset.word = word;

        card.onclick = () => flipCard(card);

        board.appendChild(card);
    });

    document.getElementById('gameScore').textContent =
        "Pasangan dijumpai: 0 / 5";

    document.getElementById('gameProgress').style.width = '0%';

    document.getElementById('gameFeedback').style.display = 'none';
}

function flipCard(card) {
    if (locked || card.classList.contains('matched') ||
        card === firstCard || card.classList.contains('open')) return;

    card.classList.add('open');
    card.textContent = card.dataset.word;

    if (!firstCard) {
        firstCard = card;
        return;
    }

    secondCard = card;
    locked = true;

    if (firstCard.dataset.word === secondCard.dataset.word) {
        firstCard.classList.add('matched');
        secondCard.classList.add('matched');

        matched++;

        document.getElementById('gameScore').textContent =
            `Pasangan dijumpai: ${matched} / 5`;

        document.getElementById('gameProgress').style.width =
            (matched/5*100) + '%';

        firstCard = null;
        secondCard = null;
        locked = false;

        if (matched === 5) {
            const feedback = document.getElementById('gameFeedback');
            feedback.style.display = 'block';
            feedback.className = 'feedback good';
            feedback.innerHTML = '🎉 Hebat! Anda berjaya mencari semua pasangan!';
        }

    } else {
        setTimeout(() => {
            firstCard.classList.remove('open');
            secondCard.classList.remove('open');

            firstCard.textContent = '?';
            secondCard.textContent = '?';

            firstCard = null;
            secondCard = null;
            locked = false;
        },900);
    }
}

startGame();

// UJI MINDA

const quizData = [
{
    q:"1. Kita menggunakan mata untuk ______.",
    options:["Mendengar","Melihat","Menghidu"],
    answer:"Melihat"
},
{
    q:"2. Apakah kata adjektif yang sesuai untuk bunga yang mempunyai bau menyenangkan?",
    options:["Busuk","Hanyir","Harum"],
    answer:"Harum"
},
{
    q:"3. Suara penyanyi itu sangat sedap didengar. Suaranya ______.",
    options:["Merdu","Bising","Garau"],
    answer:"Merdu"
},
{
    q:"4. Kita menggunakan lidah untuk merasa makanan yang ______.",
    options:["Licin","Manis","Kacak"],
    answer:"Manis"
},
{
    q:"5. Permukaan batu itu tidak rata dan terasa ______.",
    options:["Lembut","Kasar","Wangi"],
    answer:"Kasar"
},
{
    q:"6. Suasana perpustakaan sangat ______ kerana tiada orang membuat bising.",
    options:["Riuh","Nyaring","Senyap"],
    answer:"Senyap"
},
{
    q:"7. Apakah deria yang digunakan untuk menghidu bau?",
    options:["Deria Bau","Deria Sentuh","Deria Dengar"],
    answer:"Deria Bau"
},
{
    q:"8. Sup yang mempunyai terlalu banyak garam terasa ______.",
    options:["Manis","Masin","Harum"],
    answer:"Masin"
}
];

const quizContainer = document.getElementById('quizQuestions');

quizData.forEach((q,i) => {
    let html = `
    <div class="question">
        <b>${q.q}</b>
        <div>`;

    q.options.forEach(option => {
        html += `
        <label class="option">
            <input type="radio" name="q${i}" value="${option}">
            ${option}
        </label>`;
    });

    html += `</div></div>`;
    quizContainer.innerHTML += html;
});

function checkQuiz() {
    let score = 0;
    let unanswered = 0;

    quizData.forEach((q,i) => {
        const selected = document.querySelector(
            `input[name="q${i}"]:checked`
        );

        if (!selected) {
            unanswered++;
        } else if (selected.value === q.answer) {
            score++;
        }
    });

    const result = document.getElementById('quizResult');
    result.style.display = 'block';

    if (unanswered > 0) {
        result.className = 'feedback bad';
        result.innerHTML =
            `Sila jawab semua soalan dahulu. ${unanswered} soalan belum dijawab.`;
        return;
    }

    result.className = score >= 6 ? 'feedback good' : 'feedback bad';

    result.innerHTML = `
        <h3>Keputusan Anda: ${score}/8</h3>
        ${
            score === 8
            ? "🏆 Tahniah! Semua jawapan betul. Anda memang hebat!"
            : score >= 6
            ? "👏 Bagus! Anda sudah menguasai kebanyakan soalan."
            : "💪 Jangan risau! Cuba baca kad imbas sekali lagi dan jawab semula."
        }
    `;
}

function resetQuiz() {
    document.querySelectorAll('input[type="radio"]').forEach(input => {
        input.checked = false;
    });

    document.getElementById('quizResult').style.display = 'none';
}

</script>

</body>
</html>
