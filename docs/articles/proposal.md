# Homicide Mortality Before and After Permitless Concealed-Carry Adoption

### Research Question

How did age-adjusted homicide mortality rates change before versus after
permit-less concealed-carry of weapons in US states with the most Gun
violence history ?

### Data

Combine CDC homicide mortality and RAND firearm legislation, documenting
sources, versions, variable definitions, and cleaning decisions, and
verifying policy dates against official state sources. Eligible states
have a documented adoption during 2017–2021 and complete homicide rates
for a 2014–2016 baseline and the three years before and after adoption.
Among eligible states, the five with the highest baseline rates are
Missouri, Oklahoma, Tennessee, Kentucky, and Texas.

### Exposure and outcome

Exposure: pre-adaptation versus post-adoption status for permit-less
concealed carry. Adoption years are excluded from primary comparisons.
Outcome: annual age-adjusted homicide mortality rate per 100,000
residents (continuous), including firearm and nonfirearm homicides.
Missing or suppressed values stay missing.

### Analysis

I will summarize rates, compare before and after averages, and make
trend plots and paired-dot comparisons. Exploratory per-state
regressions of rate on year and post-adoption status will be interpreted
cautiously given the short, correlated series.

### Confounders and limitations

Socioeconomic conditions and concurrent firearm laws may confound the
association. I will document concurrent policies where feasible, but
socioeconomic adjustment is not possible within these two datasets.
Pandemic-era changes, selection of high-baseline states, and no
untreated comparison group limit interpretation. Findings describe
associations, not causal policy effects.

### Deliverables

An R package and public pkgdown site with two vignettes: one on homicide
patterns, one on policy histories and before-and-after comparisons.
