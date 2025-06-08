#### Hello, World! 👋
```python
class Introduction():
    def __init__(self):
        self._personal_info()
        self._skills()
        self._achievements()

    def _personal_info(self):
        self.age = 24
        self.job = "student_in_KNU"

    def _skills(self):
        self.tech_stack = ["Python", "Kali Linux", "Docker"]
        self.current_interests = ["AWS",
                                   "JavaScript",
                                   "Express",
                                   "Information Security Engineer Certificate"]

    def _achievements(self):
        self.experience = ["Socializer", "knu-notice", "Tocky"]
        self.certifications = ["Information Processing Engineer Certificate",
                               "Computer Specialist in Spreadsheet & Database Level-1"]

if __name__=="__main__":
    Wonjun_Yang = Introduction()
```
