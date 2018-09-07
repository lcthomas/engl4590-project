---
id: 36
title: From the Geographic Lens
date: 2016-04-13T20:35:05+00:00
author: lindsaythomas
layout: page
guid: http://lindsaythomas.net/engl4590-project/?page_id=36
ample_page_layout:
  - no_sidebar_full_width
---
## <span style="text-decoration: underline"><strong>Project Overview</strong></span>

Group Members: Betsy Boggs, Tanner Massey, Kelsey Turner

As a group, we decided to focus our analysis of our class&#8217; Gothic and Horror corpora on how an author&#8217;s country of origin informs his or her genre or the content of his or her story. Like the Project Overview page of this site explains, our class corpus includes 213 Gothic and Horror texts from the 18th, 19th, and 20th centuries. Along with our class corpora, as a class we also created an accompanying metadata spreadsheet listing biographic and demographic information about the authors, publication information, word count, etc.. Throughout the process of collecting these texts and recording their metadata, our group became interested in the many different nations of origin represented by the authors in our corpora and the differences in vocabulary or content of story that may appear with the varying countries of origin. Our group began by creating a spreadsheet that listed the different authors and their biographic and demographic information. We continued our project by mapping the locations of these authors&#8217; nations of origin, dividing the corpora up by country between our group members, and then organizing the texts from our collaborative class corpus by author nation of origin. After doing this, we ran each country&#8217;s texts (both scrubbed using Lexos and unscrubbed) through Antconc and created another spreadsheet to keep track of the most frequently used words for each country&#8217;s texts. We were then able to take this information and plug it into Gephi in order to create a data visualization in the form of a network analysis graph to view the relationships between the most frequently used words and the authors&#8217; countries of origin.

## <u>Data Visualization: Author Origins</u>

#### **Author Nation of Origin Map**

<img class="alignnone size-full wp-image-259" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-8.20.34-PM.png" alt="Screen Shot 2016-04-25 at 8.20.34 PM" width="1265" height="428" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-8.20.34-PM.png 1265w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-8.20.34-PM-300x102.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-8.20.34-PM-768x260.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-8.20.34-PM-1024x346.png 1024w" sizes="(max-width: 1265px) 100vw, 1265px" />

This map, constructed in <a href="https://www.google.com/fusiontables/data?dsrcid=implicit" target="_blank">Google Fusions</a>, shows the origins of the 64 authors in our gothic/horror corpus. The locations were determined by the author&#8217;s birthplace. As you can see, they are largely concentrated in the United States and Europe, with the United Kingdom as the dominant source of texts.

#### **Percentage of Texts in Corpora Represented by Country**

<img class="alignnone size-full wp-image-281" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-10.52.02-AM.png" alt="Screen Shot 2016-04-26 at 10.52.02 AM" width="654" height="441" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-10.52.02-AM.png 654w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-10.52.02-AM-300x202.png 300w" sizes="(max-width: 654px) 100vw, 654px" />

Also created in Google Fusions, this pie chart is another way to visualize our origin data. It confirms that the majority of the texts in our corpus come from English authors.

We made our own mini-corpora containing the works of all authors in our corpus from each country.

## <u>Word Frequency by Country</u>

<img class="alignnone size-full wp-image-282" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-10.57.38-AM.png" alt="Screen Shot 2016-04-26 at 10.57.38 AM" width="1005" height="467" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-10.57.38-AM.png 1005w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-10.57.38-AM-300x139.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-10.57.38-AM-768x357.png 768w" sizes="(max-width: 1005px) 100vw, 1005px" />

This is the spreadsheet that contained our word frequency data for each nation, collected with <a href="http://www.laurenceanthony.net/software/antconc/" target="_blank">Antconc</a>, a text analysis software. The following is an explanation of each column.

  * **Location: **The country that the given corpus represents.
  * **Scrubbed/Unscrubbed: **We used the <a href="http://lexos.wheatoncollege.edu/upload" target="_blank">Lexos scrubbing tool</a> to clear our texts of stop words, such as articles and common proper names. The corpora labelled &#8220;unscrubbed&#8221; were run through Antconc before being scrubbed with Lexos, which yielded different results.
  * **Frequently Used Words: **Here, we listed the top three words given by frequency in Antconc. The unscrubbed words, however, had to be selected by hand as relevant, as the actual top words are articles like &#8220;and&#8221; or &#8220;the.&#8221; We used the unscrubbed documents because sometimes, stop lists can take out words that may be important to the texts.
  * **Frequency: **This column contains the number of times a word shows up in the given corpus.
  * The next two columns are the actual top words in the unscrubbed corpora and their frequencies. They are articles and don&#8217;t show anything unique about the corpora, but we included them for the sake of accuracy.
  * **Word Types:** The number of unique words in the corpus.
  * **Word Tokens: **The number of total words in the corpus. As you can see, some are much larger than others.

