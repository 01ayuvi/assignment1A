activity 1

<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>About Me</title>
 <style>
 body {
 font-family: Arial, sans-serif;
 color: black;
 background-color: #c2c0f2;
 margin: 0;
 padding: 0;
 }
 h1 {
 text-align: center;
 color: #2b2b70;
 margin-top: 20px;
 }
 h2 {
 text-align: center;
 font-style: italic;
 color: #4040b2;
 }
 .highlight {
 font-weight: bold;
 color: #706dcd;
 }
 p {
 text-align: justify;
 margin: 20px auto;
 width: 60%;
 }
 img {
 float: left;
 margin: 0 20px 10px 0;
 border-radius: 8px;
 border: 2px solid #706dcd;
 width: 120px;
 height: auto; }
 strong {
 font-weight: bold;
 }
 em {
 font-style: italic;
 }
 </style>
</head>
<body>
 <!-- name as Heading -->
 <h1>Ayuvi Chaudhary</h1>
 <h2>"Aspiring Coder"</h2>
 <!-- Description of Yourself -->
 <p>
 <img src="q1.jpg" alt="My Photo">
 My name is <span class="highlight">Ayuvi Chaudhary</span>. I hail from Delhi, India,
and currently, I am pursuing my B.Tech degree in CSE from VIT Vellore, Tamil Nadu. I am
passionate about <span class="highlight">web development and programming</span>. I
love <strong>solving problems</strong> and creating <strong>beautiful</strong>,
<strong>functional</strong> web applications. I believe <em>learning</em> is a
continuous process, and I always strive to improve my skills.
 </p>
 <p>
 In my free time, I enjoy exploring <span class="highlight">new technologies</span>,
reading books, and engaging in outdoor activities. I am a <span class="highlight">detailoriented</span> person who pays attention to design and functionality, ensuring every
project I create meets user needs.
 </p>
 <p>
 I aim to work as a professional web developer and contribute to innovative projects
that make a difference in people's lives. My strengths include <em>hard work</em>,
<em>dedication</em>, and the <em>ability</em> to adapt to new challenges.
 </p>
</body>
</html>


activity 2
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>List Activity</title>
 <style>
 body {
 font-family: Arial, sans-serif;
 background-color: #eaf1fb;
 color: #333;
 margin: 20px;
 }
 h1 {
 color: #1a5276;
 text-align: center;
 }
 ul, ol {
 margin: 20px;
 }
 li {
 margin: 10px 0;
 }
 </style>
</head>
<body>
 <h1>Activity 2: List Representation</h1>
 <!-- Unordered List for Courses -->
 <h2>1. List of Courses in Winter 2024-2025</h2>
 <ul>
 <li>Design Analysis and algorithm</li>
 <li>Microprocessors and Microcontrollers</li>
 <li>Computer Architecture and Organization</li>
 <li>Quantitative Skills Practice II</li>
 <li>Probability and Statistics</li>
 <li>Theory of Computation</li>
 </ul>
 <!-- Ordered List for Programming Languages and Ratings -->
 <h2>2. Programming Languages and My Ratings</h2>
 <ol>
 <li>Python - 9/10</li>
 <li>Java - 7/10</li>
 <li>C++ - 8/10</li>
 <li>HTML/CSS - 9/10</li>
 <li>JavaScript - 6/10</li>
 </ol>
 <!-- Unordered List with Reviews/Summaries -->
 <h2>3. Reviews of My 3 Favourite Media</h2>
 <ul>
 <li>
 <strong>Movie:</strong> ZINDAGI NA MILEGI DUBARA<br>
 <em> It is a heartwarming tale of friendship, self-discovery, and living life to the
fullest, as three friends embark on a transformative road trip across Spain. </em>
 </li>
 <li>
 <strong>Book:</strong> The Alchemist by Paulo Coelho<br>
 <em>An inspiring journey of self-discovery and chasing dreams.</em>
 </li>
 <li>
 <strong>TV Show:</strong> Gilmore Girls<br>
 <em>An intense drama series with brilliant storytelling and character
development.</em>
 </li>
 </ul>
</body>
</html>


activity 3
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Table Layout</title>
 <style>
 body {
 background-color: lightblue;
 }
 table {
 border-collapse: collapse;
 width: 60%;
 margin: 20px auto;
 }
 td {
 border: 1px solid black;
 text-align: center;
 padding: 10px;
 }
 .shaded {
 background-color: lightgreen; /* Your favorite color */
 }
 .affirmation {
 font-family: Arial, sans-serif;
 color: green;
 font-size: 18px;
 font-style: italic;
 }
 h2 {
 text-align: center;
 font-weight: bold;
 font-size: 24px;
 }
 </style>
</head>
<body>
 <h2>Activity 3</h2>
 <table border="1" cellspacing="0">
 <tr>
 <td colspan="2" rowspan="2" width="120" height="60">
 <img src="cute.jpeg" alt="Image" width="100" height="100">
 </td>
 <td width="60" height="30">r1c3</td>
 <td rowspan="2" width="60" height="60">r1c4</td>
 <td colspan="2" rowspan="2" width="120" height="60">r1c5</td>
 </tr>
 <tr>
 <td rowspan="2" width="60" height="60">
 <a href="mailto:someone@example.com">Email</a>
 </td>

 <td rowspan="2" width="60" height="60">r2c3</td>
 </tr>
 <tr>
 <td colspan="2" width="120" height="30">
 <a href="home.html">Home.html</a>
 </td>
 <td colspan="2" width="120" height="30">r3c4
 <a href="sea.jpeg">
 <img src="sea.jpeg" alt="Image" width="50" height="50">
 </a>
 </td>
 <td width="60" height="30">r3c6</td>
 </tr>
 <tr>
 <td class="shaded" width="60" height="30">r4c1</td>
 <td class="shaded" colspan="2" width="120" height="30">r4c2</td>
 <td rowspan="2" width="60" height="60">r4c4</td>
 <td colspan="2" width="120" height="30">r4c5</td>
 </tr>
 <tr>
 <td rowspan="2" colspan="2" class="shaded" width="120" height="60">r5c1</td>
 <td rowspan="2" width="60" height="60">r5c3</td>
 <td rowspan="2" colspan="2" width="120" height="60">r5c5</td>
 </tr>
 <tr>
 <td class="affirmation" width="60" height="30">Stay positive!</td>
 </tr>
 <tr>
 <td width="60" height="30">r6c4</td>
 <td class="affirmation" colspan="2" width="120" height="30">You are capable of
amazing things!</td>
 <td width="60" height="30">r6c5</td>
 </tr>
 </table>
</body>
</html>
