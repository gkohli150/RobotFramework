# RobotFramework with Python-Selenium


---

## 🚀 Features

- 💡 Human-readable Robot Framework syntax
- 🌐 Selenium-based web automation
- ⚙️ Parallel execution with Pabot
- 🧱 Page Object Model for reusability
- 🧪 Headless browser testing support
- 🌍 Configurable environments and variables

---
### Requirements
- robotframework
- robotframework-seleniumlibrary
- robotframework-pabot
- webdriver-manager


## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/robot-framework-project.git
cd robot-framework-project

python -m venv venv
source venv/bin/activate       

Run a Single Test File
robot -d results tests/smoke/login.robot

Run All Tests in Parallel with Pabot
pabot --processes 4 --outputdir results tests/

Run Tests in Headless Mode
robot -v headless:true -d results tests/
```