A word that consistently shows up in the top three across countries is **time**. It seems to suggest that the gothic/horror genre as a whole is concerned with time in some way, but it&#8217;s hard to say how with only a list of words. Another word that appears frequently is **little**. What&#8217;s being described as little so much in these works? We conduct further analysis to try and answer these questions (see Interpretations).

## <u>Network Analysis</u>

[<img class="alignleft wp-image-268 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.53.23-PM-1-152x300.png" alt="Screen Shot 2016-04-25 at 9.53.23 PM" width="152" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.53.23-PM-1-152x300.png 152w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.53.23-PM-1.png 340w" sizes="(max-width: 152px) 100vw, 152px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.53.23-PM-1.png)    [<img class="alignnone wp-image-267 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.54.56-PM-152x300.png" alt="Screen Shot 2016-04-25 at 9.54.56 PM" width="152" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.54.56-PM-152x300.png 152w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.54.56-PM.png 343w" sizes="(max-width: 152px) 100vw, 152px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-9.54.56-PM.png)

The network analysis below illustrates the relationship between countries and the top three most frequent words found in the texts from those countries. The nodes of the network represent countries or words and increase in sized based on the number of interactions &#8212; each country will, therefore, be the same size because they only connect to three other nodes. Word nodes range in size based on the number of countries that connect to them. Word nodes like room, sir, baron, and nose only have 1 connection while larger word nodes like little and time are found most often in more countries. Time, for example, has 7 connections.

Each country node has been given a color that extends from the node along an edge and into a word node. The word nodes take on the color of country nodes that connect to it, each color adding together and creating a new color. Theoretically, if there were a very large number of country nodes that connected to a single word node, that word node would eventually turn black. The colored edges can be followed from the node of origin, the country node, to the word nodes in a clockwise manner. This signifies direction along the edge.

Two country nodes, Czech Republic and Ukraine, do not share any of their top three words with other countries. They are disconnected from the network as is illustrated below.<figure id="attachment_260" style="width: 300px" class="wp-caption alignnone">

[<img class="wp-image-260 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords-300x300.png" alt="NationWords" width="300" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords-300x300.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords-150x150.png 150w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords-768x768.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords-230x230.png 230w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords-330x330.png 330w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords.png 1024w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/NationWords.png)<figcaption class="wp-caption-text">Countries and Top Words Network (click to expand)</figcaption></figure> 

## <span style="text-decoration: underline"><strong>Interpretations</strong></span>

#### **Antconc: Collocates and Concordance**

## &#8220;Time&#8221;

As the most frequently occurring word in our class&#8217; collective corpus of Gothic and Horror texts, it makes sense that &#8220;time&#8221; is also one of the most frequently occurring words in many of the corpora organized by nation of author origin. Listed as one of the top three most frequently occurring words for our mini-corpora of texts from Ireland, England, France, Scotland, the United States, Russia, and Germany, this suggests that _time_ was perhaps a very scary concept, idea, or theme that seemed to characterize much of the literature from 18th, 19th, and 20th even across cultures. Because of this, _time_ seems to function as a sort of unifying theme for Gothic and Horror literature from this time period. Below, there are screenshots of the word &#8220;time&#8221; in context in the concordance view in Antconc for both the United States&#8217; and Ireland&#8217;s corpora of texts. The concordance view allows the user to view a certain word being used in context across a large span of texts. With the U.S. making up 15.4% of our class&#8217; collaborative corpus, learning about how &#8220;time&#8221; functions as a theme of texts from the Gothic and Horror genres produced by American authors using the concordance view can also provide insight into what about time during that particular historical period in American history was so frightening or horrific. For example, from the text listed in the concordance view of the American corpus, the text seems to suggest that much of the literature from the Gothic and Horror genres during this particular time period seemed to be focused on time and its relation to or its functioning as storms and natural disasters. Words like &#8220;island,&#8221; &#8220;shore,&#8221; &#8220;distant,&#8221; &#8220;strong,&#8221; eddies,&#8221; &#8220;slackwater,&#8221; &#8220;water,&#8221; &#8220;surface,&#8221; &#8220;gasping,&#8221; &#8220;ocean,&#8221; &#8220;smashing,&#8221; and &#8220;branches&#8221; from the screenshot below convey this.

United States

