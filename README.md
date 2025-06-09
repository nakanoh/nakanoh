### 👋 Working towards becoming an OSS contributor  
I started by fixing typos and have been learning how to contribute step by step.

🔹 **Typo Fixes – PRs merged to:**  
- [Next.js #80181](https://github.com/vercel/next.js/pull/80181)  (`them` → `it`)  
- [Tailwind CSS #18227](https://github.com/tailwindlabs/tailwindcss/pull/18227), [#18223](https://github.com/tailwindlabs/tailwindcss/pull/18223)  (`a arbitrary` → `an arbitrary`, `a the` → `the`)  
- [PyTorch #155301](https://github.com/pytorch/pytorch/pull/155301)  (`intialize` → `initialize`)  
- [LangChain #31509](https://github.com/langchain-ai/langchain/pull/31509)  (`practicies` → `practices`)  
- [Scrapy #6875](https://github.com/scrapy/scrapy/pull/6875)  (`a argument` → `an argument`)  
- [Chart.js #12084](https://github.com/chartjs/Chart.js/pull/12084)  (`an segment` → `a segment`)

🔍 **Insights from 7 typo fixes:**  
- **Types of mistakes**  
  - Incorrect articles (e.g., `a` → `an`, `an` → `a`, `a the` → `the`): **4 cases (57.2%)**  
  - Spelling errors (e.g., `practicies` → `practices`, `intialize` → `initialize`): **2 cases (28.6%)**  
  - Pronoun misuse (e.g., `them` → `it`): **1 case (14.3%)**

- **Where typos appeared**  
  - Markdown files (README, SECURITY.md, etc.): **2 cases (28.6%)**  
  - TypeScript files (tests, compatibility code): **3 cases (42.9%)**  
  - Python files (comments, docstrings): **1 case (14.3%)**  
  - JavaScript files (plugin logic): **1 case (14.3%)**

🧠 Initially, I assumed that spelling errors would be the most common type of typo.  
However, it turns out that **incorrect articles (a/an/the)** were the most frequent.  
These subtle grammatical mistakes often **slip through standard Linters and CI checks**,  
so I'm interested in researching this area further—and hopefully building tools to help catch these kinds of issues.

💡 Analyzing these patterns can help improve review and CI processes.  
Next, I’m planning to take on flaky test fixes and contribute more actively.
