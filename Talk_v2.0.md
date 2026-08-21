---
marp: true
theme: default
paginate: true
backgroundColor: #0D1B2A
color: #ECEFF4
style: |
  section {
    font-family: 'Segoe UI', Inter, sans-serif;
    font-size: 26px;
    padding: 55px 70px;
  }
  section.title {
    text-align: center;
    justify-content: center;
    background-color: #0D1B2A;
  }
  section.light {
    background-color: #F4F6F8;
    color: #1A1A2E;
  }
  section.divider {
    background-color: #1B9AAA;
    color: #FFFFFF;
    text-align: center;
    justify-content: center;
  }
  section.closing {
    background-color: #0D1B2A;
    color: #ECEFF4;
    text-align: center;
    justify-content: center;
  }
  h1 {
    font-size: 46px;
    font-weight: 700;
    color: #1B9AAA;
    margin-bottom: 10px;
  }
  h2 {
    font-size: 34px;
    font-weight: 700;
    color: #1B9AAA;
    margin-bottom: 14px;
  }
  h3 {
    font-size: 22px;
    font-weight: 600;
    color: #06D6A0;
    margin-bottom: 8px;
  }
  section.light h1, section.light h2 {
    color: #0D1B2A;
  }
  section.light h3 {
    color: #1B9AAA;
  }
  section.divider h1, section.divider h2, section.divider p {
    color: #FFFFFF;
  }
  section.closing h1 {
    color: #1B9AAA;
    font-size: 52px;
  }
  p {
    line-height: 1.6;
    margin: 6px 0;
  }
  ul {
    margin: 8px 0;
    padding-left: 26px;
  }
  li {
    margin-bottom: 8px;
    line-height: 1.5;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 21px;
    margin-top: 14px;
  }
  th {
    background-color: #1B9AAA;
    color: #FFFFFF;
    padding: 9px 13px;
    text-align: left;
  }
  section.light th {
    background-color: #0D1B2A;
  }
  td {
    padding: 7px 13px;
    border-bottom: 1px solid #2E3440;
  }
  section.light td {
    border-bottom: 1px solid #CBD5E0;
    color: #1A1A2E;
  }
  code {
    font-family: 'JetBrains Mono', 'Fira Code', monospace;
    font-size: 17px;
    background-color: #1A2E3E;
    color: #06D6A0;
    padding: 2px 6px;
    border-radius: 4px;
  }
  pre {
    background-color: #1A2E3E;
    border-left: 4px solid #1B9AAA;
    padding: 18px 22px;
    border-radius: 6px;
    overflow: auto;
    font-size: 16px;
    margin: 12px 0;
  }
  pre code {
    background: none;
    padding: 0;
    color: #A8D8EA;
  }
  blockquote {
    border-left: 4px solid #06D6A0;
    padding-left: 20px;
    margin: 14px 0;
    color: #88C0D0;
    font-style: italic;
  }
  section.light blockquote {
    color: #2E5B6E;
  }
  footer {
    font-size: 15px;
    color: #88C0D0;
  }
  section.light footer {
    color: #718096;
  }
---

<!-- _class: title -->

# Microsoft & .NET in South Africa
## Still Relevant?

<br>

**Neil Thompson** & **Zachary Jackson**

*AccsoCON 2026*

<!--
SPEAKER: Neil

Walk on stage. Pause. Let the silence sit for a beat too long.

"Quick show of hands — Java developers in the room? AWS people? Anyone running Spring Boot in production right now?"

Let the hands go up. Nod.

"Perfect. Don't worry — this is a safe space. I won't tell anyone you sat through a .NET talk."

Wait for the laugh. Then shift tone — still warm, but now genuine:

"But seriously — I'm not here to convert anyone. I'm here to tell you what's happening on the other side of the fence. In a country you probably don't immediately think of when you think cutting-edge tech."

Hand over to Zachary.
-->

---

<!-- _class: divider -->

