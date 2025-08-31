
<br>

**\[[🇧🇷 Português](README.pt_BR.md)\] \[**[🇺🇸 English](README.md)**\]**


<br><br>



# <p align="center">  [2 and 3]() - Data Mining with Python - [Stats Review]()
### <p align="center">  Specialized Consulting for Integrated Project: Data Mining - [Main Data Mining Repository Access](https://github.com/Quantum-Software-Development/1-Main_DataMining_Repository)


<br><br>


[**Institution:**]() Pontifical Catholic University of São Paulo (PUC-SP)  
[**School:**]() Faculty of Interdisciplinary Studies  
[**Program:**]() Humanistic AI and Data Science
[**Semester:**]() 2nd Semester 2025  
Professor:  [***Professor Doctor in Mathematics Daniel Rodrigues da Silva***](https://www.linkedin.com/in/daniel-rodrigues-048654a5/)

<br><br>

#### <p align="center"> [![Sponsor Quantum Software Development](https://img.shields.io/badge/Sponsor-Quantum%20Software%20Development-brightgreen?logo=GitHub)](https://github.com/sponsors/Quantum-Software-Development)


 <!--Confidentiality statement -->

<br><br><br>

#

<br><br><br>

> [!IMPORTANT]
> 
> ⚠️ Heads Up
>
> * Projects and deliverables may be made [publicly available]() whenever possible.
> * The course prioritizes [**hands-on practice**]() with real data in consulting scenarios.
> * All activities comply with the [**academic and ethical guidelines of PUC-SP**]().
> * [**Confidential information**]() from this repository remains private in [private repositories]().
>

<br><br><br>

#

<!--END-->



<!-- PUC HEADER GIF
<p align="center">
  <img src="https://github.com/user-attachments/assets/0d6324da-9468-455e-b8d1-2cce8bb63b06" />
-->

<br>

<!-- video presentation -->


##### 🎶 Prelude Suite no.1 (J. S. Bach) - [Sound Design Remix]()

https://github.com/user-attachments/assets/4ccd316b-74a1-4bae-9bc7-1c705be80498

####  📺 For better resolution, watch the video on [YouTube.](https://youtu.be/_ytC6S4oDbM)


<br><br>


> [!TIP]
> 
>  This repository is a review of the Statistics course from the undergraduate program Humanities, AI and Data Science at PUC-SP.
> 
>  If you’d like to explore the full materials from the 1st year (not only the review), you can visit the complete repository [here](https://github.com/FabianaCampanari/PracticalStats-PUCSP-2024).
>
>


<br><br>



##  [Overview]()

<br>

This repository contains materials and examples for the **Introduction to Data Mining with Python Class 1** course, focusing on fundamental statistical concepts and data analysis techniques essential for data mining applications.

<br>

## Repository Structure

```
├── data/                 # Sample datasets
├── notebooks/           # Jupyter notebooks with examples
├── scripts/             # Python scripts for analysis
├── images/              # Generated plots and visualizations
└── docs/                # Additional documentation
```

<br><br>


## Getting Started

### Prerequisites:

- Python 3.7+
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

<br>

### Installation:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

<br>

### Quick Start:

<br>

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Load sample data
data = [50, 40, 41, 17, 11, 7, 22, 44, 28, 21, 19, 23, 37, 51, 54, 42, 86,
        41, 78, 56, 72, 56, 17, 7, 69, 30, 80, 56, 29, 33, 46, 31, 39, 20,
        18, 29, 34, 59, 73, 77, 36, 39, 30, 62, 54, 67, 39, 31, 53, 44]

# Create histogram
plt.figure(figsize=(10, 6))
plt.hist(data, bins=7, edgecolor='black')
plt.title('Internet Usage Distribution')
plt.xlabel('Minutes Online')
plt.ylabel('Frequency')
plt.show()

# Calculate statistics
print(f"Mean: {np.mean(data):.2f}")
print(f"Median: {np.median(data):.2f}")
print(f"Standard Deviation: {np.std(data):.2f}")
```

<br><br>

## Key Learning Outcomes

After completing this course, students will be able to:

1. **Construct and interpret frequency distributions** from raw data
2. **Create various types of histograms** and understand their relationship to frequency distributions
3. **Identify and handle outliers** in datasets
4. **Analyze distribution shapes** and their implications
5. **Calculate and interpret central tendency measures**
6. **Apply statistical concepts** to data mining problems
7. **Use Python tools** for statistical analysis and visualization

<br>

## Important Notes

- **Outliers require careful consideration** - they may represent valuable insights or data quality issues
- **Histogram bins should be chosen thoughtfully** - too few may hide patterns, too many may create noise
- **Frequency distributions are fundamental** to understanding data structure before applying advanced data mining techniques
- **Visual analysis complements numerical statistics** for comprehensive data understanding

<br>

*This material is part of the Introduction to Data Mining with Python course, focusing on fundamental statistical concepts essential for effective data analysis and mining.*

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


#### Python Implementation Examples:

<br>

```python
import matplotlib.pyplot as plt
import numpy as np

# Create frequency distribution
def create_frequency_distribution(data, num_classes=7):
    min_val, max_val = min(data), max(data)
    class_size = (max_val - min_val) / num_classes
    
    # Define class boundaries
    boundaries = [min_val + i * class_size for i in range(num_classes + 1)]
    
    # Count frequencies
    frequencies = []
    for i in range(num_classes):
        count = sum(1 for x in data if boundaries[i] <= x < boundaries[i+1])
        frequencies.append(count)
    
    return boundaries, frequencies

# Create histogram
def plot_histogram(data, title="Frequency Distribution"):
    plt.figure(figsize=(10, 6))
    plt.hist(data, bins=7, edgecolor='black', alpha=0.7)
    plt.title(title)
    plt.xlabel('Values')
    plt.ylabel('Frequency')
    plt.grid(True, alpha=0.3)
    plt.show()
```


<br><br><br>


## [Exemple 1]() - Finding the Mean of a Frequency Distribution


### [Step-by-Step Instructions]()

### In Words \& In Symbols](

<br>


| In Words | In Symbols |
| :-- | :-- |
| 1. Find the midpoint of each class. | \$ x = \frac{lower limit + upper limit}{2} \$ |
| 2. Multiply each midpoint by its class frequency and sum the results. | \$ \sum (x \cdot f) \$ |
| 3. Find the sum of all frequencies. | \$ n = \sum f \$ |
| 4. Calculate the mean by dividing the sum from step 2 by step 3. | \$ \bar{x} = \frac{\sum (x \cdot f)}{n} \$ 


<br><br>


### [Example](): Finding the Mean of a Frequency Distribution

Use the frequency distribution below to approximate the average number of minutes that a sample of internet users spent connected in their last session.

<br>

| Class | Midpoint ($x$) | Frequency ($f$) |
| :-- | :--: | :--: |
| 7 – 18 | 12.5 | 6 |
| 19 – 30 | 24.5 | 10 |
| 31 – 42 | 36.5 | 13 |
| 43 – 54 | 48.5 | 8 |
| 55 – 66 | 60.5 | 5 |
| 67 – 78 | 72.5 | 6 |
| 79 – 90 | 84.5 | 2 |


<br><br>


### [Let's compute the products and their sumLet's compute the products and their sum:


| Class | Midpoint ($x$) | Frequency ($f$) | $x \cdot f$ |
| :-- | :-- | :-- | :-- |
| 7 – 18 | 12.5 | 6 | 75.0 |
| 19 – 30 | 24.5 | 10 | 245.0 |
| 31 – 42 | 36.5 | 13 | 474.5 |
| 43 – 54 | 48.5 | 8 | 388.0 |
| 55 – 66 | 60.5 | 5 | 302.5 |
| 67 – 78 | 72.5 | 6 | 435.0 |
| 79 – 90 | 84.5 | 2 | 169.0 |
| **Total** |  | **50** | **2089.0** |:


<br><br>

### [Therefore, the mean is]():

<br><br>

$$
\Huge
\bar{x} = \frac{\sum (x \cdot f)}{n} = \frac{2089}{50} \approx 41.8 \text{ minutes}
$$


<br><br>

```latex
\Huge
\bar{x} = \frac{\sum (x \cdot f)}{n} = \frac{2089}{50} \approx 41.8 \text{ minutes}
```

<br><br>


### [Shapes of Distributions]()

### Symmetrical Distribution

- A vertical line can be drawn at the middle of the graph, and the halves are nearly identical.


<br><br>


### [Shapes of Distributions]()

<br>

### Symmetrical Distribution

- A vertical line can be drawn at the middle of the graph, and the halves are nearly identical.


<br>


### [Uniform Distribution]() (Rectangular)

- All entries have equal or nearly equal frequencies.
- The distribution is symmetric.



<br><br>


### [Left-Skewed Distribution]() (Negatively Skewed)

- The "tail" of the graph extends more to the left.
- The mean is to the left of the median.


<br>


### [Right-Skewed Distribution]() (Positively Skewed)

- The "tail" of the graph extends more to the right.
- The mean is to the right of the median.


<br>


### [Finding the Weighted Mean]()

Sometimes, the mean is calculated considering different "weights" for each value.


<br><br>


## [Exemple 2]() 

<br>

### [A student's grade is determined based on 5 sources]():

- 50% for the average of exams
- 15% for the midterm exam
- 20% for the final exam
- 10% for computer lab work
- 5% for homework

<br>

### [Suppose your grades are]():

- Exam average: 86
- Midterm: 96
- Final Exam: 82
- Lab: 98
- Homework: 100


<br><br>


### [Weighted Mean Calculation Table](()

| Source | Grade ($x$) | Weight ($w$) | $x \cdot w$ |
| :-- | :--: | :--: | :--: |
| Exam Average | 86 | 0.50 | 43.0 |
| Midterm | 96 | 0.15 | 14.4 |
| Final Exam | 82 | 0.20 | 16.4 |
| Lab | 98 | 0.10 | 9.8 |
| Homework | 100 | 0.05 | 5.0 |
| **Sum** |  | **1** | **88.6** |


<br><br>

$$
\Huge
\bar{x} = \frac{\sum (x \cdot w)}{\sum w} = \frac{88.6}{1} = 88.6
$$


<br>

```latex
\Huge
\bar{x} = \frac{\sum (x \cdot w)}{\sum w} = \frac{88.6}{1} = 88.6
```


<br><br>

So, the student did [**not**]() get an [A (minimum required is 90)]().


<br><br>


## [Mean of Grouped Data]()

The mean of a frequency distribution is calculated as:

<br><br>


$$
\Huge
\bar{x} = \frac{\sum (x \cdot f)}{n}
$$


<br>

```latex
\Huge
\bar{x} = \frac{\sum (x \cdot f)}{n}
```

<br><br>

Where [x]() is the class midpoint and [f]() is the frequency of the class.





<br><br>

<br><br>

<br><br>

<br><br>


























































<br><br>

## Bibliography

### Primary References:

1. **Castro, L. N. & Ferrari, D. G.** (2016). *Introdução à mineração de dados: conceitos básicos, algoritmos e aplicações*. Saraiva.

2. **Ferreira, A. C. P. L. et al.** (2024). *Inteligência Artificial - Uma Abordagem de Aprendizado de Máquina*. 2nd Ed. LTC.

3. **Larson & Farber** (2015). *Estatística Aplicada*. Pearson.

<br><br>

<br><br>


## 💌 [Let the data flow... Ping Me !](mailto:fabicampanari@proton.me)

<br><br>



#### <p align="center">  🛸๋ My Contacts [Hub](https://linktr.ee/fabianacampanari)


<br>

### <p align="center"> <img src="https://github.com/user-attachments/assets/517fc573-7607-4c5d-82a7-38383cc0537d" />




<br><br><br>

<p align="center">  ────────────── 🔭⋆ ──────────────


<p align="center"> ➣➢➤ <a href="#top">Back to Top </a>

<!--
<p align="center">  ────────────── ✦ ──────────────
-->



<!-- Programmers and artists are the only professionals whose hobby is their profession."

" I love people who are committed to transforming the world "

" I'm big fan of those who are making waves in the world! "

##### <p align="center">( Rafael Lain ) </p>   -->

#

###### <p align="center"> Copyright 2025 Quantum Software Development. Code released under the [MIT License license.](https://github.com/Quantum-Software-Development/Math/blob/3bf8270ca09d3848f2bf22f9ac89368e52a2fb66/LICENSE)




