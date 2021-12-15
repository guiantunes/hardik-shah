# Interview Exercise

Open Covid CA (https://opencovid.ca/api/) offers an API with data around Covid cases in Canada.

One of the available endpoints is the summary endpoint: (https://api.opencovid.ca/summary)

It gives us:

Cumulative and daily totals for all data (cases, mortality, recovered, testing, active cases, vaccine administration or vaccine distribution) on a selected date or range of dates. By default returns province-level summaries for the most recent date in the dataset. Note that only case and mortality data are available as health region-level summaries at present.

We need to build a page that receives a date as a parameter and queries this API to show a table with the summary data by province.
