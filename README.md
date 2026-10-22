# Kemira — Low-Cost SEO, GEO & Communications Automation

### Practical projects built with n8n, JavaScript and AI

## Key GEO Finding

In October 2026, I tested how Claude and Gemini describe Kemira.

**I found a clear mistake in Gemini's answer:** it described Kemira using an outdated two-part business structure, although Kemira introduced three business units in January 2025.

I checked this against Kemira's official announcement.

This project shows how I approach problems: **test, find the issue, verify it and suggest a practical solution.**

I also have real WordPress and PHP experience from Coreorient, where I maintained websites, cleaned up spam and built custom solutions to avoid unnecessary plugin costs.

**[Read my GEO Case Study](Kemira-GEO-Case-Study.md)**

**[See AI Test Evidence](AI-Test-Evidence/)**

## Why I Built These Projects

I am a programmer interested in combining web development, AI and digital communications.

I wanted to explore a simple question:

**How can we make everyday communications and website tasks easier without relying on expensive tools?**

I used Kemira's publicly available website as a practical example and built three small projects.

My approach was to start with simple tools, test what works, fix problems and use AI only where it adds value.

These are independent portfolio projects, not official Kemira systems.

---

## 1. AI Visibility Agent — Reviewing Website Content

![Kemira AI Visibility Agent](kemira_8n8.png)

**The idea:** Website content should be clear for people, search engines and AI-powered search tools.

**What I built:**

I created an n8n workflow that:

- Reads content from Kemira's public company webpage.
- Extracts the main text.
- Uses a Google language model to review the content.
- Suggests three possible SEO/GEO content improvements based on the extracted text.

**What I learned:**

AI can help with a first content review, but its suggestions still need to be checked by a person.

This workflow does not measure actual AI search rankings or prove that website visibility has improved.

**Website tested:** https://www.kemira.com/company/

---

## 2. Low-Cost SEO/GEO Optimizer — Finding Things to Check

![Kemira Low-Cost SEO GEO Optimizer](KemiraLowCostCeoGeoOptimizer.png)

**The idea:** Some useful website checks can be automated without buying a large SEO platform.

**What I built:**

I created a workflow to retrieve webpage information and check selected SEO-related elements.

During testing, the workflow flagged a possible missing meta description and produced other observations for review.

**What I learned:**

A workflow can help find potential problems, but every finding needs verification before calling it a confirmed website issue.

For example, something missing from raw HTML may still exist on the rendered webpage.

**How this could help:**

It could give a communications or website team a quick checklist of things to investigate before updating a page.

No changes were made to Kemira's website.

---

## 3. Communications Change Monitor — Tracking Company News

![Kemira Communications Change Monitor](KemiraCominucation.png)

**The idea:** Instead of manually checking the same news page every day, a workflow can remember which announcements it has already seen.

**What I built:**

Using n8n and JavaScript, I created a workflow that:

1. Reads Kemira's public news webpage.
2. Extracts the latest displayed announcements.
3. Saves their titles, dates, categories and links in an n8n Data Table.
4. Compares the current announcements with previously saved records.
5. Identifies announcements that have not been stored before.

**What I actually tested:**

- Successfully extracted three official Kemira releases.
- Saved all three releases with their correct information.
- Fixed an issue with data storage.
- Fixed incorrect field mappings that initially created empty records.
- Ran the workflow again and confirmed that the saved releases were not reported as new.

The repeat test returned:

```json
{
  "status": "no_change",
  "newCount": 0,
  "monitoredCount": 3,
  "newNews": []
}
```

**Why this matters:**

This kind of workflow could help a communications team avoid repeatedly reviewing the same announcements and focus on newly discovered information.

The workflow is configured for daily execution, but long-term unattended operation has not yet been verified.

**Website monitored:** https://www.kemira.com/news-and-stories/

---

## Why Low Cost Matters to Me

My goal is not to use AI for everything.

I prefer to start with the simplest solution that can do the job.

For these projects, I used:

- **n8n** to connect tasks and automate workflows.
- **JavaScript** for extracting information and comparing data.
- **n8n Data Tables** to remember previously collected information.
- **AI** for content analysis, where language understanding is useful.
- **Public website content** without needing access to internal systems.

This approach can reduce unnecessary software complexity and AI usage.

It does not mean that hosting, maintenance or AI services are always free.

I believe useful automation should be practical, understandable and affordable to maintain.

---

## How I Could Take These Projects Further

These prototypes were built using public website information. With appropriate access and approval, I could also work directly on the website itself.

Because I have a programming background, I can combine automation with hands-on WordPress development.

For example, I can:

- **Work inside the WordPress dashboard:** Review and update pages, posts and website content.
- **Improve SEO settings:** Update page titles, meta descriptions and other relevant content or technical elements.
- **Fix website bugs:** Investigate and correct problems in themes, templates or plugins.
- **Edit website sections:** Improve layouts, content structure and selected page elements.
- **Build custom WordPress plugins with PHP:** Develop small features or integrations when existing plugins are not the right solution.
- **Connect AI agents and automation:** Use n8n and APIs to support content workflows, monitoring, reporting and other repetitive tasks.

For me, the advantage of being a programmer is that I am not limited to producing an audit report.

I can also help investigate the technical problem, make an approved change, build a small tool or automate the process.

I would still test changes carefully and work within the team's security, publishing and approval procedures.

---

## What These Projects Show

These projects helped me practice:

- Finding practical opportunities for automation.
- Working with public website data.
- Building workflows in n8n.
- Using JavaScript to process and compare information.
- Using AI for content analysis.
- Debugging real workflow problems.
- Testing results instead of assuming everything works.
- Thinking about cost, maintenance and usability.

I have not measured time savings, search-ranking improvements or increases in AI visibility. Those would require further testing.

## Final Thought

I believe the best solution is not always the most complicated or expensive one.

Sometimes a small automation, a useful WordPress improvement or a custom PHP plugin can solve a practical problem.

My goal is to combine **programming, SEO/GEO knowledge and AI automation** to help communications teams work more efficiently, while keeping people responsible for reviewing and approving the final results.

---

## Disclaimer

These are independent portfolio projects created for learning and demonstration purposes.

They are not official Kemira projects and are not affiliated with or endorsed by Kemira.

All testing used publicly accessible information. No changes were made to Kemira's website or internal systems.


## GEO Research

I also compared AI answers about Kemira and found an example of outdated company information.

[Read my GEO Case Study](Kemira-GEO-Case-Study.md)
