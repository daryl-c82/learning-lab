# Copilot Instructions for this Repository

## 1. Repository purpose
This repository belongs to **Daryl Chan (daryl-c82)** and serves as a learning and experimentation lab for:
- Software development fundamentals
- AI tooling and applied prompt engineering
- Cloud technologies and backend concepts
- Early prototypes for Journey Inspired’s Digital Travel Concierge platform

Treat this repo as a **learning + prototyping environment**, but aim for clean, readable, maintainable code.

---

## 2. How Copilot should behave
When generating code or explanations:

1. Use clear, modern coding conventions.
2. Include brief comments for non-obvious logic.
3. Default to simple, maintainable patterns.
4. Avoid deprecated methods, outdated libraries, or overengineering.
5. Prioritize readability over cleverness.
6. Suggest improvements and refactoring proactively.
7. Follow security, ethics, and privacy best practices.

---

## 3. Preferred languages and frameworks

Primary languages:
- Python
- JavaScript / TypeScript

Preferred Python tools:
- FastAPI for APIs
- Typer for CLI tools
- Requests for HTTP
- Pandas only when required

Preferred JS/TS tools:
- Node.js
- React with Vite
- Express or Fastify for APIs

---

## 4. Coding conventions

### Python
- Follow **PEP 8**
- Use **type hints**
- Use **f-strings**
- Use `src/` folder structure when relevant
- Use specific exceptions (avoid bare except)

### JavaScript / TypeScript
- Prefer TypeScript
- Use ES modules
- Prefer async/await
- Follow broadly accepted ESLint-style rules

---

## 5. Project structure
Default structure for new learning modules:

```
project-name/
  README.md
  src/
    main.py or main.ts
  tests/
    test_main.py or test_main.ts
  requirements.txt or pyproject.toml
```

Keep it lightweight and beginner-friendly.

---

## 6. Testing expectations

**Python:** pytest  
**JS/TS:** Jest or Vitest

Minimum viable tests:
- One happy-path test
- One failure-case test

---

## 7. Documentation expectations
Copilot should automatically:
- Add docstrings to functions and classes
- Insert comments explaining reasoning
- Update README files with installation + usage
- Provide examples or sample commands

---

## 8. AI & external API handling
- Never hardcode API keys or secrets
- Use `.env` or environment variables
- Include minimal error handling + logging
- Provide mock examples when necessary

---

## 9. Constraints
Copilot should NOT generate:
- Malicious or harmful code  
- Code that violates terms of service  
- Overly complicated abstractions for simple tasks  
- Vendor boilerplate unless explicitly requested  

---

## 10. Example prompt categories for Daryl

Copilot should excel at:

- Explaining code line-by-line  
- Refactoring functions into smaller units  
- Adding type hints and documentation  
- Converting Python <→ JavaScript  
- Creating minimal APIs in FastAPI or Express  
- Building example scripts for learning  
- Suggesting better folder structures  
- Writing tests  

---

These instructions guide Copilot to produce clean, modern, educational code aligned with your learning journey and Journey Inspired’s future engineering work.
