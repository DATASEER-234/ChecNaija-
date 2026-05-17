# ChecNaija — Rebuilding Civic Participation Through AI

> An LLM-powered civic intelligence agent that gives every Nigerian
> verified truth, visible possibility, and a clear next action.

## The Problem

Over 60% of Nigerian migrants are aged 18–35 (IOM, 2024).
53% of Nigerian youth are unemployed.
52% of Nigerian workers surveyed already plan to leave the country.
Voter turnout collapsed to 26% in 2023.

But the crisis is not just governance. It is an information vacuum.

Nigerian youth are consuming a constant feed of what is broken 
with no verified information about what is working,
no tools to hold leaders accountable,
and no pathway from frustration to action.

The result is a generation leaving the very country
whose problems they are uniquely positioned to solve.

## What ChecNaija Does

1. CLAIM VERIFICATION
   Any political message verified against INEC, government records,
   and trusted news. Returns: VERIFIED / FALSE / MISLEADING / UNCONFIRMED

2. POLITICIAN SCORECARD
   Enter your state and representative.
   See what they promised vs. what they delivered. With evidence.

3. POLICY PLAIN-LANGUAGE EXPLAINER
   Any Nigerian policy explained simply.
   Personalised to your state, job, and situation.

4. CIVIC ACTION GUIDE
   Not just what is wrong — but exactly what you can legally do about it.
   Petitions. FOI requests. Town halls. Lawful protest. Step by step.

5. GLOBAL DEMOCRACY MIRROR
   How does a working democracy handle this same problem?
   What is the gap? What should Nigeria look like?
   What can citizens demand and build to get there?

6. NIGERIA'S POTENTIAL DASHBOARD  ← NEW
   The resources. The growth sectors. The opportunities.
   Because a citizen who only knows the problems will leave.
   A citizen who knows both will stay and build.

## Tech Stack

- LLM: Gemini 1.5 Flash (Google AI Studio — free API)
- Agent Framework: LangChain
- Interface: Streamlit
- Language: Python 3.11
- Data: INEC, V-Dem, Freedom House, World Bank, Nigerian news archives

## Team

- Project Lead: Igwe Chinecherem Clara
- Data Engineer: Ogedengbe OluwaFemi Sunday
- AI/LLM Engineer: Wisdom Chilotam
- Product Engineer: Ernest Akubueze
  
## Run Locally
pip install -r requirements.txt
streamlit run interface/app.py

## Dataset Disclosure

See Docs/SOURCES.md for full disclosure of all data sources used
## Hackathon

DSN x Bluechip LLM Agent Hackathon 3.0
Submission: 24 May 2026 | Finale: 10 June 2026 @ Eko Hotel & Suites
