# projectPython
EDA of the 1692 Salem Witch Trials

I found this data set on Kaggle, uploaded by Rachel Tatman, who credits Professor Richard Latner of Tulane University for making this material available. There are 8 .csv files providing quantitative data listing names of all 152 accused, focusing on the geographic spread of the outbreak, the socio-economic conditions of the populace, and the chronology of events.

While vetting this data set for my python project, two files, in particular, caught my eye: a Pro Parris file, and an Anti Parris file. Two petitions signed in 1695, two years after the end of the outbreak. The first was the Anti-Parris Petition, signed by 85 villagers. Their intent was to strip the local minister, named Samuel Paris of his job and titles. The responding petition was Pro-Parris, and contained 105 signatures.

In the year before the outbreak, the villagers decided to stop paying taxes, as the good Rev's wages were drawn from them. They revoked his title to the parish estate, and refused to attend his services. This was not an unusual tactic for the village, as they had sent four Puritan Ministers packing in similar fashion before Paris ever arrived. Such was the contentious background of this entire episode of colonial history.

I focused a lot of my time in the Tax Data Set, as this set had gender, church affiliation and tax payments of each villager over the duration of Samuel Parris's tenure, whether they paid taxes or not.

Salem was notoriously cantankerous. There was friction between Salem and the other townships and churches. The Puritans didn't like Catholics or Quakers, and according to the historical record, Salem Villagers were a litigious group on the whole.

Samuel Paris was the Nexus point of the outbreak. As fate would have it, he was the head of the first household to produce an accusation of witchcraft. Her name was Tituba Indian. An enslaved woman that Samuel purchased while still living in Barbados. Samuel's children accused her of longtime magical exploits, to which she confessed when 'questioned'. Her husband, John Indian joined forces with Samuel's children and began accusing other villagers of witchraft. And it just sort of bloomed outwards from there.

It stopped as quickly as it began In October 1692.

![accused_fig.1](https://user-images.githubusercontent.com/90716926/144075411-dc5cc991-bb97-4393-8b6e-7211f7152168.png)

#Main Take Aways:
the histogram follows a bimodal pattern, suggesting we are looking at two mirroring outbreaks. The distribution plot below, shows us two major sectors driving the outbreak. 
![distribution_fig1](https://user-images.githubusercontent.com/90716926/144080766-fa09ab4f-db2c-4bfc-ba5c-d9fb624b8b6c.png)

Sentiments by voter vs sentiments by taxpayer's show an inversed pattern.
![sentiment_by_voter_fig1](https://user-images.githubusercontent.com/90716926/144081321-ac2ab289-3db3-456d-a0a3-5c9728f5866c.png)
![sentiment_by_taxpayer_fig1](https://user-images.githubusercontent.com/90716926/144081303-faddf525-f1b8-4307-8c8e-000522fc7029.png)

It appears there were two major groups driving the outbreak.
Those with political power and money.  On one side they were pro Parris, on the other, they were anti-Parris.
The LARGEST group, were the least economically advantaged, least engaged in politics and least likely to care about Samuel Parris.
Paradoxically - those who threw the most support behind Parris were unaffiliated with the church in question.  Church goers were more likely to oppose him than support him.  There fore the Null Hypothesis, that church membership would predict support for Parris, was rejected with a huge p-value of 9.

It appears while much has changed over the past 300 years, somethings remain the same.
