# Kemira AI Visibility Agent

**An AI-powered SEO & Generative Engine Optimization (GEO) content audit workflow built with n8n and Google Gemini.**

## Project Overview

This portfolio project demonstrates how AI-assisted automation can support content analysis for corporate communications and digital visibility.

The workflow retrieves public content from Kemira's company webpage, extracts the main page text, and uses a language model to generate three evidence-based SEO/GEO improvement recommendations.

**Target webpage:** https://www.kemira.com/company/

## Technology Stack

- **n8n** — Workflow automation
- **HTTP Request** — Webpage retrieval
- **HTML Extraction** — Main content extraction using the `main` CSS selector
- **Google Gemini / Gemma** — AI-assisted content analysis

## Workflow

1. **Manual Trigger:** Start the audit.
2. **HTTP Request:** Retrieve Kemira's company webpage.
3. **HTML Node:** Extract the main webpage content.
4. **Message a Model:** Generate three SEO/GEO recommendations with supporting evidence.

## Audit Methodology

Each recommendation includes:

- **Evidence:** An exact quotation from the extracted webpage content.
- **Recommendation:** A specific content improvement.
- **Expected Benefit:** A potential SEO/GEO benefit presented as a hypothesis.

The workflow currently analyzes the first 3,000 characters of the extracted main content.

## Limitations

This is a prototype for content-focused auditing, not a complete technical SEO or AI visibility measurement platform.

It does not independently verify search rankings, metadata, structured data, backlinks, or citations in AI-generated answers. AI recommendations require human review before implementation.

## Future Improvements

- Analyze complete webpage content using chunking.
- Extract and review page titles, meta descriptions, and structured data.
- Compare multiple Kemira webpages.
- Export a structured audit report automatically.

## Disclaimer

This is an independent portfolio project created for demonstration purposes. It is not an official Kemira project and is not affiliated with or endorsed by Kemira.
