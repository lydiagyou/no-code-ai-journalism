# AI Tools for Journalism

## Intro

With a wave of new AI products hitting the market every day, disrupting industries from law and medicine to journalism and the nonprofit sector, it's hard to know where to start, especially as a journalist.

Intelligence is now available in vast quantities, waiting to be scraped, analyzed, and turned into insight. Today’s journalists must be equipped with a technical toolkit. They are not just reporters, but also researchers, data scrapers, analysts, fact-checkers, interviewers, data engineers, prototypers, and storytellers.

---

## Special Considerations: AI for Journalism

### 🔍 Data Accuracy

Data accuracy is the most important consideration when using AI tools in journalism. While many tools promise to “automate” away manual work, they can produce inaccurate or misleading results. Journalists can improve accuracy by:

- Fine-tuning custom models for specific tasks (e.g., image classification, source research)
- Choosing tasks where directional accuracy is sufficient (e.g., trend analysis from scraped data)

**Best practice**: Treat AI output as a *starting point*, not a source. Every claim must be independently verified.

### 📎 Citations

Citations are a major concern in AI + media. Models often fail to trace or explain how they generate outputs. Traceability varies by model, company, and prompt. Much of the journalistic work will still center around credibility and traceability.

### 🧭 Benchmarking for Journalistic Criteria

Editorial criteria such as originality, clarity, flow, impact, and tone, are still ill-defined for AI-generated content. Developing benchmarks for these standards will be crucial to responsibly integrating AI into journalism, and ensuring its work is interpreted correctly.

### 🧠 Ethical Considerations

Some journalists and publications may have ethical concerns around the use of AI for use cases like research, copy-editing, sourcing, etc.  The AP has published a guide for [Generative AI in Journalism](https://www.researchgate.net/publication/379668724_Generative_AI_in_Journalism_The_Evolution_of_Newswork_and_Ethics_in_a_Generative_Information_Ecosystem).

## 🛠️ Tool: Clay

### Use Cases
- Sourcing
- Interview prep
- Research logistics

### What Is It?

Clay is a fast-growing AI-powered data enrichment and automation tool. Originally built for sales teams to find and enrich leads, it has powerful potential for journalists. For example, Clay can help identify senior VPs at Fortune 500 companies who have published thought leadership on climate and have over 5,000 social media followers, or find military contractors backed by Founders Fund.

Clay integrates with custom HTTP requests, OpenAI, and scraping tools, enabling journalists to automate complex people-finding or company research tasks.

### The Problem

Journalists often spend more time on logistics than reporting. Time-consuming tasks include sourcing, researching, scheduling, and prepping interviews. The sheer volume and variety of online data (tweets, blogs, panels, podcasts) is overwhelming for individuals and can be better suited to AI-assisted search.

### How Clay Can Help

Clay is especially useful for business journalists or investigations involving corporate data. It pulls data from LinkedIn and other B2B data providers, and uses AI agents to complete research tasks, like finding a company's latest SEC filing or summarizing its recent press mentions.

### Journalism Considerations

Journalists should evaluate the accuracy of data from private SaaS tools and be cautious of AI hallucinations.

Get the template [here](https://app.clay.com/shared-workbook/share_suHxV9SjxDvR).

👉 [Watch Clay demo](https://www.loom.com/share/de6eb6e82cd442c38e42495ce8cac683?t=224)

---

## 🌀 Tool: Gaussian Splatting for 3D Scene Rendering

### Use Cases

- AR/VR journalism
- Spatial storytelling
- 3D scene reconstruction

### What Is It?

Gaussian splatting is a cutting-edge 3D rendering technique offering faster, more photorealistic, and geometrically accurate results than traditional photogrammetry or NeRFs. It's lightweight and efficient enough for web, mobile, and AR/MR devices, making it ideal for immersive journalism.

### Journalism Considerations

Inspired by the NYT R&D team’s work on spatial journalism, and the legacy of Nonny de la Peña’s VR work (e.g. *Hunger in LA*), I’m particularly interested in using Gaussian splats for immersive storytelling. Use cases include:

- Walkthroughs of modeled crime or protest scenes
- Interactive 3D object visualizations
- Sports or feature stories in augmented reality

I'm currently experimenting with the open-source [Nerfstudio `gsplat`](https://github.com/nerfstudio-project/nerfstudio) library for journalism applications.

---

## 💻 Tools: Cursor, Lovable, and Code Assistants

### Use Cases

- Building custom tools for reporting
- Writing web scrapers and HTTP requests
- Prototyping reader-facing data interactives

### What Are They?

- **Cursor** is an AI-powered IDE that helps developers write, debug, and understand code.
- **Lovable** is a no-code AI design tool that builds user interfaces and websites from natural language prompts.

### Journalism Considerations

These tools lower the barrier to technical prototyping, helping journalists build scrapers, APIs, dashboards, or custom web apps for data projects. While “no-code” is a selling point, understanding basic web technologies (HTML/CSS/JS, APIs) is still important for using them effectively.

Sample use cases include:

- Writing an HTTP API to monitor SEC filings
- Building a site to track local eviction filings
- Creating a simple UI for reader interaction with datasets
