### 👋 Working towards becoming an OSS contributor  
I started by fixing typos and have been learning how to contribute step by step.

🔹 **Typo Fixes – PRs merged or approved (awaiting merge):**  
- [Next.js #80181](https://github.com/vercel/next.js/pull/80181)  (`them` → `it`)  
- [Tailwind CSS #18227](https://github.com/tailwindlabs/tailwindcss/pull/18227), [#18223](https://github.com/tailwindlabs/tailwindcss/pull/18223)   (`a arbitrary` → `an arbitrary`) / (`a the` → `the`)  
- [PyTorch #155301](https://github.com/pytorch/pytorch/pull/155301)  (`intialize` → `initialize`)  
- [LangChain #31509](https://github.com/langchain-ai/langchain/pull/31509)  (`practicies` → `practices`)  
- [Scrapy #6875](https://github.com/scrapy/scrapy/pull/6875)  (`a argument` → `an argument`)  
- [Chart.js #12084](https://github.com/chartjs/Chart.js/pull/12084)  (`an segment` → `a segment`)  
- [Matplotlib #30151](https://github.com/matplotlib/matplotlib/pull/30151)  (`them scale them` → `then scale them`)  
- [XGBoost #11503](https://github.com/dmlc/xgboost/pull/11503)   (`a open` → `an open`) / (`Committers comes` → `Committers come`)  
- [Flutter #170206](https://github.com/flutter/flutter/pull/170206) (`disabeling` → `disabling`)  
- [Django #19537](https://github.com/django/django/pull/19537) (`Geodjango` → `GeoDjango`)  
- [Gensim #3613](https://github.com/piskvorky/gensim/pull/3613) (`Replaceed` → `Replaced`) 

🔍 **Insights from 13 typo cases:**  
- **Types of mistakes**  
  - Incorrect articles (e.g., `a` → `an`, `an` → `a`, `a the` → `the`): **5 cases (38.5%)**  
  - Spelling errors (e.g., `practicies` → `practices`, `intialize` → `initialize`, `disabeling` → `disabling`, `Replaceed` → `Replaced`, `them` → `then`): **5 cases (38.5%)**  
  - Subject-verb agreement (e.g., `Committers comes` → `Committers come`): **1 case (7.7%)**  
  - Pronoun misuse (e.g., `them` → `it`): **1 case (7.7%)**  
  - Capitalization inconsistency (e.g., `Geodjango` → `GeoDjango`): **1 case (7.7%)**

- **Where typos appeared**  
  - Markdown files (README, SECURITY.md, CONTRIBUTORS.md, CHANGELOG.md): **4 cases (30.8%)**  
  - TypeScript files (tests, compatibility code): **3 cases (23.1%)**  
  - Python files (comments, docstrings, test files): **3 cases (23.1%)**  
  - JavaScript files (plugin logic): **1 case (7.7%)**  
  - YAML config files: **1 case (7.7%)**  
  - Test scripts (GeoDjango-specific): **1 case (7.7%)**

🧠 Initially, I assumed that spelling errors would be the most common type of typo.  
However, it turns out that **incorrect articles (a/an/the)** were the most frequent.  
These subtle grammatical mistakes often **slip through standard Linters and CI checks**,  
so I'm interested in researching this area further—and hopefully building tools to help catch these kinds of issues.  
Also, I’ve noticed that **spelling errors often occur in words that contain the letter “i”**—this might be an interesting pattern worth exploring!

💡 Analyzing these patterns can help improve review and CI processes.  
Next, I’m planning to take on flaky test fixes and contribute more actively.