# Part 1
## One Company, Two Contexts

*🎤 Zachary*

---

<!-- _class: light -->

## The Conversation Is Shifting — And That Makes Sense

Across Europe, the conversation around technology choices is evolving.

Questions around **digital sovereignty**, data residency, and dependency on U.S. hyperscalers are real and worth taking seriously. Germany in particular has been thoughtful about evaluating these tradeoffs — and that's a sign of a mature engineering culture, not a rejection of good technology.

Accso's German teams navigate this every day. The considerations are legitimate.

<br>

> This talk isn't about that debate. It's about what's happening in South Africa — and why it matters for all of us at Accso.

<!--
SPEAKER: Zachary

Keep this warm and collegial. You're talking to colleagues, not critics.

"Our German colleagues think carefully about technology choices — and that's something to respect, not argue with. The sovereignty conversation is real and important."

"But South Africa sits in a different context. And we think that context is worth sharing — because we're one company, and what's thriving in Cape Town is relevant to everyone here."
-->

---

<!-- _class: light -->

## .NET in South Africa — Still Very Much Alive

While the technology landscape is always evolving, .NET has deep roots in South Africa — and it's not standing still.

🏢 Microsoft opened its first **African data centres** in Johannesburg & Cape Town in **2019** — a long-term commitment to the continent

☁️ Azure is the **#1 or #2** cloud provider in SA enterprise

🏦 JSE, FNB, Standard Bank, Nedbank — running on Microsoft stacks

🏛️ Government digitisation — largely built on Microsoft platforms

💼 .NET — among the **most in-demand** developer skills in the SA job market

📊 C# — **top 5** most-used languages globally *(Stack Overflow 2025)*

<!--
SPEAKER: Zachary

"Microsoft didn't just sell licences to South Africa. They invested in infrastructure, training, and communities. That investment compounds over 30 years."

"The 2019 data centre announcement mattered enormously — it meant SA enterprises could keep data on African soil, which matters for banking and healthcare compliance."

"C# in the top 5 globally, year after year. This is not a language kept alive by legacy systems. It's actively chosen by developers building new things."
-->

---

<!-- _class: light -->

## One Accso, Two Continents

The SA and Germany teams are part of the same company — and the .NET work we do in Cape Town is directly connected to clients our German colleagues know well.

🎬 **ZDF** — one of Germany's oldest public broadcasters. Built on .NET.

🏛️ **BAFA** — German Federal Office for Economic Affairs. Production .NET.

📡 **DSO** — long-standing Accso project. Same stack.

<br>

**Accso is a Microsoft Gold Partner** — certified expertise, demonstrated delivery, formal relationship with Microsoft.

<br>

> The team building these systems is sitting in Cape Town — working alongside our German colleagues.

<!--
SPEAKER: Zachary

Frame this as a shared story, not a competition. We're one company.

Pause after ZDF, BAFA, DSO. Let the German audience connect the dots — everyone in the room knows what ZDF is.

"This is a shared story. The .NET work happening in Cape Town is connected to clients and projects that matter to all of us."

Hand over to Neil.
-->

---

<!-- _class: divider -->

# Part 2
## What Are We Building With It?

*🎤 Neil*

<!--
SPEAKER: Neil

"So the stack is alive and well in SA. The investment is real. The clients are real. But the more interesting question is: what does it actually let us build in 2026? And is it keeping up?"

"Let's look at Blazor — because it's a good example of where the .NET ecosystem is going, and it's directly relevant if you have .NET people in your team and you're thinking about what to recommend to clients."
-->

---

<!-- _class: light -->

## What is Blazor?

Blazor is Microsoft's framework for building **interactive web UIs in C#** — not JavaScript.

Instead of React components in TypeScript, you write Blazor components in **C# and Razor** — a simple templating syntax that mixes HTML with C# logic.

Those components run either on the **server** or directly in the **browser via WebAssembly**.

The result: a modern web application where the entire codebase — front end and back end — is written in **one language**.

