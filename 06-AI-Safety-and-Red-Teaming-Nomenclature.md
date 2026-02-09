# AI Safety & Red Teaming Nomenclature Quick Reference

This is a quick glossary of common terms used in AI safety/red-teaming work, especially from the perspective of remote evaluators. Formal terms are used in contracts/SOWs; informal terms are what workers/contractors actually say in chats or Slack.

- **Originator**  
  Formal: AI Lab / Model Developer / Frontier AI Company  
  Informal: Lab / the company / the big AI firm  
  Meaning: The organization that creates the model and contracts the safety/red-teaming work.

- **Employer**  
  Formal: Third-party contractor / AI data vendor / Evaluation partner  
  Informal: Vendor / platform / the company  
  Meaning: The intermediary company that hires remote workers to perform the safety/red-teaming tasks.

- **Remote Worker**  
  Formal: AI Safety Evaluator / Red Teamer / Adversarial Tester  
  Informal: Red teamer / tester / evaluator  
  Meaning: The person doing the adversarial prompting, jailbreak attempts, and safety testing work.

- **Assignment / Task**  
  Formal: Evaluation Task / Safety Probe  
  Informal: Task / Probe  
  Meaning: A single objective given to the worker to utilize a single or multi-turn prompt in attempt(s) to cause the model to bypass refusal, leak system prompt, trigger bias, etc.

- **Batch**  
  Formal: Safety evaluation batch / Red teaming project  
  Informal: Batch / queue / drop  
  Meaning: A grouped set of tasks (typically 100–1,000) with a deadline (usually 3–7 days).  
  • Between AI Lab and contractor:  
    Formal: Statement of Work / Evaluation agreement / Safety testing contract  
    Informal: SOW / the contract / the deal  
    Meaning: The top-level agreement covering thousands to tens of thousands of tasks across multiple batches.

- **Task / Goal of the remote worker**  
  Formal: Adversarial prompt / Safety probe / Jailbreak test  
  Informal: Jailbreak attempt / attack / test / prompt hack  
  Meaning: A single objective given to the worker (e.g., bypass refusal, leak system prompt, trigger bias).

- **Report / Submission of the remote worker**  
  Formal: Evaluation report / Test report / Safety submission  
  Informal: Write-up / submission / log  
  Meaning: The worker’s summary of prompt(s), model output, success/failure, and suggested fixes.

- **Prompt Collab with AI**  
  Formal: AI-assisted prompt ideation / Brainstorming with LLM  
  Informal: Prompt collab / AI draft help  
  Meaning: Worker collaborates with an AI tool to generate or refine adversarial prompts before testing — final prompt and judgment are always the worker's.

- **Quality Check / Audit**  
  Formal: Quality audit / Agreement check  
  Informal: Audit / gold review / QC  
  Meaning: Random or targeted review of submitted work to verify accuracy and guideline adherence.

- **Outcome / Status of the remote worker**  
  Formal: Approved / Rate-limited / Removed  
  Informal: Approved / rate-limited / removed / booted  
  Meaning: The worker’s standing after submission review (approved = paid, rate-limited = throttled or paused, removed = terminated).

This reference is exploratory and self-directed. Focused on clear terminology for understanding and discussing red-teaming workflows responsibly.
  Informal: Passed / flagged / dropped / rate-limited
  Meaning: Result of audit: continued access, reduced tasks, or removal from project.
  • Downgrade / Removal Triggers
    Formal: Failed audit / Low agreement rate
    Informal: Flagged / audited out

    Meaning: Worker may be downgraded (fewer tasks, lower pay) or removed from project if audits show consistent low quality, guideline violations, spamming, or detectable AI copying.
