### 👋 Working towards becoming an OSS contributor  
I started by fixing typos and have been learning how to contribute step by step.

🔹 **Typo Fixes – PRs merged or approved (awaiting merge):**
- [Next.js #80181](https://github.com/vercel/next.js/pull/80181)  (`them` → `it`)  
- [Tailwind CSS #18227](https://github.com/tailwindlabs/tailwindcss/pull/18227), [#18223](https://github.com/tailwindlabs/tailwindcss/pull/18223)  (`a arbitrary` → `an arbitrary`, `a the` → `the`)  
- [PyTorch #155301](https://github.com/pytorch/pytorch/pull/155301)  (`intialize` → `initialize`)  
- [LangChain #31509](https://github.com/langchain-ai/langchain/pull/31509)  (`practicies` → `practices`)  
- [Scrapy #6875](https://github.com/scrapy/scrapy/pull/6875)  (`a argument` → `an argument`)  
- [Chart.js #12084](https://github.com/chartjs/Chart.js/pull/12084)  (`an segment` → `a segment`)  
- [Matplotlib #30151](https://github.com/matplotlib/matplotlib/pull/30151)  (`them scale them` → `then scale them`)

🔍 **Insights from 8 typo fixes:**  
- **Types of mistakes**  
  - Incorrect articles (e.g., `a` → `an`, `an` → `a`, `a the` → `the`): **4 cases (50.0%)**  
  - Spelling errors (e.g., `practicies` → `practices`, `intialize` → `initialize`, `them` → `then`): **3 cases (37.5%)**  
  - Pronoun misuse (e.g., `them` → `it`): **1 case (12.5%)**

- **Where typos appeared**  
  - Markdown files (README, SECURITY.md, etc.): **2 cases (25.0%)**  
  - TypeScript files (tests, compatibility code): **3 cases (37.5%)**  
  - Python files (comments, docstrings): **2 cases (25.0%)**  
  - JavaScript files (plugin logic): **1 case (12.5%)**

🧠 Initially, I assumed that spelling errors would be the most common type of typo.  
However, it turns out that **incorrect articles (a/an/the)** were the most frequent.  
These subtle grammatical mistakes often **slip through standard Linters and CI checks**,  
so I'm interested in researching this area further—and hopefully building tools to help catch these kinds of issues.

💡 Analyzing these patterns can help improve review and CI processes.  
Next, I’m planning to take on flaky test fixes and contribute more actively.
