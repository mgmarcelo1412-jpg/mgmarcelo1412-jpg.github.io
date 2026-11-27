# Marketing, Sales & Finance CRM — Claude build prompt

Copy the prompt below into Claude to generate the application in this folder.

---

Build a polished, responsive CRM for a small marketing or digital agency. The product must bring together **Marketing, Sales, and Finance** in one workspace.

## Stack and deployment
- Use Next.js with TypeScript and Tailwind CSS.
- Structure the app for deployment on Vercel.
- Do not require paid services, API keys, or external integrations.
- Include realistic demo data and a clear, usable first-run experience.
- Use local storage for demo persistence if needed. Do not collect or process real payment details.

## Main sections

### Dashboard
Show useful summary cards and charts for:
- Marketing campaign spend, leads generated, and conversion rate.
- Sales pipeline value, open opportunities, and won deals.
- Finance revenue, outstanding invoices, expenses, and cash flow.
Add a recent activity feed and a short list of upcoming tasks or due dates.

### Marketing
- Campaign list with channel, budget, spend, dates, status, and owner.
- Track leads and campaign outcomes.
- Show simple performance metrics such as impressions, clicks, leads, cost per lead, and conversion rate.
- Include filters and a campaign detail view.

### Sales
- Lead and contact management with source, owner, status, and notes.
- Opportunity pipeline with stages such as New, Qualified, Proposal, Negotiation, Won, and Lost.
- Opportunity value, expected close date, and related client/campaign.
- Search, filters, and a clear pipeline view.

### Finance
- Invoices with client, amount, issue date, due date, and status.
- Expense tracking by category, date, amount, and campaign/project.
- Revenue and expense summaries with simple charts.
- Make it clear that these are CRM records and demo data; do not build payment processing or tax filing.

### Shared CRM records
- Client and contact profiles linking their campaigns, leads, opportunities, invoices, and activity.
- Task management with priority, due date, owner, and completion status.
- Notes and an activity history on relevant records.

## Design
Create a professional, cohesive agency dashboard. Use clear navigation between Marketing, Sales, Finance, Clients, and Reports. Make tables and charts easy to scan, and ensure the interface works on desktop and mobile. Include accessible controls, helpful empty states, and believable sample data.

## Deliverables
Create a complete runnable project in this folder, including all source files, package.json, a suitable .gitignore, and a README with local setup and Vercel deployment instructions. Check that it builds successfully and fix build errors. In your final response, list the files created and the exact commands to run the app locally.
