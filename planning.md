# RulesBot — Planning Doc

Use this file to record your design decisions as you work through the lab.
There are no wrong answers — write enough that you could explain your reasoning to another group.

---

## Chunking Strategy

**Chunk size:**
300 character chunk sizes ensure that rules - often written in 1-3 sentences - are captured without fragmenting parts of the rule with too short of a chunk size, or grabbing more than one rule in a chunk with too large of a chunk size.


**Overlap:**
A 50 character overlap is allowed between chunks to emulate adding a roughly a sentence of context to the datastore. 


**Why this strategy fits rule book text:**
Rulebooks pack a lot short passages, so smaller chunks tend to outperform paragraph-level splittingfor targeted Q&A.


---

## Retrieval Observations

After implementing retrieval, try these test queries and record what comes back:

| Query | Top result game | Does it make sense? |
|-------|----------------|---------------------|
| "How do you win?" | | |
| "What happens when you roll a 7?" | | |
| "Can two players share a route?" | | |

**Anything surprising?**


---

## Response Quality

After implementing generation, try 2–3 questions and assess the answers:

| Query | Answer accurate? | Properly grounded? | Cited the right game? |
|-------|-----------------|-------------------|----------------------|
| | | | |
| | | | |

**What would you change about the prompt to improve grounding?**

