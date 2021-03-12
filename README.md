# :deciduous_tree: nyc-trees :deciduous_tree:

> ## Documents Information ###
> * README.md file
> * .csv file
> * Source code file


## :blossom: Project Mission :blossom:

The Department of Environmental Conservation, from New York city, has recently made the news by telling the people that they needed their help. Indeed, their request is simple: They needed the people of New York city, whether young or old, to go to the nearest tree in their street and gather information about that tree. **This is all in an effort to make the population aware that nature is important**, even in big Metropolis like NYC. Now that they have heard back from the people, the DEC noticed that they missed a crucial step. They forgot to give the people a data collection guide, and so the data they received back is a bit messy.

:seedling: **Can you help them clean the data so that they can begin to raise awareness to ecological issues, such as climate change ?** :seedling:

![NYC Picture (Image)](https://www.hudsonallergy.com/wp-content/uploads/2016/04/nyc-street-trees.jpg)


## :blossom: Dataset Information :blossom:

### :leaves: Data as it is 

There is 42 columns and 100,000 to start

### :leaves: Data Interpretation 

What does each columns means?

After this ask ourselves for what kind of prediction or model it could be interesting.

Explain here this **Why**.

:collision: First columns to be removed :

* 'tree_id' : /100,000 unique values/ , it is meaningless.

* 'borocode' : /5 unique values/ --> 1,2,3,4,5 integers, it is redundant and we get more meaning out of 'boroname'column

* 'state' : /1 unique value/ --> 'State of New York' , it is meaning less

* 'x_sp' and 'y_sp' : we already have the 'latitude' and 'longitude' column

* 'created_at' : Not meaningful information

:collision: column to be merged :

* 'status' with 'stump_diam' : 


## :blossom: Work-flow : Dataset Cleaning Steps  :blossom:


## :blossom: State of the project :blossom:
