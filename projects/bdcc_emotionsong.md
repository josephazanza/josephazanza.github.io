# Finding patterns between emotional state and played songs

[Joseph Azanza](https://www.linkedin.com/in/josephazanza/) <br>
Asian Institute of Management

## Executive Summary

<p align='justify'> The study of music and emotions is well-explored in neuroscience, psychology, and physiology. However, experiments in these fields are usually time-consuming, costly, and have poor ability to scale as the technology researchers use, e.g. MRI, PET, EEG, ERP, etc., are usually designed to be conducted in a small-scale setting, focusing on one participant at a time. This can potentially limit the important basic research and preliminary studies that are required before delving into more complicated experiments. Here is where we thought we can apply Frequent Itemset Mining and Association Pattern Mining. More specifically we asked, "can we utilize FIM and APM techniques to identify patterns and rules between emotions and songs, such that researchers in the fields of neuroscience, psychology, and physiology can adapt the project for use in their preliminary studies?" If done right, instead of manually screening for the effect of songs, the researchers can use the mined patterns and rules as guidance for more targeted research. </p>

<p align='justify'> To build a proof of concept, we used the #nowplaying-RS dataset published by Poddar, Zangerle, and Yang in 2018. The dataset contains 11.6 million music listening events (LE) spanning the whole 2014, collected via Twitter. The dataset contains basic listening event information, Tweet information, track musicality (via Spotify API), and sentiment analysis results performed on the hashtags (by the original researchers). In building the pipeline, we first cleaned and preprocessed the sentiment data, choosing to keep data from the SentiStrength lexicon. We then joined the sentiment data to the basic listening event data, with the sentiment scores functioning as the emotion state per listening event. Further data cleaning was done on the hashtags and tweet language to ensure proper distribution and to keep English only tweets. The transactional database was then generated from the result of the preceding step. </p>

<p align='justify'> From the transactional database, we performed FIM and APM techniques, where we were able to recommend actionable insights such as: <p align='justify'>

<ul> 
	<li> FIM: 
		<ol>
			<li> <p align='justify'> Exploring songs that invoke different emotions and how it translates to brain activity </p> </li>
			<li> <p align='justify'> Exploring how songs can potentially synergize positive emotions and identifying how this synergistic mechanism looks like in MRI / PET scans </p> </li>
			<li> <p align='justify'> Exploring how songs associated with negative emotions affect the brain and different patient demographics </p> </li>
		</ol>
	</li>
	<li> APM:
		<ol>
			<li> <p align='justify'> Verifying the validity of a rule in an experimental manner. </p> </li>
			<li> <p align='justify'> For example, whether making patients listen to a song invoking sad emotions <code> ((ef356d7f3dcb4772dec2e5310ae5c398,) -> 0.375, lift of 368.783984 </code> would really translate to an invoked negative emotion in terms of brain activity. </p> </li>
		</ol>
	</li>
</ul>

<p align='justify'> Overall, we were successful in finding patterns between emotions and songs. With the methodology and findings of this project, the researchers can then replicate, adapt, or tweak the study using their own databases of emotion states and songs. The flexibility offered by the methodology of the project gives the researchers the ability to have guided insights before performing experiments. These can potentially cut down time, cost, and the required effort in performing preliminary studies. In terms of recommendations, future studies can use a larger dataset with more time periods and more songs for better generalizability. The musical characteristics of each song can also be factored in for more interesting insights and rules. </p>

---

**Source code available at [BDCC_MP1](https://github.com/josephazanza/BDCC_MP1)**

---

## [Back to main page](https://josephazanza.github.io/)