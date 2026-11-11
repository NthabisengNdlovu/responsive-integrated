Nthabiseng - Junior Automation Specialist (Ticket Routing Lead)

Designed routing logic: Invoice → Finance, Password → IT, Leave → HR, Delivery → Operations
Built "Route Ticket" button and routing path visual: Requester → [SERVIQ Automation] → Receiver
Tested routing with 10+ different ticket types to ensure correct department every time
Fixed bug where "Leave" was routing to Finance instead of HR

How Meta AI helped:
Prompted Meta AI: "Generate JavaScript routing logic for keyword-based ticket routing"
Meta AI generated starter code for if (ticket.includes('invoice')) return 'Finance'
Person 1 reviewed, corrected, and tested the logic - did not copy blindly. They added the Requester/Receiver mapping on top.
Used Meta AI to debug why routing was not showing toast - Meta AI suggested adding showToast() after routing.

Mushaisano Setautsi

Digital Operations Assistant (Email & Content Integration Lead)
What they did:
Integrated Week 2 Content Generator with Week 7 Workflow
Built email preview: To: (Receiver), Subject from generated content, Body = generated letter
Built "Send Email to Receiver" button + Email Log (last 3 emails)
Ensured when Week 7 routes a ticket, Week 2 automatically writes the email text - no manual copy-paste

How Meta AI helped:
Asked Meta AI: "How to make Week 2 auto-generate email when Week 7 routes a ticket?"
Meta AI suggested using a single function routeAndGenerate() that calls both routing + content generation
Person 2 implemented this, then used Meta AI to generate 3 tone variations (Formal / Simple / Friendly) for email templates
Validated all emails with real Receiver names - checked that Receiver name appears correctly in "To:" field

Zenani - Automation Specialist (Integration & Optimisation Lead)

Verified Week 2 + Week 7 integration still works in final build: Routing auto-generates email, Approval swaps Requester/Receiver
Ran Optimisation Check: Load time, button functionality, responsiveness
Fixed responsive bugs: Buttons cut off on mobile, header too wide - made all layouts stack on phone
Verified all 8 weeks work in All-in-One Dashboard: Chatbot, Content Generator, Sentiment, Reporting, Predictive, Compliance, Workflow, Showcase

How Meta AI helped:

Asked Meta AI: "Make project responsive, test mobile 375px vs desktop 1440px"
Meta AI generated media query CSS - Zenani tested on real phone, found 0px overflow after fix
Used Meta AI to debug integration: "Why is approval not updating content?" - Meta AI suggested calling generateApprovalContent() after status change
Zenani implemented fix and re-tested all flows

Adriyell - QA, Documentation & Sign-Off Lead

Tested EVERY button: Route, Generate, Send Email, Approve, Reject, Copy, Download Word, Clear
Built Human Sign-Off: Name + Surname + checkbox required before Word download - Responsible AI
Built Audit Log: Last 5 actions with timestamp, e.g. "Thabo requested → Naledi, Routed, Email sent, Approved"
Wrote README, deployment instructions, and presentation script for lecturer
Created GitHub + Vercel deployment: verified vercel.json present, tested live link

How Meta AI helped:
Asked Meta AI: "Generate Word .doc download code with sign-off embedded"
Meta AI generated Blob download code - Person 4 tested it, ensured Name/Surname appears inside Word doc
Used Meta AI to draft README and to write test checklist: "Test routing, email, approval, responsive"
Used Meta AI to explain Week 7 to a 5-year-old for presentation - helped team explain to panel in simple language
