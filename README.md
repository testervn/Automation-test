# ABBank Automation Tests (UI + API)

This repository contains:
- **UI automation tests** using **Selenium WebDriver + TestNG** (Java)
- **API tests** using **Apache JMeter**

---

## 1) Setup Instructions

### Prerequisites
- **Java JDK 21.0.1**
- **Eclipse IDE** (recommended, because the UI test project is prepared to be opened/run in Eclipse)
- **Apache JMeter 5.6.3** (for API tests)

### Project package
The UI automation project is provided as a **ZIP** file which already includes:
- Source code
- Required libraries (`lib`)

### Setup steps
1. **Install Java JDK 21.0.1**
   - Ensure `java -version` shows **21.0.1**
2. **Unzip the project**
   - Extract the ZIP to your preferred folder.
3. **Open the project in Eclipse**
   - Make sure Eclipse is using **JDK 21.0.1**:
     - `Window` → `Preferences` → `Java` → `Installed JREs`
     - Select / add JDK **21.0.1**
   - Import/open the existing project in your workspace:
     - If the project already exists in workspace, just open it.
     - Otherwise: `File` → `Import` → `Existing Projects into Workspace`

### A short video demonstrating the test execution: https://youtu.be/a_rexC8eHRg?si=dLx-uR7V4EnZQIS6
[![Video Title](https://i9.ytimg.com/vi/a_rexC8eHRg/mqdefault.jpg?sqp=COz3wMoG-oaymwEmCMACELQB8quKqQMa8AEB-AHUBoAC4AOKAgwIABABGE8gXChlMA8%3D&rs=AOn4CLA9qVApl1rsZmSXVO_cfQ_wdzLUQA&retry=5)](https://www.youtube.com/watch?v=a_rexC8eHRg)
---

## 2) How to Run UI Tests (Selenium + TestNG)

### Test entry point
Run this file as **TestNG Test**:

`workspace\ABBank_automation\src\Testcases\Flow_AddUser.java`

### Steps
1. In Eclipse, locate the file:

   `ABBank_automation/src/Testcases/Flow_AddUser.java`

2. Right-click the file → **Run As** → **TestNG Test**
3. TestNG will execute the test flow and show results in the Eclipse console/TestNG view.

---

## 3) How to Run API Tests (JMeter)

### Requirements
- **Apache JMeter 5.6.3**
- Test plan file: **`ABBank_github_rest_api.jmx`**

### Steps
1. Open **JMeter 5.6.3**
2. `File` → `Open` → select:

   `ABBank_github_rest_api.jmx`

3. Click **Start** (green play button) to run the test plan
4. View results in the configured listeners inside the test plan (e.g., Summary Report / View Results Tree, if enabled)

### A short video demonstrating the test execution: https://youtu.be/WeGWL1lH9BI?si=EIshvRYJaGQcEn94
[![Video Title](https://i9.ytimg.com/vi/WeGWL1lH9BI/mqdefault.jpg?sqp=COz3wMoG-oaymwEmCMACELQB8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGEogWyhlMA8=&rs=AOn4CLDZizAphSW9dJXoWQR6umsBe2Mnow)](https://www.youtube.com/watch?v=WeGWL1lH9BI)
---

## Notes
- If you encounter issues related to Java compatibility, please verify Eclipse is running and compiling with **JDK 21.0.1**.
- The UI automation ZIP package includes dependencies (`lib`) to simplify setup.



No file chosenNo file chosen
ChatGPT can make mistakes. Check important info. See Cookie Preferences.
