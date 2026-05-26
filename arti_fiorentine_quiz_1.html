<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<title>A quale Arte appartieni?</title>
<style>
  :root {
    --gold: #ede8d0;
    --gold-light: #F0D78C;
    --gold-dark: #8B6914;
    --bg: #952d29;
    --surface: #631f1d;
    --surface-2: #952d29;
    --border: rgba(0,0,0,0.1);
    --border-hover: rgba(0,0,0,0.2);
    --text: #ede8d0;
    --text-muted: #ede8d0;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: 'Palatino Linotype', Palatino, Georgia, serif;
    background-color: var(--bg);
    color: var(--text);
    padding: 40px 20px;
    min-height: 100vh;
  }
  .wrap {
    max-width: 620px;
    margin: 0 auto;
  }
  .header {
    text-align: center;
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
    border-bottom: 0.5px solid var(--border);
  }
  .header h1 {
    font-size: 26px;
    font-weight: 500;
    letter-spacing: 0.02em;
    margin-bottom: 0.4rem;
    color: var(--text);
  }
  .header p {
    font-size: 13px;
    color: var(--text-muted);
    font-style: italic;
  }
  .progress-bar {
    height: 3px;
    background: var(--border);
    border-radius: 2px;
    margin-bottom: 0.5rem;
    overflow: hidden;
  }
  .progress-fill {
    height: 100%;
    background: var(--gold);
    border-radius: 2px;
    transition: width 0.4s ease;
  }
  .step-label {
    font-size: 12px;
    color: var(--text-muted);
    text-align: right;
    margin-bottom: 1.5rem;
  }
  .question-card {
    background: var(--surface);
    border: 0.5px solid var(--border);
    border-radius: 12px;
    padding: 1.75rem;
    margin-bottom: 1.5rem;
  }
  .question-text {
    font-size: 17px;
    line-height: 1.6;
    margin-bottom: 1.25rem;
    color: var(--text);
  }
  .options-grid {
    display: flex;
    flex-direction: column;
    gap: 8px;
  }
  .option-btn {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    padding: 10px 14px;
    border: 0.5px solid var(--border);
    border-radius: 8px;
    background: var(--surface-2);
    cursor: pointer;
    text-align: left;
    transition: border-color 0.15s, background 0.15s;
    font-family: inherit;
    font-size: 14px;
    color: var(--text);
    line-height: 1.5;
    width: 100%;
  }
  .option-btn:hover {
    border-color: var(--gold);
    background: var(--surface);
  }
  .option-letter {
    font-size: 12px;
    font-weight: 600;
    color: var(--gold-dark);
    min-width: 16px;
    padding-top: 1px;
  }
  .nav-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 0.5rem;
  }
  .nav-btn {
    padding: 9px 20px;
    border: 0.5px solid var(--border-hover);
    border-radius: 8px;
    background: transparent;
    color: var(--text);
    font-size: 13px;
    cursor: pointer;
    font-family: inherit;
    transition: background 0.15s;
    font-weight: 500;
  }
  .nav-btn:hover { background: var(--surface-2); }
  .nav-btn:disabled { opacity: 0.3; cursor: default; }
  .nav-btn.primary {
    background: var(--gold);
    border-color: var(--gold-dark);
    color: #2C1E00;
    font-weight: 600;
  }
  .nav-btn.primary:hover { background: var(--gold-light); }
  .nav-btn.primary:disabled { opacity: 0.3; }

  /* RESULT */
  .result-card {
    background: var(--surface);
    border: 1px solid var(--gold);
    border-radius: 12px;
    padding: 2.5rem 2rem;
    text-align: center;
    display: none;
  }
  .result-card.show { display: block; }
  .ornament {
    color: var(--gold);
    font-size: 20px;
    margin-bottom: 1.25rem;
    letter-spacing: 0.3em;
  }
  .result-arte-num {
    font-size: 13px;
    color: var(--gold-dark);
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin-bottom: 0.5rem;
  }
  .result-arte-name {
    font-size: 28px;
    font-weight: 500;
    color: var(--text);
    margin-bottom: 1rem;
    line-height: 1.3;
  }
  .result-arte-desc {
    font-size: 15px;
    color: var(--text-muted);
    font-style: italic;
    line-height: 1.75;
    margin-bottom: 1.75rem;
  }
  .restart-btn {
    padding: 10px 28px;
    border: 0.5px solid var(--border-hover);
    border-radius: 8px;
    background: transparent;
    color: var(--text);
    font-size: 13px;
    cursor: pointer;
    font-family: inherit;
    transition: background 0.15s;
    letter-spacing: 0.04em;
    font-weight: 500;
  }
  .restart-btn:hover { background: var(--surface-2); }