[<img class="alignnone wp-image-274 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.23.28-PM-300x178.png" alt="Screen Shot 2016-04-25 at 10.23.28 PM" width="300" height="178" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.23.28-PM-300x178.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.23.28-PM-768x456.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.23.28-PM.png 948w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.23.28-PM.png)

Although the texts from Irish authors only make up 9.2% of our class&#8217; collective corpus, that is still one of the most represented countries in terms of author nation in our corpus. According to the concordance view in the Antconc screenshot for the Irish corpus below, _time_ seems to function a bit differently for Irish authors and in Irish Gothic and Horror texts of the 18th, 19th, and 20th centuries than it did for American authors and in American Gothic and Horror literature of the same time period.

Ireland

[<img class="alignnone wp-image-272 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.24.40-PM-300x177.png" alt="Screen Shot 2016-04-25 at 10.24.40 PM" width="300" height="177" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.24.40-PM-300x177.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.24.40-PM-768x454.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.24.40-PM.png 948w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-25-at-10.24.40-PM.png)

Making up the largest percentage of our corpus, English texts account for nearly half (49.2%) of the texts in the corpus. Drawing conclusions on this particular time period in England based off of the words most commonly located in these English texts near the word _time_ may seem valuable, but because most of the collocates are commonly used words like &#8220;little,&#8221; &#8220;came,&#8221; &#8220;short,&#8221; and &#8220;night,&#8221; while this does seem to suggest a physicality to _time_, there isn&#8217;t much else that I feel as though I can argue in terms of how _time _functions as a theme for English Gothic and Horror texts of the 18th, 19th, and 20th centuries.

England collocates of &#8220;time&#8221; arranged by statistic.                            England collocates of &#8220;time&#8221; arranged by frequency.

<a href="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Stat.jpg" rel="attachment wp-att-305"><img class="wp-image-305 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Stat-237x300.jpg" alt="EnglandCollocatesTime_Stat" width="237" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Stat-237x300.jpg 237w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Stat-768x972.jpg 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Stat.jpg 775w" sizes="(max-width: 237px) 100vw, 237px" /></a>                                                         <a href="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Freq.jpg" rel="attachment wp-att-304"><img class="wp-image-304 size-medium alignnone" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Freq-236x300.jpg" alt="EnglandCollocatesTime_Freq" width="236" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Freq-236x300.jpg 236w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Freq-768x976.jpg 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandConcordance_Freq.jpg 777w" sizes="(max-width: 236px) 100vw, 236px" /></a>

For many of the countries represented in our corpus, so few texts compose their corpora that any conclusions drawn or analyses suggested may not be of much merit. Drawing conclusions about the countries of Russia, Scotland, France, and Germany by simply running a few texts by authors from each country through Antconc does not allow me to interpret _time_ as functioning as a theme in the Gothic and Horror literature of the 18th, 19th, and 20th centuries, nor does it allow me to draw very many conclusions about how _time_ informs my understanding of the historical context of these countries during this time period. If I had to speculate using these few texts, however, I might suggest that _time_ seems to function in the literature from these countries as something more physical. In the collocate view in Antconc, you can see the words that most often surround the word _time _in these texts. Words like &#8220;short,&#8221; &#8220;day,&#8221; &#8220;began,&#8221; &#8220;hours,&#8221; &#8220;day,&#8221; and &#8220;present&#8221; suggest a more physical association of _time _for these countries. Perhaps, the physicality of time was an important aspect of the Gothic and Horror genres of this time period because humanity was (is) often fearful of death (and sometimes even life) and wasting time (minutes, hours, days). Then again, I am drawing this conclusion from solely looking at the collocates view in Antconc for a very few number of texts. If there were more texts in each corpus and viewing the word _time _in context using the concordance view also confirmed this sense of physicality I am getting, I feel as though I would be able to offer up more of an intelligent analysis.

Russia

[<img class="alignnone wp-image-348 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.51.05-PM-300x219.png" alt="Screen Shot 2016-04-26 at 4.51.05 PM" width="300" height="219" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.51.05-PM-300x219.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.51.05-PM.png 766w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.51.05-PM.png)

Scotland

[<img class="alignnone wp-image-342 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.44.28-PM-300x216.png" alt="Screen Shot 2016-04-26 at 4.44.28 PM" width="300" height="216" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.44.28-PM-300x216.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.44.28-PM-768x553.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.44.28-PM.png 769w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.44.28-PM.png)

France

[<img class="alignnone wp-image-344 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.46.43-PM-300x216.png" alt="Screen Shot 2016-04-26 at 4.46.43 PM" width="300" height="216" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.46.43-PM-300x216.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.46.43-PM-768x552.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.46.43-PM.png 776w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.46.43-PM.png)

