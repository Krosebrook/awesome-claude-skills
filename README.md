# Awesome Claude Skills

## 📚 Table of Contents  
- [Document Skills](#-document-skills)  
- [Development & Code Tools](#-development--code-tools)  
- [Data & Analysis](#-data--analysis)  
- [Scientific & Research Tools](#-scientific--research-tools)  
- [Writing & Research](#-writing--research)  
- [Learning & Knowledge](#-learning--knowledge)  
- [Media & Content](#-media--content)  
- [Collaboration & Project Management](#-collaboration--project-management)  
- [Security & Web Testing](#-security--web-testing)  
- [Utility & Automation](#-utility--automation)


## 📄 Document Skills  
**High-Level Overview:** Tools for working with common office document formats. These skills enable Claude to create, read, modify, and analyze documents including Word files, PDFs, presentations, and spreadsheets - essential for business workflows, report generation, and document automation.

**Skills (5):**
- [docx](https://github.com/anthropics/skills/tree/main/document-skills/docx) - Create, edit, analyze Word docs with tracked changes, comments, formatting. *Use for: Document creation, contract editing, report generation*
- [pdf](https://github.com/anthropics/skills/tree/main/document-skills/pdf) - Extract text, tables, metadata, merge & annotate PDFs. *Use for: PDF parsing, form extraction, document merging*
- [pptx](https://github.com/anthropics/skills/tree/main/document-skills/pptx) - Read, generate, and adjust slides, layouts, templates. *Use for: Presentation creation, slide deck automation*
- [xlsx](https://github.com/anthropics/skills/tree/main/document-skills/xlsx) - Spreadsheet manipulation: formulas, charts, data transformations. *Use for: Data analysis, financial modeling, report generation*
- [revealjs-skill](https://github.com/ryanbbrown/revealjs-skill/tree/main) - Generate polished, professional presentations using the Reveal.js HTML presentation framework. *Use for: Web-based presentations, interactive slide decks*



## 🛠 Development & Code Tools
**High-Level Overview:** Comprehensive development utilities for software engineering workflows. These skills cover frontend development, testing methodologies, Git workflows, AWS infrastructure, code quality analysis, and development environment enhancements - designed to streamline the entire software development lifecycle.

**Skills (9):**
- [artifacts-builder](https://github.com/anthropics/skills/tree/main/artifacts-builder) - Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui). *Use for: Interactive UI components, rapid prototyping*
- [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - Use when implementing any feature or bugfix, before writing implementation code. *Use for: TDD workflows, test-first development*
- [using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/) - Creates isolated git worktrees with smart directory selection and safety verification. *Use for: Parallel feature development, context switching*
- [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) - Guides completion of development work by presenting clear options and handling chosen workflow. *Use for: Branch cleanup, merge workflows*
- [pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) - Design comprehensive test cases using PICT (Pairwise Independent Combinatorial Testing) for requirements or code, generating optimized test suites with pairwise coverage. *Use for: Test case generation, combinatorial testing*
- [aws-skills](https://github.com/zxkane/aws-skills) - AWS development with CDK best practices, cost optimization MCP servers, and serverless/event-driven architecture patterns. *Use for: AWS infrastructure, cloud development*
- [claude-starter](https://github.com/raintree-technology/claude-starter) - Production-ready Claude Code configuration template with 40 auto-activating skills across 8 domains, TOON format support for 30-60% token savings, and native Zig encoder/decoder. *Use for: Project bootstrapping, configuration management*
- [move-code-quality-skill](https://github.com/1NickPappas/move-code-quality-skill) - Analyzes Move language packages against the official Move Book Code Quality Checklist for Move 2024 Edition compliance and best practices. *Use for: Move blockchain development, code quality audits*
- [claude-code-terminal-title](https://github.com/bluzername/claude-code-terminal-title) - Gives each Claude Code terminal window a dynamic title that describes the work being done so you don't lose track of what terminal window is doing what. *Use for: Terminal organization, workflow tracking*



## 📊 Data & Analysis  
**High-Level Overview:** Tools for data investigation and debugging workflows. These skills help trace execution flows, analyze datasets, and extract insights from structured data - essential for troubleshooting complex systems and understanding data patterns.

**Skills (2):**
- [root-cause-tracing](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) - Use when errors occur deep in execution and you need to trace back to find the original trigger. *Use for: Debugging, error investigation, stack trace analysis*
- [csv-data-summarizer-claude-skill](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) - Automatically analyzes CSVs: columns, distributions, missing data, correlations. *Use for: Data exploration, statistical analysis, data quality assessment*



## 🔬 Scientific & Research Tools
**High-Level Overview:** Specialized tools for scientific research and laboratory workflows. These skills provide access to major scientific databases, lab automation platforms, specialized computational packages, and research methodologies - enabling advanced bioinformatics, drug discovery, and scientific computing tasks.

**Skills (4):**
- [scientific-databases](https://github.com/K-Dense-AI/claude-scientific-skills/tree/main/scientific-databases) - Access to 26 scientific databases including PubMed, PubChem, UniProt, ChEMBL, and AlphaFold DB. *Use for: Literature research, protein analysis, drug discovery*
- [scientific-integrations](https://github.com/K-Dense-AI/claude-scientific-skills/tree/main/scientific-integrations) - Platform integrations for lab automation and workflow management (Benchling, DNAnexus, Opentrons, and more). *Use for: Lab automation, experiment management, workflow orchestration*
- [scientific-packages](https://github.com/K-Dense-AI/claude-scientific-skills/tree/main/scientific-packages) - 58 specialized Python packages for bioinformatics, cheminformatics, machine learning, and data analysis. *Use for: Computational biology, chemical analysis, scientific computing*
- [scientific-thinking](https://github.com/K-Dense-AI/claude-scientific-skills/tree/main/scientific-thinking) - Analysis tools and document processing for scientific writing, visualization, and methodology. *Use for: Research paper writing, data visualization, experimental design*



## ✍️ Writing & Research  
**High-Level Overview:** Content creation and research tools for various writing contexts. These skills support web research, content development, internal communications, ideation, and specialized research domains - helping produce well-researched, high-quality written materials.

**Skills (5):**
- [article-extractor](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) - Extract full article text and metadata from web pages. *Use for: Web scraping, content aggregation, research compilation*
- [content-research-writer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/content-research-writer) - Assists in writing high-quality content by conducting research, adding citations, improving hooks, iterating on outlines, and providing real-time feedback on each section. *Use for: Blog posts, articles, long-form content*
- [internal-comms](https://github.com/anthropics/skills/tree/main/internal-comms) - Create internal communications (status reports, leadership updates, etc). *Use for: Company announcements, team updates, executive summaries*
- [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) - Transform rough ideas into fully-formed designs through structured questioning and alternative exploration. *Use for: Product ideation, creative problem-solving, design thinking*
- [family-history-research](https://github.com/emaynard/claude-family-history-research-skill) - Provides assistance with planning family history and genealogy research projects. *Use for: Genealogy, ancestry research, family tree building*


## 📘 Learning & Knowledge  
**High-Level Overview:** Knowledge management and continuous learning tools. These skills help organize information into interconnected knowledge graphs and guide iterative learning or development processes - ideal for building personal knowledge bases and planning growth trajectories.

**Skills (2):**
- [tapestry](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) - Interlink and summarize related documents into knowledge networks. *Use for: Knowledge graphs, research synthesis, concept mapping*
- [ship-learn-next](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) - Skill to help iterate on what to build or learn next, based on feedback loops. *Use for: Learning roadmaps, product iteration, skill development*



## 🎬 Media & Content  
**High-Level Overview:** Multimedia processing and content extraction tools. These skills work with video platforms, images, and digital books - enabling content analysis, media downloads, image enhancement, and ebook processing for various media workflows.

**Skills (4):**
- [youtube-transcript](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) - Fetch transcripts from YouTube videos and prepare summaries. *Use for: Video analysis, content summarization, transcript extraction*
- [video-downloader](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/video-downloader) - Downloads videos from YouTube and other platforms for offline viewing, editing, or archival. *Use for: Video archiving, offline access, content preservation*
- [image-enhancer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/image-enhancer) - Improves the quality of images, especially screenshots. *Use for: Image upscaling, screenshot enhancement, visual quality improvement*
- [claude-epub-skill](https://github.com/smerchek/claude-epub-skill) - Parse and analyze EPUB ebook contents for querying or summarizing. *Use for: Ebook analysis, digital library management, book summarization*



## 🤝 Collaboration & Project Management  
**High-Level Overview:** Team workflow and project coordination tools. These skills automate version control operations, facilitate code reviews, manage testing workflows, analyze team communications, and integrate with project management systems - streamlining engineering and team collaboration processes.

**Skills (5):**
- [git-pushing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) - Automate git operations and repository interactions. *Use for: Git automation, commit workflows, repository management*
- [review-implementing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) - Evaluate code implementation plans and align with specs. *Use for: Code review, implementation validation, spec compliance*
- [test-fixing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) - Detect failing tests and propose patches or fixes. *Use for: Test maintenance, CI/CD fixes, test debugging*
- [meeting-insights-analyzer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/meeting-insights-analyzer/) - Transforms your meeting transcripts into actionable insights about your communication patterns. *Use for: Meeting analysis, communication improvement, team dynamics*
- [linear-cli-skill](https://github.com/Valian/linear-cli-skill) - A skill teaching claude how to use linear-CLI (provided alongside the skill), meant to replace linear MCP. *Use for: Issue tracking, project management, Linear integration*


## 🛡 Security & Web Testing  
**High-Level Overview:** Security assessment and quality assurance tools. These skills enable vulnerability scanning, multi-layered security testing, automated web application testing, and systematic debugging methodologies - critical for ensuring application security and reliability.

**Skills (4):**
- [ffuf_claude_skill](https://github.com/jthack/ffuf_claude_skill) - Integrate Claude with FFUF (fuzzing) and analyze results for vulnerabilities. *Use for: Fuzzing, vulnerability scanning, security testing*
- [defense-in-depth](https://github.com/obra/superpowers/blob/main/skills/defense-in-depth) - Implement multi-layered testing and security best practices. *Use for: Security architecture, layered testing, threat modeling*
- [webapp-testing](https://github.com/anthropics/skills/tree/main/webapp-testing) - Toolkit for interacting with and testing local web applications using Playwright. *Use for: E2E testing, browser automation, UI testing*
- [systematic-debugging](https://github.com/obra/superpowers/blob/main/skills/systematic-debugging) - Use when encountering any bug, test failure, or unexpected behavior, before proposing fixes. *Use for: Bug investigation, methodical debugging, root cause analysis*



## 🔧 Utility & Automation  
**High-Level Overview:** General-purpose automation and skill development tools. These skills automate file management, organize financial documents, and provide templates for creating new Claude skills - essential for productivity enhancement and skill ecosystem expansion.

**Skills (4):**
- [file-organizer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/file-organizer) - Intelligently organizes your files and folders across your computer. *Use for: File management, folder organization, automated cleanup*
- [invoice-organizer](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/invoice-organizer/SKILL.md) - Automatically organizes invoices and receipts for tax preparation. *Use for: Financial document management, tax prep, expense tracking*
- [skill-creator](https://github.com/anthropics/skills/tree/main/skill-creator) - Template / helper to build new Claude skills. *Use for: Skill development, custom tool creation, skill scaffolding*
- [template-skill](https://github.com/anthropics/skills/tree/main/template-skill) - Minimal skeleton for a new skill project structure. *Use for: Skill boilerplate, project initialization, template setup*  

## 🤝 Contribution

If you have suggestions, improvements, or new resources to add:

1. Fork this repo
2. Make your changes
3. Submit a Pull Request

You can also open an **Issue** 🐛 if you spot something that needs fixing.

## 📬 Contact

If you want to contact me, you can reach me on [X](https://x.com/Behi_Sec).