</style>
</head>
<body>
<div class="wrap">
  <div class="header">
    <h1>A quale Arte appartieni?</h1>
    <p>Sette domande per scoprire la tua corporazione tra le Arti di Firenze</p>
  </div>

  <div id="quiz-section">
    <div class="progress-bar"><div class="progress-fill" id="progress-fill"></div></div>
    <div class="step-label" id="step-label">Domanda 1 di 7</div>
    <div class="question-card">
      <p class="question-text" id="question-text"></p>
      <div class="options-grid" id="options-grid"></div>
    </div>
    <div class="nav-row">
      <button class="nav-btn" id="btn-back" onclick="goBack()">← Indietro</button>
      <button class="nav-btn primary" id="btn-next" onclick="goNext()">Avanti →</button>
    </div>
  </div>

  <div class="result-card" id="result-card">
    <div class="ornament">✦ ✦ ✦</div>
    <div class="result-arte-num" id="result-arte-num"></div>
    <div class="result-arte-name" id="result-arte-name"></div>
    <div class="result-arte-desc" id="result-arte-desc"></div>
    <button class="restart-btn" onclick="restart()">Ricomincia il quiz</button>
  </div>
</div>

<script>
const arti = {
  1: { name: "Giudici e Notai", desc: "Amministravi la giustizia e ricoprivi ruoli di massima fiducia nello stato. La tua mente ordinata e il tuo senso dell'autorità ti collocano tra i custodi della legge e della res publica fiorentina." },
  2: { name: "Mercanti di Calimala", desc: "Importavi e rifinivi stoffe preziose, dominando il commercio internazionale. Il tuo spirito cosmopolita e il fiuto per gli affari ti aprono le porte dei mercati d'Europa." },
  3: { name: "Cambiavalute", desc: "Potente banchiere e cambiavalute, gestivi il denaro con precisione e strategia. La tua acutezza matematica è la vera moneta del potere." },
  4: { name: "Arte della Lana", desc: "Specializzato nella produzione di panni di altissimo valore, il tuo lavoro è fatto di concretezza, calore e sapienza artigianale." },
  5: { name: "Arte della Seta", desc: "Lavoravi tessuti preziosi e velluti con raffinatezza incomparabile. Il tuo gusto per l'eleganza si traduce in capolavori di filo e colore." },
  6: { name: "Medici e Speziali", desc: "Medici, farmacisti e mercanti di spezie e pigmenti: la tua vocazione è prenderti cura, osservare, guarire. Hai l'occhio del sapiente e il cuore del guaritore." },
  7: { name: "Pellicciai", desc: "Lavoratori e commercianti di pelli e pellicce, ami le cose sontuose e concrete. La tua eleganza è naturale, robusta, senza fronzoli." }
};

