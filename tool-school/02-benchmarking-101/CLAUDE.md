# Tool School: Benchmarking 101 (How To Read AI Model Report Cards)

**Author(s):** Hannah Stulberg, Akshat Khandelwal | **Series:** Tool School #2

## Article Map

| Section | Line | Coverage |
|---------|------|----------|
| Title & Subtitle | 1 | How to read AI model report cards - learn to read the scorecard behind every AI model launch |
| Series Introduction | 4 | Tool School series context, link to GitHub 101 |
| Opening & Motivation | 9 | Why benchmark literacy matters - 40 models in 14 months, scorecards you can't read |
| Co-author Introduction | 17 | Akshat Khandelwal (PM at DoorDash, Help Me Unpack Substack) |
| Learning Outcomes | 25 | 5 things you'll have by the end: benchmark understanding, major benchmarks, scorecard reading, cost awareness, confidence |
| Guide Organization | 33 | 5-section roadmap of the article |
| The Short Version | 41 | 2-minute framework: 4 benchmark categories, 3 questions to ask, relevance tiers, 4 things to watch |
| The Pace of Change: 40 Models in 14 Months | 77 | Full timeline of model launches Jan 2025 - Mar 2026 across Anthropic, OpenAI, Google |
| Every Launch Changes What You Can Build | 103 | Why the accelerating pace matters for your work - build for the model coming in 6 months |
| Benchmarks 101 | 115 | What benchmarks actually measure, how models are scored, terms you need to know |
| A High SAT Score Doesn't Make Someone a Great Colleague | 119 | SAT metaphor - benchmark scores are standardized tests for AI, each measures one narrow skill |
| What a Benchmark Actually Is | 133 | Definition: standardized test for AI models - fixed questions, tasks with answers, or head-to-head |
| Benchmarks Use One of 3 Grading Systems | 139 | Pass@1 (one attempt), Pass@k (multiple attempts), Elo rating (head-to-head via Chatbot Arena) |
| There Are 4 Major Categories of Benchmarks | 155 | Knowledge & Reasoning, Coding, Reasoning, Agentic & Computer Use |
| Why Only a Handful of Benchmarks Become Standard | 171 | 3 bars: hard enough, simple enough metric, interpretable to non-researchers |
| The Benchmark Reference Table | 181 | Complete table of every major benchmark: category, year, creator, what it tests, scoring |
| The Major Benchmarks | 204 | Deep dive on each benchmark with example cards |
| Knowledge & Reasoning Benchmarks | 206 | MMLU (2020), GPQA Diamond (2023), HLE (2025), GDPval (2025) |
| Coding Benchmarks | 234 | SWE-bench Verified (2024), SWE-bench Pro (2025), SWE-Lancer (2025), plus the real-world gap |
| Reasoning Benchmarks | 262 | ARC-AGI-3 (2026) and ARC-AGI-2 (2025) - novel problem-solving the model has never seen |
| Agentic & Computer Use Benchmarks | 278 | OSWorld, tau2-bench, BigLaw Bench, Terminal-Bench 2.0 - sustained professional work |
| Why Benchmarks Expire | 304 | When everyone gets an A, the A stops meaning anything - saturation, contamination, optimization |
| Models Improve Faster Than New Tests | 316 | Saturation: scores converge, spread disappears, test becomes noise |
| Training Data Gets Contaminated | 322 | Contamination: models see test answers in training data - SWE-bench Verified example |
| Optimization Pressure (Goodhart's Law) | 332 | When a measure becomes a target, it ceases to be a good measure |
| The Cycle Compounds and Accelerates | 336 | ImageNet lasted 5 years, MMLU 3, SWE-bench Verified 2 - ARC-AGI-3's radical response |
| Which Benchmarks Are Still Working Right Now? | 352 | 3 questions: How long public? Who created it? Scores still spread out? |
| Where Each Benchmark Stands Right Now | 362 | Trust tiers: High (ARC-AGI-3, ARC-AGI-2, HLE, SWE-bench Pro, OSWorld, Terminal-Bench 2.0), Moderate, Low |
| Where to Check Scores Yourself | 399 | 5 independent sources: Chatbot Arena, Artificial Analysis, ARC Prize, Scale AI, Stanford CRFM |
| Apply What You've Learned: Read the Scorecard | 411 | Real benchmark table from Anthropic's Opus 4.6 launch - read and evaluate every line |
| You Recognize Every Name on This Table | 430 | Applying benchmark knowledge to identify each test in the Opus 4.6 scorecard |
| You Know What the Scores Actually Mean | 434 | Understanding pass@1 vs Elo rating in context |
| You Can Evaluate How Relevant Every Score Is | 440 | Relevance assessment of each Opus 4.6 benchmark score with reasoning |
| How to Read the Next Model Launch | 457 | Head-to-head comparison and what to watch for in any announcement |
| No Single Model Wins | 461 | Side-by-side comparison: Opus 4.6 vs Sonnet 4.6 vs GPT-5.4 vs Gemini 3.1 Pro |
| 4 Things to Watch for in Any Launch Announcement | 473 | Missing benchmarks, baseline comparisons, human preference vs benchmarks, methodology transparency |
| What the Scorecard Leaves Out: Cost | 501 | API pricing, tokens, input/output costs - the dimension most tables omit |
| Same Scores, Wildly Different Prices | 517 | Output token pricing comparison across models, DeepSeek R1 cost advantage |
| Cost-Adjusted Evaluation Is Coming | 529 | ARC-AGI-2 measures cost-per-task, Artificial Analysis price-performance rankings |
| Reading the 3 February-March 2026 Launches | 537 | Informed reads of Opus 4.6, Sonnet 4.6, and GPT-5.4 launches |
| Best for What? At What Price? On Which Tests? | 559 | Summary: no single model wins across the board |
| You Can Read the Next Model Announcement Yourself | 565 | Closing recap of 5 learning outcomes and confidence statement |
