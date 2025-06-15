# Paragon

**Your Standard for Security. A private, methodology-driven notebook for pentesters and bug bounty hunters.**

Paragon is a minimal, modern web app built to bring structure to the chaos of security research. It's a personal accountability partner that helps you follow a plan, document your work, and stay focused. It can be run locally, and doesn't need a website.

![image](https://github.com/user-attachments/assets/9ae1434b-88e1-4f59-aa51-61b6cdb1bea1)

---

### The Philosophy: The `notes.txt` Graveyard

We've all been there. It's 2 AM, your desktop is a crime scene of terminal windows, and your `notes.txt` file is a graveyard of good intentions. A brilliant lead is now lost, buried under a mountain of IPs, cURL commands, and random thoughts.

This is **Methodology Debt**. It leads to missed steps, lost findings, and burnout.

Paragon was built to solve this. It's not another cloud platform or a bloated suite. It's a sharp, focused tool designed to do one thing well: help you execute a professional-grade security test from start to finish. This is an **MVP**, so there are limitations. Your feedback is welcome.

### Core Features

*   **Methodology-First Workflow:** Start every hunt with a plan. The UI is built around a central checklist, ensuring every note and finding is contextual and organized by default.
*   **A Pro's Playbook, Built-In:** The default template is based on the **TBHMv4 (The Bug Hunter's Methodology v4)**, curated from the legendary work of Jason Haddix. It provides a world-class road map for both beginners and veterans.

![image](https://github.com/user-attachments/assets/4ae02834-f829-48e0-9905-f1433f1f7965)

*   **Focused, Contextual Notes:** Clicking on a methodology step filters your workbench to show *only* the notes for that task. No more context switching.
*   **Clean, Minimal Interface:** A calm, clutter-free environment designed for deep work, available in both light and dark modes.

### Your Data is Yours. Period.

This isn't a feature; it's a promise.

*   **Zero Telemetry:** Paragon contains **no analytics, no tracking, no phoning home.** We don't know who you are, and we don't want to.
*   **100% Offline & Local:** The app runs entirely on your machine. No account or internet connection is required after installation.
*   **You Own Your Work:** Your entire project is yours to control.

### How Data Persistence Works (MVP Note)

Paragon uses a simple, transparent data model.

*   **YAML is the Source of Truth:** Your entire project is stored in a single, human-readable `.yaml` file.

![image](https://github.com/user-attachments/assets/c459b650-4142-424b-82ab-e5cde8bfbd6a)

*   **Data is Ephemeral by Default:** Work lives in memory during a session. **If you close the app without saving, your progress will be lost.**
*   **Save to Persist:** The only way to keep your work is to use **`Save`** to export your current state to a `.yaml` file. To resume, you simply **`Open`** that file.  

This model was chosen for the MVP to guarantee user privacy and data portability.

### Collaboration Through Control

While Paragon is designed for the solo hunter, collaboration is simple. Because your project is a single `.yaml` file, you can:

*   **Share your hunt** by sending the file to a trusted colleague.
*   **Version control your work** in a private Git repository.

You control who sees your work. Always.

### Getting Started

#### Online
- Visit [notes.bugbountyhunting.com](https://notes.bugbountyhunting.com)
- Follow the steps

![image](https://github.com/user-attachments/assets/d2ef5f02-7f3e-4fae-a069-0df997e70284)


#### Host Yourself
1.  Download the latest release for your OS from the [Releases](https://github.com/payloadartist/paragon/releases) page.
2.  Unzip and open the application.
3.  Click `+ New` to start a project with the default TBHM methodology.
4.  Work through the checklist, taking notes in the workbench.
5.  Click `Save` to export your progress to a `.yaml` file when you're done.

## Appearance
- There are two themes that can be toggled via the icon in the top right corner:
    - Light

  ![image](https://github.com/user-attachments/assets/0c3fea62-66e8-4680-a57f-f0b9497fecb2)

    - Dark

  ![image](https://github.com/user-attachments/assets/9ae1434b-88e1-4f59-aa51-61b6cdb1bea1)


### Contributing

Paragon is a tool for the community. Bug reports, feature requests, and pull requests are welcome. Please see `CONTRIBUTING.md` for details.

---

*This tool is inspired by the invaluable work of the security community, especially the methodologies shared by professionals like Jason Haddix. It aims to give back by providing a free, private, and powerful tool to help the next generation of hunters succeed.*
