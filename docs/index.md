![](assets/img/naassom-azevedo-Q_Sei-TqSlc-unsplash-min.jpg)
<span>Photo by <a href="https://unsplash.com/@naassomz1?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Naassom Azevedo</a> on <a href="https://unsplash.com/s/photos/students?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

## Who Does Well on ENEM?<a name="introduction"></a>

For this project I'm using a random sample of the 2019 ENEM data (Brazil's SAT like exam) to answer some questions regarding brazilian high school students.

Here's what I've got so far:

> ### Brazilian white students have higher average scores than brown students.

![](assets/img/white_brown_scores.png)

On average, there is a score gap between white and brown brazilian ENEM students in favor of the first. It does not mean that every white student had a higher score than the brown students. But it does mean that if we take a random group of ENEM students the average score for the white will be higher than for the brown.

> ### There are more white students with higher family income than brown students.

The proportion of brazilian students with a family monthly income of more than two minimum wages is higher for those declared as white than for brown skin. This should be no surprise if you're aware of social inequalities in Brazil.

But what about brown and black students? Are these differences also shown? Well, turns out that the answer is no!

> ### Brazilian brown students don't have higher average scores than black students

![](assets/img/brown_black_scores.png)

On average, there is no statistically significant difference between the score of brown and black brazilian ENEM students. 

> ### There are no more brown students with higher family income than black students.

On average, there is no statistically significant difference between the proportion of brazilian students with a family monthly income of more than two minimum wages for those self declared as brown or black.

> ### Brazilian students who pick "english" as their prefered foreing language have higher language average scores than those who pick "spanish".

![](assets/img/english_spanish_scores.png)

As the previous findings, this one could also be explained by social inequalities: since spanish have some similarities with portuguese, students who can't afford a private english course tend to pick it as their prefered foreign language.

> ### Brazilian female students have higher essay average scores than male students.

![](assets/img/male_female_scores.png)

This one is quite interesting (at least for me). On average, female students outscored male on the essay exam on ENEM 2019.

### Learn more

The above conclusions were reached by hypothesis testing, using both bootstrap and two sample t-test. If you want to know more about the technical aspects of this study, check the [github repo](https://github.com/thiagofuruchima/enem_ds).
