# Participation capacity instrument

A simple scoring tool for judging how ready an emerging farmer programme is to take part in a commercial supply chain. It was developed in the thesis for intensive ostrich farming, but it is designed to be adapted to other sectors.

## Status

This is a **prototype**. It was built to compare case studies and has not been statistically validated, so its predictive power is unknown. Treat scores as a structured basis for discussion, not as a measurement.

## How it works

The instrument combines four indices. Each is scored, converted to a percentage of its maximum, and compared across programmes or over time. A higher combined score suggests greater capacity to participate.

Because it is quick to administer, it can be repeated at intervals to track a programme's progress.

The Local Vulnerability and Human Capacity indices are hard to change through intervention. The Agrarian Capacity and Market Access indices are where support can make the biggest difference.

## 1. Local Vulnerability Index (LVI)

Measures how a programme's location affects its chances, mainly remoteness and environmental fragility.

The thesis used the nearest available sub-national score from Naudé, McGillivray and Rossouw (2008), which combines indicators such as local economy size and structure, trade capacity, remoteness, development level, income volatility, demography and health, governance and environment. On that scale the maximum (lowest vulnerability) is 354.

Other contexts will need an equivalent local index.

## 2. Human Capacity Index (HCI)

Indicates farmers' likely productivity and capacity. Adapted from Kinsey and Binswanger (1993) and Van Rooyen et al. (1998). The criteria below sum to a maximum of 12. (The thesis table gives the maximum as 11, which appears to be an arithmetic slip.)

| Criterion | Scoring |
|---|---|
| Electricity | Yes = 4, otherwise 0 |
| Age | 30 to 45 years = 2; younger or older = 1 |
| Agricultural experience | 1 to 2 years = 1; 3 to 4 years = 2; over 4 years = 3 |
| Education | None = 0; primary or secondary = 1; senior certificate = 2; tertiary = 3 |

## 3. Agrarian Capacity Index (ACI)

Based on sustainable agriculture themes of environmental soundness, economic viability and social equity (Allen et al., 1993). Each criterion is rated weak = 1, moderate = 2 or strong = 3. Maximum 60 across the 20 scored criteria.

1. Institutional support from industry
2. Scale of production required for the sector
3. Independence from mentorship
4. Training programme
5. Supply chain engagement
6. Agricultural capability of the land
7. Economic strength post-farm gate
8. Influence on decisions post-farm gate
9. Contractual linkages with the value chain
10. Community acceptance
11. Collective action strength
12. Independence from donors
13. Access to credit
14. Independence from non-farm income
15. Governance in the supply chain
16. Price leverage
17. Farm record-keeping
18. Programme leadership
19. Home-to-farm distance
20. Programme income

The thesis text also lists *dependence on government or extension involvement*. It was not part of the scored table, but it can be added as a 21st criterion (raising the maximum to 63).

## 4. Market Access Capacity Index (MACI)

Built from the literature on what determines smallholder market participation. Maximum 20.

| Criterion | Scoring |
|---|---|
| Sufficient infrastructure | Yes = 1 |
| Sufficient equipment | Yes = 1 |
| Owns transport | Yes = 1 |
| Owns a mobile phone | Yes = 1 |
| Engaged with a market channel | Yes = 1 |
| Receives market information feedback | Yes = 1 |
| Distance to market | Over 100 km = 1; 21 to 100 km = 2; 0 to 20 km = 3 |
| Distance to nearest town | Over 100 km = 1; 21 to 100 km = 2; 0 to 20 km = 3 |
| Agricultural experience | 1 to 2 years = 1; 3 to 4 years = 2; over 4 years = 3 |
| Education | None = 0; primary = 1; secondary = 2; tertiary = 3 |
| Collective action present | Yes = 1 |
| Access to market information | Yes = 1 |

## Using it

1. Collect data through observation, a short questionnaire and a group discussion with farmers and support staff.
2. Score each index with `scoring-template.csv`.
3. Convert each index to a percentage of its maximum.
4. Plot the four percentages (a bar or radar chart works well) to see where a programme is strong or weak.
5. Repeat after interventions to track change.

## Sources

- Allen, P., Van Dusen, D., Lundy, J., & Gliessman, S. (1993). *Expanding the definition of sustainable agriculture*. Agroecology Program, University of California, Santa Cruz.
- Kinsey, B. H., & Binswanger, H. P. (1993). Characteristics and performance of resettlement programs: A review. *World Development*, 21, 1477–1494.
- Koenig, T., Blatt, J., Brakel, K., Kloss, K., Nilges, T., & Woellert, F. (2008). *Market-driven development and poverty reduction: A value chain analysis of fresh vegetables in Kenya and Tanzania*. The scoring approach was adapted from this study.
- Naudé, W., McGillivray, M., & Rossouw, S. (2008). *Measuring the vulnerability of subnational regions*. UNU-WIDER Research Paper 2008/54.
- Van Rooyen, J., Groenewald, J., Ngqangweni, S., & Fenyes, T. (1998). *Agricultural policy reform in South Africa*. Francolin.

Full references are in the thesis.
