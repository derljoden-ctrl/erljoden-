<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Understanding Acceleration</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#f4f9ff;
    color:#222;
    line-height:1.6;
}

header{
    background:linear-gradient(135deg,#0077ff,#00bfff);
    color:white;
    padding:40px 20px;
    text-align:center;
}

header h1{
    font-size:3rem;
}

header p{
    margin-top:10px;
    font-size:1.2rem;
}

nav{
    background:#003366;
    padding:15px;
    position:sticky;
    top:0;
    z-index:1000;
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
    flex-wrap:wrap;
}

nav ul li{
    margin:10px 15px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
}

nav ul li a:hover{
    color:#00ccff;
}

section{
    padding:50px 10%;
}

section h2{
    color:#0077ff;
    margin-bottom:20px;
    font-size:2rem;
}

.card{
    background:white;
    padding:25px;
    border-radius:12px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    margin-bottom:25px;
}

.formula{
    background:#eaf4ff;
    padding:15px;
    border-left:5px solid #0077ff;
    font-size:1.3rem;
    margin:15px 0;
}

ul{
    margin-left:20px;
}

.quiz{
    background:#ffffff;
    padding:20px;
    border-radius:10px;
    margin-top:20px;
}

button{
    background:#0077ff;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:8px;
    cursor:pointer;
    margin-top:15px;
    font-size:1rem;
}

button:hover{
    background:#0056b3;
}

footer{
    background:#003366;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}

.hero-image{
    width:100%;
    max-width:700px;
    margin-top:20px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

.activity-box{
    background:#f0f8ff;
    padding:20px;
    border-radius:10px;
    margin-top:20px;
}

.reference{
    margin-top:10px;
}

@media(max-width:768px){
    header h1{
        font-size:2rem;
    }

    section{
        padding:30px 5%;
    }
}
</style>
</head>

<body>

<header>
    <h1>Understanding Acceleration</h1>
    <p>The Science of Motion and Change in Velocity</p>

    <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70"
    class="hero-image" alt="Car acceleration">
</header>

<nav>
    <ul>
        <li><a href="#intro">Introduction</a></li>
        <li><a href="#types">Types</a></li>
        <li><a href="#formula">Formula</a></li>
        <li><a href="#examples">Examples</a></li>
        <li><a href="#applications">Applications</a></li>
        <li><a href="#quiz">Quiz</a></li>
        <li><a href="#references">References</a></li>
    </ul>
</nav>

<section id="intro">
    <h2>Introduction to Acceleration</h2>

    <div class="card">
        <p>
            Acceleration is the rate at which an object changes its velocity over time.
            Velocity includes both speed and direction. An object accelerates whenever
            it speeds up, slows down, or changes direction.
        </p>

        <br>

        <h3>Real-Life Examples</h3>
        <ul>
            <li>A car speeding up on a highway</li>
            <li>A bicycle slowing down using brakes</li>
            <li>A falling apple due to gravity</li>
            <li>A roller coaster moving around curves</li>
        </ul>
    </div>
</section>

<section id="formula">
    <h2>Acceleration Formula</h2>

    <div class="card">
        <div class="formula">
            a = (vf - vi) / t
        </div>

        <p><strong>Where:</strong></p>

        <ul>
            <li><strong>a</strong> = acceleration</li>
            <li><strong>vf</strong> = final velocity</li>
            <li><strong>vi</strong> = initial velocity</li>
            <li><strong>t</strong> = time</li>
        </ul>

        <br>

        <p>
            The SI unit of acceleration is:
            <strong>meters per second squared (m/s²)</strong>
        </p>
    </div>
</section>

<section id="types">
    <h2>Types of Acceleration</h2>

    <div class="card">
        <h3>1. Positive Acceleration</h3>
        <p>Occurs when speed increases over time.</p>
    </div>

    <div class="card">
        <h3>2. Negative Acceleration (Deceleration)</h3>
        <p>Occurs when speed decreases over time.</p>
    </div>

    <div class="card">
        <h3>3. Uniform Acceleration</h3>
        <p>Acceleration remains constant.</p>
    </div>

    <div class="card">
        <h3>4. Non-Uniform Acceleration</h3>
        <p>Acceleration changes over time.</p>
    </div>
</section>

<section id="examples">
    <h2>Sample Problems</h2>

    <div class="card">
        <h3>Example 1</h3>

        <p>
            A car increases its velocity from 5 m/s to 25 m/s in 4 seconds.
        </p>

        <div class="formula">
            a = (25 - 5) / 4
        </div>

        <p><strong>Answer:</strong> 5 m/s²</p>
    </div>

    <div class="card">
        <h3>Example 2</h3>

        <p>
            A bicycle slows from 18 m/s to 6 m/s in 3 seconds.
        </p>

        <div class="formula">
            a = (6 - 18) / 3
        </div>

        <p><strong>Answer:</strong> -4 m/s²</p>
    </div>
</section>

<section id="applications">
    <h2>Real-Life Applications</h2>

    <div class="card">
        <ul>
            <li><strong>Transportation:</strong> Cars, airplanes, and trains rely on acceleration.</li>
            <li><strong>Sports:</strong> Athletes use acceleration during sprinting and cycling.</li>
            <li><strong>Engineering:</strong> Engineers design safer vehicles using acceleration concepts.</li>
            <li><strong>Space Exploration:</strong> Rockets need massive acceleration to leave Earth.</li>
        </ul>
    </div>
</section>

<section>
    <h2>Interactive Learning Activity</h2>

    <div class="activity-box">
        <p><strong>Identify the type of acceleration:</strong></p>

        <ol>
            <li>A plane taking off</li>
            <li>A parked car</li>
            <li>A slowing train</li>
        </ol>

        <button onclick="showAnswers()">Show Answers</button>

        <p id="answers"></p>
    </div>
</section>

<section id="quiz">
    <h2>Quiz</h2>

    <div class="quiz">
        <h3>1. What is acceleration?</h3>

        <input type="radio" name="q1"> Distance traveled<br>
        <input type="radio" name="q1"> Change in velocity over time<br>
        <input type="radio" name="q1"> Speed only<br>

        <br>

        <h3>2. What is the SI unit of acceleration?</h3>

        <input type="radio" name="q2"> m/s<br>
        <input type="radio" name="q2"> m/s²<br>
        <input type="radio" name="q2"> km/h<br>

        <br>

        <button onclick="alert('Great job! Review your answers with your teacher.')">
            Submit Quiz
        </button>
    </div>
</section>

<section id="references">
    <h2>References</h2>

    <div class="card">

        <p class="reference">
            Halliday, D., Resnick, R., & Walker, J. (2018).
            <i>Fundamentals of Physics</i> (11th ed.). Wiley.
        </p>

        <p class="reference">
            Hewitt, P. G. (2019).
            <i>Conceptual Physics</i> (13th ed.). Pearson Education.
        </p>

        <p class="reference">
            Serway, R. A., & Jewett, J. W. (2018).
            <i>Physics for Scientists and Engineers.</i>
            Cengage Learning.
        </p>

    </div>
</section>

<footer>
    <p>Educational Website About Acceleration | Physics Learning Project</p>
</footer>

<script>
function showAnswers(){
    document.getElementById("answers").innerHTML =
    "<br><strong>Answers:</strong><br>" +
    "1. Positive Acceleration<br>" +
    "2. Zero Acceleration<br>" +
    "3. Negative Acceleration";
}
</script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Understanding Acceleration</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#f4f9ff;
    color:#222;
    line-height:1.6;
}

header{
    background:linear-gradient(135deg,#0077ff,#00bfff);
    color:white;
    padding:40px 20px;
    text-align:center;
}

header h1{
    font-size:3rem;
}

header p{
    margin-top:10px;
    font-size:1.2rem;
}

nav{
    background:#003366;
    padding:15px;
    position:sticky;
    top:0;
    z-index:1000;
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
    flex-wrap:wrap;
}

nav ul li{
    margin:10px 15px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
}

nav ul li a:hover{
    color:#00ccff;
}

section{
    padding:50px 10%;
}

section h2{
    color:#0077ff;
    margin-bottom:20px;
    font-size:2rem;
}

.card{
    background:white;
    padding:25px;
    border-radius:12px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    margin-bottom:25px;
}

.formula{
    background:#eaf4ff;
    padding:15px;
    border-left:5px solid #0077ff;
    font-size:1.3rem;
    margin:15px 0;
}

ul{
    margin-left:20px;
}

.quiz{
    background:#ffffff;
    padding:20px;
    border-radius:10px;
    margin-top:20px;
}

button{
    background:#0077ff;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:8px;
    cursor:pointer;
    margin-top:15px;
    font-size:1rem;
}

button:hover{
    background:#0056b3;
}

footer{
    background:#003366;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}

.hero-image{
    width:100%;
    max-width:700px;
    margin-top:20px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

.activity-box{
    background:#f0f8ff;
    padding:20px;
    border-radius:10px;
    margin-top:20px;
}

.reference{
    margin-top:10px;
}

@media(max-width:768px){
    header h1{
        font-size:2rem;
    }

    section{
        padding:30px 5%;
    }
}
</style>
</head>

<body>

<header>
    <h1>Understanding Acceleration</h1>
    <p>The Science of Motion and Change in Velocity</p>

    <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70"
    class="hero-image" alt="Car acceleration">
</header>

<nav>
    <ul>
        <li><a href="#intro">Introduction</a></li>
        <li><a href="#types">Types</a></li>
        <li><a href="#formula">Formula</a></li>
        <li><a href="#examples">Examples</a></li>
        <li><a href="#applications">Applications</a></li>
        <li><a href="#quiz">Quiz</a></li>
        <li><a href="#references">References</a></li>
    </ul>
</nav>

<section id="intro">
    <h2>Introduction to Acceleration</h2>

    <div class="card">
        <p>
            Acceleration is the rate at which an object changes its velocity over time.
            Velocity includes both speed and direction. An object accelerates whenever
            it speeds up, slows down, or changes direction.
        </p>

        <br>

        <h3>Real-Life Examples</h3>
        <ul>
            <li>A car speeding up on a highway</li>
            <li>A bicycle slowing down using brakes</li>
            <li>A falling apple due to gravity</li>
            <li>A roller coaster moving around curves</li>
        </ul>
    </div>
</section>

<section id="formula">
    <h2>Acceleration Formula</h2>

    <div class="card">
        <div class="formula">
            a = (vf - vi) / t
        </div>

        <p><strong>Where:</strong></p>

        <ul>
            <li><strong>a</strong> = acceleration</li>
            <li><strong>vf</strong> = final velocity</li>
            <li><strong>vi</strong> = initial velocity</li>
            <li><strong>t</strong> = time</li>
        </ul>

        <br>

        <p>
            The SI unit of acceleration is:
            <strong>meters per second squared (m/s²)</strong>
        </p>
    </div>
</section>

<section id="types">
    <h2>Types of Acceleration</h2>

    <div class="card">
        <h3>1. Positive Acceleration</h3>
        <p>Occurs when speed increases over time.</p>
    </div>

    <div class="card">
        <h3>2. Negative Acceleration (Deceleration)</h3>
        <p>Occurs when speed decreases over time.</p>
    </div>

    <div class="card">
        <h3>3. Uniform Acceleration</h3>
        <p>Acceleration remains constant.</p>
    </div>

    <div class="card">
        <h3>4. Non-Uniform Acceleration</h3>
        <p>Acceleration changes over time.</p>
    </div>
</section>

<section id="examples">
    <h2>Sample Problems</h2>

    <div class="card">
        <h3>Example 1</h3>

        <p>
            A car increases its velocity from 5 m/s to 25 m/s in 4 seconds.
        </p>

        <div class="formula">
            a = (25 - 5) / 4
        </div>

        <p><strong>Answer:</strong> 5 m/s²</p>
    </div>

    <div class="card">
        <h3>Example 2</h3>

        <p>
            A bicycle slows from 18 m/s to 6 m/s in 3 seconds.
        </p>

        <div class="formula">
            a = (6 - 18) / 3
        </div>

        <p><strong>Answer:</strong> -4 m/s²</p>
    </div>
</section>

<section id="applications">
    <h2>Real-Life Applications</h2>

    <div class="card">
        <ul>
            <li><strong>Transportation:</strong> Cars, airplanes, and trains rely on acceleration.</li>
            <li><strong>Sports:</strong> Athletes use acceleration during sprinting and cycling.</li>
            <li><strong>Engineering:</strong> Engineers design safer vehicles using acceleration concepts.</li>
            <li><strong>Space Exploration:</strong> Rockets need massive acceleration to leave Earth.</li>
        </ul>
    </div>
</section>

<section>
    <h2>Interactive Learning Activity</h2>

    <div class="activity-box">
        <p><strong>Identify the type of acceleration:</strong></p>

        <ol>
            <li>A plane taking off</li>
            <li>A parked car</li>
            <li>A slowing train</li>
        </ol>

        <button onclick="showAnswers()">Show Answers</button>

        <p id="answers"></p>
    </div>
</section>

<section id="quiz">
    <h2>Quiz</h2>

    <div class="quiz">
        <h3>1. What is acceleration?</h3>

        <input type="radio" name="q1"> Distance traveled<br>
        <input type="radio" name="q1"> Change in velocity over time<br>
        <input type="radio" name="q1"> Speed only<br>

        <br>

        <h3>2. What is the SI unit of acceleration?</h3>

        <input type="radio" name="q2"> m/s<br>
        <input type="radio" name="q2"> m/s²<br>
        <input type="radio" name="q2"> km/h<br>

        <br>

        <button onclick="alert('Great job! Review your answers with your teacher.')">
            Submit Quiz
        </button>
    </div>
</section>

<section id="references">
    <h2>References</h2>

    <div class="card">

        <p class="reference">
            Halliday, D., Resnick, R., & Walker, J. (2018).
            <i>Fundamentals of Physics</i> (11th ed.). Wiley.
        </p>

        <p class="reference">
            Hewitt, P. G. (2019).
            <i>Conceptual Physics</i> (13th ed.). Pearson Education.
        </p>

        <p class="reference">
            Serway, R. A., & Jewett, J. W. (2018).
            <i>Physics for Scientists and Engineers.</i>
            Cengage Learning.
        </p>

    </div>
</section>

<footer>
    <p>Educational Website About Acceleration | Physics Learning Project</p>
</footer>

<script>
function showAnswers(){
    document.getElementById("answers").innerHTML =
    "<br><strong>Answers:</strong><br>" +
    "1. Positive Acceleration<br>" +
    "2. Zero Acceleration<br>" +
    "3. Negative Acceleration";
}
</script>

</body>
</html>
