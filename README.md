# Regional Data Protection Regulation Impact on Chilling Effects Mitigation

## Abstract

Based on research by Jonathon W. Penney on the impact of online surveillance on regulatory “Chilling Effects”, our project aims to determine whether data protection regulations that have come into force in the years following the Snowden scandal is an effective measure to prevent such effects.

Data protection regulation being based on regional law, our study will focus on Europe and the introduction of the General Data Protection Regulation by the European Union. In order to better restrict our area of study to the one directly affected by GDPR, our study will focus on the German version of Wikipedia instead of the English one. Indeed, German-speaking countries all are located in central Europe, and are either members of the EU or strongly affected by GDPR.

We will concentrate our efforts on determining whether the introduction of GDPR on May 25th 2018 has a significant impact on the trend of the number of pageviews on privacy-sensitive topics, by using the same technique as Penney to study an Interrupted Time Series, using the same privacy-sensitive Wikipedia pages his study proposes.

## Research Question

- Demonstrate a significant majority of de.wikipedia.org pageviews come from GDPR-affected countries (which we will define as EU + CH + LI + UK)
- To which extent did the introduction of GDPR allow a reduction of “chilling effects” relative to privacy-sensitive Wikipedia researches?

## Proposed Dataset

In order to demonstrate a significant majority of de.wikipedia.org pageviews come from GDPR-affected countries, we can easily use data from https://stats.wikimedia.org/#/de.wikipedia.org/

Unfortunately, at the time we write these line, Penney’s source, the website https://stats.grok.se/, is completely unavailable. As such, finding the same data as the initial author for de.wikipedia.org is more of an issue. We plan on using Wikipedia REST API (https://wikimedia.org/api/rest_v1/#/Pageviews%20data), which provides access to Wikimedia content and data, including pageviews. As a backup plan, we also found another source at https://pageviews.toolforge.org/. Both these sources don't allow us to retrieve data before July 2015, but it should be sufficient since the GDPR law was introduced in 2018.

## Methods

We will use the same method as proposed by Penney’, i.e. a model-based study of an Interrupted Time Series, with the interruption date being May 2018. We will use the same set of privacy-sensitive pages, and one of the proposed control groups as a comparison basis.

## Proposed Timeline
### Week 11 - November 23 - 29
- Writing creative extension proposal
- Start data collection

### Week 12 - November 30 - December 06
- Finalise data collection
- Data cleaning
- Researching eventual outliers in data
- Demonstrating pertinence of using German data (i.e. most pageviews come from GDPR-affected countries)

### Week 13 - December 07 - 13
- Model-based analysis
- Model-based analysis of control data
- Start writing conclusions

### Week 14 - December 14 - 18
- Finalising project
- Shooting video

## Organisation within the team

- Writing creative extension proposal : Léo, Juliette
- Start data collection : Delphine, Juliette

- Finalise data collection : Delphine, Juliette
- Data cleaning : Delphine, Juliette
- Researching eventual outliers in data : Léo
- Demonstrating pertinence of using German data : Léo

- Model-based analysis : Delphine, Léo, Juliette
- Model-based analysis of control data : Delphine, Léo, Juliette
- Start writing conclusions : Delphine, Léo, Juliette

- Finalising project : Delphine, Léo, Juliette
- Shooting video : Delphine, Léo, Juliette

## Questions for TA

- We are having a little trouble understanding the change that was made to the Wikipedia data in 2015, they went from pagecounts to pageviews and we don’t understand if they are comparable or not. Is it possible to aggregate these two? 
- They say mobile views are not included in the data before 2015, but does this mean that the number of views on mobile were not counted at all or are they just not distinguished from the other views ?
