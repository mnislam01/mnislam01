<h1 align="center">Md Nazrul Islam</h1>

## HI 👋
I am **Nazrul**, a passionate **Software Engineer** working at **Binate Solutions** specializing in **Python**, **Django**, **Flask**, **FastAPI**, **Rest Framework**, **Postgres**, **Redis**, **Kubernetes**, **AWS** and **DigitalOcean**.

```python
class Bio:
    def __init__(self):
        self.streangth = "Backend Engineer and DevOps"
        self.currently_working = "Senior Software Engineer I @Binate Solutions."
        self.currently_learning = "AI, Golang, Rust, MongoDB, Redis, K8s, GCP, NextJS"
        self.ask_me_about = self.get_skills()
        self.contact = "mnazrul.c@gmail.com"

    def get_skills(self):
        skills_set = ("Python", "Django", "DRF", "Flask", "FastAPI", "Docker", 
                      "Postgresql", "Redis", "Elasticsearch", "CI/CD", "Design patterns", 
                      "Software Architecture", "Algorithms", "Data Structures")
        return f"{', '.join(skills_set)}"

    def __str__(self):
        return f"⚡ Quick bio: {self.streangth}\n" \
               f"🔭 I’m currently working as: {self.currently_working}\n" \
               f"🌱 I’m currently learning: {self.currently_learning}\n" \
               f"👯 I’m looking to collaborate on: {self.ask_me_about}\n" \
               f"📫 How to reach me: {self.contact}\n" \
               f"⚡ Fun fact: I love to play Chess."


def main():
    print(Bio())

if __name__ == "__main__":
    main()

```

<p align="center"><img src="https://profile-counter.glitch.me/{mnislam01}/count.svg" alt="AnhellO :: Visitor's Count" /></p>
