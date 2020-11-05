# Year 01 Week 01

## L 1.1 Introduction and types of Data - Basic definitions

### What is Statistics?  

  - **Definition**:* Statistics is the art of learning from data*. It is concerned with the collection of data, their subsequent description, and their analysis,  which often leads to the **drawing of conclusions**. 

 ### Major branches of statistics

1. **Description**  

  **Definition**: The part of statistics concerned with the **description** and **summarization** of data is called *descriptive statistics*.  

   > Descriptive statistics can be performed either on a sample or a population.

2. **Inference **

   **Definition**: The part of statistics concerned with the **drawing of conclusions** from data is called inferential statistics.  
   
   > To be able to conclude the data, we must take  into account the **<u>possibility of chance</u>**- introduction to  *probability*

- Examples

  - Suppose we are interested in knowing  
    - The percentage of  all students in India who have passed their  Class 12 exams and study engineering.  
    - The prices of all houses in Tamil Nadu.  
    - The total sales of all cars in India in the year 2019. 
    - The age distribution of people who visit a city Mall in a  particular month.  

### Population and Sample

- The total collection of all the elements that we are interested in is called a **population**.
- A subgroup of the population that will be studied in detail is called a **sample**. 

> Population is the entire group, while sample is a subset of the population which is used to describe the parameters of the population

### Purpose of Statistical analysis

- If the purpose of the analysis is to examine and explore information for its own intrinsic interest only, the study is **descriptive**.

> - general information directly obtained from the dataset given.
> - A descriptive study may be performed either on a sample or on a population.  

- If the information is obtained from a sample of a population and the purpose of the study is to use that information to conclude the population, the study is **inferential**. 

> - When an inference is made about the population, based on information obtained from the sample, does the study become inferential.  

## L 1.2 Introduction and types of Data - Understanding data

- **Data** is information that is all around us, whether we are formally doing statistical analysis or not; all of us are either creating data or contributing towards the collection of data or we are collecting data ourselves.

### What is data?

- To learn something, we need to collect data. 

  **Definition**

  - Data are the facts and figures collected, analysed, and summarized for presentation and interpretation. 

    > Statistics relies on data, information that is around us.

### Why do we collect data?

- Interested knowing in the characteristics of some group or groups of people, places, things, or events. 
  - Example: TO know about temperatures in a particular month in Chennai, India. 
  - Example: TO know about the marks obtained by students in their Class 12. 
- To know how many people like a new song/product/video- collected through comments. 

### Data Collection

- **Data available**: published data. eg, data.gov.in
- **Data not available**: need to collect, generate data.

> We assume data is available and our objective is to do a statistical analysis of available data.

### Unstructured and structured data

- For the information in a database to be useful, we must know the context of the numbers and text it holds.
- When they are scattered about with no structure, the information is of very little use.
- <u>Hence, we need to organize data</u>

### Dataset 

- A structured collection of data.
- it  is a collection of values-could be numbers, names, roll numbers.
- https://docs.google.com/spreadsheets/d/15nJvZ-xBZDGb0oii-NCvSIY4fETotXcJdm5pV1Fq2aI/edit?usp=sharing  
- https://docs.google.com/spreadsheets/d/1qZWmXsIpFx10srpFcmj9DPA961UMbTXkCiUr_SxBYq4/edit?usp=sharing  
- https://docs.google.com/spreadsheets/d/1lrmhe-E0A2LWpTB9cBK9dm-sL2SPVXYZl0MJHI6vqhM/edit?usp=sharing  

### Variables and case

| Names | fees paid | Marks |
| ----- | --------- | ----- |
| A     | 12        | 75    |
| B     | 12        | 90    |
| C     | 12        | 80    |
| d     | 12        | 68    |

- **Case** ( observation): A unit from which data are collected 

- **Variable**: 
- **Intuitive**: A variable is that "varies" 
  - **Formally**: A characteristic or attribute that varies across all  units.  
  
- In our school data set: 

  - **Case**: each student 
  - **Variable**: Name. marks obtained. Board etc. 


> Non availability on data does not mean 0.

- Rows represent cases: for each case. same attribute is recorded 

- Columns represent variables: For each variables. same type Of value for each case is recorded. 

  > We have organised data in a spreadsheet into a table
  >
  > - Each variable must have its own column
  > - Each observation must have its own row.

> - *<u>**For each variable the same type of value for each case is recorded.**</u>*
> - *<u>**But, not for each case the same type of value for each variable is recorded.**</u>*

### Question

>Q1. Which of the following is(are) example(s) of unstructured data?
>
>-  Web pages
>- Video files
>- Reports
>- Image files
>- Phone number
>- Email address
>
>**Ans**:
>
>> Web pages
>>
>> Video files
>>
>> Image files
>
>Q2. The values of temperature and relative humidity of a room are measured for 24 hours, starting at 9 AM, at time interval of 30 minutes [Table 1.2.1]. What are the case(s) and variable(s) for this data?
>
>![](D:..\images\yable.png)
>
>- Temperature is the case; relative humidity and time are the variables
>- Temperature is the case; relative humidity is the variable
>- Time is the case; temperature and relative humidity are the variables
>- Relative humidity is the case; temperature is the variable
>- 9 AM, 9:30 AM, 10 AM are cases; time, temperature, and relative humidity are variables.
>
>**Ans**:
>
>> 9 AM, 9:30 AM, 10 AM are cases; time, temperature, and relative humidity are variables.

## L 1.3 Introduction and Types of Data - Classification of data

### Categorical and numerical

```mermaid
graph TD
    A[data] --> B[categorical]
    A --> D[Numerical]
    B--> E[Nominal]
    B--> F[Ordinal]
    D--> G[Continous]
    D--> H[Discrete]

```

#### Categorical data

> - Also called qualitive variables 
> - It identifies group membership 
> - Eg Gender, School Board, Blood Group, Role, Jersey no. day and date, qualification of a candidate sitting for a job.

**Categorical variable**s: Variables which should not be treated like numbers (as in mathematics), and whose values come from a list of possibilities. 

- **Nominal variable:** A categorical variable where the categories do not have a natural ordering (e.g. gender, ethnicity, country). 
- **Ordinal variable**: A categorical variable where the categories have a natural ordering (e.g. age group, income level, educational status).

> ##### **Nominal Variable Classification Based on Numeric Property**
>
> Nominal variables are sometimes numeric but do not possess numerical characteristics. Some of thee numeric nominal variables are; **phone numbers, student numbers,** etc.
>
> Therefore, a nominal variable can be classified as either numeric or not.
>
> ##### **Characteristics of Nominal Variable****
>
> - The responses to a nominal variable can be divided into two or more categories. For example, gender is a nominal variable that can take responses male/female, which are the categories the nominal variable is divided into.
> - A nominal variable is qualitative, which means numbers are used here only to categorize or identify objects. For example, the number at the back of a player's jersey is used to identify the position he/she is playing.
> - They can also take quantitative values. However, these quantitative values do not have numeric properties. That is, arithmetic operations cannot be performed on them.

#### Numerical data

> - Also called quantitative variables 
> - Describe the numerical properties of case
> - Measurable quantity
> - Eg Marks, height, weight,Highest score.

**Numerical variables**: Numbers which should be treated as they usually are in mathematics. 

- **For example**, age and weight would be considered numerical variables, while phone number and ZIP code would not be considered numerical variables. There are 2 types of numerical variables: 
  - **Continuous variable**: A numerical variable that can take values on a continuous scale (e.g. age, weight). 
  - **Discrete** **variable**: A numerical variable that only takes on whole numbers (e.g. number of visits).

> Q. What kind of variable is latitude?
>
> a: Numerical, Continuous
>
> r:  Continuous numerical data take any value within an allowable range, whereby the range can be finite or infinite. Even though <u>Latitudes are in a finite range, they can have any value, with any level of specificity (or decimal places). So, latitudes, should be Continuous Numerical data.</u>
>
> Q. Number of days a group of students take to finish a school project is a:
>
> a: Quantitative and Discrete variable
>
> r:  For a particular group of students its a finite accurate value.
>
> Q. Suppose one is interested in calculating the weight of a bag (in kg) before leaving for the airport. What kind of variable is the weight of the bag?
>
> a: Quantitative and continuous
>
> r:

#### Measurement units

- Scale that defines the meaning of numerical data, such as weights measured in kilograms. prices in rupees, heights in centimetres. etc. 
  - The data that make up a numerical variable in a data table must share a common unit. 

### Cross- sectional and time-series data

- **Time series**- data  recorded over time
- **Timeplot** - graph of a time series showing values in chronological order
- **Cross-sectional **- data observed at the same time

## Introduction and types of Data - Scales of measurement

### Scales of measurements

- Data collection requires one of the scales of measurement: nominal ordinal, interval, or ratio.

#### Nominal scale of measurement

- When the data for a variable consists of **labels or names** used to identify the characteristics of an observation, the scale of measurement is considered  a **nominal** scale.
  - **Eg**: Name, Board, Gender, Blood group etc.
- Sometimes nominal variables might be numerically coded
  - **Eg** : We might code Men as 1 and Women as 2. Or Code Men as 3 and Women as 1. Both codes are valid.

- There is no ordering in variable.

> Nominal: name categories without implying order

#### Ordinal Scale of Measurement

- Data exhibits properties of nominal data and the **order or rank**
  of data is meaningful, the scale of measurement is considered
  a **ordinal** scale.  
- Each customer who visits a restaurant provides a service
  rating of excellent, good, or poor.  
  - The data obtained are the labels|excellent, good, or
    poor|the data have the properties of nominal data.  
  - In addition, the data can be ranked, or ordered, with respect to
    the service quality  

