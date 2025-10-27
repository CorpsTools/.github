# CorpsTools

![CorpsTools Logo](https://github.com/CorpsTools/.github/raw/main/profile/corps_tools_full.png)

---

## 🪖 Overview

**CorpsTools** is a collection of websites, applications, and digital tools made **by the Corps of Cadets, for the Corps of Cadets**. Our mission is to provide an accessible hub of utilities that assist Cadets in every aspect of their daily lives — academically, physically, and professionally.

This organization serves as both a **development platform** and a **collaboration space** for Cadet-led software projects.


## 💡 Mission

CorpsTools aims to:

* Create a unified platform to **promote Cadet-built projects** across the Corps.
* Foster **collaboration between Cadet clients and Cadet developers** to identify and resolve issues efficiently.
* Establish a system for **implementing and integrating tools** at the Corps-level to improve efficiency and accessibility.

If you have an idea, project, or tool that benefits the Corps — we want to help you make it real.


## ⚙️ Technical Architecture

### Frontend

All CorpsTools applications are **static sites** hosted through **GitHub Pages**. Each project repository contains its own front-end implementation (typically using frameworks like React, Vue, or vanilla HTML/CSS/JS).

### Backend & Data Storage

There are **no dedicated backend servers** for CorpsTools applications. Instead, all dynamic behavior is implemented using **serverless and secure integrations** through:

* **Microsoft SharePoint Lists** — for structured data storage and retrieval.
* **Azure Services** — for limited serverless compute or managed data flows.

This approach ensures that **all Cadet-related data stays within USMA-controlled infrastructure**, adhering to operational and security best practices.

#### Microsoft OAuth Integration

Applications that use **Cadet data** are required to implement **Microsoft OAuth integration** for authentication and data access. This ensures that:

* Only authorized Cadets can access their own data.
* Applications **cannot access any Cadet information at all** — including other Cadets’ data — unless they are properly integrated with Microsoft OAuth.
* Data permissions are fully controlled through **USMA-managed Microsoft accounts**, providing a secure and compliant environment.

### Deployment

Each repository’s codebase can be deployed automatically to GitHub Pages through the organization’s build workflows. These workflows handle:

* Build and test validation
* Static file deployment
* Versioning and release management

## 🤝 Contributing

We encourage all Cadets to contribute to CorpsTools projects! Here’s how you can help:

1. **Submit Issues:** Found a bug or have a feature request? Open an issue on the respective project repo.
2. **Submit Pull Requests:** Improve code, documentation, or design by opening a PR.
3. **Code Reviews:** Reviews are handled by original creators and other interested cadet developers.

**All contributions should follow our standard code review and security practices.**


## 🧭 Joining the Team

Interested in helping out? Here are a few ways to get involved:

* Join the **CorpsTools Software Development Team** — help maintain and develop new tools for the Corps.
* **Publish your own project** — we’ll help you integrate it into the CorpsTools ecosystem.
* **Collaborate or learn** — reach out to learn more about how we develop and deploy tools for Cadets.

📧 Contact: [korbin.deary@westpoint.edu](mailto:korbin.deary@westpoint.edu)


## 🧑‍💻 Maintainers
| CDT Korbin Deary       | CDT Salar Sheriff |
| :---------------:      |  :---:            |
| F1, '26                |           I1, '27 |
| Lead Technical Officer | Software Developer |
| [korbin.deary@westpoint.edu](mailto:korbin.deary@westpoint.edu) | [salar.sheriff@westpoint.edu](mailto:salar.sheriff@westpoint.edu)   |

## 📜 License

All CorpsTools repositories will specify their own license terms. Unless otherwise stated, projects are internal-use tools for the Corps of Cadets and distributed under appropriate USMA guidelines.

---

> *Built by the Corps, for the Corps.*
