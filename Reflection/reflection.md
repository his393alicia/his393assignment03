# Reflection

This exercise relies on Wikipedia to turn a simple text table into "linked data". In the following exercies, you'll be asked to think about where this model can and cannot be replicated. You will probably want to use markdown source blocks and tables in some of your ansers.  You can create a table with vertical pipes:

```markdown
Header 1 | Header 2
---------+---------
Content cell 1 | Content Cell 2
Content Row 2 | Content Row 2
```

The block above uses fenced code blocks to show the table syntax; you might use code blocks for other purposes in this reflection, as well. 

## Question 1 (150 words)
#### Our underlying dataset was a list of political leaders. Describe another possible dataset which could use Wikipedia in the same way. Give an example of a possible Javascript object description of one record in the dataset, using the Javscript objects from Parts 1 and 3 as a starting point.

Another data set that could use Wikipedia similarly are information about dog breeds. Headings and information could include a breed's geographic origins, their original purpose, size, height, temperament and more. One example is the Samoyed breed https://en.wikipedia.org/wiki/Samoyed_dog: 
let samoyed = {
    breed: 'Samoyed'
    other names: 'Bjelkier, Samoiedskaya, Sobaka'
    common nicknames: 'Smiley, Sammy'
    geographic origin: 'Northwest Russia & Siberia'
    temperament: 'Samoyeds' friendly and affable disposition makes them poor guard dogs; an aggressive Samoyed is rare. The breed is characterized by an alert and happy expression which has earned the nicknames "Sammie smile" and "smiley dog." With their tendency to bark, however, they can be diligent watch dogs, barking whenever something approaches their territory. Samoyeds are excellent companions, especially for small children or even other dogs, and they remain playful into old age. According to the Samoyed Club of America, when Samoyeds become bored, they may become destructive or start to dig.With their sled dog heritage, a Samoyed is not averse to pulling things, and an untrained Samoyed has no problem pulling its owner on a leash rather than walking alongside.'
    male height: '20-22 inches'
    female height: '18-20 inches'
    male weight '44-66 pounds'
    female weight '35-44 lbs'
    life span '12-13 years'
}
Dog breeds are compatible because their information fits into the same headings (and are generally agreed upon and uncontroversial). For instance, while a Golden Retriever and Samoyed were bred for different purposes, the "Purpose" heading would both still be filled. Furthermore, their differences would be an interesting and contrasting analysis. 

## Question 2 (150 words)
#### Now describe another dataset for which Wikipedia would **not** be as good a resource. What does this tell you about the limitations of Wikipedia? WHat kind of work would you need to do to make useful links for this dataset?

A dataset in which Wikipedia would not be a good resource are the causes of World War I: https://en.wikipedia.org/wiki/Causes_of_World_War_I. This topic is still rather contentious even among historians. The Wikipedia page itself is complicated. Furthermore, distilling the long term (such as the polarization of Europe) and immediate causes of World War I (the assasination of the Archduke) into a tabular format would be convuluted. There isn't a consensus among historians regarding the definitive causes of World War 1. Furthermore, even if there was a consensus, the causes would likely span decades (if not centuries) and continents. The causes would also be different in nature and scope too. For example, fitting the "French distrust of Germany" and July Crisis into the same dataset would be challenging. If someone was going to make a dataset based off the Wikipedia causes of World War 1, it would probably be too difficult to squeeze every thing into a single table. They would probably have to make several ones, such as a dataset about the 1887-1914 polarization of Europe and another one about the July Crisis. These difficulties illustrate that while Wikipedia is undoubtedly useful and has democratized knowledge to an unprecedented degree, there are still limitations. It doesn't necessarily allow for complex and multiple interpretations of events or subjects - particularly controversial ones. Nevertheless, Wikipedia is still useful for quick and casual (albeit simplified) information.

## Question 3 (150 words)
#### Finally, what problems do you see with this tabular format? What are its limitations, and what do they suggest more broadly about the limitations of data-based historical/humanistic inquiry?
The tabular format is not compatible with all types of information and histories – especially only data-based inquiries are used. While they are useful, especially in looking at broader trends and patterns, additional analyses are still important. One example is Google Books' Ngram Viewer. For instance, searching "Samoyed" illustrates peaks in 1860, 1934 and 1997. However, the graph does not and cannot provide societal and cultural context for the potential reasons behind the increases. Additionally, if the topic is contentious and not as widely accepted like a politician's date of birth or a breed's life span, the table risks presenting only one interpretation. 
