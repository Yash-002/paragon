# Paragon

**Your Standard for Security. A Private, Minimalistic Methodology-Driven Notebook for Pentesters and Bug Bounty Hunters.**

Paragon is a minimal, modern desktop application built for one purpose: to bring structure and discipline to the chaotic process of security research. It's an accountability partner that helps you follow a plan, document your work meticulously, and keep your focus sharp.

 ![image](https://github.com/user-attachments/assets/9ae1434b-88e1-4f59-aa51-61b6cdb1bea1)


---

## The Philosophy: The Graveyard of `notes.txt`

We've all been there. It's 2 AM. Your desktop is a digital crime scene of terminal windows, and your `notes.txt` file is a graveyard of good intentions. A brilliant lead you found hours ago is now lost, buried under a mountain of IPs, cURL commands, and random thoughts.

This is **Methodology Debt**. It leads to missed steps, lost findings, and burnout.

Paragon was built to solve this. It's not another cloud platform. It's not another feature-bloated suite. It is a sharp, focused tool designed to do one thing well: help you execute a professional-grade security test from start to finish. This is still an **MVP** stage, so there are some limitations, and shortcomings. Your feedback is most welcome.

## Core Features

*   **Methodology-First Workflow:** Start every hunt with a structured plan. The entire UI is built around a central checklist, ensuring every note and finding is contextual and organized by default.
*   **The Pentester's Bible, Built-In:** The default template is the **TBHMv4 (The Bug Hunter's Methodology v4)** and conference talks, curated from the legendary work of Jason Haddix. It provides a world-class road map for both beginners and veterans.
*   **Focused, Contextual Note-Taking:** Clicking on a methodology step filters your workbench to show *only* the notes relevant to that task. No more context switching.
*   **Clean, Minimal Interface:** A calm, clutter-free environment designed for deep work, available in both light and dark modes.

## Your Data is Yours. Period. (The Privacy Promise)

This is not a feature; it's a fundamental principle.

*   **Absolutely No Analytics or Tracking:** Paragon contains **zero** analytics, tracking pixels, or telemetry of any kind. It doesn't "phone home." It doesn't care who you are or how you use it. We will never collect your data.
*   **100% Offline & Local:** The application runs entirely on your machine. No cloud account is needed. No internet connection is required after installation.
*   **You Own Your Work:** Your entire project—notes, progress, and all—is yours to control.

## How Data Persistence Works (Important MVP Note!)

Paragon uses a simple, transparent, and powerful data model.

*   **It Only Supports YAML:** The single source of truth for your project is a human-readable `.yaml` file.
*   **Data is Ephemeral by Default:** Your work lives in memory during a session. **If you close the app or reload, your current unsaved progress will be lost.**
*   **Save to Persist:** The **only way to retain your work** between sessions is to use the **`Save`** or **`Save As...`** function to export your current state to a `.yaml` file. To resume, you simply **`Open`** that file.

This model was chosen deliberately for the MVP to maximize user privacy and data portability.

## Collaboration Through Control

While Paragon is designed for the solo hunter, collaboration is simple and secure. Because your entire project is a single `.yaml` file, you can:

*   **Share your hunt:** Send your `project.yaml` file to a trusted colleague. They can open it in their instance of Paragon and see your exact progress and notes.
*   **Version control your work:** Commit your YAML files to a private Git repository to track your changes over time.

You control who sees your work, always.

## Getting Started

1.  Download the latest release for your OS from the [Releases](https://github.com/payloadartist/paragon/releases) page. 
2.  Unzip, and open the application in any browser (tested on Chrome).
3.  Click `+ New` to start a new project with the default TBHM methodology.
4.  Work through the checklist, taking notes in the workbench.
5.  When you're done for the session, click `Save` to export your progress to a `.yaml` file.

## Contributing

Paragon is a tool for the community. Bug reports, feature requests, and pull requests are all welcome. Please check out the `CONTRIBUTING.md` file for more details on how to get involved.

---

*This tool is inspired by the invaluable contributions of the security community, especially the methodologies shared by professionals like Jason Haddix. It aims to give back by providing a free, private, and powerful tool to help the next generation of hunters succeed.*
