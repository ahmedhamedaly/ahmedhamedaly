# [![Ahmed Hamed Aly](images/banner.gif)][website]

``` python
import ahmedhamedaly

class AboutMe:

    def __init__(self, name, email, website, linkedin):
        self.name = 'Ahmed Hamed Aly'
        self.email = 'hamedala@tcd.ie'
        self.website = 'https://ahmedhamedaly.com'
        self.linkedin = 'https://linkedin.com/in/ahmedhamedaly'


    def education(self):
        return {
            'course': 'Integrated Computer Science',
            'college': 'Trinity College Dublin',
            'year': [
                3,
                'Junior Sophister'
            ],
            'graduation': 'June 2023',
            'grade': 1.1
        }


    def hobbies(self):
        return [
            'Coding 💻',
            'Swimming 🏊‍♀️',
            'Cooking 👩‍🍳',
            'Gym 💪🏽',
            'Blockchain 📃'
        ]


    def goal(self):
        return 'Contribute to open source projects.'

```

<!--Links-->
[website]: https://ahmedhamedaly.com/
[github]: https://github.com/ahmedhamedaly
[linkedIn]: https://www.linkedin.com/in/ahmedhamedaly/
[Email]: mailto:hamedala@tcd.ie
