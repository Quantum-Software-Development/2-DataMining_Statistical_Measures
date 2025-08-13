
<br>

# [Introduction to Data Mining with Python and Stats Review]() - Class 1

<br><br>

#### <p align="center"> [![Sponsor Quantum Software Development](https://img.shields.io/badge/Sponsor-Quantum%20Software%20Development-brightgreen?logo=GitHub)](https://github.com/sponsors/Quantum-Software-Development)

<br><br>


##  [Overview]()

<br>

This repository contains materials and examples for the **Introduction to Data Mining with Python Class 1** course, focusing on fundamental statistical concepts and data analysis techniques essential for data mining applications.

<br>

## [Class_1 Content]()

### Syllabus (Ementa)

- **Descriptive Statistics Review**
- **Data Mining Concepts**
- **Exploratory Data Analysis**
- **Predictive Analysis**
- **Clustering**
- **Association Rules**

<br>

### [Assessment Criteria]()

- Minimum 75% attendance required
- Final grade ≥ 5.0
- Formula: MF = (N₁ + N₂)/2, where Nᵢ = (Pᵢ + Aᵢ)/2
  - Pᵢ = Project grade for semester i
  - Aᵢ = Activity/exam grade for semester i

<br>

## [Key Topics Covered]()

<br>

### [1](). Frequency Distribution

A **frequency distribution** is a table that shows classes or intervals of data with a count of the number of entries in each class. It's fundamental for understanding data patterns and is the foundation for creating histograms.

<br> 

#### [Components]():

- **Class limits**: Lower and upper boundaries of each class
- **Class size**: The width of each class interval
- **Frequency (f)**: Number of data entries in each class
- **Relative frequency**: Proportion of data in each class (f/n)
- **Cumulative frequency**: Sum of frequencies up to a given class

<br> 

#### Construction Steps:
1. Decide the number of classes (typically 5-20)
2. Calculate class size: (max - min) / number of classes
3. Determine class limits
4. Count frequencies for each class
5. Calculate additional measures (relative, cumulative frequencies)

<br><br> 

### 2. Histograms and Their Relationship to Frequency Distributions


**Histograms are vectorially related to frequency distributions** - they are the graphical representation of frequency distribution tables.

<br> 

#### Key Characteristics:

- **Bar chart** representing frequency distribution
- **Horizontal axis**: Quantitative data values (class boundaries)
- **Vertical axis**: Frequencies or relative frequencies
- **Consecutive bars must touch** (unlike regular bar charts)
- **Class boundaries**: Numbers that separate classes without gaps

<br> 

#### Types of Histograms:

1. **Frequency Histogram**: Shows absolute frequencies
2. **Relative Frequency Histogram**: Shows proportions/percentages
3. **Frequency Polygon**: Line graph emphasizing continuous change

<br><br> 

### 3. Outliers in Histograms  

**Outliers, by definition, have few values** and can represent various phenomena:

<br>

#### What Outliers May Indicate:

- **Data entry errors** (typing mistakes)
- **Measurement errors**
- **Fraudulent activities**
- **Genuine extreme values**
- **Equipment malfunctions**

<br>

#### Impact on Histograms:
- **Generate few bars** (sparse representation)
- **Create gaps** in the distribution
- **Skew the overall pattern**
- **Affect central tendency measures**
- **May require special handling** in analysis

<br>

#### Outlier Detection in Histograms:
- Visible as **isolated bars** far from main distribution
- **Large gaps** between bars
- **Extremely tall or short bars** at distribution extremes
- **Asymmetric patterns** in otherwise normal distributions

<br><br>

### 4. Distribution Shapes

Understanding distribution shapes helps identify data characteristics:

#### Symmetric Distribution:

- Mean ≈ Median ≈ Mode
- Bell-shaped or uniform patterns
- Equal spread on both sides

<br>

#### Left-Skewed (Negatively Skewed):

- Mean < Median < Mode
- Tail extends to the left
- Few extremely low values

<br>

#### Right-Skewed (Positively Skewed):

- Mode < Median < Mean
- Tail extends to the right
- Few extremely high values

<br>

#### Uniform Distribution:

- All classes have equal frequencies
- Rectangular shape in histogram

<br><br>

### 5. Central Tendency Measures

#### Mean (μ or x̄):
- Sum of all values divided by count
- Most affected by outliers
- Uses all data points

#### Median:
- Middle value when data is ordered
- Less affected by outliers
- Robust measure

#### Mode:
- Most frequently occurring value
- May not exist or may be multiple
- Good for categorical data

<br><br>

### 6. Practical Applications

#### Data Mining Context:
- **Pattern Recognition**: Identifying data distributions
- **Anomaly Detection**: Finding outliers
- **Data Quality Assessment**: Checking for errors
- **Feature Engineering**: Understanding variable distributions
- **Model Selection**: Choosing appropriate algorithms based on data distribution

<br><br>