<br>

One language. One team. One codebase. No context switching.

<!--
SPEAKER: Neil

"If you've never heard of Blazor, that's completely fine — this will make everything else make sense."

"One language. One team. One codebase. If you're a .NET shop, that's a pretty compelling proposition."
-->

---

<!-- _class: light -->

## A Blazor Component

```razor
@* Counter.razor — a complete interactive component *@
<h3>Count: @currentCount</h3>
<button @onclick="Increment">Click me</button>

@code {
    private int currentCount = 0;

    private void Increment()
    {
        currentCount++;
    }
}
```

A fully interactive component — click, state update, re-render — in **10 lines**.

No JavaScript. No npm install. No webpack config. Just C#.

<!--
SPEAKER: Neil

Keep this slide up long enough for people to read it. The point isn't to explain every line — it's to show how approachable it is.

"That's it. That's a fully interactive UI component. In about 10 lines. Just C#."
-->

---

<!-- _class: light -->

## Built at Accso — Rocket Poker 🚀

The Accso .NET Community didn't just talk about Blazor — they built something real with it.

**Rocket Poker** is an internal planning poker tool for agile estimation sessions, written **entirely in Blazor**.

Real-time updates across participants. Interactive UI. No JavaScript framework involved.

Just .NET developers building a web application in the language they already knew — and shipping it.

<br>

> Not a tutorial. Not a proof of concept. A tool Accso developers actually use.

<!--
SPEAKER: Neil

"This is the proof of concept right there. Not a tutorial. A real internal tool that real Accso developers use. Built by the .NET Community — in Blazor."
-->

---

<!-- _class: light -->

## "Isn't Blazor Dead Though?"

The short answer: **no**. But the reputation problem is real and worth addressing.

Early Blazor WebAssembly (2019–2020) had genuine performance issues — slow initial load times, heavy bundle downloads. Developers tried it, hit friction, and wrote blog posts. **Those posts still rank on Google in 2026.**

Meanwhile the JavaScript ecosystem is loud — React, Vue, Next.js dominate the press. Blazor is quieter. It just keeps shipping.

Three major releases later, the performance issues are fixed. The people still citing them **haven't looked recently**.

<br>

> Blazor's reputation is being judged on a version that's three major releases old. That's like saying electric cars are bad because you drove one in 2012.

<!--
SPEAKER: Neil

"The early criticism was valid. Those were real problems. The point is they've been addressed systematically, and the people still citing them haven't checked since 2020."
-->

---

## The Agentic Coding Argument

We're entering an era where **AI coding agents write significant chunks of your code**. In that world, the framework you choose matters in ways people aren't talking about enough.

The agent doesn't care what language it writes. **But you should care about what it writes into.**

<br>

**npm:** hundreds of vulnerabilities, three levels deep, in packages you've never heard of — malicious packages, abandoned maintainers, breaking changes.

**NuGet:** curated, centrally governed, Microsoft-maintained at the platform level. Security patching happens at the runtime level, not package by package.

<br>

> When your AI agent writes Blazor, you know what you're getting. 400 transitive npm dependencies? Good luck with that audit.

<!--
SPEAKER: Neil

"We've all seen the npm audit output. Hundreds of vulnerabilities. Critical ones. In packages three levels deep that you've never heard of."

"When your AI agent writes C# and Blazor, it lands in a stable, well-typed, strongly-governed ecosystem. That matters enormously when you're responsible for what ships."
-->

---

<!-- _class: light -->

## Blazor in 2026 — Four Rendering Modes

The framework has matured significantly. There are now four well-considered rendering strategies:

| Mode | How it works | Best for |
|---|---|---|
| **Blazor Server** | UI runs on server, updates via SignalR WebSocket | Internal apps, fast networks |
| **Blazor WebAssembly** | Runs entirely in browser via WASM | Offline-capable apps |
| **Blazor SSR** | Server-side rendered HTML on first request | SEO-critical pages, fast first load |
| **Auto** | SSR on first load, switches to WASM once cached | Best of both worlds |

