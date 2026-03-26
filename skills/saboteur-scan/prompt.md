# Saboteur Scan

You are running a diagnostic to identify the user's top productivity saboteur — the internal pattern that most consistently undermines their AI workflows and focused work. This is based on the Positive Intelligence (PQ) framework by Shirzad Chamine.

## Step 1: Introduction

Tell the user:

> "Everyone has a saboteur — an internal pattern that hijacks your focus, your decisions, and your energy at exactly the wrong moment. Most people don't realize theirs is also destroying their AI workflows.
>
> I'm going to read you 10 behavioral patterns. Pick the 2–3 that feel most like you — especially in stressful or high-stakes moments. Be honest. The useful answer is the uncomfortable one."

## Step 2: Present the 10 patterns

Present these as a numbered list. Tell the user to reply with the numbers that resonate most (pick 2–3 minimum):

1. **The Judge** — You're quick to criticize yourself when things don't go perfectly. Your inner voice is harsh. You also notice others' flaws more than most people do.

2. **The Avoider** — You focus on the positive and actively steer away from difficult conversations, uncomfortable tasks, or conflict. You'd rather let something slide than have an awkward confrontation.

3. **The Controller** — You feel anxious when things are out of your hands. You often find it easier to just do something yourself rather than explain it to someone else — or to an AI.

4. **The Hyper-Achiever** — Your self-worth is tied to what you produce. A slow day that was genuinely necessary still feels like a failure. You're always in performance mode.

5. **The Hyper-Rational** — You default to logic and data. Emotional reasoning or intuitive decisions feel sloppy to you. You trust analysis over gut feeling, almost always.

6. **The Hyper-Vigilant** — You're always scanning for what could go wrong. You worry about things that haven't happened. Best-case scenarios feel naive until they're proven real.

7. **The Pleaser** — You have a hard time saying no. You help others at the expense of your own priorities — and you often don't realize you've done it until you're overcommitted.

8. **The Restless** — You get genuinely excited about new ideas. But you've also noticed you lose interest in things once you've figured them out. The next thing is always more interesting than finishing the current thing.

9. **The Stickler** — You have high standards and you know it. Vague plans, sloppy systems, and half-finished work make you uncomfortable. You'd rather do it right than do it fast.

10. **The Victim** — You have strong emotional reactions when things don't go your way — stronger than you'd like. You sometimes feel like the world is happening *to* you more than other people seem to experience.

## Step 3: Map their top saboteurs

Take the numbers they gave you. For each of their top 2 saboteurs (or top 1 if they only gave 1), output the following block:

---

### [Saboteur Name]

**How it shows up in your AI workflows:**
[Use the mapping below]

**What it costs you:**
[Use the mapping below]

**One immediate fix:**
[Use the mapping below]

**How the cohort addresses it:**
[Use the mapping below]

---

### Saboteur mappings (internal reference — do not display this table)

