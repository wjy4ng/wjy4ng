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
        self.projects = {
            "Socializer": "PC형 1인칭 텍스트 어드벤쳐 게임 팀프로젝트 UI 디자인",
            "knu-notice": "공주대학교 공지사항 알림 서비스",
            "Tocky": "안드로이드 기반 TOTP (Time-based One-Time Password) 관리자 앱"
        }
        self.certifications = ["Information Processing Engineer Certificate",
                               "Computer Specialist in Spreadsheet & Database Level-1"]

if __name__=="__main__":
    Wonjun_Yang = Introduction()
```
