# Analysis of Superheroes
### Co-authors : Vinit Nair, Ben Richman 

To view the interactive plots you can check the python notebook at - 
[NB Viewer Jupyter Notebook](http://nbviewer.jupyter.org/github/palakbhatia/Analysis_of_Superheroes/blob/5e6da407993928797967fe7c9aa3d42a105268d7/Notebook/Superheroes_v3.3.ipynb)

## Summary
Superheroes and villains are products of their time - representations of people's hopes and fears. They are reflections of ourselves and the cultural experience at the time, but while representative of the whole, they often miss accurate representations of minorities. 

## Getting Started
In this Github, there is a Python notebook titled Superheroes_v3.3.ipynb with details on the data mining, cleaning and analysis, and the production of the graphs and images. The corresponding datasets are also uploaded as .csv files. 

### Prerequisites/Tech Stack
The following software is required for completing the notebook:
    pandas, seaborn, matplotlib, plotly.
Each package can be installed through pip installation (https://packaging.python.org/tutorials/installing-packages/) or some packages are available to install through package managers built into software like Canopy or Anaconda. 
All packages function best in the latest update of Python 3. 

If you are unfamiliar with working with dataframes, seaborn, plotly or matplotlib, it is recommended to refresh yourself on those packages before moving forward.

### Background
With Marvel and DC's recent return to movie spotlight, claiming 4 of the top 10 highest grossing movies spots, it seemed a good idea to remind ourselves of the cultural and historical origins of the characters, and where the industry is headed. The datasets used encompass superheroes/villains and their first appearances, demographics, and powers, as well as a note on the relative grossing of the Marvel and DC movie universes. It is also important to note most of the data is centered around United States produced comics and superheroes. 

### Superheroes and Their Origins Timeline
To visualize the relationships between historical events and the superheroes that represent shifts in cultural paradigms, we plotted significant historical events and the first appearances of prominent superheroes to display the relationship. To enable interactivity, we used Plotly so that hovering over the superhero logo would provide information on the specific first appearance year. 

![alt text][logo]

[logo]: https://github.com/palakbhatia/Analysis_of_Superheroes/blob/master/Plots/Birth%20of%20Superhero_%20A%20Timeline.png "Birth of Superheroes: A Timeline"
Captain America is a product of WW2, a military symbol of all cultural calls of the time - that America act against Nazism, fascism, and communism, with the utmost leadership, strength, and honor. 

The Cold War brought renewed interest in science and nuclear energy. Prominent scientist-heroes emerged, such as the Flash, the Hulk and Iron Man. Each character's alter ego romanticized science as America started valuing scientists as cultural and political figures. 

These lasting superheroes are deep characters whose origins reflect the will of the common person, serving as a source of hope, an outlet for anger, and sometimes a thinly veiled threat. 

### Alignment by Gender

![alt text][logo1]

[logo1]: https://github.com/palakbhatia/Analysis_of_Superheroes/blob/master/Plots/Character%20Alignment%20By%20Gender.png "Character Alignment by Gender"

Using Marvel Comics to dive into character alignment by gender, male characters dominate the overall number of comic book characters. More interesting though, is that the distribution of alignment (good, bad, or neutral) is different for male characters than for other genders. Male characters are above-and-beyond bad, with around half as many good characters as bad, and around one quarter as many neutral as bad. 

Switching to other genders, the good and bad characters are approximately equal, and neutral is around half as many as either. It may be that the prominence of bad male characters shows a self-awareness that males in America are more likely to commit violent crimes, or perhaps a dangerous grandeur that the type of power a bad character requires could only be gained by a male in American society. 

![alt text][logo2]

[logo2]: https://github.com/palakbhatia/Analysis_of_Superheroes/blob/master/Plots/Increading%20Diversity%20Among%20Bad%20Characters.png "Increasing Diversity Among Bad Characters"

To see if the representation of male-other changes over time, we plotted the gender ratio of new characters in each decade. An increasing trend in 'other genders' becomes apparent starting in the '60s. The 1960s witnessed a renewed fight for women's equality that partnered with the Civil Rights Movement. Though while there is a smaller proportion of male characters in the modern times, it is still far from a 50-50 representation and appears to be slowing at around a 75-25 male-other gender ratio.

### Representation of Sexuality

![alt text][logo3]

[logo3]: https://github.com/palakbhatia/Analysis_of_Superheroes/blob/master/Plots/Representation%20of%20Sexual%20Minorities.jpg "Representation of Sexual Minorities"

Sexuality may be the conversation at the forefront of the representation debate, and the representation of sexual orientation in comics does not show a balanced representation. Even looking at characters created after 2000, the representation is around 99% straight which is not indicative of the times. (https://www.psychologytoday.com/us/blog/sex-sexuality-and-romance/201607/how-many-straight-people-are-there).

### Settling Marvel vs DC: Movie Success

![alt text][logo5]

[logo5]: https://github.com/palakbhatia/Analysis_of_Superheroes/blob/master/Plots/Marvel%20vs%20DC%20Top%20Grossing%20Movies.png "Marvel vs DC Top Grossing Movies"

While many comic fans have a deep personal preference for one comic universe or the other, there is no debate about which has been more successful in the box office. Marvel is far more successful, with the 5th highest earning Marvel movie out grossing the most successful DC movie. 

### Appendix
#### Additional Origins Timeline Insights
Following the Great Depression, which is the greatest national financial disaster to date in the United States, Superman and Batman were created. Superman represented an outside view of the best parts of rural America - an alien that grew up with the rural American values of honesty and hard work, choosing to stand up for his 'adopted' family (both the Kents themselves and the American people) and protect the weak and vulnerable. This was a hero that grew up in the area most affected by the Great Depression and would fight for their cause. 

As a parallel, Batman was one of the wealthy elite that would have been a part of causing the Great Depression. However, he chose to fight against the corruption he would otherwise benefit from. This represents the hope the common person would have that one with power would stand up with them. It also served as a warning that fighting for their cause might not be done 'in the light,' but could be part of a dangerous vigilante movement.

After the Civil Rights Act of 1964 was signed, there was more dialogue on the place of race, leading to prominent African American hero Luke Cage, and the African hero Black Panther. While Luke Cage was written with honor, he also may have been written with some stereotypes in mind. Diverging from recent scientific heroes, Luke is a large, intimidating character who solved issues with brawn rather than brain. 

Black Panther, however, was modeled after more positive views of the Black Panther political party. A true African, he represented the strength of the party, the connections the Black Panthers wanted with their African heritage, as well as the sophistication and rich heritage the party believed may exist in Africa had they not faced devastating oppression under slavery and colonialism. 

And the last historical event we viewed was the Vietnam War - a deeply contentious war that drove many to confront the disillusion that America was always right in its fights. Born of this confliction, the Punisher was a war hero returned home, whose family was killed by a corrupted country he barely recognized. He chose to seek retribution and cleanse the country with the very thing it had endlessly romanticized - bullets, war, death.
