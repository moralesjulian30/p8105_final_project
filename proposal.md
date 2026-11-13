Proposal
================
2026-11-11

## The group members (names and UNIs)

- Yueran Pan (yp2743)
- Zaixin Gao (zg2582)
- Andrea Vasquez (adv2123)
- Julian Morales (jem2315)

## The tentative project title

Bin There, Done That? Evaluating rat activity after NYC’s Trash Bin
Mandate

## Motivation

To the world, New York City is the “Big Apple,” but many New Yorkers
know it as the city of rats. A 2023 estimate put the population at as
many as 3 million rats, roughly one for every three New Yorkers. Rats
are also a public health concern: they spread leptospirosis, and NYC
reported a record 24 human cases in 2023.

To cut off rats’ food supply, the city began requiring trash to be
placed in lidded bins instead of bags on the curb. The rules were phased
in: food-related businesses in 2023, all businesses in March 2024, and
buildings with 1–9 residential units in November 2024. But does it work?

This project will test whether 311 rat sightings, a proxy for rat
activity, declined after the bin rules took effect, and whether they
declined more in neighborhoods where the residential rule applied to
more housing.

## Intended final products

A public website with a full report, interactive maps of NYC community
districts showing rule exposure and changes in rat activity, time-series
plots of monthly rat sightings with the policy dates marked, and a
two-minute screencast.

## Anticipated data sources

- **NYC 311 Service Requests** (2010–2019 and 2020–present): monthly
  rat-sighting counts by community district
- **NYC Rodent Inspection**: share of initial inspections finding active
  rat signs
- **PLUTO**: share of residential units in 1–9 unit buildings in each
  community district
- **NYC Community District boundaries**: for mapping

## Planned analyses, visualizations, and coding challenges

We will compare rat sightings before and after each rule, citywide and
by district, and test whether the decline was larger in districts with
more small residential buildings, using count models that account for
seasonality. Visualizations will include district maps, time-series
plots, and borough comparisons using Plotly.

Challenges include combining datasets with different district formats,
efficiently downloading and filtering large 311 files, separating
seasonal patterns and overlapping policies from the rules’ effects, and
the fact that 311 complaints reflect reporting, not true rat numbers.

## Planned timeline

- **Nov 16–20:** Project review meeting; review and download all data
  sources
- **Nov 20–27:** Clean and merge data; define comparison periods;
  preliminary analysis
- **Nov 28–Dec 4:** Build maps and plots; run models; set up website
  pages
- **Dec 5–11:** Write report; finish website; record screencast
- **Dec 12:** Submit report, website, screencast, and peer assessment
