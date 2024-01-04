```python
from dataclasses import dataclass


@dataclass
class Profile:
    name = "edaucohe"
    role = "Python developer"
    preferred_technology = "Python"
    working_on = ["gui", "voice_recognition", "api"]
    interests = ["web development", "TDD", "ci/cd"]
    language_spoken = ["es_MX", "fr_FR", "en_US"]
    hobbies = ["piano", "boardgames", "read", "football"]

    def say_hi(self):
        print(f"Hi! I'm {self.name} and welcome to my GitHub profile! "
              f"I hope you find my work useful and interesting.")


edaucohe = Profile()
edaucohe.say_hi()
```
