# /career-ops network

## Purpose
Help Pragyansh build a professional network systematically to 
increase job landing probability before and after graduation 
(July 2026).

## Profile context
- MSc AI, Heriot-Watt Edinburgh, graduating July 2026
- Target: AI Engineer, Applied AI, Responsible AI, Human-AI Interaction
- Location: Edinburgh → open to all UK
- Unique angle: AI Engineering + Human-Centred Design + XAI/Responsible AI
- Dissertation: Multi-agent financial AI system (LangGraph, RAG, FTSE 100)

## Sub-commands

### /career-ops network outreach [person details]
Given: name, role, company, how you found them (alumni/conference/LinkedIn)
Generate: a personalised 3-paragraph LinkedIn connection message
Rules:
- Max 300 characters for connection request (LinkedIn limit)
- Longer version for InMail or email
- Always mention Heriot-Watt connection if alumni
- Always reference something specific about their work
- Never sound templated or generic
- End with a specific, low-friction ask (not "pick your brain")

Output format:
**Connection request (300 chars max):**
[short version]

**Follow-up message after connecting:**
[longer version — send 2 days after they accept]

**Suggested follow-up date:** [5 days from today]

### /career-ops network alumni [search criteria]
Search Heriot-Watt alumni tracker and suggest:
- Who to connect with this week (5 targets)
- Anyone at companies where Pragyansh has evaluated a job
- Anyone who could provide a referral for a specific role

To find alumni manually:
1. Go to linkedin.com
2. Search people → filter by Heriot-Watt University
3. Filter by: Location (UK) + Industry (Technology/Financial Services)
4. Look for: AI Engineer, ML Engineer, Data Scientist, Applied AI, 
   Software Engineer at AI companies

### /career-ops network followup
Check followups.md and surface:
- Anyone overdue for follow-up (past their follow-up date)
- Anyone who accepted connection but hasn't had a follow-up message
- Suggested action for each person

### /career-ops network add [person details]
Add a new contact to the appropriate tracker:
- alumni.md if they went to Heriot-Watt
- contacts.md for all others
Update followups.md with initial follow-up date (5 days from today)

### /career-ops network stats
Quick summary:
- Total connections made this week
- Total alumni contacted
- Total in active conversation
- Follow-ups due this week
- Network health score (connections ÷ target)

## Weekly networking target
- 5 new Heriot-Watt alumni contacted per week
- 3 broader AI professionals contacted per week
- 0 follow-ups missed

## Message principles
1. Always specific — reference their actual work, not generic praise
2. Always give before asking — offer something (dissertation insight, 
   shared interest) before making any request
3. Small ask only — "would you be open to a 20-min call" not 
   "can you refer me"
4. Heriot-Watt angle — shared university is the strongest opener 
   with alumni, always use it
5. Dissertation as conversation starter — your FTSE 100 multi-agent 
   work is genuinely interesting to fintech/AI people, use it

## Token efficiency
- outreach: generate messages only, no research unless asked
- alumni: read alumni.md only, no web browsing unless asked  
- followup: read followups.md only, surface overdue items
- add: update files only, confirm addition
- stats: read tracker files only, return numbers
