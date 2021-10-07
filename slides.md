---
theme: default
background: https://i.redd.it/4w8jxyi56if41.jpg
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  Slides for Open Source India 2021 talk
drawings:
  persist: false
---

# Importance of documentation for open source communities

Harsh Bardhan Mishra, Google Season of Docs Intern - [moja global](https://moja.global)

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/harshcasper/OSI-Days-2021" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# Agenda
<br>
<br>

- Getting started with open source documentation
<br>
<br>
- Need of documentation for open source projects
<br>
<br>
- Decluttering messy open source documentation
<br>
<br>
- Strategy towards crowdsourced documentation efforts
<br>
<br>
- Q&A

<br>
<br>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# Getting started with open source documentation


Let’s start with the basic ethos of open source.
<br>
<br>

- Enables transparency in the entire software development lifecycle.
<br>
<br>
- Helps mitigate vendor lock-in and enabling redistribution.
<br>
<br>
- Channels community efforts towards a mutual goal of cooperation.
<br>
<br>
- Provides a platform for users and enterprise customers to collaborate and build.
<br>
<br>
- Allows adaptation of processes and workflows to sustain new requirements.

---
layout: image-right
image: https://images.unsplash.com/photo-1600267204091-5c1ab8b10c02?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80
---

# Different parts of documentation

Open Source documentation consists of various moving parts. Some of them include:

- README/Project-specific overviews
- Reference Guides
- Community-specific documentation
- User documentation
- Developer/API documentation
- Blogs/Videos

---

# Tools to get started with documentation

There are various tools available today to get you started with documenting your open source projects.

- Docusaurus
- Vuepress
- Sphinx (ReadTheDocs)
- Jekyll
- Hugo
- GitBook
- Antora

Some writing tools include Markdown, AsciiDoc, HTML and more.

---

# Popular examples

Some of the (opinionated) examples of good open-source documentation projects include:

- [FastAPI Docs](https://fastapi.tiangolo.com/)

- [PyTorch Docs](https://pytorch.org/docs/stable/index.html)

- [Angular Docs ](https://angular.io/docs)

- [GitHub Docs](https://docs.github.com/en)

- [Django Docs](https://docs.djangoproject.com/en/3.2/)

- [Kubernetes Docs](https://kubernetes.io/docs/home/)

- [Flutter Docs](https://flutter.dev/docs)

---

# Need of documentation for open source projects

Open source documentation completes the puzzle of a project’s usability.
<br>
<br>
- Essential documentation efforts drive forward adoption and collaboration.
<br>
<br>
- Helps develop community specific content to help developers and users alike.
<br>
<br>
- Ensure transparency in software quality, existing processes and the overall design.
<br>
<br>
- Paves way towards an open content infrastructure to provide support to the open source project.

---
layout: image-right
image: https://imgs.xkcd.com/comics/rtfm.png
---

# What “bad” documentation can lead to?

A “bad” documentation can essentially “kill” the software product. And there are various ways that can lead to the same.

- Low user and customer drive and adoption due to software product.
- Overt burden on support and engineering teams for sharing context.
- Leads to bugs, errors which turns away the existing user-base.
- Product crumbles under the heavy scope of development and reduces its life span.

---

# What scope does a documentation fill in?

A documentation piece provides a general scope of contribution to enhance it’s usability.

- Documentation should act as the “primary source of truth”.
<br>
<br>
- Fill in the customers’ information needs as and when required.
<br>
<br>
- Provide necessary references to support engineers, solution architects and stakeholders to make important decisions.
<br>
<br>
- Enhance the product outreach and its purpose with the help of essential documentation.
<br>
<br>
- Bring up an infrastructure working towards continuous improvement and development.

---

# Documentation as Code

Documentation as Code references towards continuous development of docs alongside software.

- Track relevant documentation development on Issue trackers (Bugzilla, GH Issues, Jira).
<br>
<br>
- Version-control documentation to be specific to project releases.
<br>
<br>
- Use peer reviews, automated toolings and tests to validate and release docs.
<br>
<br>
- Build a docs team to focus on docs development and improvement.
<br>
<br>
- Build feedback channels to find areas of improvement and scope of new work.

---

# Decluttering messy open-source documentation

There are various reasons for messy open source documentation development.

- Non compliance with style guides and documentation standards.
<br>
<br>
- Assumption that the users can navigate through and understand everything.
<br>
<br>
- Notion that the technical documentation is good for non-technical users as well.
<br>
<br>
- Lack of reviews and feedback loops to ensure documentation quality.
<br>
<br>
- Minimal to no connection between documentation and developer teams.

---

# Style guides for open source documentation

Style guides define specific rules around documentation efforts to ensure consistency and standardize docs.
<br>
<br>
- Google, Microsoft, write-good, proselint, JobLint
	[https://github.com/errata-ai/styles ](https://github.com/errata-ai/styles)
<br>
<br>
- Middlebury, Pedantic, Rust, ttd-light
    [https://github.com/testthedocs/vale-styles](https://github.com/testthedocs/vale-styles)
<br>
<br>
- Utilize automated tests on CI to verify compliance with style guides (Vale).

---

# Standardizing documentation

Standardized documentation pieces are essential to maintain consistency, share an overall context with users and identify missing parts.

- Create pre-defined templates to capture essential details during documentation.
<br>
<br>
- Identify user-centric changes and document them continuously with every change.
<br>
<br>
- Develop standard workflows for adding documentation pieces along with review and publish process.
<br>
<br>
- Conduct reviews with teams to analyze the context and information and find improvement scope.

---

# Feedbacks and automated reviews

There are various ways to ensure continuous feedbacks and reviews are done for the documentation being developed.

- Utilize automated tests on CI to verify compliance with style guides (Vale).
<br>
<br>
- Seek Subject matter expert (SME) feedback as documentation is updated continuously.
<br>
<br>
- Setup peer review channels to get suggestions for improvements from fellow documentation developers.
<br>
<br>
- Have feedback surveys on user-facing documentation to understand its helpfulness.

---

# Strategy towards crowdsourced documentation efforts

Developing docs in open source is a great way to drive contributions from external contributors.

- Provide a quick-start to new contributors through documentation-related work and issues.
<br>
<br>
- Find out areas to improve on and plug in efforts from various contributors to work and collaborate.
<br>
<br>
- Develop external user-centric documentation for signifying the purpose of each project.
<br>
<br>
- Build learning courses, contribution guides and documentation-related workflows to help new contributors.

---

# Defining consistent content strategy

A consistent content strategy goes a long way to ensure a long-term vision for the documentation efforts and the infrastructure.

## Resources

- Project Docs
- Case Studies & Whitepapers
- Project Architecture

## Branded Content:

- Blogs & Guest Posts
- News & Community stories
- Learning Courses

---

# Writing with purpose

Writing with Purpose is about WHY, not HOW

- What is my goal of writing this documentation?
<br>
<br>
- What is the message and the persona that needs to be reflected?
<br>
<br>
- What action would you like to the user to take up after this?
<br>
<br>
- What was the value that I shared with the reader?
<br>
<br>
- Am I concise and consistent with my writing efforts?

---

# Tips for Docs teams

A few good suggestions for the teams starting with open source documentation efforts to follow:

- Start small and define the parts that need an immediate attention.
<br>
<br>
- Identify your users and their expectations from a potential documentation overview.
<br>
<br>
- Use automated toolings to effect and collaborate with stakeholders and developers to identify areas of work.
<br>
<br>
- Keep documentation open and accessible to all with attention to usability.
<br>
<br>
- Prevent documentation scatter across multiple projects and stakeholders.

---
layout: center
class: text-center
---

# Q&A

[LinkedIn](https://linkedin.com/in/harshcasper) · [GitHub](https://github.com/harshcasper) · [Twitter](https://twitter.com/harsh_casper)