<br>

The **Auto mode** is genuinely clever — the user gets a fast first load, then full client-side interactivity once the bundle is cached. They never notice the transition.

<!--
SPEAKER: Neil

"You don't need to go deep on all four modes. The point is that the framework has grown up. Four well-considered rendering strategies. That's not a framework standing still."
-->

---

<!-- _class: light -->

## When to Use It — A Practical Guide

If you have .NET people in your team — in SA or in Germany — Blazor is a **genuinely solid option** for the right projects. No new language, no new paradigm.

✅ The team already knows C# — zero context switching, immediate productivity

✅ You want one language across the full stack

✅ Enterprise internal tools, dashboards, admin portals

✅ AI-generated code that needs a stable, auditable ecosystem

✅ Projects tightly integrated with Azure or Microsoft identity

<br>

*If the team has deep JavaScript expertise, don't force it. React still wins on raw component ecosystem size. This is about pragmatic choices, not tribal ones.*

<br>

> The question isn't "is Blazor better than React?" It's: where do you want your AI-generated UI code to land?

<!--
SPEAKER: Neil

"This is the practical question for anyone advising clients — or thinking about their own team's next project. For .NET shops building enterprise internal tooling — Blazor is a solid recommendation in 2026. Whether that team is in Cape Town or Frankfurt."

Hand over to Zachary.
-->

---

<!-- _class: divider -->

# Part 3
## AI in Your Solutions — .NET Makes It Straightforward

*🎤 Zachary*

<!--
SPEAKER: Zachary

"The third thing I want to talk about is AI — not as a buzzword, but as something we're actually being asked to deliver."

"More and more projects require AI to be integrated into the solution itself. Not as a side experiment — as a core feature. Processing applications, analysing documents, extracting information, making decisions based on unstructured data. That's real work, and it's growing."

"And this is exactly where .NET becomes a real consideration. Because the tooling is already there, it fits into patterns your team knows, and you don't need to introduce a second language or a separate service just to add AI capability."
-->

---

<!-- _class: light -->

## AI Is No Longer Optional in Many Projects

More and more, clients are coming to us with AI as a **core requirement** — not a nice-to-have.

Processing applications. Analysing documents. Extracting structured data from unstructured inputs. Routing, classifying, summarising at scale.

These are not research projects. They are **production features** that need to be built, maintained, and trusted.

The question our teams face is: **how do we add AI capability to a .NET solution without introducing a whole new stack?**

<br>

The answer is that the .NET ecosystem has already solved this — and it fits naturally into the patterns your team already knows.

<!--
SPEAKER: Zachary

"We have projects — growing in number — where AI integration is a requirement from day one. Processing applications, document analysis, that kind of work."

"The natural instinct might be to reach for Python. But if your team is in .NET, you don't have to. The tooling is mature, it's model-agnostic, and it slots into your existing architecture without friction."

"Let me show you what that actually looks like."
-->

---

## The Model Doesn't Matter — The Integration Does

The model most of us reach for: **Claude by Anthropic** — excellent for reasoning, document analysis, and long-context tasks.

But the most important thing about the .NET AI ecosystem is that it is **completely model-agnostic**.

Claude, GPT-4, Mistral, or a local model running on your own machine via Ollama — you write your application code once and **swap the model in one line**. Your architecture doesn't change. Your tests don't change. Your deployment doesn't change.

This matters enormously when you're integrating AI into a production solution — you're not locked in, and you're not rebuilding when requirements change.

<!--
SPEAKER: Zachary

"In a real project, the model you use today might not be the model you use in six months. New models come out. Client requirements change. Costs shift."

"The abstraction means you make that change in one place and nothing else breaks. That's the kind of thing that matters when you're building something that has to be maintained."
-->

---

## Microsoft.Extensions.AI — Think HttpClient for LLMs

