<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Little Universe For You 🌙</title>

<style>
:root {
  --night: #050b1b;
  --blue: #14294d;
  --silver: #dce7ff;
  --lavender: #c5b5f0;
  --rose: #fff4f5;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  background:
    radial-gradient(ellipse at top, #172c53 0%, #080f24 48%, #02050e 100%);
  color: var(--silver);
  font-family: Georgia, "Times New Roman", serif;
  text-align: center;
  overflow-x: hidden;
}

#stars {
  position: fixed;
  inset: 0;
  pointer-events: none;
  overflow: hidden;
  z-index: 0;
}

.star {
  position: absolute;
  width: 2px;
  height: 2px;
  border-radius: 50%;
  background: white;
  box-shadow: 0 0 8px #b9d6ff;
  animation: twinkle 3s infinite alternate;
}

@keyframes twinkle {
  from { opacity: .2; }
  to { opacity: 1; }
}

main {
  position: relative;
  z-index: 1;
  width: min(92%, 620px);
  margin: auto;
  padding: 45px 0 60px;
}

h1 {
  font-size: clamp(2rem, 8vw, 3.4rem);
  font-weight: normal;
  color: white;
  text-shadow: 0 0 25px #829fdf66;
}

h2 {
  color: #e3d8ff;
  font-weight: normal;
}

p {
  line-height: 1.9;
}

.moon {
  font-size: 65px;
  filter: drop-shadow(0 0 25px #d6e5ff77);
  animation: float 4s ease-in-out infinite;
}

@keyframes float {
  50% { transform: translateY(-8px); }
}

.card {
  margin: 22px 0;
  padding: 26px 21px;
  border: 1px solid #a7c5ff30;
  border-radius: 22px;
  background: #101c33cc;
  box-shadow: 0 10px 40px #00000025;
  backdrop-filter: blur(8px);
}

button, .song a {
  display: inline-block;
  margin: 7px 4px;
  padding: 12px 18px;
  border: 1px solid #b9caff66;
  border-radius: 30px;
  background: #1c3155;
  color: white;
  font: inherit;
  text-decoration: none;
  cursor: pointer;
  transition: .25s;
}

button:hover, .song a:hover {
  background: #344b76;
  transform: translateY(-2px);
}

.hidden {
  display: none;
}

.rose {
  color: var(--rose);
  font-size: 30px;
}

.lavender {
  color: var(--lavender);
}

.letter {
  text-align: left;
  white-space: pre-line;
}

.song {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 10px;
  text-align: left;
  padding: 9px 0;
  border-bottom: 1px solid #ffffff15;
}

.song a {
  font-size: .85rem;
  padding: 9px 13px;
  flex-shrink: 0;
}

.small {
  font-size: .85rem;
  color: #b5c5e5;
}

#feedback {
  min-height: 50px;
  color: #e8dfff;
  line-height: 1.8;
}

footer {
  margin-top: 40px;
  color: #9eafd0;
  font-size: .85rem;
}
</style>
</head>

<body>

<div id="stars"></div>

<main>

  <!-- OPENING -->
  <section id="opening">
    <div class="moon">☾</div>

    <p class="lavender">✦ 27 OCTOBER ✦</p>

    <!-- CHANGE THIS PLACEHOLDER TO HER NAME -->
    <h1>The One And Only Sorfina</h1>

    <p>
      Happy 16th birthday babe, I love you a lot.
    </p>

    <p class="rose">❀</p>
    <p class="lavender">White roses, lavender, and a little midnight magic.</p>

    <button onclick="enterUniverse()">
      Sorfina ✨
    </button>
  </section>

  <div id="experience" class="hidden">

    <!-- BIRTHDAY LETTER -->
    <section class="card">
      <div class="rose">❀</div>
      <h2>A letter beneath the stars</h2>

      <div class="letter">
        Happy birthday. 💙

        If I could give you one thing today,
        it would be the chance to see yourself
        through the eyes of someone who cares about you.