const domande = [
  {
    text: "Quando eri piccolo, cosa facevi per passare il tempo?",
    options: [
      { text: "Giocavo in giardino, soprattutto se c'era la neve", arti: [7] },
      { text: "Giocavo a fare il venditore o la stilista", arti: [2] },
      { text: "Giocavo a fare il medico", arti: [6] },
      { text: "Mi travestivo per fare le sfilate", arti: [5] },
      { text: "Giocavo a Monopoly", arti: [3] },
      { text: "Giocavo con i soldatini organizzando l'esercito", arti: [1] },
      { text: "Facevo i fortini con le coperte", arti: [4] }
    ]
  },
  {
    text: "In che cosa sei più bravo?",
    options: [
      { text: "Fare il caposquadra", arti: [1] },
      { text: "Avere stile", arti: [2,4,5,7] },
      { text: "Matematica", arti: [3] },
      { text: "Cucire", arti: [2,4,5,7] },
      { text: "Prendermi cura di chi non sta bene", arti: [6] },
      { text: "Giocare ai quattro ristoranti", arti: [6] }
    ]
  },
  {
    text: "Scegli un aggettivo per descriverti:",
    options: [
      { text: "Organizzato", arti: [1] },
      { text: "Internazionale", arti: [2] },
      { text: "Strategico (preciso)", arti: [3] },
      { text: "Pratico", arti: [4] },
      { text: "Raffinato", arti: [5] },
      { text: "Scientifico (attento ai dettagli)", arti: [6] },
      { text: "Elegante (sontuoso)", arti: [7] }
    ]
  },
  {
    text: "Quale oggetto preferisci?",
    options: [
      { text: "Libro", arti: [1] },
      { text: "Vestito elegante", arti: [2] },
      { text: "Calcolatrice", arti: [3] },
      { text: "Coperta", arti: [4] },
      { text: "Sciarpa di seta", arti: [5] },
      { text: "Camice", arti: [6] },
      { text: "Pelliccia", arti: [7] }
    ]
  },
  {
    text: "Quale simbolo ti rappresenta maggiormente?",
    options: [
      { text: "Stella", arti: [1] },
      { text: "Aquila", arti: [2] },
      { text: "Scudo", arti: [3] },
      { text: "Agnello", arti: [4] },
      { text: "Porta", arti: [5] },
      { text: "Vaso", arti: [6] },
      { text: "Campana", arti: [7] }
    ]
  },
  {
    text: "Mi vesto principalmente in modo:",
    options: [
      { text: "Formale", arti: [1] },
      { text: "Colorato", arti: [2] },
      { text: "Preciso e abbinato", arti: [3] },
      { text: "Caldo", arti: [4] },
      { text: "Sofisticato", arti: [5] },
      { text: "Curato e semplice", arti: [6] },
      { text: "Sgargiante e sfarzoso", arti: [7] }
    ]
  },
  {
    text: "Che colore preferisci?",
    options: [
      { text: "Azzurro", arti: [1] },
      { text: "Oro", arti: [2] },
      { text: "Rosso", arti: [3] },
      { text: "Bianco", arti: [4] },
      { text: "Argento", arti: [5] },
      { text: "Blu", arti: [6] },
      { text: "Grigio", arti: [7] }
    ]
  }
];

const letters = ['A','B','C','D','E','F','G'];
let current = 0;
let answers = new Array(domande.length).fill(null);

function render() {
  const q = domande[current];
  document.getElementById('question-text').textContent = q.text;
  const grid = document.getElementById('options-grid');
  grid.innerHTML = '';
  q.options.forEach((opt, i) => {
    const btn = document.createElement('button');
    btn.className = 'option-btn';
    btn.innerHTML = '<span class="option-letter">' + letters[i] + '.</span><span>' + opt.text + '</span>';
    btn.onclick = () => selectOption(i);
    grid.appendChild(btn);
  });
  const pct = (current / domande.length) * 100;
  document.getElementById('progress-fill').style.width = pct + '%';
  document.getElementById('step-label').textContent = 'Domanda ' + (current + 1) + ' di ' + domande.length;
  document.getElementById('btn-back').disabled = current === 0;
  const btnNext = document.getElementById('btn-next');
  btnNext.textContent = current === domande.length - 1 ? 'Scopri il risultato ✦' : 'Avanti →';
  btnNext.disabled = answers[current] === null;
}

function selectOption(i) {
  answers[current] = i;
  if (current < domande.length - 1) {
    current++;
    render();
  } else {
    showResult();
  }
}

function goNext() {
  if (answers[current] === null) return;
  if (current < domande.length - 1) {
    current++;
    render();
  } else {
    showResult();
  }
}

function goBack() {
  if (current > 0) { current--; render(); }
}

function showResult() {
  const scores = {};
  const firstSeen = {};
  answers.forEach((ansIdx, qIdx) => {
    if (ansIdx === null) return;
    domande[qIdx].options[ansIdx].arti.forEach(a => {
      if (!(a in scores)) scores[a] = 0;
      scores[a]++;
      if (!(a in firstSeen)) firstSeen[a] = qIdx;
    });
  });
  const maxScore = Math.max(...Object.values(scores));
  const winner = Object.keys(scores)
    .filter(a => scores[a] === maxScore)
    .map(Number)
    .sort((a, b) => firstSeen[a] - firstSeen[b])[0];

  document.getElementById('quiz-section').style.display = 'none';
  const rc = document.getElementById('result-card');
  rc.classList.add('show');
  document.getElementById('result-arte-num').textContent = 'Arte n. ' + winner;
  document.getElementById('result-arte-name').textContent = arti[winner].name;
  document.getElementById('result-arte-desc').textContent = arti[winner].desc;
}

function restart() {
  current = 0;
  answers = new Array(domande.length).fill(null);
  document.getElementById('result-card').classList.remove('show');
  document.getElementById('quiz-section').style.display = 'block';
  render();
}

render();
</script>
</body>
</html>