A unified abstraction layer for AI in .NET. One interface, any model behind it.

```csharp
IChatClient client = new AnthropicChatClient("claude-sonnet-4")
    .AsBuilder()
    .UseLogging()          // every prompt & response logged automatically
    .UseOpenTelemetry()    // AI calls appear in your existing observability stack
    .Build();

var response = await client.CompleteAsync(
    "Summarise this contract in plain English"
);
```

To switch models — change **one line**. App code, tests, and deployment stay the same.

These are not AI-specific features. They are **.NET features that now apply to AI**.

<!--
SPEAKER: Zachary

"Out of the box: logging middleware, OpenTelemetry, retry and rate limiting via Polly, semantic caching. The same patterns .NET developers already know — now applied to AI calls."

"That's the power of the abstraction."
-->

---

## Semantic Kernel — Your App Calls the AI. The AI Calls Your App.

Semantic Kernel is Microsoft's open-source SDK for building AI-powered applications in C#. Think of it as the **orchestration layer** between your application and any LLM.

```csharp
var kernel = Kernel.CreateBuilder()
    .AddAnthropicChatCompletion("claude-sonnet-4", apiKey)
    .Build();

kernel.ImportPluginFromType<InvoicePlugin>();  // wrap your C# method as an AI tool

var result = await kernel.InvokePromptAsync(
    "Find all overdue invoices from last quarter and total them up"
);
```

The AI reasoned about the tools available and **decided on its own** to call your code.

You didn't tell it to. **That's an agent.**

<!--
SPEAKER: Zachary

"What just happened there? The AI decided — on its own — that it needed to call your InvoicePlugin. It reasoned about the tools available and used the right one."

"You can wrap any existing C# method as a tool the AI can call. That's it. Your existing business logic becomes AI-callable with one line."
-->

---

## RAG — Your Documents. Your Answers.

Instead of relying on what the model was trained on, you feed it **your own content** at query time. The model reasons over your documents. The answers are grounded in what you actually wrote.

```csharp
await vectorStore.UpsertAsync(new TextDocument
{
    Id = "policy-2026",
    Text = File.ReadAllText("company-policy.txt")
});

var answer = await kernel.InvokePromptAsync(
    "What is our policy on remote work expenses?"
);
// Returns answer grounded in your actual policy document
```

This pattern is **replacing internal wikis, policy docs, and FAQ pages** across SA enterprises — not because it's trendy, but because it works.

<!--
SPEAKER: Zachary

"RAG — Retrieval Augmented Generation. The technique behind most enterprise AI tools that actually work in production."

".NET developers can build this without learning a new language or a new paradigm. It fits into the patterns they already know."
-->

---

## Streaming AI in a Blazor App

Combine Blazor + SignalR + Microsoft.Extensions.AI and you get **real-time streaming AI responses** — built entirely in C#.

```csharp
// In your Blazor component — no JavaScript needed
await foreach (var chunk in chatClient.CompleteStreamingAsync(userMessage))
{
    responseText += chunk.Text;
    StateHasChanged();  // Blazor re-renders with each chunk
}
```

The same typing effect you see in Claude or ChatGPT.

**No JavaScript. No separate frontend team. One language. One codebase. One deployment.**

<!--
SPEAKER: Zachary

"Blazor for the UI, SignalR for the real-time WebSocket, Microsoft.Extensions.AI for the LLM call. Genuinely powerful and underappreciated."

"Most people haven't tried this combination yet. The ones who have tend not to go back."
-->

---

<!-- _class: light -->

## The Practical Answer — For Any Team With .NET People

The AI conversation has moved on. Nobody is asking "should we use AI?" anymore.

The real question is: **"How do we use it responsibly, securely, and with the skills we already have?"**

<br>

The .NET stack answers all three — whether your team is in Cape Town or Frankfurt:

**Model-agnostic abstractions** — swap Claude for Mistral in one line, no application changes.

