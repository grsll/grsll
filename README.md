# 👋 Hi, I'm Yoga Setyawan Purwanto!

<div align="center">

### 💼 Odoo Developer | 📱 Android Developer | 🎓 SMKN 12 Malang

![Profile Views](https://komarev.com/ghpvc/?username=yogasetyawan&color=blueviolet&style=for-the-badge)

</div>

## 🚀 About Me

🎓 Currently studying at **SMKN 12 Malang**  
💼 Passionate about **Odoo Development** and **Android Development**  
🌱 Always learning and exploring new technologies  
💡 Love turning ideas into reality through code

## 🛠️ Tech Stack

### Odoo Development
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![XML](https://img.shields.io/badge/XML-FF6600?style=for-the-badge&logo=xml&logoColor=white)

### Android & Mobile Development
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

### Tools & Others
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
```python
class Developer:
    def __init__(self):
        self.name = "Yoga Setyawan Purwanto"
        self.school = "SMKN 12 Malang"
        self.role = ["Odoo Developer", "Android Developer"]
        self.location = "Malang, Indonesia"
        self.profile_views = self.get_profile_views()
    
    def get_profile_views(self):
        """Track profile visitors"""
        try:
            with open('profile_views.txt', 'r') as f:
                count = int(f.read())
        except FileNotFoundError:
            count = 0
        
        count += 1
        
        with open('profile_views.txt', 'w') as f:
            f.write(str(count))
        
        return count
    
    def greet(self):
        print(f"Thanks for visiting! You are visitor #{self.profile_views} 👋")
        print("Let's build something amazing together! 🚀")

me = Developer()
me.greet()
```

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yogasetyawan&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yogasetyawan&layout=compact&theme=radical)

</div>

## 📫 Let's Connect!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yoga-setyawan-ab9b98339/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/yog_aaa4/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yoga.setyawan.work@gmail.com)

</div>

---

<div align="center">
    <i>💡 "Code is like humor. When you have to explain it, it's bad." – Cory House</i>
</div>
