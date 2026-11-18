# PMA-3-1 · Fundamentals of Ad Tech, Data & Analytics · Fall 2026

**Name:** Andrii Bohdan
**Group:** KM-43

Lab notebooks for the course. Every notebook downloads the course dataset from Kaggle with `kagglehub` (`shkarupylomaxim/adtech-lab1-tv-panel`) and runs top to bottom on Google Colab or Kaggle. Data files are not committed.

| Lab | Notebook | Topic |
|---|---|---|
| 1 | `lab1.ipynb` | Intro to Behavioral TV Data |
| 2 | `lab2.ipynb` | What Did the Campaign Deliver? |
| 3 | `lab3.ipynb` | Millions of TVs, Who Is Watching? |

## Lab 1 — Intro to Behavioral TV Data

Working with a people-meter TV panel (October 2024, ten networks): programs, viewing sessions, daily weights and respondent attributes.

- **Task 1:** panel size and the US universe its weights represent; projected average audience by hour (weekdays vs weekends); distribution of session length (weighted mean vs median).
- **Task 2:** household and person ratings of *CBS Evening News* and its cumulative reach curve for P2+, A18–34 and A18–49.
- **Task 3:** viewing frequency of the program's audience.
- **Task 4:** audience demographics by network.

## Lab 2 — What Did the Campaign Deliver?

Post-campaign evaluation of a TV ad campaign (BRAND_A) using the commercial log, the rate card and the Lab 1 panel.

- **Task 1:** size of the ad log, ad load by network, pricing every spot from the rate card.
- **Task 2:** delivery for P2+ and A18–49 (impressions, GRPs, reach, average frequency), frequency distribution, how well the campaign hit its target.
- **Task 3:** cost, CPM and CPP overall and by network; whether the GRP guarantee was met and the value of make-goods.
- **Task 4:** reach overlap between big and small networks, and the cost of reach they add.
- **Task 5:** sampling error of spot ratings and zero-cells for small audiences.
- **Bonus:** moving budget to cheaper A18–49 inventory.

## Lab 3 — Millions of TVs, Who Is Watching?

Due diligence on a smart-TV ACR dataset (29,940 TVs, October 14–27, 2024) compared with the Lab 1 panel and currency ratings.

- **Task 1:** five questions for a dataset (grain, key, coverage, weight, provenance), size and the edit rule, the share of viewing ACR cannot recognize.
- **Task 2:** matching TVs to households by hashed IP, the footprint's profile against the panel (index), TV-based household ratings against the reference.
- **Task 3:** devices versus people: live hours per home and network shares compared with the panel, what each source can see.
- **Task 4:** daily in-tab TVs and network hours, the biggest spike and a broken data day.
- **Task 5:** sampling error versus bias, and an answer to a media planner.
- **Bonus:** A25–54 rating from the TVs with VPVH from the panel.
