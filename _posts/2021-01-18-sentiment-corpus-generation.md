---
layout: post
title: Sentiment Corpus Generation in Low Resource Language A bumpy Journey
date: 2021-01-18
description: Development of sentiment corpus for Nigerian languages
tags: corpus
categories: sample-post
thumbnail: assets/img/9.jpg
featured: false
---


## Introduction

Sentiment analysis (SA) is one of the most trending research areas in Artificial Intelligence (AI). Sentiment analysis is a technique used to identify the sentiments contained in natural language, which is mostly shared on social media platforms. A lot has been achieved in sentiment analysis research, focusing mostly on Rich-Resource Languages like English, German, and Arabic. However, there is little research on many Low Resources Languages. Consequently, we embarked on a mission to promote research on SA in languages spoken in Nigeria, which are all low resources languages. Our research was found worthy by Lacuna Fund, and they supported our team to develop sentiment corpus, sentiment lexicon, and hate speech lexicon for Hausa, Yoruba, and Igbo languages. These are important resources required in sentiment analysis in any language. The project is ongoing, notwithstanding, this article summarizes some of the challenges we faced in the study.


## Data Acquisition

In sentiment analysis, extracting data is very crucial and is often considered as one of the least challenging stage. This is because there are several tools, packages, and libraries to extract and preprocess the data from social media platforms like Twitter and Facebook. However, that’s not the case in many low resource languages.
The first challenge we faced in data extraction is, Twitter does not have language codes for Hausa, Yoruba, and Igbo and so,[d] extraction tweets in these languages based on language code is impossible. Again, the location code can also not be used because multiple languages are used all over the country. Consequently, we had to crawl the tweets using distant supervision and via the use of stop words. The stop word list is also not available in the languages, we had to devise a methodology, and generated stop words for the languages.
Despite all the above, a lot of preprocessing was done to filter out tweets that are not in the target languages. In conclusion, data extraction in low resource languages is possible despite insufficiency of standard methods for the extraction. Each language is unique and appropriate methods should be devised to fit the purpose.    

## Annotation Tools


Annotating text means adding meta-data to text, like semantics or sentiments. A good way for the AI to learn and understand nuances is through human annotations. Annotation is used to create datasets for natural language processing. The texts are either annotated or labeled with the purpose to mak the keywords or important words comprehensible to machines, and helping them to respond in the same way. We can either annotate an entire body of text into a class, called classification or annotate a specific word (s) called tagging.
Text annotation can easily be done in spreadsheet software like MS Excel; however, the process becomes tedious when the amount of data to annotate is large. Other limitations are spreadsheets are not convenient for multiuser annotation or calculating Inter Annotator Agreement (IAA). Consequently, it is more efficient to use specialized tools for the text annotation. However, most of the tools available (both free and paid) are in the development stage with obvious bugs. We tried over five tools and all of them have one problem or the other. The tool that we finally settled on comes near to perfection, but the review option is not working, and so the annotation texts cannot be reviewed in the tool.
The challenge of choosing an annotation tool came as a shock to us, because during our preliminary study, we saw a lot of good options but upon using the tools, we found out that most of the developers are over-selling the capabilities of their tools. In conclusion, when choosing an annotation tool, it's good to thoroughly explore the tool and try their functionality early to see if they fit your use-case.
 
## Annotation Guideline and Annotation Training

Annotation is mostly done by multiple annotators, preparable odd numbers, typically three to five in number. Therefore, it is crucial to develop an annotation guideline to aid the annotators. An effective annotation guideline helps annotators to understand clearly what is expected of them and have accurate annotation. In rich resource languages, this stage is fairly straightforward. There are several annotation guidelines available in the literature and research are quite familiar with annotation in the languages. However, because of the peculiarities of each language, the existing annotation guidelines will not serve the purpose. Additionally, due to the insufficiency of researchers working on low resource languages, getting annotators that can accurately annotate texts in low resource languages is quite difficult. Several rounds of training and retraining is required to prepare the annotators and ensure a high inter annotator agreement.

## Conclusion

There are several potentials and benefits to sentiment analysis research in low resource languages. Despite the several challenges, these challenges are opportunities for novel studies.  



