# 📊 Evaluating Macro Risks: Global Pandemic vs. Policy Shocks in Turkey
I wanted to test a well-known macroeconomic case: what actually does more damage to an emerging market economy: a literal global crisis like COVID-19 (external shock) or bad domestic political decisions (internal policy shock)? 
To find out, I built a lightweight script that analyzes Turkey's inflation data from 2020 to 2024. It isolates the pandemic timeline from the era of "Erdoganomics" (the untraditiobal decision to cut interest rates while inflation was already high) and calculates which event triggered the worst economic outcome.

### A Personal Motivation
As a Turkish native, I grew up listening to people constantly saying that Erdogan’s decisions single-handedly ruined the Turkish economy. As someone who is studying economics, I wanted to use code, theoretical knowledge, and data to check if what the people say is actually mathematically true.

### Showing the Economic Logic: Standard vs. Unorthodox
To understand this project, you need to understand how standard monetary policy works compared to what happened in Turkey:
* **The Standard (Orthodox) Rulebook:** In any normal economy, when inflation starts rising, the Central Bank must **raise interest rates**. This makes borrowing expensive, cools down consumer spending, and brings prices back down. This is what the US Federal Reserve or the European Central Bank do.
* **The "Erdoganomics" Shock:** President Erdogan pushed a highly unconventional theory, claiming that high interest rates actually *cause* inflation instead of fixing it. Under his pressure, the Turkish Central Bank did the exact opposite of the rest of the world - they aggressively **cut interest rates** while inflation was already skyrocketing.

**By flooding the market with cheap credit, the local currency (the Lira) crashed, imports became incredibly expensive, and inflation completely spiraled out of control.**

### Why Python?
Instead of just importing Pandas, I chose to write this entirely in native Python. The data i found on the Internet is structured as a dictionary, and I built custom loops and functions to filter the timelines and calculate metrics (averages, peaks, and acceleration velocity). It is clean and it is easy to see the results without downloading and filtering big data sets.

### Why this matters for business
If a company is planning to expand globally or invest capital in developing markets, looking at market size isn't enough. This project shows how you can quickly build a data-driven stress test to identify high-risk regions. 

### Conclusion I made
The script automatically compares the peak metrics and generates a final report. The numbers prove that the policy shock (cutting rates) was far more destructive to corporate and price stability than the entire COVID-19 pandemic, with peak inflation scaling significantly higher.
