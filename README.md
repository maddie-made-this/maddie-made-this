## Hi, I'm Maddie

Linguist turned developer. I spent four years studying the rule-systems underneath language, and it turns out that's most of what data modeling is — finding the structure that's already there and giving it a name.

These days that means SQL, data modeling, and reporting at work, and building LLM applications on my own time.

### What I do now

IT Analyst at a Louisville landscaping company. I'm the entire technical function, which covers the database, the reporting, the Microsoft 365 environment, and the website.

Most of the job is answering questions the books can't. Their accounting lives in QuickBooks, which is fine for invoicing and no help with what the owner actually asks: why one property eats twice the crew hours of a comparable one, how much non-billable time is coming out of the margin, how to split hours between contract work and side jobs when a crew does both on the same visit. So I built a PostgreSQL database of clients and jobs that models labor hours against revenue, and the analysis comes out of there.

The thing I'm proudest of was a result of that work; several passes through the hours and job data made it clear the hours weren't being recorded at a grain that could be attributed to a client or a service type — no amount of querying was going to fix that. The answer wasn't a better report, it was a different timekeeping system. I recommended it, we changed it, and real analysis finally became possible.

Also: M.S. Computer Science at Georgia Southwestern, expected May 2027. AWS Certified AI Practitioner.

### How I got here

I was a logistics account executive at Total Quality Logistics — cold calling, building a book of business from nothing, and not too shabby at it. The CRM we had was eating the hours I needed for calls, and I couldn't see where anything stood in the sales cycle, so I built a Visual Basic application that extended it — a dashboard that surfaced the highest-impact next call. I ran my own book on it before anyone else touched it and got results. My manager liked it enough to mandate it across the team. I went chair by chair, demoing and answering questions until people who hadn't asked for a new tool understood how it worked and why it was a better workflow, and got real use out of it.

What I couldn't stop thinking about afterward was that I'd built it on my own time. The part I was best at, and the only part that actually lit me up, was the part I had to do outside of work.

Before that was Cotiviti — SQL audits against large insurer claims databases, where I found signal in a set of fields everyone had written off as uninformative, and money sitting behind them. After TQL was Double A Inventory, reconciling physical counts against invoices for clients whose data arrived with no two accounts structured the same way.

### What I'm building

**[Mirror](https://github.com/maddie-made-this/mirror)** — an LLM memory and retrieval platform. Three data stores chosen deliberately by workload: PostgreSQL for records and auth, Neo4j for the concept graph, Qdrant for vector search. FastAPI service, Next.js frontend, Docker.

Persistent memory, multi-model routing, structured-output prompting with abstention paths so the thing says "I don't know" instead of inventing an answer, and privacy constraints designed in from the schema up rather than bolted on afterward.

The architecture and data modeling are mine end to end. Implementation was AI-agent-assisted.

### What I work in

`SQL` `PostgreSQL` `Python` `Neo4j / Cypher` `TypeScript` `React / Next.js` `FastAPI` `Docker` `Power BI` `VBA`

### Elsewhere

[LinkedIn](https://linkedin.com/in/maddie-dalton) · maddie.o.dalton@gmail.com
