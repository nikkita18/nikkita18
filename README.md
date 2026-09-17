<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                  AURORA / CELESTIAL HEADER BANNER            -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0:0D1117,20:240046,45:5A189A,75:9D4EDD,100:00F5D4&height=250&section=header&text=%E2%9C%A7%20Nikita%20Kumari%20%E2%9C%A7&fontSize=48&fontAlignY=36&animation=twinkling&fontColor=ffffff&desc=Python%20Developer%20%E2%80%A2%20Tech%20Enthusiast%20%E2%80%A2%20Problem%20Solver&descAlignY=58&descAlign=50&descSize=19" width="100%"/>

<!-- ═══════════════════ GLOWING TYPING SVG ═══════════════════ -->
<p align="center">
  <a href="https://github.com/nikkita18">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=21&duration=3000&pause=1000&color=00F5D4&background=1E1E2E00&center=true&vCenter=true&multiline=false&width=620&height=50&lines=%E2%9C%A8+Crafting+intelligent+data-driven+solutions;%F0%9F%90%8D+Python+%2B+Flask+%2B+Data+Analytics;%F0%9F%9A%80+Turning+raw+datasets+into+meaningful+insights;%E2%98%95+Fueled+by+curiosity%2C+clean+code+%26+coffee" alt="Typing SVG" />
  </a>
</p>

<!-- ═══════════════════ QUICK BADGES & VIEWS ═══════════════════ -->
<p align="center">
  <a href="https://www.linkedin.com/in/nikitakumari18" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Nikita_Kumari-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=004182" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/nikkita18" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-nikkita18-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=000000" alt="GitHub"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=nikkita18&label=%E2%9C%A8+Profile+Views&color=9D4EDD&style=for-the-badge" alt="Views"/>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4300-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

</div>

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     PYTHON TERMINAL CARD                        -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<table align="center" width="100%" style="border-collapse: collapse; border: none;">
<tr>
<td width="65%" valign="top" style="border: none;">

### 🐍 `nikita.py` 🔴 🟡 🟢

```python
from dataclasses import dataclass, field
from typing import List

@dataclass
class NikitaKumari:
    """
    Python Developer & Data Analyst passionate about building
    functional web apps, extracting insights & writing elegant code.
    """
    name: str = "Nikita Kumari"
    role: str = "Computer Science Engineer"
    location: str = "India 🇮🇳"
    
    focus_areas: List[str] = field(default_factory=lambda: [
        "Backend Development (Flask, MySQL)",
        "Data Analysis & Visualization (Pandas, NumPy, Matplotlib)",
        "Clean Code & Open-Source Engineering"
    ])
    
    def status(self) -> str:
        return "Building impactful projects & analyzing data 🚀"

    def get_fuel(self) -> List[str]:
        return ["Coffee ☕", "Python 🐍", "Lo-Fi Beats 🎧"]
