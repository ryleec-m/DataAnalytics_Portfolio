# Python 

File Name: PythonEDAProject.ipynb

## Exploratory Data Analysis

### Objective
Who had higher survival rates?\
Did class matter?\
Did age influence survival?

### Dataset
titanic.csv

### Tools
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
  
### Findings
1. Who had higher survival rates?
It is very apparent that females had higher survival rates than males. This is apparent from both the visuals and the statistics. The statistics revealed that, on average, the survival rate for women was 74%, and the survival rate for men was 19%. If we look at class, we can see that on average the survival rate was higher for those in a better class, with first class  having 63%, second class having 47%, and third class having 24%. The bar chart and scatter plot both support these statistics. I also discovered that age did not necessarily influence the survival rate. For younger children, survival rates were higher, but for any other age group, there was no clear distinction. The statistics showed that the average age of those who died was about 30 years old, and the average age of those who survived was about 28 years old. Given the closeness in age, we can’t make any assumptions about age influencing survival rates.
2. Did class matter?
Yes, class did matter! We can see from the statistical analysis that the higher the class, the higher the chance of survival one had. This is revealed most clearly in the scatter plot that compares age and fare alongside survival. This graph shows that the more a passenger paid for a ticket, the more likely they were to survive. Using Plotly, I was also able to click on individual points, and this allowed me to notice that the higher fares were first-class individuals, while the lower fares were more likely to be third-class individuals. We can see the discrepancies in fares more closely in the box plot visual. This graph showed a closer look at the differences in ticket price between classes, how much more first-class tickets were compared to the second and third class tickets.
3. Did age influence survival?
The answer to this question isn’t a straightforward yes or no. Looking at the histogram that compares survival counts with age, we can see that the most common age was between 20 and 40 years old. In this range, we see the highest survival rates, but only the highest death rates. This doesn’t necessarily show age factoring into the 20-40 year old survival rate. Statistics also showed that the average age for survival was about 30, while the average age for death was about 28. For older groups, above the age of 45, we see more deaths compared to survivors. This is most likely due to the fact that older people have a harder time surviving in the conditions present during the Titanic accident. For younger groups, under the age of 20, we do see more survivors than deaths. This is most obviously due to the fact that women and children were put on the lifeboats first before any other people were.