**Enterprise-grade observability** — AI calls appear in your existing logging and telemetry.

**Strongly-typed, auditable code** — the same compile-time guarantees your team already relies on.

<br>

> If you have .NET people — this stack is ready for AI. Right now. No new paradigm required.

<!--
SPEAKER: Zachary

"If you're advising a client — or thinking about your own team's next project — and you have .NET people, you don't have to tell them to hire Python engineers or learn a new paradigm. The tooling is there. It works. And it's built on patterns they already know."

Hand over to Neil.
-->

---

<!-- _class: divider -->

# Part 4
## The Community Proving It

*🎤 Neil*

<!--
SPEAKER: Neil

"I've talked about what the stack can do. Now let me show you the living proof that it's not theoretical."
-->

---

<!-- _class: light -->

## Cape Town MS Developer User Group

🌐 **cptmsdug.dev**

<br>

👥 **2,180 members** — 63 joined recently

📅 **150+ past events**

⭐ **4.7 / 5** on Meetup

🏛️ Part of the **.NET Foundation** — one of 184 groups worldwide

🎤 **100+ speakers** have presented at our events

📆 **12+ years** running

<br>

*Connecting developers, sharing knowledge, and building the future with Microsoft technologies in the Mother City.*

<!--
SPEAKER: Neil

"Let me tell you about something I'm more proud of than any framework or code sample. Our community."

"2,180 members. 63 joined recently. 12 years. In Cape Town. For a Microsoft developer community. I'll let that speak for itself."
-->

---

<!-- _class: light -->

## The Community Shows Up

These are not passive members. They actually show up.

| Event | Attendees |
|---|---|
| Teaching AI Agents & ASP.NET Core | **95** |
| GitHub Copilot Dev Days 2026 | **110** |
| Microsoft BUILD //localhost Cape Town | **92** |
| Monkeys in Production + LangChain AI Agents | **107** |
| VS Code Dev Days — SOLD OUT | **97** |
| GitHub Copilot Global Bootcamp | **98** |
| .NET Conf 2025 Cape Town | 🏆 **SOLD OUT — biggest ever in SA** |
| Games Evening — next week at the Accso office | **94 registered** |

<!--
SPEAKER: Neil

".NET Conf 2025 Cape Town was the biggest .NET Conf event in the history of South Africa. In any city."

"And 94 people are registered for our Games Evening next week — at the Accso office. Pizza, trivia, Kahoot. That's the culture."
-->

---

## 📅 .NET Conf South Africa — Cape Town

**Saturday, 28 November 2026**

CPTMSDUG is hosting **.NET Conf South Africa** in Cape Town this year.

Speakers, sessions, and networking — celebrating the South African .NET community at a national level.

<br>

**Accso is directly connected** — as venue partner and sponsor.

<br>

> We went from hosting monthly meetups in our office to bringing a national conference to Cape Town. Accso is part of that story.

<!--
SPEAKER: Neil

"This is something I'm genuinely excited about."

"Accso's involvement has grown from putting our logo on a sponsor page to being a core part of how this community operates and scales. That's a different level of visibility in the local tech market."
-->

---

<!-- _class: light -->

## Accso Cape Town Hosts CPTMSDUG

📍 **V&A Waterfront, Clock Tower** — one of our primary regular venues

Named sponsor alongside **Microsoft, JetBrains, the .NET Foundation, and UWC**

<br>

| When | Attendees |
|---|---|
| February 2026 | 61 developers at the Accso office |
| April 2026 | 57 developers at the Accso office |
| July 2026 | 95 developers at the Accso office |
| Next week | 94 registered |

<br>

> Developers walk into an Accso office and leave knowing who we are.

<!--
SPEAKER: Neil

"Here's what's directly relevant to everyone in this room."

"The numbers tell the story. Don't over-explain — let the audience do the maths on what it means to have 57, 61, 95 developers walking through your office door regularly."

"That's not a marketing campaign. That's a relationship built by showing up, consistently, for years."
-->

