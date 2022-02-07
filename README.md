# IM_Assignment1

https://aliawaleed.github.io/SoftwareArt/Assemblage/index.html

<h1 align="center">Assemblage</h1>

<h2>The Concept</h2>

<p align="justify"> Having the idea to allow people to escape from the ordinary news that we are bombarded with every day, we decided to create our own version of ‘The Daily Kid’, where people can choose the news category that they want to read and have it mixed with the names of characters from their favorite cartoons as children. The user is given the choice to decide on the cartoon before having the news displayed. The idea is to allow users and readers to reminisce about the past and take them back to their childhood while they do the everyday act of reading the news. The goal is to evoke memories and feelings of happiness and youthfulness while they go about reading the news.</p> 

The link to 'The Daily Kid' can be found [here](https://aliawaleed.github.io/SoftwareArt/Assemblage/index.html).

<h2>The Algorithm</h2>

<p align="justify">First, we found three samples of texts, from the internet, for each news category we wanted to cover; sports, celebrities, and politics. We imported several libraries that would allow us to scrape the information off of the websites and requested the links for each. We then used beautiful soup to parse the source code and extract the text from the section of the article that we want. For some websites, there would be some leading information that we did not wish to use and so we removed the text by replacing it with empty quotes. The lines are then split by ‘.’ and placed into an array. This is followed by a for loop that combines the first five lines of the three texts, of the same category, and stores them in a new string. We then created arrays consisting of the names of cartoon characters for five different cartoons. The code then goes through the newly created string and replaces the names of people and some places with the names of cartoon characters from the users’ chosen category and cartoon. With that, the algorithm combining the texts and replacing the names is complete and the code is concluded by an if-else statement that prints the output for the chosen news segment and cartoon.</p> 

The code can be found [here](https://colab.research.google.com/drive/10cxXTuh4eaB0RbM2YLhGDCy4PX-hQNW7?usp=sharing).

<p align="justify">With a sample output for each of the 15 combinations, we then created a webpage to display and print our results. Our first/main page contains 3 images, one for each of our news categories. When chosen and clicked on, each category has its own cartoon menu, although they look the same. The users are given the choice between Mickey Mouse, Phineas and Ferb, The Powerpuff Girls, The Simpsons, and Spongebob Squarepants. Finally, when the user clicks on their desired cartoon, we display the respective output. We used JavaScript to display the outputs based on the user’s choice and to hide the cartoon menu.</p>

<h2>Computer Algorithm vs. Human Writing</h2>

<p align="justify">Nowadays, when actual journalists or people are writing and sharing news, they are responsible for providing readers with actual daily news of what’s happening, regardless of the topic. However, a person would not incorporate diverse news from the same category in one text, under one title. If that ever occurs, a responsible journalist or a person writing for such a purpose would not possibly think of incorporating cartoon characters in their articles as it would make no sense at all. However, we felt that while being surrounded with dark news, an adult would enjoy a little and quick algorithmic escape when reading about how Mickey Mouse won a tennis match for instance. This could only be found in a kid’s magazine and sometimes we all need to evoke our inner child.</p>



