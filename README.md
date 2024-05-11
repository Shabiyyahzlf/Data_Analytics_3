# DATA VISUALIZATION
Data visualization is the representation of data through the use of common graphics, such as charts, plots, infographics, and even animations. These visual displays of information communicate complex data relationships and data-driven insights in a way that is easy to understand.
## Basic Visualization
1. **Bar Chart Vertical**
   Compare among categories, few categories. Can be used over time
2. **Bar Chart Horizontal**
   Has a long item label. Compare among categories. Used for many categories
3. **Line Chart**
   Compare over time, one category
4. **Stacked Bar Chart**
   Show components in a category, that can be used over time(a few periods). Relative and absolute differences matter.
5. **Stacked 100% Bar Chart**
   Show components in a category. Composition in percentage, focus contribution on each component. Can be used over time (a few periods) and only relative differences matter.
6. **Pie Chart**
   Static Composition, Useful for less than 5 categories. A simple share of the total
7.**TreeMap**
   Static Composition, accumulation to total. Absolute difference matters

## Data Visualization Using Python
Python offers several plotting libraries, namely Matplotlib, Seaborn, and many other such data visualization packages with different features for creating informative, customized, and appealing plots to present data most simply and effectively.
### Matplotlib and Seaborn
Matplotlib and Seaborn are Python libraries that are used for data visualization. They have built-in modules for plotting different graphs. While Matplotlib is used to embed graphs into applications, Seaborn is primarily used for statistical graphs.
But When should we use either of the two? Let's understand this with the help of a comparative analysis. Below is a comparison between Python's two well-known visualization packages Matplotlib and Seaborn.
#### Matplotlib
- It is used for basic graph plotting like line charts, bar graphs, etc.
- It mainly works with datasets and arrays.
- Matlotlib acts productively with data arrays and frames. It regards the access and figures as objects.
- Matlotlib is more customizable and pairs well with Pandas and Numpy for Exploratory Data Analysis.
#### Seaborn
- It is mainly used for statistics visualization and can perform complex visualizations with fewer commands.
- It works with entire datasets.
- Seaborn is considerably more organized and functional than Matlotlib and treats the entire dataset as a solitary unit
- Seaborn has more inbuilt themes and is mainly used for statistical analysis
**Import matplotlib and seaborn**
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/d48d9452-a975-4f3b-a1ae-2413e5be5e77" width="50%">
</div>

### Using Matplotlib
#### Creating Variables and Labels
We are using random data points to represent the yield of grapes. 
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/f003175f-8b87-4aeb-9c64-c23dfd4e0122" width="70%"height="70%">
</div>
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/7ebd5703-985d-42fd-ad7a-993058050302" width="70%">
</div>
To plot multiple datasets on the same graph, just use the plt.plot function once for each dataset. Let's use this to compare the yields of grapes vs kiwis on the same graph. We can add a legend which tells us what each line in our graph means. To understand what we are plotting, we can add a title to our graph.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/8a8f297c-c635-47f9-b6a2-6e4136e76b9d" width="70%">
</div>

### Using Seaborn
An easy way to make your charts look beautiful is to use some default styles from the Seaborn library. These can be applied globally using the sns.set_style function.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/ed1787d5-bc61-4e46-bb7e-0016e9f6dee6" width="50%">
</div>
We still use the same command from the matplotlib previously, but we will see the difference of adding the sns.set_style command.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/102d6c89-1549-459f-abd0-6deb54331505" width="70%">
</div>
We can also use darkgrid option to change the baground color to a darker shade
<div align="center">
  <img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/159063a5-49bf-4908-a968-3939ac5d9c97" width="70%">
</div>

#### Define Years, Grapes, and Kiwis into a New Variables
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/84d46468-24fc-4616-bd31-b209e3005ba3" width="45%">
</div>
Then we will define years, grapes, and kiwis variables in to a new variable
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/d22eeaf5-0492-4cbc-b19b-0a7d5d50d6f1" width="70%">
</div>

Let's see our newly created dataframe below
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/6372247e-7472-41eb-8811-bea0ec0a13e0" width="50%">
</div>
Then we can plot them by using seaborn as below:
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/d4c4f8c1-f949-4499-a66f-71062d2e3361" width="70%">
</div>

## Bar Graph
When you have categorical data, you can represent it with a bar graph. A bar graph plots data with the help of bars, which represent value on the y-axis and
category on the x-axis. Bar graphs use bars with varying heights to show the data which belongs to a specific category.
### Using Matplotlib
#### Bar Chart
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/d103d7e5-3572-4c3c-862b-9ba13fb84d83" width="70%">
</div>

#### Stacked Bar Chart
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/01a8969d-59c0-4590-a6a4-96224efbe7a8" width="70%">
</div>

### Using Seaborn
Let's use the tips dataset in Seaborn next. The dataset consisdt of:
1. Information about the sex (gender)
2. Time of day
3. Total bill
4. Tips given by customers visiting the restaurant for a week

This **Tips Dataset** is a dataset provided by seaborn library, so you can directly load the dataset.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/33a65cab-16c7-4623-a188-be21e9edec07" width="60%">
</div>
NLP stands for Natural Language Processing. It is a branch of artificial intelligence (AI) that focuses on the interaction between computers and humans through natural language. 

- **Model**: This column records the name of the NLP model being evaluated.
- **Year**: Indicates the year in which the model was evaluated.
- **Encoder**: Specifies the type of encoder or architecture used in the model, such as Transformer or LSTM.
- **Task**: States the task or evaluation dataset, such as CoLA (The Corpus of Linguistic Acceptability).
- **Score**: The value or score achieved by the model in that task. This score may represent accuracy, F1-score, or other evaluation metrics, depending on the specific task.

#### Bar Chart
The bar plot visualizes the scores achieved by different Natural Language Processing (NLP) models. This visualization allows for a quick comparison of the performance of different NLP models across the given dataset.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/9f28f061-8f03-4c9e-ac93-b3a1fcba9850" width="70%">
</div>

#### Bar Charts Vertical (pivot)
The bar plot compares the scores achieved by different NLP models across specific years. By visualizing the average scores of each model over time, we can observe the performance trends of these models across different years. This comparison helps us understand how the effectiveness of each NLP model evolves over time, providing insights into advancements or changes in NLP techniques and technologies.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/4cecfdf7-d2c4-40b3-87b1-2107be4990a9" width="70%">
</div>

#### Bar Charts Horizontal (pivot)
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/fdda160e-edaa-45fd-ad3d-4d2786cd6d80" width="70%">
</div>

### Using Matplotlib
we are going to plot a histogram from the 'Passengers' column
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/142e09ea-e0cd-4b6b-a141-3c16d34b2c2d" width="70%">
</div>
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/b118efb9-4a22-43db-9a37-7d03606f38b6" width="70%">
</div>
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/5ad15c8e-9455-4ad4-ba42-9ef0171841d6" width="70%">
</div>
we can control the number or size of bins too
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/49f4509a-4fe6-48eb-80b7-91d49c2282db" width="70%">
</div>
we can change the number and size of bins using numpy too
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_3/assets/89763971/a945c499-56c5-40d0-8317-76e7a9da28f3" width="70%">
</div>

# Crisp DM
The Cross-Industry Standard Process for Data Mining, or CRISP-DM, is one of the data mining process models.

**1. Business Understanding** – What does the business need?

**2. Data Understanding** – What data do we have/need? Is it clean?

**3. Data preparation** – How do we organize the data for modeling?

**4. Modeling** – What modeling techniques should we apply?

**5. Evaluation** – Which model best meets the business objectives?

**6. Deployment** – How do stakeholders access the results?