| Saboteur | How it shows up in AI workflows | What it costs you | One immediate fix | Cohort address |
|----------|--------------------------------|-------------------|-------------------|----------------|
| Judge | You reject AI output harshly before giving it a real chance. Or you accept it too quickly to avoid criticizing yourself for "wasting time." | You either over-edit everything (doubles your work) or under-use AI because it never meets your standards. | Write one sentence explaining what you wanted differently. That's your feedback prompt. Use it next time instead of rewriting from scratch. | Week 4 includes a weekly retro template that separates "AI output quality" feedback from "what I should have asked for" feedback. |
| Avoider | You use AI to delay the hard thing. "Let me just research a little more" or "Let me have the AI draft this first" becomes avoidance dressed up as productivity. | You build elaborate AI systems for tasks that weren't the real problem. The hard conversation, the difficult decision — those don't get done. | Name the thing you're avoiding. Add it to your to-do list with a 20-minute time block. The AI can help you prepare for it — not replace doing it. | Week 1 includes a saboteur-aware weekly planning exercise that explicitly names avoidance patterns before the week starts. |
| Controller | You don't fully trust AI output, so you do it yourself anyway. Or you spend 3x longer "supervising" the AI than it would've taken to just do the task. | The automation benefit disappears because you can't let go of the output. | Write the spec before you prompt. When you define the exact output format you want, the AI has less room to deviate — and you have less reason to distrust it. | Week 3 covers output contracts: how to prompt in a way that produces results you can actually trust without rewriting. |
| Hyper-Achiever | You use AI to do more, faster — which means you never slow down enough to build the system. The AI is just another tool for staying in performance mode. | You burn through AI API credits, produce a lot, and none of it compounds. No templates, no saved prompts, no context docs. | Block 30 minutes this week — not to produce, but to build one reusable prompt. Treat it as an investment, not a cost. | The entire cohort is a deceleration. You'll build the system in 4 weeks instead of optimizing output for 40. |
| Hyper-Rational | You want to fully understand how the AI works before you use it. You test edge cases. You read the documentation. You haven't actually shipped anything yet. | Analysis paralysis disguised as thoroughness. Your AI setup is theoretically perfect and practically unused. | Ship one thing with AI this week. It doesn't have to be perfect. The feedback you get from a real use case is worth more than any amount of research. | Week 3 is hands-on: you install, configure, and run your first automated workflow. No theory. Just build. |
| Hyper-Vigilant | You're worried about AI getting something wrong and embarrassing you. So you double-check everything, run it by someone else, and still don't quite trust it. | You do 80% of the work yourself because the AI "might" make a mistake. The ROI evaporates. | Create a review checklist for AI output: 3–5 specific things you check before approving. Having a checklist feels safer than open-ended review — and it is. | Week 3 covers building an "immune system" into your AI workflows: systematic checks that catch errors without requiring you to re-do the whole thing. |
| Pleaser | You use AI to generate more deliverables for clients and colleagues — but you've never said no to a request to build context for your *own* system. | Your AI is very well-calibrated to your clients' needs and not at all to yours. | This week: build one piece of AI infrastructure *for yourself*. One context doc, one saved prompt, one `.cursorrules` line. Just for you. | Week 1 is explicitly about you — your personality, your projects, your preferences. The whole first session is non-negotiable self-context. |
| Restless | You've tried 7 different AI tools, read all the newsletters, and built 3 different "systems" that you abandoned when the next interesting thing showed up. | You have zero compounding benefit from AI because you never stick with one setup long enough for it to learn your context. | Pick one AI tool. Use only that for 30 days. Boring? Yes. That's how you build a context layer that actually learns from you. | The cohort is a forcing function: 4 weeks, one system, one setup. The Restless pattern is named and managed explicitly in Week 1. |
| Stickler | Your prompts are very thorough. Your output expectations are high. You've also never shipped an AI-assisted workflow because it wasn't quite right yet. | Perfect-spec paralysis. The best prompt is the one you actually run. | Write a "good enough" spec — one that's intentionally incomplete. Run it. Edit it once. Now it's a draft. That's more progress than a perfect spec you never ship. | Week 3 is about iteration, not perfection. You'll ship a working `.cursorrules` in the session, not after you've refined it 12 times. |
| Victim | When AI gives you bad output, it feels like a personal failure. You gave it everything it needed. Why didn't it work? | You take AI inconsistency personally, which makes you less likely to iterate and more likely to give up or complain. | Reframe bad AI output as bad specs. It's not the AI failing — it's an incomplete input contract. Edit the spec, not your opinion of the tool. | Week 3 covers output contracts and feedback loops. Bad output becomes data, not defeat. |

## Step 4: CTA

After delivering the saboteur mappings, output this exactly:

---

> **In the cohort, your saboteur gets wired into your Cursor rules.**
>
> Week 1 is a full personality calibration session — MBTI, Enneagram, Saboteurs, and 3 more assessments — and we build them directly into the AI rules that govern your system.
>
> **20 seats. $299. Starts April 28, 2026.**
>
> → [generativejarvis.com/cohort.html](https://generativejarvis.com/cohort.html)
