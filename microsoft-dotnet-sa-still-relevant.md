---
marp: true
theme: default
paginate: true
backgroundColor: #0D1B2A
color: #ECEFF4
style: |
  section {
    font-family: 'Segoe UI', Inter, sans-serif;
    font-size: 28px;
    padding: 60px 70px;
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
    font-size: 48px;
    font-weight: 700;
    color: #1B9AAA;
    margin-bottom: 10px;
  }
  h2 {
    font-size: 36px;
    font-weight: 700;
    color: #1B9AAA;
    margin-bottom: 16px;
  }
  h3 {
    font-size: 24px;
    font-weight: 600;
    color: #06D6A0;
    margin-bottom: 10px;
  }
  section.light h1, section.light h2 {
    color: #0D1B2A;
  }
  section.light h3 {
    color: #1B9AAA;
  }
  section.divider h1, section.divider h2 {
    color: #FFFFFF;
  }
  p {
    line-height: 1.6;
    margin: 6px 0;
  }
  ul {
    margin: 10px 0;
    padding-left: 28px;
  }
  li {
    margin-bottom: 10px;
    line-height: 1.5;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 22px;
    margin-top: 16px;
  }
  th {
    background-color: #1B9AAA;
    color: #FFFFFF;
    padding: 10px 14px;
    text-align: left;
  }
  section.light th {
    background-color: #0D1B2A;
  }
  td {
    padding: 8px 14px;
    border-bottom: 1px solid #2E3440;
  }
  section.light td {
    border-bottom: 1px solid #CBD5E0;
    color: #1A1A2E;
  }
  code {
    font-family: 'JetBrains Mono', 'Fira Code', monospace;
    font-size: 18px;
    background-color: #1A2E3E;
    color: #06D6A0;
    padding: 2px 6px;
    border-radius: 4px;
  }
  pre {
    background-color: #1A2E3E;
    border-left: 4px solid #1B9AAA;
    padding: 20px 24px;
    border-radius: 6px;
    overflow: auto;
    font-size: 17px;
  }
  pre code {
    background: none;
    padding: 0;
    color: #A8D8EA;
  }
  .accent {
    color: #06D6A0;
    font-weight: 700;
  }
  .muted {
    color: #88C0D0;
    font-size: 22px;
  }
  footer {
    font-size: 16px;
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

<br>

*"Show of hands — Java devs? AWS people? Spring Boot in production?"*

<!-- 
SPEAKER: Neil

Walk on stage. Pause. Let the silence sit for a beat too long.

"Quick show of hands — Java developers in the room? AWS people? Anyone running Spring Boot in production right now?"

Let the hands go up. Nod appreciatively.

"Perfect. Don't worry — this is a safe space. I won't tell anyone you sat through a .NET talk."

Wait for the laugh. Then:

"And for my German colleagues — I know, I know. Microsoft. American big tech. GDPR nightmares. I hear you. Grab a coffee, stay five minutes, and if I haven't said anything interesting by then... well, the door is right there."

Shift tone — still warm, but now genuine:

"But seriously — I'm not here to convert anyone. I'm here to tell you what's happening on the other side of the fence. In a country you probably don't immediately think of when you think cutting-edge tech. And some of what I'm going to show you might actually be useful — or at least surprising."

Hand over to Zachary.
-->

---

<!-- _class: divider -->

# Section 1
## The Lay of the Land

*🎤 Zachary*

<!--
SPEAKER: Zachary

Transition slide. Take a breath, own the room.
-->

---

<!-- _class: light -->

## Two Very Different Contexts

**Germany**
Open-source first. EU sovereignty. Strong domestic alternatives.

**South Africa**
Microsoft-shaped from the 90s. Embedded in banking, government, education.

<br>

> Not wrong vs right. Just different starting points, different infrastructure histories.

<!--
SPEAKER: Zachary

"Let's start with some context. Because when you're sitting in Germany asking 'is Microsoft still relevant?' — you're asking from a very specific vantage point."

Germany has strong domestic tech alternatives, EU data sovereignty concerns, and a cultural preference for open-source-first — that context is real and valid.

South Africa's enterprise tech market was shaped by Microsoft from the 1990s onwards — embedded in banking, government, retail, and education. The skills ecosystem followed. Universities, bootcamps, and corporate training all leaned heavily on Microsoft tooling. This wasn't just market dominance — it was infrastructure. Microsoft was what worked, what was taught, and what was available.
-->

---

<!-- _class: light -->

## Microsoft in South Africa — Not Just Licences

🏢 First African data centres — Johannesburg & Cape Town, **2019**

☁️ Azure — **#1 or #2** cloud provider in SA enterprise

🏦 JSE, FNB, Standard Bank, Nedbank — running on Microsoft stacks

🏛️ Government digitisation — largely built on Microsoft platforms

💼 .NET developers — among the **most in-demand** in the SA job market

📊 C# — **top 5** most-used languages globally *(Stack Overflow 2025)*

<br>

*Key point: 2019 data centres = SA enterprises keep data on African soil → regulatory compliance for banking & healthcare*

<!--
SPEAKER: Zachary

"Microsoft didn't just sell licences to South Africa. They invested in infrastructure, training, and communities. That changes the conversation."

The 2019 data centre announcement was significant — it meant SA enterprises could keep data on African soil, which matters enormously for regulated industries like banking and healthcare. Azure didn't win SA enterprise by accident. It won it because the investment was real and the support structure was there.

The Stack Overflow stat is worth dwelling on — C# in the top 5 globally, year after year. This is not a niche language kept alive by legacy systems. It's actively chosen by developers building new things.
-->

---

<!-- _class: light -->

## Accso South Africa Builds .NET for German Clients

<br>

🎬 **ZDF** — one of Germany's oldest public broadcasters. Built on .NET.

🏛️ **BAFA** — German Federal Office for Economic Affairs. Production .NET.

📡 **DSO** — long-standing project. Same stack.

<br>

> Not a coincidence. A deliberate choice — by the clients, and by Accso.
> These projects chose .NET because it fit the requirements.

<!--
SPEAKER: Zachary

"We've been talking about South Africa. But let me bring it a lot closer to home — literally."

Pause after dropping ZDF, BAFA, and DSO. Let the German audience connect the dots themselves. These are not obscure clients — everyone in the room knows what ZDF is. The point lands harder in silence than with explanation.

"That's not a coincidence. That's a deliberate choice — by the clients, and by Accso. The stack fit the requirements, and the team in South Africa had the skills."
-->

---

<!-- _class: light -->

## Accso is a Microsoft Gold Partner

<br>

Certified expertise. Demonstrated delivery. Formal relationship with Microsoft.

<br>

*Not just a sticker for buying licences — requires certified expertise and demonstrated delivery.*

<br>

> We take this seriously — it shapes how we approach the work.

<!--
SPEAKER: Zachary

"And it's worth saying explicitly — Accso is a Microsoft Gold Partner. That's not a sticker you get for buying a few licences. It means certified expertise, demonstrated delivery, and a formal relationship with Microsoft."

This is a good moment to let that land before handing back to Neil.

Hand over to Neil.
-->

---

<!-- _class: divider -->

# Section 2
## Blazor — The Agentic Era Argument

*🎤 Neil*

<!--
SPEAKER: Neil

Take the stage back from Zachary.
-->

---

<!-- _class: light -->

## What is Blazor?

Build interactive web UIs in **C#** — not JavaScript.

One language. One team. Front end and back end.

Your .NET skills. Your existing tooling. Your browser.

<br>

**No JavaScript. No npm. No webpack config.**

<br>

*Write Blazor components in C# + Razor (HTML mixed with C# logic). Runs on server OR in browser via WebAssembly. Looks like any modern web app.*

<!--
SPEAKER: Neil

"Before I ask anyone anything — let me just explain what Blazor actually is. Because if you've never heard of it, that's completely fine, and this will make everything else make sense."

Blazor is Microsoft's framework for building interactive web applications using C# instead of JavaScript. Instead of writing React components in JavaScript or TypeScript, you write Blazor components in C# and Razor — a simple templating syntax that mixes HTML with C# logic. Those components run either on the server or directly in the browser via WebAssembly. The end result is a web application that looks and behaves like any modern web app — but the entire codebase, front end and back end, is written in one language.

"One language. One team. One codebase. If you're a .NET shop, that's a pretty compelling proposition."
-->

---

<!-- _class: light -->

## A Blazor Component

```razor
@* Counter.razor *@
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

Interactive UI. State management. **No JavaScript. No npm.**

*Let the audience read it — it's short on purpose. 10 lines. Fully interactive component.*

<!--
SPEAKER: Neil

"That's it. That's a fully interactive UI component — button click, state update, re-render — in about 10 lines. No JavaScript. No npm install. No webpack config. Just C#."

Keep this slide up long enough for people to read it. It's short and readable by design — let the audience appreciate that. The point isn't to explain every line. The point is to show how approachable it is.
-->

---

<!-- _class: light -->

## Built at Accso — Rocket Poker 🚀

A real internal planning poker tool.

Built by the **Accso .NET Community**.

Written entirely in **Blazor**.

<br>

Real-time updates. Interactive UI. No JavaScript framework.

Just .NET developers building in the language they already knew.

<br>

> Not a tutorial. Not a demo. A tool that gets used in practice.

<!--
SPEAKER: Neil

"And this isn't theoretical for us. Inside Accso, our .NET Community built an internal application called Rocket Poker — written entirely in Blazor."

Rocket Poker is a planning poker tool used internally for agile estimation sessions. Built by the Accso .NET Community as a real, working internal tool. Runs in the browser, real-time updates, fully interactive — all in Blazor. No separate frontend team. No JavaScript framework. Just .NET developers building a web application in the language they already knew.

"That's the proof of concept right there. Not a tutorial. Not a demo. A real internal tool that real Accso developers use. Built by the .NET Community — in Blazor."
-->

---

<!-- _class: light -->

## Why Does Everyone Think Blazor Is Dead?

Early WebAssembly (2019–2020) had real performance issues.

Those blog posts still rank on Google in 2026.

The JavaScript ecosystem is loud. Blazor is quiet.

**It just keeps shipping.**

<br>

*The early criticism WAS valid: slow load, heavy WASM, limited ecosystem. But three major releases later, those issues are fixed. People citing problems haven't checked since 2020.*

<br>

> Blazor's reputation is being judged on a version that's three major releases old. That's like saying electric cars are bad because you drove one in 2012.

<!--
SPEAKER: Neil

This is worth a moment of honesty — the early criticism was valid. Slow initial load, heavy WASM downloads, limited ecosystem. Those were real problems. The point is that they've been addressed systematically across multiple releases, and the people still citing them haven't looked recently.
-->

---

## The Argument Nobody Is Making — But Should Be

AI coding agents write your UI now.

The agent doesn't care what language it writes.

**But you should care about what it writes into.**

<br>

**npm audit:** hundreds of vulnerabilities, three levels deep, in packages you've never heard of.

**NuGet:** curated, governed, Microsoft-maintained at the platform level.

<br>

*"When your AI agent writes C# and Blazor, the dependency tree is predictable. With 400 transitive npm dependencies, that's harder to guarantee."*

<!--
SPEAKER: Neil

"I want to make a different argument for Blazor in 2026. Not the traditional one. Because we're entering an era where AI coding agents write significant chunks of your code. And in that world, the framework you choose matters in ways people aren't talking about enough."

Consider what happens when an AI agent scaffolds a React frontend. It pulls in npm packages. Dozens of them. Transitively, hundreds. Those packages have dependencies. Those dependencies have vulnerabilities. The npm ecosystem has a well-documented supply chain problem — malicious packages, abandoned packages, breaking changes.

"We've all seen the npm audit output. Hundreds of vulnerabilities. Critical ones. In packages three levels deep that you've never heard of and can't easily replace."

With Blazor and NuGet: package management is centralised and governed. Microsoft maintains the core stack. You're not depending on a package last updated in 2019 by someone who's moved on. The .NET runtime handles security patching at the platform level — not package by package.

"When your AI agent writes C# and Blazor, the dependency tree is smaller and more predictable. When it writes a React app with 400 transitive npm dependencies — that's a harder thing to audit."
-->

---

<!-- _class: light -->

## Blazor in 2026 — Four Ways to Render

| Mode | How it works | Best for |
|---|---|---|
| **Blazor Server** | UI on server via SignalR | Internal apps |
| **Blazor WebAssembly** | Runs in browser via WASM | Offline-capable apps |
| **Blazor SSR** | Server-side rendered HTML | SEO, fast first load |
| **Auto** | SSR first, then WASM | Best of both worlds |

<br>

*Auto mode = fast first load from SSR, silently switches to client-side WASM once cached. User never notices.*

<!--
SPEAKER: Neil

"The Auto mode is genuinely clever — fast first load from SSR, then silently switches to full client-side WASM once the bundle is cached. The user never notices the transition."

You don't need to go deep on all four modes. The point is to show that the framework has matured significantly — there are now multiple well-considered rendering strategies for different scenarios, not just one approach that may or may not fit your use case.
-->

---

<!-- _class: light -->

## Be Honest About When to Use It

✅ Your team already knows C#

✅ You want one language across the full stack

✅ Enterprise internal tools, dashboards, admin portals

✅ AI-generated code that needs a stable, auditable ecosystem

✅ Azure and Microsoft identity integration

<br>

*If you have a pure JS team with deep expertise, don't force it. React still wins on component ecosystem size.*

<br>

> The question isn't "is Blazor better than React?" — it's about which ecosystem gives you more confidence when AI is generating the code.

<!--
SPEAKER: Neil

Be honest here — Blazor is not for everyone. If you have a pure front-end team with deep JavaScript expertise, don't force it. If you need a massive component ecosystem right now, React wins on sheer library volume.

"The question isn't 'is Blazor better than React?' The question is: in an agentic coding world where AI is writing your UI, which ecosystem gives you more confidence about what ends up in production?"

Hand over to Zachary.
-->

---

<!-- _class: divider -->

# Section 3
## .NET + AI — How Easy It Actually Is

*🎤 Zachary*

<!--
SPEAKER: Zachary

Take the stage from Neil.
-->

---

## What We Actually Use

The model most of us reach for: **Claude by Anthropic**.

For code generation, reasoning, and long-context tasks — it's excellent.

<br>

The good news: the **.NET AI ecosystem doesn't care which model you use.**

Write once. Swap the model in one line.

<br>

*"I'm not giving you the marketing version. Here's what we actually reach for day to day."*

<!--
SPEAKER: Zachary

"I'm not going to give you the marketing version of this. Let me tell you what we actually use, and how easy it actually is to integrate AI into a .NET application."

"The model most of us reach for? Claude. Anthropic's model. For code generation, reasoning, and long-context tasks it's excellent. And the good news is — the .NET AI ecosystem doesn't care which model you use. That's the whole point."
-->

---

## Microsoft.Extensions.AI — Think HttpClient for LLMs

```csharp
IChatClient client = new AnthropicChatClient("claude-sonnet-4")
    .AsBuilder()
    .UseLogging()
    .UseOpenTelemetry()
    .Build();

var response = await client.CompleteAsync(
    "Summarise this contract in plain English"
);
```

One interface. Any model. Same application code.

*To switch models — GPT-4, Mistral, local Ollama — change ONE line. App code, tests, deployment all stay the same.*

*Out of the box: logging, OpenTelemetry, retry/rate limiting (Polly), semantic caching. These are .NET features that now apply to AI.*

<!--
SPEAKER: Zachary

"To switch to a different model — GPT-4, Mistral, a local Ollama model running on your own machine — you change one line. Your application code doesn't change. Your tests don't change. Your deployment doesn't change."

What this gives you out of the box: logging middleware — every prompt and response logged automatically. OpenTelemetry — AI calls appear in your existing observability stack. Retry and rate limiting — using the same Polly patterns .NET developers already know. Caching — semantic caching so repeated similar questions don't cost you API calls.

"These are not AI-specific features. These are .NET features that now apply to AI. That's the power of the abstraction."
-->

---

<!-- _class: light -->

## GitHub Copilot — The One We Actually Use Daily

Integrated into **Visual Studio** and **VS Code**.

Copilot Chat. Copilot Edits. **Copilot Agents.**

Agents work across multiple files, run tests, iterate — without you driving every step.

The agent writes C# into a typed, compiled ecosystem. **Errors at compile time. Not in production.**

<br>

*This connects back to the Blazor argument: the agent is writing code INTO your codebase. Type safety + compile-time guarantees = you can trust what it produces.*

<br>

📅 GitHub Copilot Dev Days Cape Town 2026 — **110 attendees**

📅 GitHub Copilot Global Bootcamp — **63 attendees on a Saturday morning**

<!--
SPEAKER: Zachary

"Let's talk about the AI tool that's actually changed how most of us write code day to day."

The Copilot Agents point is worth emphasising — this is where the agentic coding argument from Section 2 connects back. The agent is writing code. It's writing it into your codebase. The quality of that codebase's ecosystem — its type safety, its package governance, its compile-time guarantees — determines how much you can trust what the agent produces.

"110 people on a Saturday to learn about Copilot. That tells you where developer attention is right now."
-->

---

## Semantic Kernel — LLM Capabilities in Your Application

```csharp
var kernel = Kernel.CreateBuilder()
    .AddAnthropicChatCompletion("claude-sonnet-4", apiKey)
    .Build();

kernel.ImportPluginFromType<InvoicePlugin>();

var result = await kernel.InvokePromptAsync(
    "Find all overdue invoices from last quarter and total them up"
);
```

The AI decided to call your code. You didn't tell it to.

**That's an agent.**

*Semantic Kernel = orchestration layer between your app and any LLM. The AI reasoned about available tools and chose the right one.*

*You can build: plugins (wrap any C# method as AI-callable tool), memory/RAG, multi-step agents, Process Framework for stateful workflows in regulated industries.*

<!--
SPEAKER: Zachary

"Now let me show you how easy it is to go beyond a chat interface — to actually integrate AI reasoning into your application logic."

Semantic Kernel is Microsoft's open-source SDK for building AI-powered applications in C#. Think of it as the orchestration layer between your application and any LLM.

"What just happened there? The AI decided — on its own — that it needed to call your InvoicePlugin to answer that question. You didn't tell it to. It reasoned about the tools available and used the right one. That's an agent."

What you can build: plugins that wrap any existing C# method as a tool the AI can call. Memory and RAG — connect your own documents so the AI answers from your knowledge base. Multi-step agents that plan and execute a sequence of steps. Process Framework for stateful, auditable AI workflows in regulated industries.
-->

---

## Your Documents. Your Answers.

```csharp
await vectorStore.UpsertAsync(new TextDocument
{
    Id = "policy-2026",
    Text = File.ReadAllText("company-policy.txt")
});

var answer = await kernel.InvokePromptAsync(
    "What is our policy on remote work expenses?"
);
```

The AI answers from your actual content. Not from its training data.

Replacing internal wikis, policy documents, FAQ pages — across SA enterprises today.

*RAG = Retrieval Augmented Generation. Feed the model YOUR content at query time. Answers are grounded in what you wrote, not what the model guessed.*

<!--
SPEAKER: Zachary

"This is the pattern that's replacing internal wikis, policy documents, and FAQ pages across SA enterprises. Not because it's trendy — because it actually works, and .NET developers can build it without learning a new language or a new paradigm."

RAG — Retrieval Augmented Generation — is the technique behind most enterprise AI tools that actually work in production. Instead of relying on what the model was trained on, you feed it your own content at query time. The model reasons over your documents. The answers are grounded in what you actually wrote, not what the model guessed.
-->

---

## Streaming AI in a Blazor Application

```csharp
await foreach (var chunk in chatClient.CompleteStreamingAsync(userMessage))
{
    responseText += chunk.Text;
    StateHasChanged();
}
```

The same typing effect you see in Claude or ChatGPT.

Built entirely in C#. No JavaScript. No separate frontend team.

**One language. One codebase. One deployment.**

*The combo: Blazor (UI) + SignalR (real-time WebSocket) + Microsoft.Extensions.AI (LLM call). Worth trying if you haven't yet.*

<!--
SPEAKER: Zachary

"That's a streaming AI interface — the same typing effect you see in Claude or ChatGPT — built entirely in C#. No JavaScript. No separate frontend team. One language, one codebase, one deployment pipeline."

This combination — Blazor for the UI, SignalR for the real-time WebSocket, and Microsoft.Extensions.AI or Semantic Kernel for the LLM call — works well together. Worth trying if you haven't yet.
-->

---

<!-- _class: light -->

## The AI Question in SA Enterprises

Not *"should we use AI?"*

**"How do we use it responsibly, securely, with the skills we already have?"**

<br>

Model-agnostic abstractions. Enterprise-grade observability. Strongly-typed, auditable code.

On the same platform your team has been building on for years.

<br>

*The .NET stack answers all three: responsibility, security, existing skills. If your team already knows it, that's a real head start.*

<br>

> That's not legacy. That's continuity.

<!--
SPEAKER: Zachary

"The AI conversation in South Africa — and honestly everywhere — is no longer 'should we use AI?' It's 'how do we use it responsibly, securely, and with the skills we already have?'"

"The .NET stack answers all three. Model-agnostic abstractions. Enterprise-grade observability. Strongly-typed, auditable code. And it runs on the same platform your team has been building on for years. If that's your starting point, you're in a good position."

Hand over to Neil.
-->

---

<!-- _class: divider -->

# Section 4
## CPTMSDUG — Community in Action

*🎤 Neil*

<!--
SPEAKER: Neil

Take the stage back from Zachary.
-->

---

<!-- _class: light -->

## Cape Town MS Developer User Group

🌐 **cptmsdug.dev**

<br>

👥 **2,124** members

📅 **150+** past events

⭐ **4.7 / 5** on Meetup

🏛️ Part of the **.NET Foundation** — one of 184 groups worldwide

🎤 **100+** speakers

📆 **12+ years** running

<br>

*"Something I'm genuinely proud to be part of — our community."*

<!--
SPEAKER: Neil

"Let me tell you about something I'm genuinely proud to be part of. Our community."

"2,124 members. 12 years. In Cape Town. For a Microsoft developer community."
-->

---

<!-- _class: light -->

## The Community Shows Up

| Event | Attendees |
|---|---|
| GitHub Copilot Dev Days 2026 | **110** |
| Monkeys in Production + LangChain AI Agents | **107** |
| Programming with Agents | **100** |
| Microsoft BUILD //localhost Cape Town | **92** |
| VS Code Dev Days — SOLD OUT | **93** |
| Mastering Prompt Engineering + Hybrid Apps | **93** |
| .NET Conf 2025 Cape Town | 🏆 **SOLD OUT — biggest ever in SA** |
| Tonight at the Accso office | **83 registered** |

*".NET Conf 2025 Cape Town = biggest .NET Conf in the history of South Africa, any city."*

*"And 83 people are at our office in Cape Town TONIGHT. While we're standing here."*

<!--
SPEAKER: Neil

"The .NET Conf 2025 Cape Town event was the biggest .NET Conf event in the history of South Africa. In any city."

"And 83 people are at our office in Cape Town tonight. While we're standing here in Germany."

The "tonight" detail is a great moment if you can land it — it makes the community feel alive and present in the room, not like a slide full of past statistics.
-->

---

## 🏆 .NET Conf Africa 2026 — Coming to Cape Town

CPTMSDUG will be **hosting .NET Conf Africa** this year.

The flagship annual .NET community conference. On the African continent.

<br>

**Accso is directly connected** — as venue partner and sponsor.

<br>

> From monthly meetups in our office to helping host a continental conference.

<!--
SPEAKER: Neil

"And now something I'm genuinely excited to share."

"We went from hosting monthly meetups in our office to helping bring a continental conference to Cape Town. That's a different level — and Accso is part of that story."

This is a strong moment to let land. It's concrete, it's new, and it connects Accso directly to something significant happening in the African tech community.
-->

---

<!-- _class: light -->

## Accso Cape Town Hosts CPTMSDUG

📍 V&A Waterfront, Clock Tower — one of our primary regular venues

Named sponsor alongside **Microsoft, JetBrains, the .NET Foundation, and UWC**

<br>

February 2026 — **61 attendees** at the Accso office

April 2026 — **57 attendees** at the Accso office

Tonight — **83 registered**

<br>

> Developers walk into an Accso office — and that builds a relationship over time.

<!--
SPEAKER: Neil

"Here's what's directly relevant to everyone in this room."

"That's not a marketing campaign. That's a relationship built by showing up consistently."

The numbers tell the story here — don't over-explain. Let the audience do the maths on what it means to have 57, 61, 83 developers walking through your office door regularly.
-->

---

<!-- _class: light -->

## The Impact Goes Beyond the Events

**For developers** — real knowledge, real mentorship, real careers built here.

**For the ecosystem** — Richard Campbell came to Cape Town because of this community. Matthew Leibowitz, Principal Software Engineer at Microsoft, is a co-organiser.

**For Accso** — 2,124 potential future colleagues. A brand that means something in the local talent pool. A direct connection to .NET Conf Africa.

<br>

*Richard Campbell = host of .NET Rocks, one of the longest-running dev podcasts. He came to CT.*

*Matthew Leibowitz = Principal Engineer at Microsoft, SkiaSharp maintainer. He co-runs our meetups.*

*"100 people on a Wednesday evening after work because they're genuinely interested. That's a healthy community."*

<!--
SPEAKER: Neil

Richard Campbell is the host of .NET Rocks — one of the longest-running developer podcasts in the world. He came to Cape Town because of the community here.

Matthew Leibowitz is a Principal Software Engineer at Microsoft and maintainer of SkiaSharp. He helps run our meetups.

"This isn't a community that exists on paper. It shows up. 100 people on a Wednesday evening, after work, because they're interested in what they're building. We're glad to be part of it."

Hand over to both for the close.
-->

---

<!-- _class: divider -->

# Section 5
## Wrapping Up

*🎤 Both*

<!--
SPEAKER: Both

Both Neil and Zachary on stage together.
-->

---

<!-- _class: light -->

## Four Things to Take Away

**1️⃣ Microsoft's investment in SA is real and deliberate**
Data centres, Gold Partner ecosystem, enterprise partnerships. An active bet on the African continent.

**2️⃣ Blazor is worth considering for the agentic coding era**
When AI agents write your UI, a stable, governed ecosystem reduces supply-chain risk.

**3️⃣ Integrating AI into .NET is genuinely straightforward**
Microsoft.Extensions.AI. Semantic Kernel. GitHub Copilot. The stack you already know. No Python. No new paradigm.

**4️⃣ Community is the multiplier**
2,124 members. 150+ events. 12 years. .NET Conf Africa. We're glad to be part of it.

<!--
SPEAKER: Both

Take one point each, alternate naturally.

1 — Data centres, Gold Partner ecosystem, enterprise partnerships. This isn't legacy lock-in. It's ongoing investment in the African continent.

2 — Not because it's trendy. Because when AI agents write your UI code, a strongly-typed, centrally governed ecosystem reduces the risk of what ends up in production.

3 — Microsoft.Extensions.AI gives you a model-agnostic abstraction. Semantic Kernel gives you agents, memory, and plugins in C#. GitHub Copilot writes the code. You don't need to learn Python. You don't need a new paradigm.

4 — 2,124 members. 150+ events. 12 years. .NET Conf Africa coming to Cape Town. We're glad to be part of it.
-->

---

<!-- _class: closing -->

# Still Relevant?

*We'll let you decide.*

*From our experience —*
*there's a lot to work with here.*

<br>

*"They're not just relevant. For many developers, they're the platform on which AI-powered applications are being built today. By real teams. For real clients. Including some you'll recognise."*

<br>

🌐 cptmsdug.dev

📍 meetup.com/cape-town-ms-dev-user-group

<!--
SPEAKER: Neil closes:

"So — thank you for staying. You didn't have to. The door was right there the whole time."

"And next time someone asks whether Microsoft and .NET are still relevant in South Africa — from what we've seen, they're the platform on which AI-powered applications are being built today. By real teams. For real clients. Including some you'll recognise."

Both together on the final line:

"Still relevant? We'll let you decide. But from our experience — there's a lot to work with here."
-->

---

<!-- _class: title -->

# Questions?

<br>

🌐 **cptmsdug.dev**

📍 **meetup.com/cape-town-ms-dev-user-group**

✉️ **usergroup@cptmsdug.dev**

<br>

*Common Qs: "Why not Python for AI?" → Python=training, .NET=enterprise apps, swap model in 1 line. "Is Blazor in production?" → SA finance, healthcare, govt, ZDF. "How to join?" → meetup link, free, open to all.*

<!--
SPEAKER: Both

Both on stage. Field questions together — if a question is clearly about the community, Neil takes it. If it's about the tech, Zachary takes it.

Be ready for these:

"Why not just use Python for AI?" — Python is excellent for model training and data science. .NET is where the enterprise applications live. With Microsoft.Extensions.AI you use Claude, Mistral, or any model in C#. You don't need to switch languages.

"Which model do you actually use?" — Mostly Claude for code and reasoning. The beauty of the abstraction is you swap it in one line — pick the best model for the job and change your mind later.

"Is Blazor actually in production?" — SA financial services, healthcare portals, government systems. ZDF. Not glamorous — but real, maintained, and shipping.

"What about npm vs NuGet — isn't NuGet also a risk?" — NuGet is significantly more curated and centrally governed. The scale of the npm vulnerability problem doesn't have a direct equivalent in the .NET ecosystem.

"How do I join CPTMSDUG?" — meetup.com/cape-town-ms-dev-user-group — free, open to everyone. And if you're ever in Cape Town, come to the office on a Wednesday evening.
-->
