# Development Practices

This guide outlines the development expectations for technical submissions at Edge. It exists to help you succeed. Clean code, thoughtful design, and attention to detail are not just preferences. They are how we work. The closer you align with these standards, the easier it is to see you thrive in our environment.

## ✅ Core Expectations

We want to see that you:

* **Use GitHub to share your submission**
* **Write clean, modular, readable code**
* **Include a README** with:
  * Setup instructions
  * Summary of your architecture and design decisions
  * Notes on tradeoffs or incomplete areas, and what you'd improve next
* **Show your thinking**, not just your output

Good developers explain. Great developers document and justify.

## 📁 Repository Setup

Use a public GitHub repository for your submission. Organize it clearly, and treat it like you would any serious project:

* Use sensible naming conventions
* Split large files into modules where applicable
* Avoid committing generated files or node\_modules
* Include `.gitignore`

## 📘 Documentation Matters

We expect to see a `README.md` with:

* **Project overview**
* **Installation and running instructions**
* **Design and architecture notes**
* **Known limitations** and how you would address them
* **Bonus points:** diagrams or visual explanations of your system

If something is rough or unfinished, that is fine. Just explain what is missing and how you would approach it.

## 🎯 Bonus Points

There are things you can do to make your application stand out:

* Include documentation beyond the basics
* Add diagrams to illustrate architecture or flow
* Provide a demo

Even for non-web applications, demos help. A screen recording of the system running, terminal logs from a process, or any evidence of a working pipeline adds value. Help us understand what your project does without having to run it ourselves.

## 🧾 Commit Practices

We use structured, semantic Git commit messages.

### Prefixes

Use one of the following:

* `feat:` – new feature
* `fix:` – bug fix
* `docs:` – documentation only
* `chore:` – tooling or repo maintenance
* `refactor:` – code change that does not fix a bug or add a feature
* `test:` – test-related changes
* `wip:` – work in progress

### Format

* Use lowercase, **imperative** language
* Keep commits **atomic**: one commit per logical change

#### Examples

✅ Good:

* `feat: add retry logic to job worker`
* `fix: resolve race condition in job queue`
* `docs: add architecture diagram to readme`

❌ Bad:

* `updated stuff`
* `final commit`
* `fixed bugs and added feature`

## 🤖 Use of AI

Edge is an AI-positive company. We use AI in our daily workflows and encourage applicants to do the same. AI can be a powerful partner, but it must be used thoughtfully.

* **Use AI to help you work better**, not to work for you
* Understand and own your code. Do not blindly accept AI output
* If you use AI to assist with implementation or documentation, that is great. Just make sure you understand every line

We will ask questions about your choices, your code, and your architecture. If your submission feels AI-generated and you cannot explain it, we will know.

### TL;DR:

Use AI like a co-pilot, not an autopilot. We are hiring you, not ChatGPT.

---

Thanks for taking the time to read this. We're looking forward to what you build.
