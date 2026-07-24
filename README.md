![Header](1694541972989.jpeg)

from pathlib import Path
from pypandoc import convert_text

md = """# About Me 👨‍💻

## SHYAM SANKAR M
**Associate QA Engineer** | Manual Testing | API Testing | REST Assured | JMeter

Quality Assurance Engineer with **1 year of experience** in manual and automation testing, delivering reliable, high-quality web applications. Experienced in functional, regression, integration, API, and performance testing with a strong focus on software quality and continuous improvement.

## 🎓 Education
- **B.E. Computer Science and Engineering** – Dr. N.G.P Institute of Technology (2021–2025)

## 💼 Experience
### Associate QA Engineer | INVYPRO Pvt. Ltd. *(Nov 2025 – Present)*
**INVYPRO V3 – Retail Supply Chain & POS**
- Functional, regression, and integration testing
- API validation using Postman
- API automation using REST Assured (Java)
- Defect tracking with Jira

**INVYPRO V2 – Retail Supply Chain & POS**
- E2E, smoke, sanity, cross-browser, regression testing
- Performance testing using Apache JMeter

## 🛠️ Technical Skills
- **Programming:** Java
- **Databases:** MySQL, MongoDB
- **Query Language:** SQL
- **Manual Testing:** Functional, Regression, Smoke, Sanity, Integration, E2E, Cross-Browser, Black Box
- **API Testing:** Postman
- **API Automation:** REST Assured (Java)
- **Performance Testing:** Apache JMeter
- **Tools:** Jira, Eclipse IDE, VS Code
- **Version Control:** Git, GitHub
- **Methodologies:** SDLC, STLC, Agile Scrum, Defect Life Cycle

## 🎯 Career Objective
To contribute as a Quality Assurance Engineer by delivering robust, high-quality software through effective testing, automation, and continuous improvement while expanding my expertise in SDET practices.

## 📫 Contact
- 📧 shyamsankar3100@gmail.com
- 📱 +91 63828 44553
- 📍 Coimbatore, Tamil Nadu

Let's connect and build quality software! 🚀
"""
out="/mnt/data/README_UPDATED.md"
Path(out).write_text(md,encoding="utf-8")
print(out)


