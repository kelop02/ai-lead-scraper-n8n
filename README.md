🤖 AI Lead Generation Scraper and Auto Outreach - n8n Workflow

Automate your lead generation. Scrape, personalize, and outreach on autopilot.

The Business Problem
Small agencies, B2B businesses and freelancers spend 10+ hours every week manually searching Google Maps for businesses, hunting for emails, and writing cold emails. It's slow and boring.

The Solution
This n8n workflow automates the entire process:
Search Leads → Extract Emails → AI Personalizes Email → Saves to Sheet → Sends Outreach

Workflow Flowchart
!Workflow Diagram
Diagram generated with Grok

Node Breakdown:
 •  NODE 1 - Trigger: Schedule Trigger + Apollo.io / Apify (Google Maps) node. Searches for leads based on keyword (e.g., "restaurants in Lagos").
 •  NODE 2 - Scrape Emails: HTTP Request + HTML Extract or Hunter.io node to find business email and info.
 •  NODE 3 - AI Personalization: OpenAI / Grok / Meta Llama node. Takes business info and writes a personalized cold email.
 •  NODE 4A - Save to Google Sheets: Stores all lead data + generated email for tracking.
 •  NODE 4B - Send Outreach: Gmail or SMTP node to send personalized email instantly.

Tech Stack
 •  n8n
 •  Apollo.io / Google Maps Scraper (Apify)
 •  OpenAI / Grok / Meta Llama API
 •  Google Sheets API
 •  Gmail / SMTP

How To Use
 1.  Clone this repo
 2.  Import workflow.json into n8n
 3.  Add your API keys (Apollo, OpenAI, Google Sheets, Gmail)
 4.  Set your lead search criteria
 5.  Activate workflow

Business Value
 •  Saves 15+ hours/week
 •  Sends 50-100 personalized emails daily
 •  Zero manual work

Built with ❤️ using n8n - Automate. Connect. Scale.
