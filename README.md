# Study-Group-3-Project

As per every business student's aspiration, we only have one goal in life: becoming rich.
While we believe that LBS provides us with good foundations, we want to look the opportunity to network and talk with the real deal; actaul billionaires.
That's why we want to address the issue of how to find a billionaire and what to talk about in our netowrking session.

This project was composed of three datasets that are noted below that were merged into one main dataset that our analysis derived from. The code from this merging can be found in the Billionaires_merged.ipynb. We began by focusing on explanitory data analysis to better understand the data and clean the dataset. Following this we decided to focus on the following factors: Industry, Demographics, Self-Made, Education, and Geography. Vizualizations for these categories were built out through Python, Tableau and ThinkCell within our final posterboard.

For Industry we found the most compelling data that stood out was the count of billionaires within each industry. We found that the Finance industry has the highest count of billionaires. This was found by building out bar charts in Tableau to get a vizualization of the breakdown. Diving deeper into this data we were also able to discover that the richest billionaires within this industry all owned investment managment firms such as Berkshire Hathway and Citadel. This data led to our key reccomendation to attend investment managment career events as this would position yourself in the best place to bump into the highest count of billionaires.

For Demographics the most interesting stat that popped out was that 550 billionaires were born in January. This is almsot triple the amount of billionaires born in any other month. We continued to dive deep into other demographic stats looking at the breakdown between men and women, the amount of billionaires that are married, the number that have families with children. We highlighted in our final poster these key stats as they give way to a better understanding of these billionaires which is vital to know. Knowing that a majoirty of billionaires are men with families allows you to prepare in a tactical way how to approach the networking conversation.

This level of analysis was done across the remaing three factors of Self-Made, Education, and Geography. The key reccomendation for Self-Made was to show self-drive as most billionaires are self-made. For Education we reccomended not bringing up studnet's LBS master's degrees as most of the world's billionaires are dropouts and thus have no connections to the degrees. Finally, for Geography the key reccomendation was to go to Monaco as we dsicovered the highest density of billionaires live here.

Having this better understanding of billionaires, we now know how to effectively position ourselves in the right enviroment to meet a billionaire and what to say to them when we do get the chance to network. Now that we know how to network with a billionaire, the next part of the project was running a regression to detail what factors are the most important to billionaire wealth so that we can now look to become a billionaire ourselves. The code for this regression can be found in Regression_vFinal.ipynb. We fit a Ridge regression (RidgeCV, 5-fold CV, alpha=3,455) to predict billionaire wealth (n=2,644) using 153 features derived from geographic, industry, demographic, wealth source, and education variables. The model achieved R²=0.078 with feature importance showing Geography (28%), Industry (22%), and Demographics (21%) as top contributors. French citizenship, Fashion & Retail industry, and founder status showed strongest positive effects, while formal education had minimal impact. The low explanatory power indicates 92% of wealth variance stems from idiosyncratic factors beyond observable characteristics.

Finally we built out an interactive dashboard using streamlit that is a billionaire hunting cheat sheet, showing where the richest people cluster by country and industry. It highlights the biggest contributors so you know exactly where to focus your networking efforts.




**Data**

1. Billionaires Statistics Dataset (2023) (https://www.kaggle.com/datasets/nelgiriyewithana/billionaires-statistics-dataset/data)

Dataset was collected from Kaggle, through toolbox.google.com.

This dataset contains statistics on the world's billionaires, including information about their businesses, industries, and personal details. It provides insights into the wealth distribution, business sectors, and demographics of billionaires worldwide.

2. Billionaires CSV (https://corgis-edu.github.io/corgis/csv/billionaires/)

Dataset was collected from CORGIS DATASET PROJECT on Github

Researchers have compiled a multi-decade database of the super-rich. Building off the Forbes World’s Billionaires lists from 1996-2014, scholars at Peterson Institute for International Economics have added a couple dozen more variables about each billionaire - including whether they were self-made or inherited their wealth. 

3. Billionaires Listed in Forbes (https://www.kaggle.com/datasets/sujalluhar/billionaires-listed-in-forbes)
   
Dataset was collected from Kaggle, through toolbox.google.com.

What factors are affecting wealth? and in the answer to that, identify valuable opportunities for underdeveloped or developing countries. By examining the data, we can uncover insights that help nations make informed decisions on how to increase their wealth and well-being.

This dataset aims to provide actionable insights for policymakers, entrepreneurs, and anyone looking to contribute to economic growth and well-being on a global scale.