Germany

[<img class="alignnone wp-image-340 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.41.20-PM-300x216.png" alt="Screen Shot 2016-04-26 at 4.41.20 PM" width="300" height="216" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.41.20-PM-300x216.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.41.20-PM.png 768w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-4.41.20-PM.png)

## &#8220;Eyes&#8221;

‘Eyes’ is the third most connected word in our corpus. While we can come up with some compelling conclusions based on that information alone, we can look towards other data and find other connections we may not initially assume. The three mini corpora in which ‘eyes’ occurs as one of the top three most frequent words are France, Ireland, and Russia. In the network analysis section above, we can also see that these countries share one other word, ‘time.’ If they share two out of three of the most frequent words found within their corpora, we might be able to assume some common themes exist between these three countries.

<p style="text-align: left">
  Let us look at the collocates of ‘eyes’ within each mini corpora. The figures below show word collocates within five words to the left or right of ‘eyes.’ The frequency in each has been limited to five to take out high frequency words that do not appear often enough in the corpora to draw any conclusions. Few high frequency, high statistic words can be found in all of the corpora, however, there are quite a few collocates that can be found between Ireland and France. This is likely due to the higher number of word tokens in each corpus, 2,599 in France and 8,788 in Ireland, while Russia contains far less word tokens at 629. Were the Russian corpus also above 2,000 word tokens, this would be a telling statistic, but because the variance would be far less due to less word tokens, the difference might be admissible.
</p><figure id="attachment_365" style="width: 237px" class="wp-caption alignleft">

<a href="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Ireland_Collocates_Eyes_Stat.jpg" rel="attachment wp-att-365"><img class="size-medium wp-image-365 aligncenter" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Ireland_Collocates_Eyes_Stat-237x300.jpg" alt="Ireland collocates of &quot;eyes&quot; by statistic." width="237" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Ireland_Collocates_Eyes_Stat-237x300.jpg 237w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Ireland_Collocates_Eyes_Stat-768x974.jpg 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Ireland_Collocates_Eyes_Stat.jpg 777w" sizes="(max-width: 237px) 100vw, 237px" /></a><figcaption class="wp-caption-text">Ireland collocates of &#8220;eyes&#8221; by statistic.</figcaption></figure> <figure id="attachment_364" style="width: 236px" class="wp-caption alignleft"><a href="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Russia_Collocates_Eyes_Stat.jpg" rel="attachment wp-att-364"><img class="size-medium wp-image-364" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Russia_Collocates_Eyes_Stat-236x300.jpg" alt="Russian collocates of &quot;eyes&quot; by statistic." width="236" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Russia_Collocates_Eyes_Stat-236x300.jpg 236w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Russia_Collocates_Eyes_Stat-768x976.jpg 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Russia_Collocates_Eyes_Stat.jpg 777w" sizes="(max-width: 236px) 100vw, 236px" /></a><figcaption class="wp-caption-text">Russian collocates of &#8220;eyes&#8221; by statistic.</figcaption></figure> <figure id="attachment_366" style="width: 235px" class="wp-caption alignleft"><a href="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/France_Collocates_Eyes_Stat.jpg" rel="attachment wp-att-366"><img class="size-medium wp-image-366" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/France_Collocates_Eyes_Stat-235x300.jpg" alt="France collocates of &quot;eyes&quot; by statistic." width="235" height="300" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/France_Collocates_Eyes_Stat-235x300.jpg 235w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/France_Collocates_Eyes_Stat-768x979.jpg 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/France_Collocates_Eyes_Stat.jpg 773w" sizes="(max-width: 235px) 100vw, 235px" /></a><figcaption class="wp-caption-text">France collocates of &#8220;eyes&#8221; by statistic.</figcaption></figure> 

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Between each word collocate list, we can see a focus on color (blue, dark, gray, black, yellow, red) and light (blazing, fire, light, glitter, gleaming, glowed, shone) which within horror and gothic make reasonable sense. The eyes are expressive and can display malevolence or fear. Playing with and describing eyes emphasizes the elements of these similar genres and gives the reader an easily understood image. Frightened eyes are used so much in film that they are basically a meme. We understand eyes. We often assume they cannot lie. To misuse a colloquialism, “the eyes have it.”

## &#8220;Little&#8221;

<p class="p1">
  To determine how the word “little” is used across cultures, we sorted the data by frequency (how many times a word appears in the text) and by stat (how often a word correlates with the searched word) using Antconc’s collocates tool. We set the tests up to show any word that was within two places of “little”.
</p>

<p class="p1">
  When sorted by stat, the results for each country — France, India, England and the United States — turned out to be largely unique.
