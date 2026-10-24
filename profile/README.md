# BackPR

BackPR is online registration and payment software for youth and community programs in the United States, such as summer camps, after-school and childcare programs, classes, swim schools and sports. It's also built for schools, PTAs, churches and community centers.

It's free for nonprofits: no subscription and no BackPR fees. Payments run on Stripe at Stripe's standard rates. Other organizations can ask for a quote.

[backpr.com](https://backpr.com) · support@backpr.com

## Open data

Free data about US youth programs, licensed CC BY 4.0. Every fact links to its official source.

- State rules for childcare, camps and after-school programs in all 50 states and DC: licensing, staff-to-child ratios, background checks, medication administration and mandated child abuse reporting
- Youth and community nonprofits by state, from IRS records
- What registration software companies publish about their pricing

Get the CSV and JSON files from the [backpr-open-data](https://github.com/BackPR/backpr-open-data) repo, which is updated every Monday, or from [backpr.com/ai](https://backpr.com/ai), [Zenodo](https://doi.org/10.5281/zenodo.23577823), [Hugging Face](https://huggingface.co/datasets/backpr/us-youth-program-data) and [Kaggle](https://www.kaggle.com/datasets/backpr/us-youth-program-data-rules-nonprofits-pricing).

## MCP servers

MCP (Model Context Protocol) is an open protocol that lets AI assistants such as Claude and ChatGPT connect to outside data.

- **BackPR data server** (`https://backpr.com/ai/mcp`): gives AI assistants access to the open data. It's public and read-only, with no sign-in. It's listed in the official MCP Registry as `com.backpr/data`.
- **BackPR Admin and BackPR Family**: let program staff and parents connect an AI assistant to their BackPR account. Setup: [backpr.com/mcp](https://backpr.com/mcp).
