#### Hello, World! 👋
```python
class Introduction():
    def __init__(self):
        self._set_personal_info()
        self._set_skills()
        self._set_achievements()

    def _set_personal_info(self):
        self.age = 24
        self.job = "student_in_KNU"

    def _set_skills(self):
        self.tech_stack = ["Python", "Kali Linux", "Docker"]
        self.current_interests = ["AWS",
                                   "JavaScript",
                                   "Express",
                                   "Information Security Engineer Certificate"]

    def _set_achievements(self):
        self.experience = ["Socializer", "knu-notice", "Tocky"]
        self.certifications = ["Information Processing Engineer Certificate",
                               "Computer Specialist in Spreadsheet & Database Level-1"]

if __name__=="__main__":
    Wonjun_Yang = Introduction()
```
