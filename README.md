# Comicoin (Mobile Testing)

[![Manual QA](https://img.shields.io/badge/Testing-Manual%20QA-green?style=flat&logo=checkmarx)](./test_documentation/)
[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android)](https://www.android.com/)
[![English Documentation](https://img.shields.io/badge/Docs-English-blue?style=flat)](./test_documentation/)

## 📌 Project Overview
This project involves a comprehensive quality assurance (QA) research of the **[Comicoin](https://play.google.com/store/apps/details?id=com.currency.comicoin)** mobile application  - an educational platform designed to teach cryptocurrency basics through interactive stories and knowledge tests.

The project showcases expertise in in-depth mobile interface analysis and critical vulnerability detection, alongside proficiency in authoring high-quality QA documentation in professional English.

* **Object under Test:** Full functionality of the Comicoin app (Stories, Tests, Navigation, and UI/UX modules).
* **Main Business Goal:** User conversion via navigation to the partner resource **[dzengi.com](https://dzengi.com)**.

---

## 💻 Test Environment
Testing was performed on a physical device to verify real-world performance, interface responsiveness, and system interaction:

* **Device:** Samsung Galaxy A50
* **OS:** Android 11
* **Screen Resolution:** 1080 x 2340 (FHD+)
* **Aspect Ratio:** 19.5:9

---

## 🗺 App Structure (AppMap)
To visualize the application's architecture and user navigation flow, I created a comprehensive AppMap. This helped in identifying all possible user paths and ensuring full test coverage across all "Universes" and test modules.

[AppMap](./test_documentation/AppMap_Comicoin.png)

---

## 📑 Test Documentation (Manual QA)
The documentation was developed with an emphasis on atomicity and clear verification logic. All documentation is provided in English. The artifacts are located in the `test_documentation` folder:

* **QA Glossary:** Professional industry terminology and project-specific definitions
* [Google Sheets](https://docs.google.com/spreadsheets/d/1KBb3VEokFW2Pk3Aw30ox9EZo5GiXzGjB8VtByAdFNFQ/edit?usp=sharing) (recommended) or [download local XLSX copy](./test_documentation/Glossary_Comicoin.xlsx).
* **Test Cases (Story and Tests):** A suite of positive test cases verifying test logic, in-module navigation, and result scoring accuracy.
* [Google Sheets](https://docs.google.com/spreadsheets/d/1RXzrb94agzs1BjkufsWQ3cceSax6QCII9koMEgMVsCY/edit?usp=sharing) (recommended) or [local PDF copy](./test_documentation/Test_cases_Comicoin.xlsx).
* **Full-App Checklist:** A comprehensive checklist designed for full test coverage and regression testing across all application modules.
* [Google Sheets]() (recommended) or [local PDF copy](./test_documentation/Checklist_Comicoin.pdf).

---

## 🐛 Bug Reports (Selected)
Defects were identified and classified based on their impact on user experience and the **primary business goals of the application**.

* **Bug Reports Registry:** [Google Sheets]() (recommended) or [local PDF copy](./test_documentation/Bug_Reports_ComiCoin.xlsx).

### Key Findings:
1. **🔴 Critical (Security): System Lock Screen Bypass.** A critical vulnerability where the application remains active and interactable on top of the system lock screen (PIN/Biometrics), compromising user data privacy.
2. **🟠 Major (Functional): Burger Menu Interaction Issue.** An intermittent failure of the main menu call. Since the menu is the primary gateway to the target resource `dzengi.com`, this defect **critically obstructs the application's core business conversion goal**.
3. **🟡 Minor (UX/UI): [Start test] button alignment.** Inconsistent button placement on the "Dzengi.com" screen, increasing the risk of accidental taps (misclicks) during story navigation.

---

## 🛠 Methodology & Core Competencies
* **Business-Critical Testing:** Evaluating defects through the lens of business conversion and primary user "Happy Paths."
* **Security & Lifecycle Analysis:** Identifying vulnerabilities related to the Android Activity lifecycle and system interruptions (lock screen behavior).
* **Professional QA English:** Creating and maintaining technical documentation in English using industry-standard terminology and formatting.

---

## 🎯 Key Achievements
* **Analytical Research:** Discovered and localized a critical security flaw involving the application's behavior in a "locked" state.
* **Documentation Quality:** Developed a detailed test case database suitable for integration into professional Agile workflows.
* **UX Strategy:** Identified and justified user experience risks caused by inconsistent UI layout, providing actionable feedback for improvement.
