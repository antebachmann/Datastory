## Abstract

Two subjects are consistently banned at family gatherings, politics and religion. This is because ~~everyone else is wrong~~ many of us feel very strongly about those matters, generally because we are directly affected or have a lot of self-esteem riding on "being right".

As with anything so widely cared about, we generate an almost endless amount of political discourse, and everyone, no matter their qualifications, wants to express themselves. There is so much political discourse that we can often hear people commenting on the discourse itself rather than the politics it conveys, this is what we want to study here.


**How emotionally do we express our politics, and is it affected by our proximity to them?** Is the question we aim to answer.

## Methods

In our data story we focus on **how groups of people feel about certain issues**.

To test our hypothesis we use the [quotebank](https://dlab.epfl.ch/people/west/pub/Vaucher-Spitz-Catasta-West_WSDM-21.pdf) dataset, which we filter by issue, then we run sentiment analysis on every issue, keeping years separate, finally we use [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) to associate a person with each quote.

_In fine_, this allows us to observe sentiments by month, issue, country, gender, and religion. Then we can observe whether the tone of discourse evolves over time, if specific groups have different attitudes, and what is the overall mood of one issue compared to another.

We selected four highly controversial topics in the english-speaking world:

# Abortion

# Climate change

# Gender equality

# Gun control

## The tone of discourse

Looking at the distributions of the compound scores for the different four topics, we see that humans tend to not sit on the fence. They have strong opinions and are generally firm in their beliefs. On average across the four topics, only 16.4 % of the quotes are classified as neutral quotes. These quotes could have easily been facts stated by a journalist or an expert when discussing the topic. For example, in the following quote we have Peter Atkins a chemist stating that: 'Temperatures go up every year, so we got to try and mitigate that.' He is clearly stating a fact based on observations made by scientists. He is not defending the existence of climate change in this quote and is not using extremely emotive words. 

If we look more closely at each topic, we can study how people speak about their opinions. A negative score is attributed when a quote includes words with negative conotations, as opposed to a positive score. We observe that for certain topics people tend to use more words with more negative connotation as in gun control, while more positive sentiments are expressed while talking about global warming or abortion. As for gender inequality, it seems to be relatively close. 

We next study the sentiments of the issues over time. We look at how strongly people's opinions are over the months and years. Clearly during certain months there is more passionate talk about an issue. This could be caused by some event. For instance, after mass shootings occur, more people are likely to talk about gun control in a nonchalant manner. On the 12th of June 2016, a mass shooting occurred in Orlando Florida. This clearly sparked the conversation about gun control. 

When looking at the different attributes versus the topics, we first see that different groups tend to be more interested in different topics. For instance, gun control is a huge topic in the US as opposed to Germany. While global warming is more talked about in Hindu communities versus atheists. 


## What's the matter ?


## Ugly markdown example

You can use the [editor on GitHub](https://github.com/antebachmann/datastory/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/antebachmann/datastory/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
