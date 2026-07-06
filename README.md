# The Mission Has Recorded More Eviction Notices Than Any Other San Francisco Neighborhood

### Nearly three decades of city records show that eviction-notice filings have fallen from their late-1990s peak, but the burden has remained concentrated in a small group of neighborhoods.

San Francisco’s eviction story is not a straight line. Since 1997, the number of notices filed each year has fallen, risen, and fallen again as the city’s housing market, economy, and tenant protections changed. The city recorded its highest annual total in 1998, saw filings decline during the following decade, experienced another rise in the mid-2010s, and then recorded a sharp break during the COVID-19 pandemic.

Underneath those citywide changes, however, one pattern is much clearer: eviction notices have not been distributed evenly across San Francisco.

The Mission recorded **5,546 eviction notices** between January 1997 and July 2026, the highest total of any neighborhood in the dataset. That was **57 percent more** than the Tenderloin, which ranked second with 3,534 notices. The Mission alone accounted for about **11 percent of all notices with a known neighborhood**, and nearly **22 percent of the notices among the ten highest-ranking neighborhoods**.

That concentration does not prove that every tenant who received a notice was ultimately removed from their home. It also does not prove that individual landlords were motivated by race. The dataset does not identify the race, income, or immigration status of the tenant. What it does show is where the formal eviction process was initiated most often—and which communities have repeatedly lived closest to the threat of displacement.

---

## Where the data came from

