# NEXORA — AI Content Creator Marketplace

A responsive hackathon prototype built with plain HTML, CSS, and JavaScript.

## Run in VS Code

1. Download and extract `nexora_vscode.zip`.
2. Open the extracted `nexora_vscode` folder in Visual Studio Code.
3. Open `index.html`.
4. Recommended: install the **Live Server** extension, right-click `index.html`, and choose **Open with Live Server**.
5. Test Discover, search/filtering, View portfolio, project details, shortlist, brief builder, campaign saving, and creator invitations.

No Node.js or build step is required. Google Fonts require an internet connection; the page still works without them.

## Main files

- `index.html` — app structure and sections
- `style.css` — responsive visual design
- `script.js` — sample creator data and interactions

## Features

- Eight illustrative creator profiles, with three sample projects each
- Search across creators, skills, tools, and projects
- Combined specialization, AI tool, and workflow verification filters
- Portfolio detail view and individual project detail modal
- Creator shortlist saved in browser localStorage
- Campaign brief creation and campaign list
- Local template-based brief builder (not a live AI model)
- Link creators to saved campaign briefs
- Responsive layout for mobile and desktop

## Important prototype notes

- Creator identities, verification signals, portfolios, and metrics are demo content, not verified real-world information.
- The Brief Builder uses a local text template; it does not call an AI API.
- Data is stored in the browser's localStorage. It is not shared between devices or users.
- This is a front-end prototype, not a production marketplace or secure account system.

## Deployment

The project is static and can be published through a static hosting provider. For a hackathon that prefers ByteXL Nimbus, check whether your event submission rules require deployment on Nimbus or simply allow a live demo URL. If static hosting is allowed, use the provider's current static-site instructions and verify the public URL in a private/incognito browser before submitting.