You see I never thought I would have someone like you ever in my life, all these years I found love to be a foreign subject which is something I could not accomplish, yet life never goes the way you think some events would go. Then a friend invited me to his server out of goodwill or smth it was where I met countless new people and one of them was you, for someone whom I had fun talking with I never expected that it would be the start for me to discover the love of my life.

        I love everything about you, the way you look at me, the way you talk, the way you style, the way you're dedicated to something, your autism, your support, your love , your everything 

       For all Ik if I were there I would have bombarded you with tons of kisses and hugs, well technically I would've banged you too if we lived in Washington 🤩.

       Everyday I look forward talking to you, it's my number one thing, I cannot shake the urge off anytime soon it's just that I love you a lot and I wish you birthday happens to be a great day.

        Happy birthday, Sorfina. 🌙

        I'm glad you're my universe.
      </div>

      <p class="small">
      Some people are shit and some are assholes 
      </p>
    </section>

    <!-- PLAYLIST -->
    <section class="card">
      <h2>🎵 Our little soundtrack</h2>
      <p class="small">
        Five songs for a little midnight listening.
        Tap a song to open it.
      </p>

      <div class="song">
        <span>01. Teach Me How to Love</span>
        <a href="https://www.youtube.com/results?search_query=Teach+Me+How+to+Love"
           target="_blank" rel="noopener">Listen ↗</a>
      </div>

      <div class="song">
        <span>02. Lost in Japan</span>
        <a href="https://www.youtube.com/results?search_query=Lost+in+Japan"
           target="_blank" rel="noopener">Listen ↗</a>
      </div>

      <div class="song">
        <span>03. The Boy Is Mine</span>
        <a href="https://www.youtube.com/results?search_query=The+Boy+Is+Mine"
           target="_blank" rel="noopener">Listen ↗</a>
      </div>

      <div class="song">
        <span>04. Make You Mine</span>
        <a href="https://www.youtube.com/results?search_query=Make+You+Mine"
           target="_blank" rel="noopener">Listen ↗</a>
      </div>

      <div class="song">
        <span>05. Lovefool</span>
        <a href="https://www.youtube.com/results?search_query=Lovefool"
           target="_blank" rel="noopener">Listen ↗</a>
      </div>

      <p class="small">
        The songs open separately, so you can listen
        in your chosen order.
      </p>
    </section>

    <!-- MINI GAME -->
    <section class="card">
      <h2>🎮 A tiny little game</h2>
      <p>Choose the answer that feels most like us.</p>

      <div id="quiz">
        <p id="question"></p>
        <div id="answers"></div>
        <p id="feedback"></p>
      </div>

      <p class="small">
        No grades. No pressure. Just AUTISM 
      </p>
    </section>

    <!-- SURPRISES -->
    <section class="card">
      <h2>🎁 Little things hidden in the night</h2>
      <p>Three stars. Three little messages.</p>

      <button onclick="reveal(1)">🌹 The Rose</button>
      <div id="surprise1" class="hidden">
        <p>
         Beautiful things are obtainable under the worst conditions, even the beautiful looking rose is protected by it's thorns or is simply hard to attain yet you have someone who's like the nightangle unlike the student and the girl who failed to appreciate the meaning.
        </p>
      </div>

      <button onclick="reveal(2)">💜 The Lavender</button>
      <div id="surprise2" class="hidden">
        <p>
          The flower associated with stress busting association, truly the most fragrant flower making me calmer and in peace whenever I'm with you as for the sleep quality? Well the thighs are there but for today it's my chest for you to sleep on peacefully.
        </p>
      </div>

      <button onclick="reveal(3)">🌙 The Moon</button>
      <div id="surprise3" class="hidden">
        <p>
          Your birthday comes around a full moon time, a time where the moon looks the most beautiful, well for me you maintain that state everyday, millions or should I say billions can see this moon but only one can touch it. 
        </p>
      </div>
    </section>

    <!-- FINAL REVEAL -->
    <section class="card">
      <h2>One last thing...</h2>

      <p>
        I love you hehehe I know you've heard this a lot from me but I'll say it to you everyday because I want to, time for some autism now 🤩
      </p>

      <button id="finalButton" onclick="finalReveal()">
        Open your final surprise ✨
      </button>

      <div id="finalMessage" class="hidden">
        <div class="moon">🌙</div>

        <h2>Happy Birthday 💙</h2>

        <p>
          If this little gift made you smile,
          then it did exactly what I wanted it to do. But wait till tonight for the night is still young and I have a lot to spend 
        </p>

        <p class="rose">❀</p>

        <p>
          Here's to another year of you being you my             babygirl
          and to all the lovely little moments
          still waiting to happen especially thigh thursday 🤩😋.
        </p>

        <p class="lavender">With love, always. ✦</p>
      </div>
    </section>

  </div>

  <footer>
    Made under a midnight sky, especially for you. (Actually made under midnight sky) 💙
  </footer>

