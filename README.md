# Canada Youth Unemployment Analysis

## Project Overview

**What is the trend and characteristics of Youth Unemployment in Canada**

### Motivation

Research consistently shows that downturns disproportionately affect young workers. For example:

- Entry-level jobs (≤ 1 year experience) declined ~30% year-over-year in 2024 [add source link].
- Youth unemployment currently exceeds the overall unemployment rate, with the widest gap in 30+ years [add source link].
- Growing AI adoption may be eroding entry-level roles by automating tasks historically done by junior staff [add source link].

### Dataset Compilation

   Assemble open, authoritative government datasets aligned to those drivers:
   - **Statistics Canada**: Labour force (employment, participation, unemployment), unemployment **duration** buckets

      - Labour force characteristics by age group, monthly, seasonally adjusted (14-10-0287-02)
      - Duration of unemployment, monthly, seasonally adjusted (14-10-0342-01)
  
   **Scope & Frequency**
   - **Temporal coverage:** **monthly**; the project’s time span is defined by the **longest overlapping duration across all datasets** *(In this project, that resolves to ~1978–2025.)*  
   - **Age group:** **15–24** — we focus on this group **as it not only satisfies the definition of youth the best, and is the most commonly available age group among the datasets.**

### Deliverables
   - Reproducible notebook and scripts
   - Visual EDA