This project uses the [San Francisco Eviction Notices dataset](https://data.sfgov.org/Housing-and-Buildings/Eviction-Notices/5cei-gny5), published through DataSF, the City and County of San Francisco’s open-data portal. The underlying records come from eviction notices filed with the **San Francisco Rent Board** under Section 37.9(c) of the city’s rent ordinance.

The downloaded data contained records beginning on **January 2, 1997**. The most recent filing date in the version used for this analysis was **July 2, 2026**, and the dataset was marked as current through July 5, 2026.

The Google Sheets export contained 48,667 rows, but two were completely blank records with no Eviction ID and a placeholder year of 1899. After excluding those rows, the analysis contained **48,665 valid eviction-notice records**.

Because the records come from the city agency that receives the filings, this is a stronger source than an informal survey or a voluntarily submitted database. Still, an official dataset is not automatically complete or perfectly suited to every journalistic question. The Rent Board collects these records for administrative and legal purposes, not specifically to measure displacement, racial inequality, or long-term housing outcomes.

The most important limitation is that a notice is not the same thing as a completed eviction. A tenant may challenge the notice, reach an agreement, receive legal assistance, or remain in the unit for another reason. The city itself warns that the number of notices may differ from the number of tenants who were ultimately evicted.

The dataset also does not show:

- whether the notice resulted in a court case;
- whether the tenant moved;
- how many people lived in the affected unit;
- the race, age, income, or immigration status of the tenant;
- the race or motive of the landlord; or
- what happened to the tenant afterward.

There were also **98 valid records without an automatically assigned analysis neighborhood**. Those notices are included in the citywide totals but cannot be attributed to a specific neighborhood in the neighborhood comparison.

---

## How I analyzed the data

I imported the dataset into **Google Sheets**, added a year field based on the filing date, and created two pivot tables.

The first pivot table grouped records by filing year and counted Eviction IDs. This produced the annual totals used in the line chart. The second grouped records by the “Neighborhoods – Analysis Boundaries” field, counted Eviction IDs, and sorted the neighborhoods from highest to lowest.

**Google Sheets analysis:** [View the spreadsheet here](PASTE-YOUR-PUBLIC-GOOGLE-SHEETS-LINK-HERE)

The supporting files used in the project are also included in this repository:

- [Original eviction-notice data](Eviction_Notices.csv)
- [Google Sheets export with the year field](Eviction_Notices_GoogleSheet.csv)
- [Annual pivot-table results](Pivot_Annual_Evictions.csv)
- [Neighborhood pivot-table results](Pivot_Neighborhood_Evictions.csv)

The annual pivot table contained a false 1899 row created by the two blank spreadsheet rows. Because those rows had no Eviction ID, their count was zero and they were excluded from the chart and written analysis.

The analysis focuses on two questions:

1. How has the annual number of eviction notices changed since 1997?
2. Which neighborhoods accumulated the largest number of notices?

These pivot tables are useful for identifying broad patterns, but the neighborhood totals are **raw counts**, not population-adjusted rates. A neighborhood with more residents, more rental units, or more renter households may naturally generate a larger total. The chart therefore shows where notices were concentrated, not the probability that an individual renter would receive one.

---

## Eviction notices fell from the late-1990s peak—but not in a steady decline

![Annual eviction notices filed in San Francisco](eviction_numbers.png)

San Francisco recorded **2,560 eviction notices in 1997** and reached the highest annual total in the dataset one year later, with **2,917 notices in 1998**.

Filings then declined sharply. By 2002, the annual total had fallen to 1,660. The number remained near 1,400 to 1,500 for much of the mid-2000s before reaching **1,174 notices in 2009**. That represented a decline of almost **60 percent from the 1998 peak**.

The timing of that low point overlaps with the Global Financial Crisis, but the chart alone cannot prove that the crisis caused the decline. A line chart can show when two events occurred, but it cannot isolate the effect of falling property values, changes in landlord incentives, court activity, tenant finances, or housing policy.

The fall also did not last. Beginning in the early 2010s, filings rose again:

- 1,631 notices in 2012;
- 1,871 in 2013;
- 1,982 in 2014;
- 2,091 in 2015; and
- **2,134 in 2016**.

From 2009 to 2016, the annual count increased by almost **82 percent**. The rebound did not reach the 1998 peak, but it shows why the long-term pattern cannot be described as a continuous improvement.

Filings declined after 2016 and then dropped especially sharply in 2020. The city recorded **1,435 notices in 2019** and **778 in 2020**, a one-year decline of nearly **46 percent**.

That break coincided with the beginning of the COVID-19 pandemic and emergency protections limiting some evictions. San Francisco’s local COVID-era eviction moratorium eventually ended on August 29, 2023. The chart strongly suggests that the pandemic period disrupted the normal filing pattern, but it cannot measure exactly how much of the decline came from legal protections, court delays, landlord decisions, or other changes.

The low number of notices during the pandemic also should not be interpreted as proof that housing insecurity disappeared. Many tenants faced job losses, unpaid rent, and the possibility of future displacement even when a formal notice was not filed.

After 2020, the pattern became volatile. Filings increased to 987 in 2021 and 1,298 in 2022, fell to 784 in 2023, rose to 921 in 2024, and then jumped to **1,495 in 2025**. The increase between 2024 and 2025 was approximately **62 percent**.

Even after that rebound, the 2025 total remained about **49 percent below the 1998 peak**.

The 2026 point should be read differently from every earlier point because it is incomplete. The dataset contained **856 notices through early July 2026**, not a full calendar year. It would be misleading to conclude from the chart that 2026 represents another annual decline.

The most defensible conclusion is that San Francisco files substantially fewer eviction notices than it did in the late 1990s, but the decline has been interrupted by major periods of renewed pressure.

---

## The Mission stands apart from the rest of the city

![San Francisco neighborhoods with the most eviction notices](neighborhood_evictions.png)

The neighborhood results reveal a much sharper imbalance.

The ten neighborhoods with the largest cumulative totals were:

| Rank | Neighborhood | Eviction notices |
|---:|---|---:|
| 1 | Mission | 5,546 |
| 2 | Tenderloin | 3,534 |
| 3 | Sunset/Parkside | 2,948 |
| 4 | Outer Richmond | 2,372 |
| 5 | Castro/Upper Market | 2,073 |
| 6 | Lakeshore | 2,044 |
| 7 | South of Market | 1,954 |
| 8 | Nob Hill | 1,790 |
| 9 | Hayes Valley | 1,724 |
| 10 | Bayview Hunters Point | 1,487 |

Together, these ten neighborhoods accounted for **25,472 notices**, or about **52 percent of all notices with a known neighborhood**.

The Mission is not simply the first-ranked neighborhood. It is an outlier. Its 5,546 notices exceeded the Tenderloin’s total by 2,012 and were approximately 57 percent higher. The Mission and Tenderloin together accounted for almost **19 percent of all notices assigned to a neighborhood**.

That concentration matters because the Mission is not only a geographic category. It has long been a center of Latino culture, immigrant life, working-class families, neighborhood businesses, and community organizations. A 2024 San Francisco Planning report found that Latino residents made up approximately **32 percent of the Mission’s population in 2022**, compared with **16 percent citywide**.

The data does not show that all, or even most, of the tenants associated with the Mission notices were Latino. It would be inaccurate to take the neighborhood’s demographic composition and assign it to each record. That would be an example of the **ecological fallacy**, in which group-level characteristics are incorrectly treated as facts about every individual in the group.

The data also cannot establish that landlords filed notices because of racial prejudice. There is no tenant-race field, no landlord-race field, and no measure of intent.

A narrower and more supportable conclusion is that San Francisco’s largest concentration of eviction notices occurred in a historically Latino neighborhood that has also faced substantial displacement pressure. Even without proof of intentional discrimination in individual cases, a high concentration of notices can contribute to a racially unequal effect if it destabilizes a community that is disproportionately Latino.

Displacement can involve more than the loss of an apartment. Residents may be separated from schools, relatives, jobs, transit, medical providers, neighborhood businesses, places of worship, and cultural institutions. When the affected neighborhood has a distinct racial or cultural identity, the cumulative effects can change the identity of the community itself.

Bayview Hunters Point, which recorded 1,487 notices, adds another racial dimension. The neighborhood is central to San Francisco’s Black history and is home to the city’s African American Arts and Cultural District. Its presence in the top ten makes it important to investigate further.

At the same time, the full ranking prevents an overly simple racial conclusion. Sunset/Parkside, Outer Richmond, Castro/Upper Market, Lakeshore, and Nob Hill also appear near the top. These neighborhoods have different demographic profiles and housing markets. The list therefore does not support a claim that eviction notices occur only in Black and Latino neighborhoods.

The problem appears citywide, but the consequences may still be unequal.

---

## What this analysis cannot answer

The neighborhood chart shows **concentration**, not **individual risk**.

A larger neighborhood or one with more rental units can produce more notices simply because more tenants live there. To compare risk fairly, the next stage of analysis should calculate:

> **Eviction notices per 1,000 renter households**

That would require joining the Rent Board data with Census or city demographic data on renter-occupied households. The resulting rates could confirm that the Mission has unusually high eviction exposure, or they could reveal that a smaller neighborhood has a higher rate despite a lower total.

The current analysis also does not separate the different legal reasons for eviction. The dataset contains Boolean fields for owner move-in, breach, nuisance, Ellis Act withdrawal, nonpayment, capital improvement, and other causes. A preliminary count of those fields suggests that the most frequently marked reasons were owner move-in, breach, and nuisance, but reasons can overlap within a single notice. A separate chart would require explaining clearly that the categories do not necessarily add to 100 percent.

Another missing piece is the outcome of each notice. The data identifies the beginning of a legal process, not its conclusion. A complete story would need information on court filings, settlements, withdrawals, tenant departures, and legal representation.

Most importantly, the dataset cannot replace interviews. A responsible reported version of this project would include conversations with:

- tenants who received notices;
- tenant attorneys and housing counselors;
- landlord representatives;
- San Francisco Rent Board staff;
- neighborhood and cultural organizations; and
- researchers who study displacement.

Those interviews could test whether the patterns in the spreadsheet match what people experience in the city.

---

## Ethical concerns

Eviction data can unintentionally stigmatize the same communities it is meant to illuminate.

Calling the Mission, Tenderloin, or Bayview Hunters Point an “eviction neighborhood” could make residents seem responsible for conditions produced by landlords, housing prices, legal rules, and broader economic forces. A neighborhood’s high total should not be interpreted as evidence that its residents are unstable, irresponsible, or undesirable.

The racial framing also requires care. Because the dataset contains no tenant-level racial data, it would be unethical to describe every Mission notice as an eviction of a Latino tenant or every Bayview notice as an eviction of a Black tenant. Neighborhood demographics provide context, not proof of individual identity.

The charts may also create a false sense of precision. Raw totals can be counted exactly, but they do not capture the uncertainty surrounding case outcomes, missing neighborhood assignments, household size, or tenant demographics.

For these reasons, the language in this project consistently uses **“eviction notices”** rather than treating every record as a completed eviction. It describes a possible racially unequal impact without claiming that the data proves discriminatory intent.

---

## Final takeaway

San Francisco recorded far fewer eviction notices in 2025 than it did at the dataset’s 1998 peak. But the path between those years was uneven: filings fell during the 2000s, rose sharply in the mid-2010s, collapsed during the pandemic, and rebounded in 2025.

The neighborhood pattern is less ambiguous. More notices were associated with the Mission than with any other neighborhood, and the gap between the Mission and the rest of the city was substantial.

That does not prove that every notice became an eviction. It does not reveal the race of each tenant, and it does not prove racist intent. But it does show that the formal threat of eviction was concentrated most heavily in a historically Latino neighborhood already at the center of San Francisco’s displacement debate.

The most important lesson from the data is that housing instability is not experienced as a citywide average. It reaches particular buildings, blocks, households, and communities.

San Francisco may be filing fewer eviction notices than it did nearly three decades ago. The harder question is **who continues to carry the burden—and what the city loses when longtime residents can no longer remain.**

---

## Sources

- [DataSF: Eviction Notices](https://data.sfgov.org/Housing-and-Buildings/Eviction-Notices/5cei-gny5)
- [San Francisco: Evictions in San Francisco](https://www.sf.gov/evictions-san-francisco)
- [San Francisco Planning: Mission Action Plan 2020 Annual Status Report 2024](https://sfplanning.org/sites/default/files/documents/citywide/map2020/MAP2020_Status_Report_2024.pdf)
- [San Francisco Cultural Districts Program](https://www.sf.gov/san-francisco-cultural-districts-program)