</main>

<script>
/* CREATE THE STARS */
const starField = document.getElementById("stars");

for (let i = 0; i < 100; i++) {
  const star = document.createElement("div");
  star.className = "star";
  star.style.left = Math.random() * 100 + "%";
  star.style.top = Math.random() * 100 + "%";
  star.style.animationDelay = Math.random() * 3 + "s";
  star.style.animationDuration = (2 + Math.random() * 4) + "s";
  starField.appendChild(star);
}

/* OPEN THE EXPERIENCE */
function enterUniverse() {
  document.getElementById("opening").classList.add("hidden");
  document.getElementById("experience").classList.remove("hidden");
  window.scrollTo({top: 0, behavior: "smooth"});
}

/* SECRET MESSAGE BUTTONS */
function reveal(number) {
  const message = document.getElementById("surprise" + number);
  message.classList.toggle("hidden");
}

/* MINI GAME
   Change the questions and options to match your relationship.
   These are playful example questions, not facts about you.
*/
const questions = [
  {
    text: "Question 1: Which of the following defines your autism the best ?",
    answers: [
      "Doing pep talks in the bathroom",
      "Im going to the Bahamas",
      "Mard aawaz (slowed + reverbed)"
    ],
    correct: 1,
    feedback: "Correct. Everybody thought you were doing pep talk in the bathroom  while you were bathing, but really, you were just engaging in vocal self-stimulation by producing sound waves through the vibration of your vocal cords, while simultaneously utilizing the acoustic properties of ceramic surfaces to create reverberation, resulting in an enhanced auditory feedback loop that stimulated your brain's motivational response system.


  },
  {
    text: "Question 2: Which of the following is the best piece of autism known to mankind?",
    answers: [
     "Oh Samantha whispered in my right ear as she heard it from my hyphen ka second peptide as it came from kriti sanon ka 26th chromosome ka grandchild who is actually an orca named Garry , WHO is also the reincarnation of Julius Ceaser’s last apple",
      "They told my hypothalamus to tell my prefrontal cortex they have been going through son goku MAXIMA MINIMA INTEGRATION training to kill hantavirus by using the ultimate weapon of HENTAI🤩",
      "Naada is inbuilt mechanism by dr br Ambedkar for Ronaldo bc messi kept touching him"
    ],
    correct: 2,
    feedback: "Exactly. The little autism often stay with us forever like how I want to stay with you. 💙"
  },
  {
    text: "Question 3: What is your reward for being a good girl?",
    answers: [
      "A nice freak session where I'll fulfill all your festering desires of freak doing it completely raw",
      " Just cuddling 😔 (with 3 legs)",
      " Tasty food 😋 (it's Goldilocks)"
    ],
    correct: 1,
    feedback: "Congratulations, Your demands shall be fulfilled with my faster and harder services"
  }
];

let questionIndex = 0;

function showQuestion() {
  const q = questions[questionIndex];

  document.getElementById("question").textContent = q.text;

  const answers = document.getElementById("answers");
  answers.innerHTML = "";

  document.getElementById("feedback").textContent = "";

  q.answers.forEach((answer, index) => {
    const button = document.createElement("button");
    button.textContent = answer;

    button.onclick = () => {
      if (index === q.correct) {
        document.getElementById("feedback").textContent = q.feedback;
      } else {
        document.getElementById("feedback").textContent =
          "A respectable attempt. Try again. 🌙";
      }

      if (index === q.correct) {
        answers.innerHTML = "";

        if (questionIndex < questions.length - 1) {
          const next = document.createElement("button");
          next.textContent = "Next question →";

          next.onclick = () => {
            questionIndex++;
            showQuestion();
          };

          answers.appendChild(next);
        } else {
          document.getElementById("feedback").textContent +=
            " You've completed the birthday quest! ✨";
        }
      }
    };

    answers.appendChild(button);
  });
}

showQuestion();

/* FINAL SURPRISE */
function finalReveal() {
  document.getElementById("finalMessage").classList.remove("hidden");
  document.getElementById("finalButton").classList.add("hidden");
  document.getElementById("finalMessage").scrollIntoView({
    behavior: "smooth",
    block: "center"
  });
}
</script>

</body>
</html># Sorfina-s-birthday-hehehe
A special gift for her
