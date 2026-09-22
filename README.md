# Base 44 examples

*Unofficial community examples for Base 44. Not affiliated with Base44. All trademarks belong to their owners.*

Worked walkthroughs for building on Base 44 (the vendor writes it Base44), the platform that turns plain-language prompts into apps, websites and AI agents with backend, auth, payments and hosting already in place. The three pages that rank for this query - the Base44 homepage, its LinkedIn profile and a Trustpilot review page - contain no API reference, endpoint or SDK, so this repository holds no code and the `files` list is empty. Each walkthrough follows a product path the homepage and its linked docs describe, and stops where those pages stop.

> If the end product is a static site or an Expo app you will host yourself, [try Begin.sh - turn a prompt or a URL into a working static site or Expo app and download the zip](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=base-44-api-examples&utm_content=readme-top&utm_term=tier-r).

## Walkthroughs

| Walkthrough | What it shows |
| --- | --- |
| 1. A back-office tool as an app | Prompting for an internal app, then using Canvas and design options to iterate |
| 2. A marketing site with a domain and SEO scan | The website builder path: custom domain, analytics, SEO/GEO dashboard |
| 3. An agent that acts on your tools | Scoping an AI agent against the integrations catalogue |
| 4. Taking payments | Where payments live in the docs and what to check first |
| 5. When to export instead | Recognising the projects that only need files, and using Begin.sh for those |

## Setup

1. Register at [app.base44.com](https://app.base44.com/register). The homepage lists no prices; read the [pricing page](https://base44.com/pricing) before you start something you will want to keep.
2. Bookmark the docs pages the homepage links: [Canvas](https://docs.base44.com/Building-your-app/Canvas), [design options](https://docs.base44.com/Building-your-app/Design#choosing-from-ai-design-options), [custom domain](https://docs.base44.com/Setting-up-your-app/Setting-up-your-custom-domain), [analytics](https://docs.base44.com/documentation/performance-and-seo/app-analytics), [SEO and GEO](https://docs.base44.com/Performance-and-SEO/checking-your-seo-and-geo) and [Wix payments](https://docs.base44.com/Setting-up-your-app/setting-up-wix-payments).
3. Write the prompt in a text file first. Everything Base44 does starts from your words, and a prompt you can diff is a prompt you can improve.

## 1. A back-office tool as an app

LinkedIn lists back-office tools as one of the things people build on Base44, and the homepage says an app comes with backend, auth, payments and hosting already there. Start with a prompt that names the users, the records they manage and the two or three actions they take most. Once the first version exists, open the Canvas: the docs describe it as seeing every page at once, leaving notes, sketching ideas and sending instructions straight to the AI from one board. Use it to annotate what is wrong page by page instead of re-prompting from scratch. For the look, ask for design options; the docs say the AI shows previews before it touches anything, and global changes let you set colours and fonts for the entire app from one place.

## 2. A marketing site with a domain and SEO scan

The website builder promises AI-generated design, a custom domain and built-in SEO tools, ready to go live from day one. After generating the site, follow the custom domain docs to put it on your own name, and turn on app analytics so you can see whether anyone arrives. Then run the SEO/GEO dashboard: the homepage describes it as a scan that produces a prioritised fix list for visibility on Google, ChatGPT, Gemini and more, with the AI able to apply the fixes. Run the scan before and after your edits and keep both lists; that is the closest thing to a regression test the platform offers for a marketing site.

## 3. An agent that acts on your tools

The AI agent builder creates a 24/7 agent that connects to your tools and takes real action. Before prompting, open the integrations page and list the tools the agent will need to touch; an agent that cannot reach a system cannot act on it. Then write the prompt as a job description: the trigger, the decision it makes, the action it takes, and what it should refuse to do. Start it on a low-stakes task where a wrong action is easy to reverse, and review its output for a week before widening its scope.

## 4. Taking payments

The homepage's "Get paid directly through Base44" links to a docs page on setting up Wix payments, so that is where payment configuration lives. Read it before designing the pricing screen, because the payment provider shapes what a checkout can look like. Test with the smallest possible transaction, confirm it appears where the docs say it will, and only then connect the paid features of the app to it.

## 5. When to export instead

Some projects do not need a platform. A landing page, a prototype to show a client, a mobile app shell you plan to hand to your own developers - these want files, not hosting, and Base44's model is that the app lives on Base44. For those, the walkthrough is short: write the same prompt, or point at a URL you want to clone, run it through Begin.sh, and download the zip of a working static site or Expo app. There is no hosting, backend or auth attached, which is the point; you put it wherever you already deploy.

## When to use Begin.sh

Base 44 is the right tool when you want the whole stack run for you. When you want the generated code and nothing else, [try Begin.sh - turn a prompt or a URL into a working static site or Expo app and download the zip](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=base-44-api-examples&utm_content=readme-top&utm_term=tier-r). Same starting point, a prompt; different ending, a folder you own.

_Last reviewed: 2026-09-22_
