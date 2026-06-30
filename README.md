![WKT12 Penguin](https://img.shields.io/badge/WKT12-Penguin-000000?style=for-the-badge&logo=linux&logoColor=white)
![WKT12.tech](https://img.shields.io/badge/WKT12.tech-Build_Defend_Automate-0a0a0a?style=for-the-badge&logo=linux&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-OSINT-red?style=for-the-badge)


# 👋 Hi, I'm Frank Francis
### 🛡️ Cybersecurity Practitioner • Python Developer • Threat Intelligence • SOC Engineering
    
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=1200&color=00FF41&center=true&vCenter=true&width=900&lines=Welcome+to+my+GitHub!;Cybersecurity+Focus;Detection+Engineering;Python+Automation;Threat+Intelligence;" alt="Typing SVG"/>
<img src="https://komarev.com/ghpvc/?username=wkt21&label=Profile%20Views&color=0e75b6&style=flat"/>
</div>

### Languages
<p>
<img src="https://skillicons.dev/icons?i=python,bash,powershell"/>
</p>

### Operating Systems
<p>
<img src="https://skillicons.dev/icons?i=linux,ubuntu,windows"/>
</p>

### Development
<p>
<img src="https://skillicons.dev/icons?i=docker,git,github,vscode"/>
</p>

---

# 🖥️ FEDS Terminal Simulation

```python
import logging
from datetime import datetime

logging.basicConfig(
    level=logging.INFO,
    format="[%(asctime)s] [FEDS] %(levelname)s — %(message)s",
)

class FedsMonitor:
    """
    FEDS (Noun):
        those friendly government folks who really, really care about:
            - your tax returns,
            - your internet history,
            - and probably what you had for breakfast.
    """

    def __init__(self, subject: str):
        self.subject = subject
        logging.info(f"Surveillance initialized for: {self.subject}")

    def log_tax_return(self, year: int):
        logging.info(f"Reviewing tax return for {year}")
        return {"year": year, "status": "under enhanced curiosity"}

    def log_internet_history(self):
        logging.warning("Internet history audit triggered")
        return [
            "search: 'how to disappear online'",
            "14 tabs of stackoverflow.com",
            "1 suspiciously long YouTube rabbit hole",
        ]

    def log_breakfast(self, menu: str):
        logging.debug(f"Breakfast recorded: {menu}")
        if "avocado toast" in menu.lower():
            logging.error("Breakfast flagged as 'trend‑risk'")
        return {"menu": menu, "timestamp": datetime.utcnow().isoformat()}

if __name__ == "__main__":
    monitor = FedsMonitor(subject="wkt21")
    monitor.log_tax_return(2025)
    monitor.log_internet_history()
    monitor.log_breakfast("Black coffee, eggs, avocado toast")

