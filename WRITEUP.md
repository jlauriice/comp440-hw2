# COMP 440 HW2: Whose Preferences Count?

**Name:** Laurice Jimu
**Date:** 2026-10-14

## Part 0: Set up

### Step B: What an MCP server is and why it's useful

An MCP server is a server that allows integration between AI models and external sites that usually needs an API. It's like the interpreter between the AI models which essentially allows them to be Agents who can now do several things on external servers like book flights, send emails etc. It's a new standard.

### Step B: Why not paste code into Colab yourself

Because it saves time, you can just stay in the claude code workspace and not have to swap back and forth. It also reduces errors

### Step D: How the MCP server connects Claude Code to Colab

I type it on my keyboard onto Claude Code. Claude Code connects to the MCP server via the internet capabilities it has. The MCP server then translates what Claude Code gave it into understandable language for Google Colab, then Google Colab executes that and returns a response to the MCP that brings back info to Claude Code all in the space of seconds.

## Part 1: The tools and the tests

### Step 1: About the model

1. 0.6 Billion parameters
2. 28 layers
3. 36 trillion text tokens
4. 119 languages

If it's in pretraining stage, I expect it to draw only to its existing knowledge for an answer and I expect it to use my question and train on it too

### Step 2: What the model predicts next

The model is not very confident. The format of the prompt dramatically changed the answer. Shilad chose that? and a different choice would have yielded different results, yes it's possible

### Step 3: Your four grades

1. 2, this is correct and gives logical reason
2. 1, this is partial, it affirms that it's 50 percent off then proceeds to fix the mistake
3. 1, also partial, it's right that discounts don't add that way but fails to effectively explain what the new discount is and miscalculates it.
4. 0, plain wrong

Claude and I did not disagree at all!

### Step 4: The held-back items

1. The tests are held back as a form of validity to see how good the model that I would have built is. This is meant to stop me as the human from overrefining the model based on the visible cases I have. So by introducing held back items, we can be assured that there is a fresh set to test on which helps in accuracy.

2. Results on visible items could look more accurate and depict my model better than it is through me iterating over and over to suit the visible items that I see when I'm writing the constitution.

### Step 5: Your run folder

evals/runs/2026-10-14-base

### Step 6: One question traced, and your diagram

Question: facts-112
1. The question and the answer Claude was told to accept: evals/shared/facts.jsonl
2. The base model's answer: evals/runs/2026-10-14-base/responses/base.jsonl
3. Claude's grade and its reason: evals/runs/2026-10-14-base/grades/sonnet-low/grades.jsonl
4. The rules Claude followed: .claude/agents/eval-grader.md. Sonnet did the grading: evals/runs/2026-10-14-base/grades/sonnet-low/grader.json
5. The same question in the viewer: http://127.0.0.1:8440/#/run/2026-10-14-base/answers

{item file} lives on my computer and on github simultaneously → {Colab} claude sends it to colab and now it lives on Google's computer → the model's answer - lives on collab → the zip you downloaded comes back to claude and is downloaded onto my computer→ the run folder lives on my computer , claude runs it→ Claude's grade lives on my computer→ the viewer lives on my computer, claude helps create it

### Step 7: Your 10 grades and Claude's

XXXX

### Step 8: Three surprising answers

XXXX

## Part 2: Train your two models and decide what changed

### Step 1: Your famous person, and why

XXXX (your passages go in `voice-samples.md`)

### Step 2: Your constitutions

XXXX (your lines go in `constitutions.md`; answer the Step 2 questions here)

### Step 3: Your test family

XXXX (a paragraph on your family, and the Step 3 questions; your items go in `evals/mine/`)

### Step 4: Your map and predictions

XXXX (one table: each line of `constitutions.md`, its family or "not measured", your predictions)

### Step 5: What Claude's answers do

XXXX

### Step 6: Your blind labels

XXXX

### Step 7: What SFT changed

XXXX

### Step 8: Your two reward logs

XXXX

### Step 9: Three models before grading, and your run folder

XXXX

### Step 10: Your review and the audit

XXXX

### Step 11: Whose preferences count

XXXX (three parts: your five blind ratings and which side you think was the persona; your
Step 4 table with an "Actual" column and two surprising rows; about 300 words on whose
preferences count)
