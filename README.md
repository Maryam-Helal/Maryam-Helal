<h1 align="center">Hola, Welcome to my Github Profile<img height="40" src="https://emoji.gg/assets/emoji/7333-parrotdance.gif"></h1>
<hr>

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=F7A4B9&size=25&center=true&vCenter=true&width=600&height=100&lines=Iam+Maryam+Helal+;Computer+Science+Student;Software+Engineer+AI+Specialist;Competitive+Programmer;Always+learning+more+every+day">
  </a>
</p>

<p align="center">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeXRibzZieGxkMDJ5MTc4cTRwNWhjbmk3MjgzaTlpb2E5NHlxbXN1dSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/13HgwGsXF0aiGY/giphy.gif" alt="Deep Thinking/Coding">
</p>
<h2>
  <img src="https://media.giphy.com/media/qEqiI3Oq7vBkoE236M/giphy.gif" width="120px" alt="<CODER/> Icon"> About Me
</h2>
  <img align="right" src="https://media.giphy.com/media/UmbybxMJ3sRvKBV5qw/giphy.gif" width="200px">
</picture>

<br><br>
 🏫 Studying at the Faculty of `Computers & Artificial Intelligence` at `South Valley National University`.

 🧑‍🎓 Computer Science & AI Student

 🧑‍💻 Focused on building `Full Stack` and `Software Engineering` projects, with an interest in integrating `AI/ML` solutions.

 🧠 Strong foundational skills in `Algorithms` and `Data Structures (DSA)`. I maintain my skills as a `Competitive Programmer`.

 💻 Active on major CP platforms including:
    `Codeforces` / `LeetCode` / `HackerRank` / `CodeChef`

 ⚙️ Practical experience in **Robotics** and `Engineering` systems design & operation.

 ♟️ Passionate about `Chess` and solving `Logic` & `Brain-Teasing Challenges`.

<br><br>

---

## 🧠 Competitive Programming Profiles

<p align="center">

  <a href="https://codeforces.com/profile/mary_am12">
    <img src="https://img.icons8.com/external-tal-revivo-shadow-tal-revivo/50/000000/external-codeforces-programming-competitions-and-contests-programming-community-logo-shadow-tal-revivo.png"/>
  </a>

  <a href="https://www.hackerrank.com/profile/maryamhelal5555">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" width="50px"/>
  </a>

  <a href="https://leetcode.com/u/maryamhelal1/">
    <img src="https://img.icons8.com/external-tal-revivo-lineal-tal-revivo/50/000000/external-leetcode-online-programming-platform-logo-lineal-tal-revivo.png"/>
  </a>

  <a href="https://www.codechef.com/users/shy_valley_22">
    <img src="https://img.icons8.com/color/50/codechef.png"/>
  </a>

</p>

---

## 🛠️ Languages & Tools

<p align="left">

  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="40" />
  <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" width="40" />
  <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" width="40" />
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="40" />

</p>

---

## 🐍 Contribution Snake Animation

![Snake animation](https://github.com/Maryam-Helal/Maryam-Helal/blob/output/github-contribution-grid-snake.svg)

---

# ⚙️ GitHub Snake Workflow File  
**→ ضيفيه كما هو في:**  
`.github/workflows/snake.yml`

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v3

      - name: Generate Snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: Maryam-Helal
          outputs: dist/snake.svg

      - name: Push Snake Commit
        uses: EndBug/add-and-commit@v9
        with:
          add: 'dist/snake.svg'
          message: "update snake 🐍"
