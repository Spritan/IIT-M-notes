# Year 01 Week 01

## Introduction and types of Data - Basic definitions

### What is Statistics?  

  - **Definition**: Statistics is the art of learning from data. It is concerned with the collection of data, their subsequent description, and their analysis,  which often leads to the **drawing of conclusions**. 

 ### Major branches of statistics

1. **Description**  

  **Definition**: The part of statistics concerned with the description and summarization of data is called *descriptive statistics*.  

   > Descriptive statistics can be performed either on a sample or a population.

2. **Inference **

   **Definition**: The part of statistics concerned with the drawing of conclusions from data is called inferential statistics.  To be able to conclude the data, we must take  into account the <u>possibility of chance</u>- introduction to  *probability*

- Examples

  - Suppose we are interested in knowing  
    - The percentage of  all students in India who have passed their  Class 12 examS and study engineering.  
    - The prices of all houses in Tamil Nadu.  
    - The total sales of all cars in India in the year 2019. 
    - The age distribution of people who visit a city Mall in a  particular month.  

### Population and Sample

- The total collection of all the elements that we are interested in is called a **population**.
- A subgroup of the population that will be studied in detail is called a **sample**. 

### Purpose of Statistical analysis

- If the purpose of the analysis is to examine and explore information for its own intrinsic interest only, the study is **descriptive**.
- If the information is obtained from a sample of a population and the purpose of the study is to use that information to conclude the population, the study is **inferential**. 

 

## Introduction and types of Data - Understanding data

- **Data** is information that is all around us, whether we are formally doing statistical analysis or not; all of us are either creating data or contributing towards the collection of data or we are collecting data ourselves.

### What is data?

- To learn something, we need to collect data. 
- **Definition**
  - Data are the facts and figures collected, analysed, and summarized for presentation and interpretation. 
    - Statistics relies on data, information that is around us.

### Why do we collect data?

- Interested knowing in the characteristics of some group or groups of people, places, things, or events. 
- Example: TO know about temperatures in a particular month in Chennai, India. 
- Example: TO know about the marks obtained by students in their Class 12. 
- To know how many people like a new song/product/video- collected through comments. 

### Data Collection

- Data available: published data. eg, data.gov .in
- Data not available: need to collect, generate data.

> We assume data is available and our objective is to do a statistical analysis of available data

### Unstructured and structured data

- For the information in a database to be useful, we must know the context of the numbers and text it holds.
- When they are scattered about with no structure, the information is of very little use.
- <u>Hence, we need to organize data</u>

### Dataset 

- A structured collection of data.
- it  is a collection of values-could be numbers, names, roll numbers.

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

  - Case: each student 
  - Variable: Name. marks obtained. Board etc. 

- Rows represent cases: for each case. same attribute is recorded 

- Columns represent variables: For each variables. same type Of value for each case is recorded. 

  > We have organised data in a spreadsheet into a table
  >
  > - Each variable must have its own column
  > - Each observation must have its own row.

## Introduction and Types of Data - Classification of data

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
> - identify group membership 
> - Eg Gender, School Board, Blood Group, Role, Jersey no. day and date, qualification of a candidate sitting for a job.

**Categorical variable**s: Variables which should not be treated like numbers (as in mathematics), and whose values come from a list of possibilities. 

- **Nominal variable:** A categorical variable where the categories do not have a natural ordering (e.g. gender, ethnicity, country). 
- **Ordinal variable**: A categorical variable where the categories have a natural ordering (e.g. age group, income level, educational status).

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

- When the data for a variable consists of labels or names used to identify the characteristics of an observation, the scale of measurement is considered  a **nominal** scale.
  - **Eg**: Name, Board, Gender, Blood group etc.
- Sometimes nominal variables might be numerically coded
  - **Eg** : We might code Men as 1 and Women as 2. Or Code Men as 3 and Women as 1. Both codes are valid.

- There is no ordering in variable.

> Nominal: name categories without implying order

#### Ordinal Scale of Measurement

- Data exhibits properties of nominal data and the order or rank
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
  - Temperature in degrees Fahrenheit or degrees centig
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

![](D:\Notes\IItM notes\images\summery.png)