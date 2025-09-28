Task
Note: Don’t reformat with excel or open office. Use the "pandas.read_excel" function to load the data. 
You will need to use the sheetname properly to select the sheets we need (FAH for each time).  
You will extract the data you need from the loaded dataframes and create new data frames with just the information you need, and the proper headers.

Lets concentrate on Men and Women and the at home consumption of a few kinds
of fruit and dairy products to see if there are any trends. 
Make 4 line plots using python:
Fruit types over time (Men)
Fruit types over time (Women)
Dairy products over time (Men)
Dairy products over time (Women)

The fruit types you should consider will be 
"Apples as fruit", 
"Bananas", 
"Berries",
"Grapes", 
"Melons", 
"Oranges, Total", 
"Other citrus fruit", 
"Stone fruit", 
"Tropical fruit". 

For dairy products you should look at 
"Fluid milk total", 
"Butter", 
"Cheese",
"Yogurt", 
"Dairy, Other". 

Requirement:
Each product should have a line with its own color, line style. 
The graphs should have each axis labeled with the variable measured and units.
There should be a legend to understand which product is which line. 
The data source and source url should appear below the graph in the image. This should be part of the same ipython notebook with the code extracting the data. 
We are going to just use mean pounds here, which, for Men, appears in the 7th column, after the 77th row. You will figure the details out through inspecting the sheets in a spreadsheet program and checking that you get the same numbers in the ipython notebook.
Below each plot image, use a markdown cell to write a caption. The caption should quickly summarize what is in the fig (2 sentences). Those summaries should fill in some details in the attributes not obvious from reading the titles, legends and axis. You might get this information from the report summary. Each caption should say something interesting thing we conclude from the figure. Like "in the figure we see an increase in the consumption of rabbit eyeballs", or "the overall consumption of bird droppings remained flat but rained higher than red grapes." Just to be clear, do not use these quotes as captions. The analysis should be your own.