> Ordinal { name categories that can be ordered  

#### Interval scale of measurement  

- If the data have all the properties of ordinal data and the
  interval between values is expressed in terms of a fixed unit of
  measure, then the scale of measurement is **interval** scale.  
- Interval data are always numeric. Can find out difference
  between any two values.  
- Ratios of values have no meaning here because the value of
  zero is arbitrary  

> Interval: Numerical values that can be added/subtracted (no absolute zero)  

- Example: **temperature**

  - Suppose the response to a question on how hot the
    comfortable and uncomfortable, then the temperature
    variable is nominal.
  - Suppose the answer to measuring the temperature of a liquid is cold, warm, hot - the variable is ordinal.
  - Example: Consider a AC room where temperature is
    20°C and the temperature outside the room is 40°C.
    correct to say that the difference in temperature is 20
    is incorrect to say that the outdoors is twice as hot as indoors.
  - Temperature in degrees Fahrenheit or degrees centigrade
    interval variable. No absolute zero.

  | Celsius        | Fahrenheit |      |
  | -------------- | ---------- | ---- |
  | Freezing point | 0          | 32   |
  |Boiling Point|100|212|

#### Ratio scale of measurement  

- If the data have all the properties of interval data and the
  ratio of two values is meaningful, then the scale of
  measurement is **ratio** scale.  
- Example: height, weight, age, marks, etc  

> Ratio: numerical values that can be added, subtracted,  multiplied or divided (makes ratio comparisons possible)  

#### Summery

![](D:..\images\summery.png)

# Year 01 Week 02

## Describing Categorical Data- Single Variable  

### Frequency distributions  

- **Definition**: A **frequency** **distribution** of qualitative data is a listing of the distinct values and their frequencies.

  > Each row of a frequency table lists a category along with the
  > number of cases in this category.  

- **Example**
  Construct a frequency table for the given data

  1. A,A,B,C,A,D,A,B,D,C
  2. A,A,B,C,A,D,A,B,D,C,A,B,C,D,A
  3.  A,A,B,C,A,A,B,B,D,C,A,B,C,D,B
  4.  A,A,B,C,A,D,A,B,D,C, A,B,C,D,A,C,D,D  

- **Construct a frequency distribution**
  The steps to construct a frequency distribution

  1. List the distinct values of the observations in the data set in
     the first column of a table.
  2. For each observation, place a tally mark in the second column
     of the table in the row of the appropriate distinct value.
  3. Count the tallies for each distinct value and record the totals
     in the third column of the table.  

- **Example**

  1. A,A,B,C,A,D,A,B,D,C

  | Category | Tally mark | Frequency |
  | -------- | ---------- | --------- |
  | A        |            |           |
  | B        |            |           |
  | C        |            |           |
  | D        |            |           |
  | Total    |            |           |

  2. A,A,B,C,A,D,A,B,D,C, A,B,C,D,A

  | Category | Tally mark | Frequency |
  | -------- | ---------- | --------- |
  | A        |            |           |
  | B        |            |           |
  | C        |            |           |
  | D        |            |           |
  | Total    |            |           |
  3. A,B,B,C,A,D,B,B,D,C, A,B,C,D,B

  | Category | Tally mark | Frequency |
  | -------- | ---------- | --------- |
  | A        |            |           |
  | B        |            |           |
  | C        |            |           |
  | D        |            |           |
  | Total    |            |           |

  4. A,A,B,C,A,D,A,B,D,C, A,B,C,D,A,C,D,D

  | Category | Tally mark | Frequency |
  | -------- | ---------- | --------- |
  | A        |            |           |
  | B        |            |           |
  | C        |            |           |
  | D        |            |           |
  | Total    |            |           |

### Frequency table in a google sheet
1. Select/Highlight the cells having data you want to visualize.
2. In the Formatting bar click on the Data option.
3. In the Data option go to Pivot Table option and create a new
   sheet.
4. After creating Pivot Table go in Pivot Table Editor and in
   that first add rows and then values.  

### Relative frequency  

- **Definition**: The ratio of the frequency to the total number of observations is called relative frequency

  - The steps to construct a relative frequency distribution
    1. Obtain a frequency distribution of the data.
    2. Divide each frequency by the total number of observations  

- Example

  1. A,A,B,C,A,D,A,B,D,C

  | Category | Tally mark | Frequency | Relative frequency |
  | -------- | ---------- | --------- | ------------------ |
  | A        | \|\|\|\|   | 4         | .4                 |
  | B        | \|\|       | 2         | .2                 |
  | C        | \|\|       | 2         | .2                 |
  | D        | \|\|       | 2         | .2                 |
  | Total    |            | 10        | 1                  |

  2. A,A,B,C,A,D,A,B,D,C, A,B,C,D,A

  | Category | Tally mark | Frequency | Relative frequency |
  | -------- | ---------- | --------- | ------------------ |
  | A        | \|\|̸\|\|\| | 6         | 04                 |
  | B        | \|\|\|     | 3         | .2                 |
  | C        | \|\|\|     | 3         | .2                 |
  | D        | \|\|\|     | 3         | .2                 |
  | Total 15 |            | 15        | 1                  |

### Why relative frequency?  

- For comparing two data sets.
- Because relative frequencies always fall between 0 and 1, they provide a standard for comparison.  

## Describing Categorical Data- Single Variable  

### Charts of categorical data  

- The two most common displays of a categorical variable are a **bar chart** and a **pie chart**.
- Both describe a categorical variable by displaying its **frequency** table

### Pie charts  

- **Definition**: A pie chart is a circle divided into pieces proportional to the relative frequencies of the qualitative data.  

- The steps to construct a pie-chart1
  1. Obtain a relative-frequency distribution of the data.
  2. Divide a circle into pieces proportional to the relative
     frequencies.
  3. Label the slices with the distinct values and their relative
     frequencies.  

- **Example**
  Use a protractor and the fact that there are 360◦ in a circle. Thus,
  for example, the first slice of the circle is obtained by marking off
  0:4 × 360 = 144◦.  

1. A,A,B,C,A,D,A,B,D,C, A,B,C,D,A

| Category  | Freq | Relative freq | Degrees |
| -------- | ---------- | ---- | ------------- | ------- |
| A        | 6    | 0.4           | 144     |
| B        | 3    | 0.2           | 72      |
| C         | 3    | 0.2           | 72      |
| D         | 3    | 0.2           | 72      |
| Total     | 15   | 360           | 360     |

```MERMAID
pie title EX1 
    "A" : 40
    "B" : 20
    "C" : 20
    "D" : 20
```

### Pie chart in a google sheet  

**Step 1** Select/Highlight the cells having data you want to visualize.
**Step 2** Click the Insert Chart option in Google Sheets toolbar.
**Step 3** Change the visualization type in Chart editor.
**Step 4** Select in Chart Editor Chart type to Pie chart.  

### Bar chart  

- **Definition**: A bar chart displays the distinct values of the qualitative data on a horizontal axis and the relative frequencies (or frequencies or percent) of those values on a vertical axis. The frequency/relative frequency of each distinct value is represented by a vertical bar whose height is equal to the frequency/relative frequency of that value. The bars should be positioned so that they do not touch each other.  

#### Steps to construct a bar chart  

- To Construct a Bar Chart
  1. Obtain a frequency/relative-frequency distribution of the data.
  2. Draw a horizontal axis on which to place the bars and a vertical axis on which to display the frequencies/relative frequencies.
  3. For each distinct value, construct a vertical bar whose height equals the frequency/relative frequency of that value.
  4. Label the bars with the distinct values, the horizontal axis with the name of the variable, and the vertical axis with "Frequency" /"Relative frequency."  

#### Bar chart in a google sheet  

Step 1 Select/Highlight the cells having data you want to visualize.
Step 2 Click the Insert Chart option in Google Sheets toolbar.
Step 3 Change the visualization type in Chart editor.
Step 4 Select in Chart Editor Chart type to Bar chart  

### Pareto charts  

- **Definition**: When the categories in a bar chart are sorted by frequency, the bar chart is sometimes called a Pareto chart. Pareto charts are popular in quality control to identify problems in a business process.

  > If the categorical variable is ordinal, then the bar chart must
  > preserve the ordering.  

- **Example- Pareto chart**
  A,B,B,C,A,D,B,B,A,C, B,B,C,D,A

  | Category | Tally mark | Freq | Relative freq |
  | -------- | ---------- | ---- | ------------- |
  | A        | 4          | 0.26 |               |
  | B        | 6          | 0.40 |               |
  | C        | 3          | 0.20 |               |
  | D        | 2          | 0.14 |               |
  | Total    | 15         | 1    |               |

- Example- ordinal data
  The T-shirt sizes ( Small-S, Medium-M, Large-L) of twenty
  students is listed below:
  L,M,M,S,L,S,S,M,L,M,M,S,S,L,M,S,M,S,L,M

  | Size   | Frerquency | Relative Freq |
  | ------ | ---------- | ------------- |
  | Small  | 7          | 0.35          |
  | Medium | 8          | 0.40          |
  | Large  | 5          | 0.25          |
  | Total  | 20         | 1             |

## Describing Categorical Data - Best practices while graphing data 

### Know your purpose  

- Have a purpose for every table or graph you create
  - I Choose the table/graph to serve the purpose.
- Pie charts are best to use when you are trying to compare
  parts of a whole.
- Bar graphs are used to compare things between different
  groups  

### Label your data

- Label your chart to show the categories and indicate whether some have been combined or omitted.
- Name the bars in a bar chart.
- Name the slices in a pie chart.
- If you have omitted some of the cases, make sure the label of the plot defines the collection that is summarized.  

![](..\images\pie1.png)

![](..\images\bar1.png)

### Many Categories

![..\images\pbar1.png](D:\Notes\IItM notes\IIT-M-notes\images\pbar1.png)

- A bar chart or pie chart with too
  many categories might conceal
  the more important categories.
  In some case, grouping other
  categories together might be
  done.  

#