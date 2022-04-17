# Pandas-Challenge

There are a lot of interesting results that I find from this data set. The first general summary of the data doesn't provide much insight. It only shows an overview where a lot of the underlying detail could have been masked. However, once the data is grouped by school, it became clear which school is not performing as well as other school. The downside with just grouping by school is the trend within the data is not as telling.

#### Scores by School Spending
| Spending Ranges (Per Student)   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:--------------------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| <$585                           |                83.46 |                   83.93 |            93.46 |               96.61 |               90.37 |
| $585-630                        |                81.9  |                   83.16 |            87.13 |               92.72 |               81.42 |
| $630-645                        |                78.52 |                   81.62 |            73.48 |               84.39 |               62.86 |
| $645-680                        |                77    |                   81.03 |            66.16 |               81.13 |               53.53 |

#### Scores by School Size
| School Size        |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:-------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Small (<1000)      |                83.82 |                   83.93 |            93.55 |               96.1  |               89.88 |
| Medium (1000-2000) |                83.37 |                   83.86 |            93.6  |               96.79 |               90.62 |
| Large (2000-5000)  |                77.75 |                   81.34 |            69.96 |               82.77 |               58.29 |

#### Scores by School Type
| School Type   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:--------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Charter       |              83.4739 |                 83.8964 |          93.6208 |             96.5865 |             90.4322 |
| District      |              76.9567 |                 80.9666 |          66.5485 |             80.7991 |             53.6722 |

When the data gets bin into categories, the trend is more clearly visible at a glance. These three tables show a correlation between scores and different factors. The larger the school size is the lower the students get on their test. It is not as significant between small and medium size school but with large school, there is a big drop in test result. A surprising correlation from this table is the higher spending per student does not improve test result. In fact, student actually perform worse when there is higher spending per student. Also, according to the data, charter school's test result out perform district school's in all categories. When binning and comparing in the right way, there is a lot of useful insight that can be gather from a big data. 
