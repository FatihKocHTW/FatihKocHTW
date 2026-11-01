## Hi, I'm Fatih 👋

Finishing my master's in Business Informatics (M.Sc. Wirtschaftsinformatik) at HTW Berlin.
I like building things end to end: from automating workflows in Python to shipping a full-stack app
with its own deployment. My master's thesis looked at AI-supported decision-making in management.

**Interested in:** software engineering · data & AI · IT management and cloud operations

---

### 🏛️ [Museum Catalog LLM](https://github.com/FatihKocHTW/museum-catalog-llm)

Generates museum catalogue entries from raw inventory exports and object photos with a multimodal LLM,
plus an ablation study comparing text-only and text-plus-image descriptions.

`Python` `pandas` `OpenAI API (vision)` `pytest` `GitHub Actions`

- Links inventory records to photo files via inventory-number parsing
- Rate-limit-aware API client with retries and backoff
- Tested without network access, CI on every push

### 🏋️ Gym Guide · [live app](https://gym-guide-lf.vercel.app)

A mobile-first training companion: follow a workout plan exercise by exercise, log sets,
and look back at past sessions and the progress of each exercise. Installable on the phone as a PWA.

`React` `TypeScript` `Tailwind` `Spring Boot` `Java 21` `MySQL` `Liquibase` `Docker` `Caddy`

- REST API in Spring Boot with JPA, validation and token-based access
- Versioned database schema with Liquibase migrations
- Self-hosted backend on a cloud VM: Docker Compose behind Caddy with automatic HTTPS
- Frontend deployed on Vercel

<sub>Source code is private. Happy to walk through it in a conversation.</sub>

---

### 🤝 Team projects

- **[Tegel im Tausch](https://github.com/MarcelDo01/tegel-tradeoff-modell)** · CityLAB Berlin Summer School 2026<br>
  Physical and data-based model of land-use trade-offs on the former Tegel airport site.<br>
  My part: structured data for the model (starting layout, swap matrix, key figures, sources) and the technical documentation.
- **[Labour market participation analysis](https://github.com/DulalEshmam/Stochastik-Hausarbeit)** · M.Sc. course project, team of three<br>
  Statistical analysis in R of the Mroz dataset. My part: cross-tabulations and the inductive part with hypothesis tests.

---

### 🧰 Tech stack

- **Languages:** Python · Java · TypeScript · SQL · R
- **Data & AI:** pandas · NumPy · scikit-learn · LangChain · OpenAI API
- **Web:** React · Spring Boot · REST APIs
- **Ops & tools:** Docker · Linux · Git & GitHub Actions · Selenium · pytest
