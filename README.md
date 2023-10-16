# [![Ahmed Hamed Aly](images/banner.gif)][website]

``` python
import ahmedhamedaly

class AboutMe:

    def __init__(self, name: str, email: str, website: str, linkedin: str):
        self.name = name
        self.email = email
        self.website = website
        self.linkedin = linkedin

    def education(self) -> dict:
        return {
            'course': 'Integrated Computer Science',
            'college': 'Trinity College Dublin',
            'year': 'Graduated',
            'graduation': 'June 2022',
            'grade': 1.1
        }

    def hobbies(self) -> list:
        return [
            'Coding 💻',
            'Swimming 🏊‍♀️',
            'Cooking 👩‍🍳',
            'Climbing 🪨',
            'Gym 💪🏽',
            'Blockchain 📃'
        ]

    def goal(self) -> str:
        return 'Contribute to open source projects.'
```

<!--Links-->
[website]: https://ahmedhamedaly.com/
[github]: https://github.com/ahmedhamedaly
[linkedIn]: https://www.linkedin.com/in/ahmedhamedaly/
[Email]: mailto:hamedala@tcd.ie
