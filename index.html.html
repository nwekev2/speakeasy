<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SpeakEasy — My Speech Playground</title>
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
  :root {
    --sky: #e8f4fd;
    --coral: #ff6b6b;
    --mint: #4ecdc4;
    --sunshine: #ffe66d;
    --lavender: #a29bfe;
    --peach: #ffeaa7;
    --green: #55efc4;
    --pink: #fd79a8;
    --dark: #2d3436;
    --soft: #636e72;
    --white: #ffffff;
    --card-shadow: 0 8px 32px rgba(0,0,0,0.10);
    --bounce: cubic-bezier(0.68,-0.55,0.27,1.55);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'Nunito', sans-serif;
    background: var(--sky);
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* Animated background bubbles */
  body::before {
    content: '';
    position: fixed;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle at 20% 20%, #ffecd2 0%, transparent 40%),
                radial-gradient(circle at 80% 80%, #d4f8e8 0%, transparent 40%),
                radial-gradient(circle at 60% 20%, #e8d5f5 0%, transparent 35%),
                radial-gradient(circle at 20% 70%, #d5eaff 0%, transparent 35%);
    z-index: 0;
    animation: bgshift 12s ease-in-out infinite alternate;
  }
  @keyframes bgshift {
    0% { transform: translateX(0) translateY(0); }
    100% { transform: translateX(3%) translateY(2%); }
  }

  .container {
    position: relative;
    z-index: 1;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px 16px 60px;
  }

  /* HEADER */
  header {
    text-align: center;
    padding: 30px 0 24px;
  }
  .logo {
    font-family: 'Fredoka One', cursive;
    font-size: clamp(2.2rem, 7vw, 3.5rem);
    color: var(--coral);
    text-shadow: 4px 4px 0 #ffd6d6;
    animation: logobounce 2.5s ease-in-out infinite;
    display: inline-block;
  }
  @keyframes logobounce {
    0%,100% { transform: translateY(0); }
    50% { transform: translateY(-6px); }
  }
  .tagline {
    font-size: 1.05rem;
    color: var(--soft);
    margin-top: 4px;
    font-weight: 600;
  }

  /* STAR BAR */
  .star-bar {
    display: flex;
    justify-content: center;
    gap: 6px;
    margin: 10px 0;
  }
  .star {
    font-size: 1.5rem;
    opacity: 0.25;
    transition: all 0.3s var(--bounce);
  }
  .star.lit {
    opacity: 1;
    animation: starlit 0.4s var(--bounce);
  }
  @keyframes starlit {
    0% { transform: scale(0.5); }
    100% { transform: scale(1); }
  }

  /* CATEGORY TABS */
  .tabs {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px 0;
  }
  .tab-btn {
    background: white;
    border: 3px solid transparent;
    border-radius: 50px;
    padding: 10px 20px;
    font-family: 'Nunito', sans-serif;
    font-size: 1rem;
    font-weight: 700;
    cursor: pointer;
    transition: all 0.2s var(--bounce);
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .tab-btn:hover { transform: translateY(-3px) scale(1.05); }
  .tab-btn.active {
    color: white;
    transform: translateY(-3px) scale(1.05);
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
  }
  .tab-btn[data-cat="animals"].active { background: var(--coral); border-color: #ff4444; }
  .tab-btn[data-cat="colors"].active  { background: var(--lavender); border-color: #6c5ce7; }
  .tab-btn[data-cat="food"].active    { background: var(--mint); border-color: #00b894; }
  .tab-btn[data-cat="actions"].active { background: var(--pink); border-color: #e84393; }
  .tab-btn[data-cat="sounds"].active  { background: var(--sunshine); border-color: #f9ca24; color: var(--dark); }

  /* MAIN CARD */
  .main-card {
    background: white;
    border-radius: 32px;
    padding: 36px 28px;
    box-shadow: var(--card-shadow);
    text-align: center;
    position: relative;
    overflow: hidden;
    min-height: 380px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .main-card::before {
    content: '';
    position: absolute;
    top: -40px; right: -40px;
    width: 160px; height: 160px;
    border-radius: 50%;
    background: radial-gradient(circle, var(--sunshine) 0%, transparent 70%);
    opacity: 0.4;
  }

  .word-emoji {
    font-size: clamp(5rem, 18vw, 9rem);
    line-height: 1;
    display: block;
    animation: emojipop 0.5s var(--bounce);
    filter: drop-shadow(0 8px 16px rgba(0,0,0,0.12));
    margin-bottom: 10px;
    cursor: default;
  }
  @keyframes emojipop {
    0% { transform: scale(0) rotate(-15deg); opacity: 0; }
    100% { transform: scale(1) rotate(0deg); opacity: 1; }
  }

  .word-label {
    font-family: 'Fredoka One', cursive;
    font-size: clamp(2rem, 8vw, 3.5rem);
    color: var(--dark);
    letter-spacing: 0.05em;
    margin-bottom: 6px;
    animation: wordin 0.4s ease;
  }
  @keyframes wordin {
    0% { opacity: 0; transform: translateY(12px); }
    100% { opacity: 1; transform: translateY(0); }
  }

  .word-syllables {
    font-size: 1.1rem;
    color: var(--soft);
    font-weight: 600;
    letter-spacing: 0.12em;
    margin-bottom: 4px;
  }

  .word-prompt {
    font-size: 1rem;
    color: var(--soft);
    margin-bottom: 20px;
    font-style: italic;
    min-height: 26px;
  }

  /* BUTTONS ROW */
  .btn-row {
    display: flex;
    gap: 12px;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 4px;
  }

  .btn {
    font-family: 'Nunito', sans-serif;
    font-weight: 800;
    font-size: 1rem;
    border: none;
    border-radius: 50px;
    padding: 13px 26px;
    cursor: pointer;
    transition: all 0.2s var(--bounce);
    display: flex;
    align-items: center;
    gap: 8px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.12);
  }
  .btn:hover { transform: translateY(-3px) scale(1.05); }
  .btn:active { transform: scale(0.97); }

  .btn-listen  { background: var(--lavender); color: white; }
  .btn-next    { background: var(--coral);    color: white; }
  .btn-back    { background: #dfe6e9;         color: var(--dark); }
  .btn-speak   { background: var(--mint);     color: white; }
  .btn-speak.listening { background: var(--coral); animation: pulse 0.8s ease-in-out infinite; }
  @keyframes pulse {
    0%,100% { box-shadow: 0 5px 15px rgba(255,107,107,0.3); }
    50%      { box-shadow: 0 5px 30px rgba(255,107,107,0.7); }
  }

  /* FEEDBACK AREA */
  .feedback-area {
    min-height: 70px;
    margin-top: 14px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 6px;
  }
  .feedback-msg {
    font-size: 1.15rem;
    font-weight: 800;
    color: var(--mint);
    opacity: 0;
    transform: translateY(8px);
    transition: all 0.3s ease;
  }
  .feedback-msg.show { opacity: 1; transform: translateY(0); }
  .feedback-msg.great { color: var(--mint); }
  .feedback-msg.try   { color: var(--coral); }
  .feedback-msg.info  { color: var(--lavender); }

  .transcript-box {
    background: #f8f9fa;
    border-radius: 16px;
    padding: 10px 18px;
    font-size: 0.95rem;
    color: var(--dark);
    font-weight: 600;
    min-width: 220px;
    min-height: 38px;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 2px dashed #dfe6e9;
    opacity: 0;
    transition: opacity 0.3s;
  }
  .transcript-box.show { opacity: 1; }

  /* CONFETTI */
  .confetti-burst {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    pointer-events: none;
    z-index: 999;
  }
  .confetto {
    position: absolute;
    width: 10px; height: 10px;
    border-radius: 2px;
    animation: confettifall 1.2s ease-in forwards;
  }
  @keyframes confettifall {
    0%   { transform: translateY(-20px) rotate(0deg); opacity: 1; }
    100% { transform: translateY(100vh) rotate(720deg); opacity: 0; }
  }

  /* PROGRESS BAR */
  .progress-wrap {
    background: #eee;
    border-radius: 50px;
    height: 10px;
    margin: 18px 0 6px;
    overflow: hidden;
  }
  .progress-fill {
    height: 100%;
    background: linear-gradient(90deg, var(--coral), var(--lavender));
    border-radius: 50px;
    transition: width 0.5s ease;
  }
  .progress-label {
    font-size: 0.85rem;
    color: var(--soft);
    font-weight: 700;
    text-align: right;
  }

  /* TIP BOX */
  .tip-box {
    background: linear-gradient(135deg, #fff9e6, #fff0f8);
    border-radius: 20px;
    padding: 16px 20px;
    margin-top: 18px;
    border-left: 5px solid var(--sunshine);
    text-align: left;
    font-size: 0.92rem;
    color: var(--dark);
    font-weight: 600;
    line-height: 1.5;
  }
  .tip-box strong { color: var(--coral); }

  /* WAVEFORM */
  .waveform {
    display: flex;
    align-items: center;
    gap: 4px;
    height: 32px;
    margin-top: 6px;
    opacity: 0;
    transition: opacity 0.3s;
  }
  .waveform.active { opacity: 1; }
  .wave-bar {
    width: 5px;
    background: var(--mint);
    border-radius: 4px;
    animation: wavebar 0.6s ease-in-out infinite;
  }
  .wave-bar:nth-child(2) { animation-delay: 0.1s; }
  .wave-bar:nth-child(3) { animation-delay: 0.2s; }
  .wave-bar:nth-child(4) { animation-delay: 0.3s; }
  .wave-bar:nth-child(5) { animation-delay: 0.4s; }
  @keyframes wavebar {
    0%,100% { height: 6px; }
    50% { height: 28px; }
  }

  /* MODE SELECTOR */
  .mode-row {
    display: flex;
    gap: 8px;
    justify-content: center;
    margin-bottom: 14px;
  }
  .mode-btn {
    background: white;
    border: 2.5px solid #e0e0e0;
    border-radius: 20px;
    padding: 7px 16px;
    font-family: 'Nunito', sans-serif;
    font-size: 0.88rem;
    font-weight: 700;
    cursor: pointer;
    color: var(--soft);
    transition: all 0.2s;
  }
  .mode-btn.active {
    background: var(--lavender);
    border-color: var(--lavender);
    color: white;
  }

  footer {
    text-align: center;
    padding: 20px;
    color: var(--soft);
    font-size: 0.82rem;
  }

  @media (max-width: 500px) {
    .btn { padding: 11px 18px; font-size: 0.9rem; }
  }
</style>
</head>
<body>
<div class="container">

  <header>
    <div class="logo">🗣️ SpeakEasy</div>
    <p class="tagline">Your friendly speech playground!</p>
    <div class="star-bar" id="starBar">
      <span class="star">⭐</span>
      <span class="star">⭐</span>
      <span class="star">⭐</span>
      <span class="star">⭐</span>
      <span class="star">⭐</span>
    </div>
  </header>

  <!-- Mode -->
  <div class="mode-row">
    <button class="mode-btn active" data-mode="practice" onclick="setMode('practice')">🎯 Practice</button>
    <button class="mode-btn" data-mode="listen"   onclick="setMode('listen')">👂 Listen First</button>
    <button class="mode-btn" data-mode="spell"    onclick="setMode('spell')">🔤 Spell It</button>
  </div>

  <!-- Category Tabs -->
  <div class="tabs">
    <button class="tab-btn active" data-cat="animals" onclick="setCategory('animals')">🐾 Animals</button>
    <button class="tab-btn" data-cat="colors"  onclick="setCategory('colors')">🎨 Colors</button>
    <button class="tab-btn" data-cat="food"    onclick="setCategory('food')">🍎 Food</button>
    <button class="tab-btn" data-cat="actions" onclick="setCategory('actions')">🏃 Actions</button>
    <button class="tab-btn" data-cat="sounds"  onclick="setCategory('sounds')">🔊 Sounds</button>
  </div>

  <!-- Progress -->
  <div class="progress-wrap">
    <div class="progress-fill" id="progressFill" style="width:0%"></div>
  </div>
  <p class="progress-label" id="progressLabel">0 of 8 done</p>

  <!-- Main Card -->
  <div class="main-card" id="mainCard">
    <span class="word-emoji" id="wordEmoji">🐱</span>
    <div class="word-label" id="wordLabel">CAT</div>
    <div class="word-syllables" id="wordSyllables">C · A · T</div>
    <div class="word-prompt" id="wordPrompt">Say the word out loud!</div>

    <!-- Spell It input (hidden by default) -->
    <div id="spellSection" style="display:none; margin-bottom:10px;">
      <input id="spellInput" type="text" placeholder="Type the word..."
        style="font-family:'Nunito',sans-serif;font-size:1.3rem;font-weight:700;border:3px solid #e0e0e0;border-radius:16px;padding:10px 20px;width:220px;text-align:center;outline:none;transition:border 0.2s;"
        oninput="checkSpelling()"
        onfocus="this.style.borderColor='var(--lavender)'"
        onblur="this.style.borderColor='#e0e0e0'"
      >
    </div>

    <div class="waveform" id="waveform">
      <div class="wave-bar"></div>
      <div class="wave-bar"></div>
      <div class="wave-bar"></div>
      <div class="wave-bar"></div>
      <div class="wave-bar"></div>
    </div>

    <div class="btn-row">
      <button class="btn btn-back" onclick="prevWord()">⬅ Back</button>
      <button class="btn btn-listen" onclick="speakWord()">🔊 Hear It</button>
      <button class="btn btn-speak" id="speakBtn" onclick="startListening()">🎤 Try It!</button>
      <button class="btn btn-next" onclick="nextWord()">Next ➡</button>
    </div>

    <div class="feedback-area">
      <div class="feedback-msg" id="feedbackMsg">Amazing job! 🎉</div>
      <div class="transcript-box" id="transcriptBox">You said: ...</div>
    </div>
  </div>

  <!-- Tip Box -->
  <div class="tip-box" id="tipBox">
    💡 <strong>Tip:</strong> Look at the picture, say the word slowly, then press 🎤 Try It to practice!
  </div>

</div>

<div class="confetti-burst" id="confetti"></div>

<footer>Made with ❤️ for every voice that wants to be heard · SpeakEasy Speech Playground</footer>

<script>
const WORDS = {
  animals: [
    { emoji:'🐱', word:'CAT',      syllables:'C · A · T',      tip:'Can you make a meowing sound? Now say CAT!', prompt:'A fluffy pet that says meow!' },
    { emoji:'🐶', word:'DOG',      syllables:'D · O · G',      tip:'Puff out your cheeks for the "D" sound!', prompt:'A loyal pet that wags its tail!' },
    { emoji:'🐘', word:'ELEPHANT', syllables:'EL · E · PHANT', tip:'Stretch the word — EL... E... PHANT! Slow and steady!', prompt:'The biggest land animal with a long trunk!' },
    { emoji:'🦁', word:'LION',     syllables:'LI · ON',        tip:'Put your lips together for the "L" sound — Li... on!', prompt:'The king of the jungle!' },
    { emoji:'🐸', word:'FROG',     syllables:'F · R · O · G',  tip:'Feel your lips together then blow — F... rog!', prompt:'It jumps and lives near ponds!' },
    { emoji:'🦋', word:'BUTTERFLY',syllables:'BUT · TER · FLY',tip:'Three parts — BUT... ter... FLY! Clap along!', prompt:'Colorful wings that flutter in the air!' },
    { emoji:'🐧', word:'PENGUIN',  syllables:'PEN · GUIN',     tip:'PEN... guin. Say it like a name!', prompt:'A bird that swims but can\'t fly!' },
    { emoji:'🦊', word:'FOX',      syllables:'F · O · X',      tip:'The "X" makes a "ks" sound — fo... ks!', prompt:'A clever orange animal with a bushy tail!' },
  ],
  colors: [
    { emoji:'❤️', word:'RED',      syllables:'R · E · D',      tip:'Roll the "R" gently — rrr... ed!', prompt:'The color of fire and hearts!' },
    { emoji:'💙', word:'BLUE',     syllables:'B · L · U · E',  tip:'Press lips for "B", then BLUE!', prompt:'The color of the sky and ocean!' },
    { emoji:'💚', word:'GREEN',    syllables:'GR · EEN',       tip:'Squeeze the "GR" together — green!', prompt:'The color of grass and leaves!' },
    { emoji:'💜', word:'PURPLE',   syllables:'PUR · PLE',      tip:'PUR... ple. The second part is quick!', prompt:'A mix of red and blue!' },
    { emoji:'🧡', word:'ORANGE',   syllables:'OR · ANGE',      tip:'OR... ange. Say it like the fruit!', prompt:'The color of a yummy orange!' },
    { emoji:'💛', word:'YELLOW',   syllables:'YEL · LOW',      tip:'YEL... low. Two clear parts!', prompt:'The color of the sunshine!' },
    { emoji:'🩷', word:'PINK',     syllables:'P · I · N · K',  tip:'End with a hard "K" sound — pin... k!', prompt:'A light, rosy color!' },
    { emoji:'🤍', word:'WHITE',    syllables:'WH · ITE',       tip:'The "Wh" is like blowing out a candle!', prompt:'The color of clouds and snow!' },
  ],
  food: [
    { emoji:'🍎', word:'APPLE',    syllables:'AP · PLE',       tip:'AP... ple. Short and snappy!', prompt:'A crunchy red or green fruit!' },
    { emoji:'🍌', word:'BANANA',   syllables:'BA · NA · NA',   tip:'Three NA sounds — ba...NA...NA! Clap each one!', prompt:'A yellow fruit monkeys love!' },
    { emoji:'🍕', word:'PIZZA',    syllables:'PIZ · ZA',       tip:'PIZ... za. Double Z sounds like "tz"!', prompt:'A cheesy, saucy round food!' },
    { emoji:'🥕', word:'CARROT',   syllables:'CAR · ROT',      tip:'CAR... rot. Two crisp parts!', prompt:'An orange veggie rabbits love!' },
    { emoji:'🍓', word:'STRAWBERRY',syllables:'STRAW · BER · RY',tip:'Three parts — STRAW... ber... ry!', prompt:'A red berry with tiny seeds!' },
    { emoji:'🍦', word:'ICE CREAM',syllables:'ICE · CREAM',    tip:'Two words — ICE... CREAM. Enjoy it slowly!', prompt:'A cold, sweet frozen treat!' },
    { emoji:'🥞', word:'PANCAKE',  syllables:'PAN · CAKE',     tip:'PAN... cake. Flat and yummy!', prompt:'A fluffy flat cake for breakfast!' },
    { emoji:'🫐', word:'BLUEBERRY',syllables:'BLUE · BER · RY',tip:'BLUE... ber... ry. Three smooth parts!', prompt:'A tiny blue fruit, sweet and round!' },
  ],
  actions: [
    { emoji:'🏃', word:'RUN',      syllables:'R · U · N',      tip:'Quick and short — like you\'re actually running!', prompt:'Moving your legs very fast!' },
    { emoji:'🤸', word:'JUMP',     syllables:'J · U · M · P',  tip:'End with a "P" pop — jum... p!', prompt:'Leaping up into the air!' },
    { emoji:'🎨', word:'DRAW',     syllables:'DR · AW',        tip:'Blend DR together — Draw!', prompt:'Making pictures with a pencil or crayons!' },
    { emoji:'😴', word:'SLEEP',    syllables:'SL · EEP',       tip:'Blend SL together — sleeep. Stretch the EEP!', prompt:'Resting with your eyes closed!' },
    { emoji:'🎵', word:'SING',     syllables:'S · I · N · G',  tip:'End with a ng humming sound — sin... ng!', prompt:'Making music with your voice!' },
    { emoji:'📚', word:'READ',     syllables:'R · EAD',        tip:'The EA makes a long "ee" sound — reed!', prompt:'Looking at words in a book!' },
    { emoji:'🤗', word:'HUG',      syllables:'H · U · G',      tip:'Breathe out for "H" — hh... ug!', prompt:'Wrapping your arms around someone!' },
    { emoji:'👏', word:'CLAP',     syllables:'CL · AP',        tip:'Blend CL together — cl... ap!', prompt:'Hitting your hands together!' },
  ],
  sounds: [
    { emoji:'🐝', word:'BUZZ',     syllables:'B · UZZ',        tip:'Feel your lips vibrate — bzzz... uzz!', prompt:'The sound a bee makes!' },
    { emoji:'🐍', word:'HISS',     syllables:'H · ISS',        tip:'Let air escape through your teeth — ssss!', prompt:'The sound a snake makes!' },
    { emoji:'🔔', word:'DING',     syllables:'D · ING',        tip:'End with a humming ng — din... ng!', prompt:'The sound a bell makes!' },
    { emoji:'💥', word:'BOOM',     syllables:'B · OOM',        tip:'Round your lips for OOM — boooom!', prompt:'A big, loud explosion sound!' },
    { emoji:'🐱', word:'MEOW',     syllables:'ME · OW',        tip:'ME... ow. Slide from ME to OW!', prompt:'The sound a cat makes!' },
    { emoji:'🚂', word:'CHOO',     syllables:'CH · OO',        tip:'CH is like a sneeze — ch... oo!', prompt:'The sound a train makes!' },
    { emoji:'🐸', word:'RIBBIT',   syllables:'RIB · BIT',      tip:'RIB... bit. Two bouncy parts!', prompt:'The sound a frog makes!' },
    { emoji:'💨', word:'WHOOSH',   syllables:'WH · OOSH',      tip:'Blow air out — whoooosh!', prompt:'The sound the wind makes!' },
  ],
};

const TIPS = {
  animals:  '🐾 Look at the animal picture. Say the word slowly, one sound at a time!',
  colors:   '🎨 Think about what you see that color. Say it clearly!',
  food:     '🍽️ Imagine the taste! Say the food word with a big smile!',
  actions:  '🏃 Try doing the action while you say it — it helps!',
  sounds:   '🔊 Make the sound first, then say the word. Fun!',
};

const ENCOURAGEMENTS_GREAT = ['Wonderful! 🌟','Amazing! 🎉','You nailed it! 🏆','Super star! ⭐','Brilliant! 🎊','Perfect! 💫','Wow, great job! 🥳'];
const ENCOURAGEMENTS_TRY   = ['Keep trying! 💪','Almost there! 🌈','Good effort! Try again! 🤗','You can do it! 🌟','Practice makes perfect! 🎯'];

let currentCat = 'animals';
let currentIndex = 0;
let currentMode = 'practice';
let stars = 0;
let done = new Set();
let recognizing = false;
let recognition = null;

function setMode(mode) {
  currentMode = mode;
  document.querySelectorAll('.mode-btn').forEach(b => b.classList.toggle('active', b.dataset.mode === mode));
  const spellSec = document.getElementById('spellSection');
  const speakBtn = document.getElementById('speakBtn');
  if (mode === 'spell') {
    spellSec.style.display = 'block';
    speakBtn.style.display = 'none';
    document.getElementById('spellInput').value = '';
  } else {
    spellSec.style.display = 'none';
    speakBtn.style.display = 'flex';
  }
  updatePrompt();
}

function setCategory(cat) {
  currentCat = cat;
  currentIndex = 0;
  done.clear();
  document.querySelectorAll('.tab-btn').forEach(b => b.classList.toggle('active', b.dataset.cat === cat));
  document.getElementById('tipBox').innerHTML = `💡 <strong>Tip:</strong> ${TIPS[cat]}`;
  updateCard(true);
  updateProgress();
}

function getWords() { return WORDS[currentCat]; }

function updateCard(animate = true) {
  const words = getWords();
  const item = words[currentIndex];
  if (animate) {
    const emoji = document.getElementById('wordEmoji');
    emoji.style.animation = 'none';
    emoji.offsetHeight; // reflow
    emoji.style.animation = 'emojipop 0.5s var(--bounce)';
    const label = document.getElementById('wordLabel');
    label.style.animation = 'none'; label.offsetHeight;
    label.style.animation = 'wordin 0.4s ease';
  }
  document.getElementById('wordEmoji').textContent = item.emoji;
  document.getElementById('wordLabel').textContent = item.word;
  document.getElementById('wordSyllables').textContent = item.syllables;
  document.getElementById('tipBox').innerHTML = `💡 <strong>Tip:</strong> ${item.tip}`;
  clearFeedback();
  updatePrompt();
  if (currentMode === 'spell') {
    document.getElementById('spellInput').value = '';
    document.getElementById('spellInput').style.borderColor = '#e0e0e0';
  }
}

function updatePrompt() {
  const words = getWords();
  const item = words[currentIndex];
  let prompt = '';
  if (currentMode === 'listen') prompt = '👂 Press 🔊 Hear It, then try saying it!';
  else if (currentMode === 'spell') prompt = `✏️ ${item.prompt} Type the word!`;
  else prompt = `🗣️ ${item.prompt}`;
  document.getElementById('wordPrompt').textContent = prompt;
}

function prevWord() {
  const words = getWords();
  currentIndex = (currentIndex - 1 + words.length) % words.length;
  updateCard();
}
function nextWord() {
  const words = getWords();
  currentIndex = (currentIndex + 1) % words.length;
  updateCard();
}

function speakWord() {
  const words = getWords();
  const item = words[currentIndex];
  const utter = new SpeechSynthesisUtterance(item.word);
  utter.rate = 0.75;
  utter.pitch = 1.1;
  window.speechSynthesis.speak(utter);
  showFeedback(`Listening... Say it like that! 🔊`, 'info');
}

function updateProgress() {
  const words = getWords();
  const pct = Math.round((done.size / words.length) * 100);
  document.getElementById('progressFill').style.width = pct + '%';
  document.getElementById('progressLabel').textContent = `${done.size} of ${words.length} done`;
}

function addStar() {
  stars = Math.min(5, stars + 1);
  const starEls = document.querySelectorAll('.star');
  starEls.forEach((s, i) => s.classList.toggle('lit', i < stars));
}

function clearFeedback() {
  const msg = document.getElementById('feedbackMsg');
  const box = document.getElementById('transcriptBox');
  msg.classList.remove('show','great','try','info');
  box.classList.remove('show');
}

function showFeedback(text, type = 'great') {
  const msg = document.getElementById('feedbackMsg');
  msg.textContent = text;
  msg.className = `feedback-msg show ${type}`;
}

function showTranscript(text) {
  const box = document.getElementById('transcriptBox');
  box.textContent = `You said: "${text}"`;
  box.classList.add('show');
}

function celebrate() {
  const colors = ['#ff6b6b','#ffe66d','#4ecdc4','#a29bfe','#fd79a8','#55efc4','#ffeaa7'];
  const burst = document.getElementById('confetti');
  burst.innerHTML = '';
  for (let i = 0; i < 50; i++) {
    const c = document.createElement('div');
    c.className = 'confetto';
    c.style.cssText = `left:${Math.random()*100}%;top:${-10+Math.random()*20}px;background:${colors[Math.floor(Math.random()*colors.length)]};animation-delay:${Math.random()*0.5}s;animation-duration:${0.9+Math.random()*0.5}s;transform:rotate(${Math.random()*360}deg);border-radius:${Math.random()>0.5?'50%':'2px'}`;
    burst.appendChild(c);
  }
  setTimeout(() => burst.innerHTML = '', 2000);
}

function startListening() {
  if (!('webkitSpeechRecognition' in window) && !('SpeechRecognition' in window)) {
    showFeedback('🎤 Speech not available in this browser. Try saying the word aloud and press Next!', 'info');
    return;
  }

  if (recognizing) {
    recognition && recognition.stop();
    return;
  }

  const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
  recognition = new SpeechRecognition();
  recognition.lang = 'en-US';
  recognition.interimResults = false;
  recognition.maxAlternatives = 5;

  const btn = document.getElementById('speakBtn');
  const wave = document.getElementById('waveform');

  recognition.onstart = () => {
    recognizing = true;
    btn.textContent = '⏹ Listening...';
    btn.classList.add('listening');
    wave.classList.add('active');
    showFeedback('🎤 Go ahead... say the word!', 'info');
  };

  recognition.onend = () => {
    recognizing = false;
    btn.innerHTML = '🎤 Try It!';
    btn.classList.remove('listening');
    wave.classList.remove('active');
  };

  recognition.onresult = (e) => {
    const words = getWords();
    const target = words[currentIndex].word.toLowerCase();
    let heard = '';
    let matched = false;

    for (let i = 0; i < e.results[0].length; i++) {
      const alt = e.results[0][i].transcript.trim().toLowerCase();
      if (alt === target || alt.includes(target) || target.includes(alt)) {
        matched = true;
        heard = alt;
        break;
      }
      if (i === 0) heard = alt;
    }

    showTranscript(heard);

    if (matched) {
      const msg = ENCOURAGEMENTS_GREAT[Math.floor(Math.random()*ENCOURAGEMENTS_GREAT.length)];
      showFeedback(msg, 'great');
      if (!done.has(currentIndex)) {
        done.add(currentIndex);
        addStar();
        celebrate();
        updateProgress();
      }
      setTimeout(() => nextWord(), 1600);
    } else {
      const msg = ENCOURAGEMENTS_TRY[Math.floor(Math.random()*ENCOURAGEMENTS_TRY.length)];
      showFeedback(msg, 'try');
    }
  };

  recognition.onerror = (e) => {
    showFeedback('Could not hear you clearly. Try again! 🎤', 'try');
  };

  recognition.start();
}

function checkSpelling() {
  const words = getWords();
  const target = words[currentIndex].word.toLowerCase();
  const input = document.getElementById('spellInput');
  const val = input.value.trim().toLowerCase();

  if (val === target) {
    input.style.borderColor = 'var(--mint)';
    showFeedback('Perfect spelling! 🌟', 'great');
    if (!done.has(currentIndex)) {
      done.add(currentIndex);
      addStar();
      celebrate();
      updateProgress();
    }
    setTimeout(() => nextWord(), 1400);
  } else if (target.startsWith(val) && val.length > 0) {
    input.style.borderColor = 'var(--sunshine)';
    showFeedback('Keep going... you\'re on the right track! ✏️', 'info');
  } else if (val.length >= target.length) {
    input.style.borderColor = 'var(--coral)';
    showFeedback('Not quite! Try again 💪', 'try');
  } else {
    input.style.borderColor = '#e0e0e0';
    clearFeedback();
  }
}

// Init
updateCard(false);
updateProgress();
</script>
</body>
</html>
