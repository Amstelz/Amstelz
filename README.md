## Hi, I'm Amstelz 👋

Software Enginner at [Erudite Co., Ltd.](https://erd.ai/meet-the-team)

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareEngineer:

    def __init__(self):
        self.name = "Amstelz"
        self.role = "Software Engineer"
        self.language_spoken = ["english", "thai"]
        self.code = ["Python", "JavaScript", "TypeScript", "Java", "C#"]
        self.tools = [
            "AWS",
            "Docker",
            "PostgreSQL",
            "MySQL",
            "MongoDB",
            "Redis",
            "RabbitMQ",
            "Git",
        ]
        self.experience = "2+ years in backend development"
        self.interests = [
            "Data Structures and Algorithms",
            "Backend Optimization",
            "Tech Innovations",
        ]

    def say_hi(self, language="english"):
        messages = {
            "english": "Thanks for dropping by, hope you find some of my work interesting.",
            "thai": "ขอบคุณที่แวะมา หวังว่าคุณจะสนใจผลงานของผม",
        }

        if language in self.language_spoken:
            print(messages.get(language))
        else:
            print(f"Sorry, I don't speak {language} yet.")

me = SoftwareEngineer()
me.say_hi()
```

I'm always open to collaborating on exciting projects and learning new things. Feel free to reach out! 😊
