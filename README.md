
👋 Hi, I’m Frank Francis

🛡️ Cybersecurity Practitioner • Python Developer • Threat Intelligence • SOC Engineering

![WKT12.tech](https://img.shields.io/badge/WKT12.tech-Build_Defend_Automate-0a0a0a?style=for-the-badge&logo=linux&logoColor=white)


Languages



Operating Systems



Development



logging.basicConfig( level=logging.INFO, format=”[%(asctime)s] [FEDS] %(levelname)s — %(message)s”, )

class FedsMonitor: “”” FEDS (Noun): those friendly government folks who really, really care about: - your tax returns, - your internet history, - and probably what you had for breakfast. “””

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


if name == “main”: monitor = FedsMonitor(subject=“wkt21”) monitor.log_tax_return(2025) monitor.log_internet_history() monitor.log_breakfast(“Black coffee, eggs, avocado toast”)

Description

This episode explores practical cyber operations, defensive strategies, and building repeatable workflows for security teams.

Topics

• SOC Operations
• Detection Engineering
• Threat Intelligence
• Incident Response
• Python Automation


Resources

• WKT12.tech
• Related GitHub projects


🎙️ Spotify Episodes

• Spotify Podcast RSS Feed




• Episode 1: WKT12 Cyber Operations Manual
• Episode 2: THE ART IN VULNERABILITY
• Episode 3: Cybersecurity’s Architect
• Episode 4: Elite Critical Thinking
• Episode 5: End Point Security




---

👕 WKT12 Merch



Exclusive Cybersecurity Apparel by WKT12

Check out our themed collection designed for cybersecurity professionals and enthusiasts!



Building WKT while building_wkt(): Limited Edition



All designs feature premium quality and are available now! 🔐



---

📊 GitHub Statistics



---

🔥 GitHub Streak



---

📈 Contribution Graph



🤝 Connect



---



⭐ Thanks for visiting!

If you enjoy cybersecurity, automation, or Python, feel free to explore my repositories, open an issue, or collaborate on a project. Build • Learn • Share • Improve
