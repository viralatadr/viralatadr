<h1 align="center">Hey there 👋, I'm viralatadr!</h1>
<p align="center">
    <i>Self proclaimed</i> <b>CEO of labpcsupport</b> <i>and</i> <b>Avid Python & C Enjoyer</b>
<br />
<br />
  
```py
from datetime import date

class AboutMe():
    def __init__(self):
        self.username = "viralatadr"
        self.pronouns = ("he", "him")
        self.location = "Dominican Republic"
        self.occupation = "SysAdmin"
        self.birthday = date(day=25, month=2, year=1993)
        self.age = (date.today()-self.birthday).days/365  # 31 y/o
        self.hobbies = ["Coding", "Gaming", "Music", "YouTube"]
        self.interests = ["Programming", "Linux", "Open Source"]
        self.hotel = "Trivago"
        self.breed = "Different"

if __name__ == "__main__":
    me = AboutMe()
```
