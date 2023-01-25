# minimal_description_analysis
An analysis of applications with very little text for the title, or abstract information.

How many applications are in our database that need more detail, in order to better identify the title and goals?

Some initial questions include:
  - What is the distribution of lengths of title and the different notes?
  -	Is there a minimum number of characters/words?
  -	Does this distribution change over time?
  -	There are three types of sources to be looked into: title, (tech) summary, expected impact. Should the counts be independent, or analysed in a combined method?

Data tables/fields involved:
  ukri_ssd.dbo.ssd_applications
  - application_title
  ukri_ssd.dbo.ssd_notes
  - summary_abstract
  - technical_abstract
  - expected_impact