---

<!-- _class: light -->

## Why This Community Matters

**For developers** — real knowledge, real mentorship, real careers built here. SA's formal education moves slowly. This community fills the gap in real time.

**For the ecosystem** — **Richard Campbell**, host of .NET Rocks (one of the longest-running developer podcasts in the world), came to Cape Town because of this community. **Matthew Leibowitz**, Principal Software Engineer at Microsoft and maintainer of SkiaSharp, is a co-organiser. Microsoft's own engineers help run our meetups.

**For Accso** — 2,180 potential future colleagues. A brand that means something in the local talent pool. A direct connection to .NET Conf South Africa.

<!--
SPEAKER: Neil

"This isn't a community that exists on paper. It shows up. 100 people on a Wednesday evening, after work, because they're genuinely excited about what they're building."

"That's the culture .NET has in Cape Town. And Accso gets to be part of it."

Hand over to both for the close.
-->

---

<!-- _class: divider -->

# Wrapping Up

*🎤 Both*

---

<!-- _class: light -->

## The Bottom Line

**The technology landscape is always evolving — and that's healthy.**
Our German colleagues navigate those tradeoffs thoughtfully every day. We respect that.

**In South Africa, .NET is thriving.**
Microsoft-shaped infrastructure, a growing skills market, real enterprise delivery — including for German clients we all know.

**If you have .NET people — SA or Germany — there's exciting stuff to build.**
Blazor for modern UIs in a governed, agentic-coding-friendly ecosystem. AI integration that's genuinely straightforward with the tools your team already knows.

**The community in Cape Town is the living proof.**
2,180 members. 150+ events. 12 years running. Still growing. Still showing up. And Accso is right in the middle of it.

<!--
SPEAKER: Both

Tie it back to the opening — collegial, not competitive.

"We're one company. The .NET expertise in Cape Town and the engineering culture in Germany aren't in opposition — they're complementary. We wanted to show you what's alive and well on our side of the world."

"And we hope some of it is useful — or at least surprising."
-->

---

<!-- _class: closing -->

# Still Relevant?

<br>

*We'll let you decide.*

*But from where we're standing —*
*it looks pretty good from here.*

<br>

🌐 cptmsdug.dev
📍 meetup.com/cape-town-ms-dev-user-group

<!--
SPEAKER: Neil closes:

"So — thank you for staying. You didn't have to. The door was right there the whole time."

"We're not here to tell anyone what stack to use. We're here to show you what's alive and thriving in Cape Town — and why the .NET people in your team, wherever they are, have a lot of exciting things ahead of them."

Both together on the final line:

"Still relevant? We'll let you decide. But from where we're standing — it looks pretty good from here."
-->

---

<!-- _class: title -->

# Questions?

<br>

🌐 **cptmsdug.dev**

📍 **meetup.com/cape-town-ms-dev-user-group**

✉️ **usergroup@cptmsdug.dev**

<!--
SPEAKER: Both

Both on stage. Neil takes community questions, Zachary takes tech questions.

Common questions to be ready for:

"Why not just use Python for AI?" — Python is excellent for model training and data science. .NET is where the enterprise applications live. With Microsoft.Extensions.AI you use Claude, Mistral, or any model in C#. No language switch needed.

"Which model do you actually use?" — Mostly Claude. The beauty of the abstraction is you swap it in one line — pick the best model for the job.

"Is Blazor actually in production anywhere?" — SA financial services, healthcare portals, government systems. ZDF. Not glamorous — but real, maintained, and shipping.

"What about npm vs NuGet — isn't NuGet also a risk?" — NuGet is significantly more curated and centrally governed. The scale of the npm vulnerability problem doesn't have a direct equivalent in the .NET ecosystem.

"How do I join CPTMSDUG?" — meetup.com/cape-town-ms-dev-user-group — free, open to everyone. And if you're ever in Cape Town, come to the office on a Wednesday evening.
-->
