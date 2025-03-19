<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=40&duration=3000&pause=1000&color=6A5ACD&center=true&vCenter=true&random=false&width=600&height=70&lines=%F0%9F%91%8B+Hi%2C+I'm+Aruljothi+N;%F0%9F%92%BB+Python+Developer;%F0%9F%8C%9F+MCA+Student;%F0%9F%9A%80+Open+Source+Enthusiast" alt="Typing SVG" />
</h1>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">
</div>

<img align="right" height="270px" alt="GIF" src="https://camo.githubusercontent.com/61491d59e71fec5c794945fed916a4a682b6c0404fc31f30b08a0d919c558404/68747470733a2f2f696d616765732e73717561726573706163652d63646e2e636f6d2f636f6e74656e742f76312f3537363966633430316236333162616231616464623261622f313534313538303631313632342d5445363451474b524a4738535741495553374e532f6b6531375a77644742546f6464493870446d34386b506f73776c7a6a53564d4d2d53784f703743563539425a772d7a505067646e346a557756634a45315a7657515578776b6d794578676c4e714770304976544a5a616d574c49327a76595748384b332d735f3479737a63703272795449304871544f6161556f68724938504936465879386339505774426c7141566c555335697a7064634958445a71445976707252715a32395077306f2f636f64696e672d667265616b2e676966" />

<p align="left">
  <h2>🧙‍♂️ About Me</h2>
  <p>
    I'm a passionate software developer pursuing my MCA at Gobi Arts and Science College, Gobichettipalayam. My focus is on Python development and creating solutions that make a difference.
  </p>
</p>

<h2>🚀 Current Project: Forum Selection System</h2>

<p>
  I'm currently developing a comprehensive Forum Selection System for co-curricular activities at my college. This platform is designed to:
</p>

- ✅ **Ensure inclusive selection processes** with equal opportunities for all students
- ✅ **Streamline selection** using modern technology and data-driven approaches
- ✅ **Provide real-time feedback** to both administrators and participants
- ✅ **Enable transparent tracking** of the entire selection process
- ✅ **Align with educational values** by promoting fairness and merit-based selection

<p>
  The system employs Python for backend processing, a database for storing participant information, and a user-friendly interface for both administrators and students. Key features include automated scoring, customizable selection criteria, and comprehensive reporting.
</p>

```python
class ForumSelectionSystem:
    def __init__(self):
        self.participants = []
        self.criteria = {
            "academic": 0.3,
            "extracurricular": 0.3,
            "interview": 0.25,
            "attendance": 0.15
        }
    
    def add_participant(self, student_id, name, department):
        self.participants.append({
            "id": student_id,
            "name": name,
            "department": department,
            "scores": {},
            "total_score": 0
        })
        return f"Added {name} to the selection process"
    
    def evaluate(self, student_id, criteria_scores):
        for participant in self.participants:
            if participant["id"] == student_id:
                participant["scores"] = criteria_scores
                participant["total_score"] = sum(
                    score * self.criteria[criteria] 
                    for criteria, score in criteria_scores.items()
                )
                return f"Evaluated {participant['name']}, total score: {participant['total_score']:.2f}"
        return "Participant not found"
    
    def get_rankings(self):
        return sorted(
            self.participants, 
            key=lambda x: x["total_score"], 
            reverse=True
        )
```

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">
</div>

<h2 align="center">📊 My GitHub Stats</h2>

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=Aruljo55&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Aruljothi's GitHub Stats" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Aruljo55&theme=tokyonight&hide_border=true" alt="Aruljothi's GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Aruljo55&theme=discord&column=6&no-frame=true&no-bg=true&margin-w=10" alt="GitHub Trophies" />
</div>

<h2 align="center">🛠️ Languages and Tools</h2>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white" alt="Apache" />
  <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white" alt="Canva" />
</div>

<h2 align="center">📚 My Coding Profiles</h2>

<div align="center">
  <a href="https://leetcode.com/u/Aruljothi_55/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="https://www.hackerrank.com/profile/aruljothinanjap1">
    <img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" alt="HackerRank" />
  </a>
  <a href="https://neetcode.io/">
    <img src="https://img.shields.io/badge/NeetCode-D14836?style=for-the-badge&logo=leetcode&logoColor=white" alt="NeetCode" />
  </a>
</div>

<h2 align="center">🌟 Language Usage</h2>

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Aruljo55&theme=tokyonight&hide_border=true&layout=compact" alt="Top Languages" />
</div>

<h2 align="center">📫 Connect With Me</h2>

<div align="center">
  <a href="mailto:aruljothinanjappan12@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/aruljothi-nanjappanutm">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Aruljo55">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

<h2 align="center">✍️ Random Dev Quote</h2>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Aruljo55&style=flat-square&color=6A5ACD" alt="Profile views" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%" />
</div>
