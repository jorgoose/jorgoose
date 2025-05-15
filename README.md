## Hi there 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


# 👇 Full skillset down below in the README, or on my personal website
from logan_profile import full_skillset


class SoftwareEngineer:
    def __init__(self, name, title, years_experience, hobbies):
        self.name = name
        self.title = title
        self.years_experience = years_experience
        self.hobbies = hobbies
        self.skills = full_skillset.preview(top_n=5)

    def introduce(self):
        print(f"👋 Hey, I'm {self.name} — a {self.title} with {self.years_experience}+ years of experience.")
        print("In my free time, I enjoy:")
        for hobby in self.hobbies:
            print(f"  • {hobby}")
        print("\nSome of my go-to tech:")
        for skill in self.skills:
            print(f"  → {skill}")

    def __str__(self):
        return f"{self.name} ({self.title}) — {self.years_experience}+ yrs experience"


if __name__ == "__main__":
    logan = SoftwareEngineer(
        name="Logan Jorgensen",
        title="Software Engineer",
        years_experience=2,
        hobbies=["Weightlifting", "Live music", "Hiking", "Side projects"]
    )

    logan.introduce()

```
```
$ python logan_profile.py
Logan Jorgensen (Software Engineer) — 2+ yrs experience
👋 Hey, I'm Logan Jorgensen — a Software Engineer with 2+ years of experience.
In my free time, I enjoy:
  • Weightlifting
  • Live music
  • Hiking
  • Side projects

Some of my go-to tech:
  → Python
  → Go
  → Rust
  → FastAPI
  → React
```

## Project Stats

<a href="https://github.com/jorgoose/github-readme-stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jorgoose&langs_count=10&hide=jupyter%20notebook,blade,astro,svelte,html,css,cmake&layout=compact&theme=dark&width=300" alt="Top Langs"/>
</a>

## Things I Use

<table>
  <tr>
    <td valign="top">
      <h4>🧠 Languages</h4>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" />
        <img alt="Go" src="https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square&logo=go&logoColor=white" />
        <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white" />
        <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E" />
        <img alt="Dart" src="https://img.shields.io/badge/Dart-%230175C2.svg?style=flat-square&logo=dart&logoColor=white" />
        <img alt="PHP" src="https://img.shields.io/badge/PHP-%23777BB4.svg?style=flat-square&logo=php&logoColor=white" />
        <img alt="Java" src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat-square&logo=openjdk&logoColor=white" />
        <img alt="R" src="https://img.shields.io/badge/R-%23276DC3.svg?style=flat-square&logo=r&logoColor=white" />
      </p>
      <h4>📦 Frameworks</h4>
      <p>
        <img alt="React" src="https://img.shields.io/badge/React-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB" />
        <img alt="Svelte" src="https://img.shields.io/badge/Svelte-%23f1413d.svg?style=flat-square&logo=svelte&logoColor=white" />
        <img alt="Next.js" src="https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white" />
        <img alt="Vue.js" src="https://img.shields.io/badge/Vue.js-%2335495e.svg?style=flat-square&logo=vuedotjs&logoColor=%234FC08D" />
        <img alt="TailwindCSS" src="https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white" />
        <img alt="Express.js" src="https://img.shields.io/badge/Express.js-%23404d59.svg?style=flat-square&logo=express&logoColor=%2361DAFB" />
        <img alt="Laravel" src="https://img.shields.io/badge/Laravel-%23FF2D20.svg?style=flat-square&logo=laravel&logoColor=white" />
        <img alt="Spring" src="https://img.shields.io/badge/Spring-%236DB33F.svg?style=flat-square&logo=spring&logoColor=white" />
        <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi" />
      </p>
    </td>
    <td valign="top">
      <h4>🧠 ML / AI</h4>
      <p>
        <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat-square&logo=PyTorch&logoColor=white" />
        <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat-square&logo=TensorFlow&logoColor=white" />
        <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-%23white.svg?style=flat-square&logo=opencv&logoColor=white" />
      </p>
      <h4>📱 Mobile</h4>
      <p>
        <img alt="Flutter" src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=flat-square&logo=Flutter&logoColor=white" />
        <img alt="Android Studio" src="https://img.shields.io/badge/Android%20Studio-346ac1?style=flat-square&logo=android%20studio&logoColor=white" />
      </p>
      <h4>🗄 Databases</h4>
      <p>
        <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white" />
        <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
        <img alt="Neo4J" src="https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white" />
      </p>
      <h4>☁️ Cloud</h4>
      <p>
        <img alt="AWS" src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white" />
        <img alt="Google Cloud" src="https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?style=flat-square&logo=google-cloud&logoColor=white" />
      </p>
    </td>
  </tr>
</table>


## Currently Exploring
<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-%23000000.svg?style=flat-square&logo=rust&logoColor=white" />
  <img alt="CUDA" src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img alt="GraphQL" src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
  <img alt="Apache Spark" src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img alt="NLP" src="https://img.shields.io/badge/NLP-%2370268E.svg?style=flat-square&logo=ai&logoColor=white" />
</p>

## What I've been listening to
<p align="center">
  <a href="https://open.spotify.com/user/deadmixer">
    <img src="https://spotify-recently-played-readme.vercel.app/api?user=deadmixer" alt="Spotify recently played"/>
  </a>
</p>