</p>

<p class="p1">
  <img class="alignnone size-full wp-image-388" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-9.05.25-PM.png" alt="Screen Shot 2016-04-26 at 9.05.25 PM" width="496" height="131" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-9.05.25-PM.png 496w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/Screen-Shot-2016-04-26-at-9.05.25-PM-300x79.png 300w" sizes="(max-width: 496px) 100vw, 496px" />
</p>

<p class="p1">
  It seems to suggest that little is used differently across cultures, as far as what would be described as “little”. However, there is a huge problem with making this statement definitively. Even in the larger corpora, these words that “little” correlates with only show up once or twice in the whole corpus, hence why they have such a high stat number. Because of this issue, I found it more useful to sort collocates by frequency.
</p>

<p class="p1">
  Sorting by frequency is where we start to see some similarities. We have to be careful and pay attention to the stat number though, as a low stat number indicates that the word does not appear with “little” as often as it shows up in the corpus. With that in mind, the data shows that “little” often correlates with domestic places or objects, like “shop”, “room”, “lamp” or “table”. Looking at the concordance, it’s hard to tell if “little” is being used to suggest cozy or crowded space, or something else entirely, but the fact of the matter is that it comes in conjunction with objects, particularly ones of the everyday variety, often.
</p>

<p class="p1">
  In three of the four corpora, “girl” appears together with “little” often enough to be statistically significant. It’s worth noting that “boy” appears in the Indian corpus too. “Little” is also associated with “dear” in two of the three corpora. Perhaps this shows that we associate “little” with precious or “dear” things, like children, and in particular “little” is used to describe the feminine or delicate, even across cultures.
</p>

<p class="p1">
  It’s hard to say how these ideas might be useful for Gothic/horror fiction without some close reading. Perhaps describing something as “little” evokes some desire to protect within us due to our associations with “dear” things, and that can be conducive to fright when those things are harmed. “Little” in terms of space can provide comfort or unsettlement depending on how it’s used too. To conclude, “little” as a descriptor can work in different ways, but it might be used to bring up similar feelings in Gothic and horror works, even across cultures.
</p>

**India**

[<img class="alignnone wp-image-393 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaFreq-300x215.png" alt="IndiaFreq" width="300" height="215" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaFreq-300x215.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaFreq-768x551.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaFreq.png 779w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaFreq.png) [<img class="alignnone wp-image-394 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaStat-300x215.png" alt="IndiaStat" width="300" height="215" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaStat-300x215.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaStat-768x550.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaStat.png 778w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/IndiaStat.png)

&nbsp;

**England**

[<img class="alignnone wp-image-395 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandFreq-300x215.png" alt="EnglandFreq" width="300" height="215" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandFreq-300x215.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandFreq-768x551.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandFreq.png 772w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandFreq.png) [<img class="alignnone wp-image-396 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandStat-300x217.png" alt="EnglandStat" width="300" height="217" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandStat-300x217.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandStat.png 767w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/EnglandStat.png)

**United States**

[<img class="alignnone wp-image-397 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USFreq-300x217.png" alt="USFreq" width="300" height="217" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USFreq-300x217.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USFreq-768x555.png 768w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USFreq.png 775w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USFreq.png) [<img class="alignnone wp-image-398 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USStat-300x219.png" alt="USStat" width="300" height="219" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USStat-300x219.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USStat.png 762w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/USStat.png)

**France**

[<img class="alignnone wp-image-399 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceFreq-300x220.png" alt="FranceFreq" width="300" height="220" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceFreq-300x220.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceFreq.png 768w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceFreq.png) [<img class="alignnone wp-image-400 size-medium" src="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceStat-300x217.png" alt="FranceStat" width="300" height="217" srcset="http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceStat-300x217.png 300w, http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceStat.png 767w" sizes="(max-width: 300px) 100vw, 300px" />](http://lindsaythomas.net/engl4590-project/wp-content/uploads/sites/13/2016/04/FranceStat.png)

## <span style="text-decoration: underline">Conclusion</span>

Each data set and word found here can be interpreted in any number of ways. Just by examining the collocates, we can define time, eyes, and little by changing how we define each other word. The relationship between words and countries can be informed by any number of hypotheses – what makes this possible is the availability of the data. To this end, we have provided multiple forms of visualizations that just begin to represent the relationship between language and location within our corpus.

## <span style="text-decoration: underline">Works Consulted</span>

Wilkens, Matthew. &#8220;The Geographic Imagination of Civil-War Era American Fiction.&#8221; _American Literary History_ 25.4 (2013): 803-840. Print.

&nbsp;