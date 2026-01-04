# 👋 Hi there! I'm Maruf  

```py
from typing import List

class PersonMeta(type):
    def __new__(cls, name: str, bases: tuple, dct: dict) -> type:
        dct['summary'] = f"{dct['name']} graduated from {dct['education']} with a {dct['degree']} in {dct['major']}."
        dct['skills'] = ', '.join(dct['expertise'])
        dct['current_work'] = f"Currently, {dct['name']} works as a {dct['current_position']} at {dct['current_company']}, where they {dct['current_role']}."
        dct['additional_info'] = f"{dct['name']} also {dct['additional_activities']}."
        return super().__new__(cls, name, bases, dct)

class Me(metaclass=PersonMeta):
    name: str = "Maruf Bepary"
    education: str = "Royal Holloway University of London"
    degree: str = "First-Class Honours"
    major: str = "BSc Computer Science"
    expertise: List[str] = [
        "Software Engineering",
        "Web Development",
        "Machine Learning",
        "DevOps",
        "Mathematics"
    ]
    current_position: str = "DevOps Engineer"
    current_company: str = "Commerzbank"
    current_role: str = "build backend services and enhance operational workflows"
    additional_activities: str = "contributes to open source, sharing expertise through various initiatives"
```


## ⚙️ Languages

<p align="center">
  <a>
    <img src="https://skillicons.dev/icons?i=py,js,ts,java," />
  </br>
  </br>
    <img src="https://skillicons.dev/icons?i=c,haskell,bash,php,kotlin,scala,r,matlab" />
  </a>
</p>

## 🛠 Tools and Skills

You can view the technologies, skills and tools on my [personal portfolio](https://www.maruf-bepary.com/skills?group=category&hard=false&general=true&soft=true&no-material=true) . You can sort them by language and category too!

## 📊 GitHub Stats

<p align="center">
	<img  src="https://github-readme-streak-stats.herokuapp.com/?user=mbeps&theme=transparent"/>
	<br/>
	<img src="https://github-readme-stats.vercel.app/api?username=mbeps&count_private=true&theme=transparent&show=prs_merged,prs_merged_percentage" />
	<br/>
    <img  src="https://github-readme-stats.vercel.app/api/top-langs/?username=mbeps&hide_progress=true&theme=transparent"/>
</p>

<img src="https://algora.io/og/user/mbeps" />


## 🛠 Projects

[Projects Portfolio](https://www.maruf-bepary.com/projects) - I've been involved in a range of software development projects, covering various domains and technologies. If you're interested, you can explore the gallery, features, tech stack, as well as the repositories and deployed sites for each project.


## 🏅 Certifications

[Professional Certifications](https://www.maruf-bepary.com/certificates) - Dive into my certifications showcasing a commitment to diverse skills and continuous learning. Explore credentials across various domains, view the certification details, and see acknowledgements of my expertise and dedication to professional development.

## 💼 Work Experience & Volunteering

[Professional Experience & Volunteer Work](https://www.maruf-bepary.com/experience) - Browse through my professional and volunteer experiences across various organizations. This section details the roles I've held, my responsibilities, and the tools and technologies I've utilized. You can learn about the diverse skills I've developed throughout my career and see how I've applied them in real-world scenarios.

## 🎓 Education

[Academic Background](https://www.maruf-bepary.com/education) - Discover my educational journey through the courses I've completed at university. This section features a detailed list of modules, projects, and the specific certificate awarded upon completion. You can also explore the technologies, tools, and skills I've mastered during my academic career, contributing to my comprehensive understanding of various technical fields.

## ✍️ Blogs

[Technical Blogs/Articles](https://www.maruf-bepary.com/blogs) - I regularly write technical blogs and articles discussing a variety of technologies, tools, and best practices in the software development field. My blogs aim to contribute to the community by sharing knowledge and sparking interesting discussions.
