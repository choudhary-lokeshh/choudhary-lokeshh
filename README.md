<p align="center"><img src="./assets/header.svg" width="100%" alt="Lokesh Choudhary — Full Stack + AI Engineer" /></p>

<div align="center">

### Full Stack Developer & AI Engineer

**Interfaces that feel good. Backends that connect them. AI that takes action.**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1500&color=55FF99&center=true&vCenter=true&width=700&lines=Full+Stack+Development+%C3%97+AI+Engineering;Multi-Agent+Systems+%2F+LLM+Integrations;React+%E2%86%92+APIs+%E2%86%92+Databases+%E2%86%92+AI" alt="Full stack development, AI engineering, multi-agent systems and LLM integrations" />

[Projects](#selected-builds) &nbsp; / &nbsp; [Tech stack](#engineering-stack) &nbsp; / &nbsp; [AI architecture](#inside-the-ai-system) &nbsp; / &nbsp; [GitHub](https://github.com/choudhary-lokeshh?tab=repositories)

</div>

---

### Beyond the interface

I'm **Lokesh Choudhary**, a **Full Stack Developer & AI Engineer** building across frontend, backend, databases and AI integrations. My projects span React and Next.js interfaces, Node.js services, TypeScript applications and agent-based workflows.

- **Full stack:** web interfaces, REST APIs, authentication and database-backed applications.
- **AI engineering:** specialist agents, prompt design, tool calling, model routing and conversational memory.
- **Across platforms:** web, admin and creator interfaces, plus React Native / Expo mobile development.

<a id="engineering-stack"></a>

### Engineering stack


**FRONTEND**

<p>
<img src="https://img.shields.io/badge/React-101b20?style=flat-square&logoColor=55ff99&logo=react" alt="React" />
<img src="https://img.shields.io/badge/Next.js-101b20?style=flat-square&logoColor=55ff99&logo=nextdotjs" alt="Next.js" />
<img src="https://img.shields.io/badge/TypeScript-101b20?style=flat-square&logoColor=55ff99&logo=typescript" alt="TypeScript" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-101b20?style=flat-square&logoColor=55ff99&logo=tailwindcss" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/Zustand-101b20?style=flat-square&logoColor=55ff99" alt="Zustand" />
<img src="https://img.shields.io/badge/Framer%20Motion-101b20?style=flat-square&logoColor=55ff99&logo=framer" alt="Framer Motion" />
</p>

**BACKEND**

<p>
<img src="https://img.shields.io/badge/Node.js-101b20?style=flat-square&logoColor=55ff99&logo=nodedotjs" alt="Node.js" />
<img src="https://img.shields.io/badge/Express-101b20?style=flat-square&logoColor=55ff99&logo=express" alt="Express" />
<img src="https://img.shields.io/badge/Bun-101b20?style=flat-square&logoColor=55ff99&logo=bun" alt="Bun" />
<img src="https://img.shields.io/badge/Elysia-101b20?style=flat-square&logoColor=55ff99" alt="Elysia" />
<img src="https://img.shields.io/badge/REST%20APIs-101b20?style=flat-square&logoColor=55ff99" alt="REST APIs" />
<img src="https://img.shields.io/badge/JWT-101b20?style=flat-square&logoColor=55ff99&logo=jsonwebtokens" alt="JWT" />
</p>

**DATA & JOBS**

<p>
<img src="https://img.shields.io/badge/MongoDB-101b20?style=flat-square&logoColor=55ff99&logo=mongodb" alt="MongoDB" />
<img src="https://img.shields.io/badge/PostgreSQL-101b20?style=flat-square&logoColor=55ff99&logo=postgresql" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Redis-101b20?style=flat-square&logoColor=55ff99&logo=redis" alt="Redis" />
<img src="https://img.shields.io/badge/Mongoose-101b20?style=flat-square&logoColor=55ff99&logo=mongoose" alt="Mongoose" />
<img src="https://img.shields.io/badge/Drizzle%20ORM-101b20?style=flat-square&logoColor=55ff99&logo=drizzle" alt="Drizzle ORM" />
<img src="https://img.shields.io/badge/BullMQ-101b20?style=flat-square&logoColor=55ff99" alt="BullMQ" />
</p>

**AI ENGINEERING**

<p>
<img src="https://img.shields.io/badge/OpenRouter-101b20?style=flat-square&logoColor=55ff99" alt="OpenRouter" />
<img src="https://img.shields.io/badge/Multi%20Agent%20Systems-101b20?style=flat-square&logoColor=55ff99" alt="Multi Agent Systems" />
<img src="https://img.shields.io/badge/LLM%20Routing-101b20?style=flat-square&logoColor=55ff99" alt="LLM Routing" />
<img src="https://img.shields.io/badge/Tool%20Calling-101b20?style=flat-square&logoColor=55ff99" alt="Tool Calling" />
<img src="https://img.shields.io/badge/Prompt%20Engineering-101b20?style=flat-square&logoColor=55ff99" alt="Prompt Engineering" />
<img src="https://img.shields.io/badge/Conversation%20Memory-101b20?style=flat-square&logoColor=55ff99" alt="Conversation Memory" />
</p>


<a id="inside-the-ai-system"></a>

### Inside the AI system

My **[AI_Legal_CA](https://github.com/choudhary-lokeshh/AI_Legal_CA)** project coordinates a planner, specialist agents and a response validator. Its LLM router selects model tiers and falls back to another model when a request fails.

<img src="./assets/ai-system.svg" width="100%" alt="AI Legal CA pipeline: memory, planner, specialist, validator and response, with OpenRouter routing, fallback and tool calling." />

<details>
<summary><b>Under the hood →</b></summary>

- **Orchestration:** planner routes requests to legal, CA or data agents.
- **Context:** session history is loaded before execution and saved afterward.
- **Model routing:** agent-specific tiers, primary/fallback models and token settings.
- **Tool interface:** tool definitions are passed to the model using automatic tool selection.
- **Validation:** responses pass through a validator before returning reply metadata.
- **SDK dependencies:** OpenAI, Google Generative AI and Groq are also present in the backend manifest; the inspected router uses OpenRouter.

</details>

<a id="selected-builds"></a>

### Selected builds

<table>
<tr>
<td width="50%" valign="top">
<h3>01 / AI_Legal_CA</h3>
<p>Agent orchestration for legal, CA and data workflows, with conversation history, model fallback and response validation.</p>
<p><code>React</code> <code>Express</code> <code>MongoDB</code> <code>OpenRouter</code></p>
<a href="https://github.com/choudhary-lokeshh/AI_Legal_CA"><b>Explore AI system ↗</b></a>
</td>
<td width="50%" valign="top">
<h3>02 / VELORA</h3>
<p>TypeScript monorepo spanning web, admin, creator studio, mobile and API applications.</p>
<p><code>Next.js</code> <code>Expo</code> <code>Bun / Elysia</code> <code>Drizzle</code></p>
<a href="https://github.com/choudhary-lokeshh/VELORA"><b>Explore platform ↗</b></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>03 / IShop</h3>
<p>Full-stack project with separate frontend and backend directories, an Express backend and Mongoose dependencies.</p>
<p><code>JavaScript</code> <code>Node.js</code> <code>Express</code> <code>MongoDB</code></p>
<a href="https://github.com/choudhary-lokeshh/Full-Stack-Ishop-project"><b>Explore repository ↗</b></a>
</td>
<td width="50%" valign="top">
<h3>04 / OrayTech</h3>
<p>Marketing website combining a React / Next.js foundation with Tailwind styling and Framer Motion.</p>
<p><code>Next.js</code> <code>React</code> <code>Tailwind CSS</code> <code>Motion</code></p>
<a href="https://github.com/choudhary-lokeshh/oraytech-website"><b>Explore website code ↗</b></a>
</td>
</tr>
</table>

<p align="center"><a href="https://github.com/choudhary-lokeshh?tab=repositories"><b>Browse all repositories →</b></a></p>

---

<div align="center">

**`BUILD THE INTERFACE. ENGINEER THE SYSTEM. CONNECT THE INTELLIGENCE.`**

<sub>Lokesh Choudhary · Full Stack Developer & AI Engineer</sub>

</div>
