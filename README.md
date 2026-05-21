# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Factors Influencing Healthcare Insurance Cost 

This project looks at how personal factors (e.g. gender, age, BMI, smoking status) and geographical location (region of the USA) may impact on medical insurance costs. The aim is to analyse the dataset and identify which factors significantly increase healthcare insurance costs.

## Dataset Content
* The dataset was taken from Kaggle and contains anonymised personal information of people in the USA that have taken out medical insurance. https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance
* Personal information includes age, gender, BMI, number of children, smoking status and their geographical location in the USA. Additionally, the cost of their medical insurance. 


## Business Requirements
* Analyse dataset to identify potential factors influencing medical insurance costs for customers. 
* The findings will assist in the data driven decision on pricing strategies and cost estimation. 


## Hypothesis and how to validate?
* People with a smoking habit (smokers) are likely to pay more for medical insurance than non-smokers.
* Based on the outcome of data visulisation we can prove that this hypothesis is true.
![output Smoking impact](Images/output%20Smoking%20impact.png) 
* A person with high BMI will pay more for medical insurance compared to lower BMI person.
* Based on the outcome of data visulisation we can prove that this hypothesis is true.
![output BMI impact](Images/output%20BMI%20impact.png)
* Older people will pay more for medical insurance compared with younger individuals.
* Based on the outcome of data visulisation we can prove that this hypothesis is true.
![output Age impact](Images/output%20Age%20impact.png)
* Geographic location should not impact on the cost of the medical insurance.
* Based on the outcome of data visulisation we can prove that this hypothesis is true.
![output Region Impact](Images/output%20Region%20Impact.png)
* The number of children in the family will have no impact the cost of medical insurance.
* Based on the outcome of data visulisation we can prove that this hypothesis is true.
![output number of children impact](Images/output%20number%20of%20children%20impact.png)
* The gender of the individual will have an impact on the medical insurance cost.
* Based on the outcome of data visulisation we can prove that this hypothesis is true.
![output smoking and sex impact](Images/output%20smoking%20and%20sex%20impact.png)
* A smoking person also having a high BMI will pay more for medical insurance 
* Based on the outcome of data visulisation we can prove that this hypothesis is true.
![output BMI and smoking correlation](Images/output%20BMI%20and%20smoking%20correlation.png)

## Application of Statistical and Probabilistic Principles

While descriptive statistics provide an overview of the dataset, formal statistical analysis techniques are necessary to validate findings and support reliable conclusions. This project incorporates inferential statistical methods and probabilistic reasoning to strengthen the analytical process.
* Hypothesis Testing
Hypothesis testing was used to determine whether observed patterns in the dataset are statistically significant rather than occurring by chance.
The statistical decision is based on the p-value, which measures the probability of observing the data if the null hypothesis is true.
A significance level of 0.05 was used in this analysis:
•	If p < 0.05, the null hypothesis is rejected. 
•	If p ≥ 0.05, there is insufficient evidence to reject the null hypothesis. 
This approach ensures that conclusions are supported by statistical evidence rather than assumptions.

Example: Independent t-Test
To compare the mean values between two groups, an independent t-test can be applied.
The t-test evaluates whether differences between groups are statistically significant. This supports objective interpretation of the dataset and improves the validity of analytical findings.
* Probability Distributions
Probability distributions describe how values are expected to occur within a dataset and help analysts understand uncertainty and variability.
Normal Distribution
Many real-world datasets follow a normal distribution, where values cluster around the mean.
The normal distribution is important because it forms the basis for many statistical techniques, including hypothesis testing and confidence interval estimation.
In this project, understanding data distribution helped determine whether statistical assumptions were satisfied before applying analytical methods.
Standard Deviation and Variability
Standard deviation was used to evaluate how dispersed the data values are around the mean.
This measure supports interpretation by identifying whether observations are tightly grouped or highly variable.

* Correlation Analysis
Correlation analysis was used to measure the strength and direction of relationships between variables.
Correlation coefficients range from:
•	+1 → strong positive relationship 
•	0 → no relationship 
•	−1 → strong negative relationship 
This analysis helps identify meaningful associations within the dataset and supports evidence-based conclusions.
* Importance of Statistical Validation
Applying statistical testing and probability theory improves the reliability and credibility of the analysis. These methods ensure that findings are not based solely on visual observations or descriptive summaries, but are supported through quantitative evidence.
The integration of hypothesis testing, probability distributions, variability analysis, and correlation analysis demonstrates a structured and scientifically grounded data analysis approach.


I will use visualisation tools like Matplotlib and Seaborn to clearly show the factors impacting medical insurance costs. Additionally, I will use PowerBI to create a interactive dashboard page.


## Project Plan
* Data collection and set up: The data was taken from Kaggle and saved as CSV file (RawData folder). This data was loaded in VS Code.
* Data cleaning: The data extraction, transformation and loading (ETL) was completed. The data was reviewed for duplicates, outliers, missing values. The data cleaning was completed (CleanData folder) analysis was commenced. 
* Data analysis and visualisation was completed using Matplotlib and Seaborn. The data presented using box-plots and scatter plots. Chart types were chosen based on data distribution. 
* The interactive dashboard page was created using PowerBI.

## The rationale to map the business requirements to the Data Visualisations
* The aim is to identify which factors impact the medical insurance cost for customers in the USA. Matplotlib visualisation tool was used to clearly identify the patterns and test the hypothesis questions.

1/ Do smokers pay more for medical insurance vs non smokers? 
The box plot visualisation used and dashboard page clearly shows that smokers pay significantly more than non-smokers. 
![smoking impact picture](Images/output%20Smoking%20impact.png)

2/ Does having a high BMI and smoking increase medical insurance cost? 
The scatter plot visualisation used and dashboard page clearly shows that being a smoker and having also having a high BMI means they pay more compared to a non-smoker with low BMI.
![BMI and smoking correlation](Images/output%20BMI%20and%20smoking%20correlation.png)

3/ Do medical insurance cost increase with age? 
The scatter plot visualisation shows a the older you get the more you pay for medical insurance. There is gradual increase in cost with increase in age of the person. 
![Age impact](Images/output%20Age%20impact.png)

4/ Does the region impact insurance cost? 
The box plot visualisation and dashboard page shows that region has very little impact on costs. All four regions have a similar median value. 
![Region Impact](Images/output%20Region%20Impact.png)

5/ Does the number of children a person have impact on medical insurance cost? The box plot visual shows no impact on insurance cost. 
![number of children impact](Images/output%20number%20of%20children%20impact.png)

## Analysis techniques used
* I used visualisation tools (Matplotlib and Seaborn) to analyse my dataset and identify which factors increased medical insurance costs. 
* I used box plots to show that smokers pay higher medical insurance compared to non-smokers.
* I used a scatter plot to show increasing age is linked to higher medical insurance cost i.e. the older you get the more you pay for insurance. 
* I used scatter plots to show correlation between a smoker and high BMI resulting in higher cost for medical insurance. 
* I used Co-pilot to help as required. 

## Ethical considerations
* The data was sourced from Kaggle, a Google-owned online platform offering datasets, and tools to learn, practice, and collaborate on real-world data challenges. 
* The dataset does include anonymised personal information so needs to be handled carefully and used solely for the purpose of this data analysis. 

## Dashboard Design
* The dashboard page was developed using PowerBI to assits in understanding and allow the analysis of factors that impact healthcare insurance costs in four reagions of the USA.
*The dashboard has various graphs (e.g. scatter plot, line plots and histograms) and buttons to drill down on the data looking at impact of smoker status, BMI, sex and by region.  
* In the dashboard page I have used simple smoker yes and no button, male vs female button to explain the impact on insurance cost to both technical and non-techincal audiences. 
* The dashboard page also communicates complex data insight using a scatter plot. The scatter plot shows a positive correlation between BMI and insurance cost.  
![PowerBI Dashboard page](/Images/PowerBI%20Dashboard_page.png)

## Unfixed Bugs
* As this is my first project and I am new to data analysis I did use Co-Pilot for code. 
* I had gaps in coding knowledge and AI assistance was helpful.

## Development Roadmap
* Faced challenge using VS code to load the CSV file.
* Folder and file structure not recognised and needed to restart the kernal.
* I used the LMS to review past lesson to refresh my knowledge.
* I also asked for help from my tutor.
* Also using CoPilot to help
* I would like learn more on using VS code, PowerBI and using the Jupyter notebook more proficiently. 

## Conclusion
In this project using the healthcare insurance dataset I was able to identify using visual analysis that smoking, high BMI and old age will significantly raise the cost of medical insurance. Smoking status had the strongest impact. Additionally, if you are a smoker and also have a high BMI you will pay significantly more compared to non-smoker with a low BMI. The geographical region and number of children does not appear to impact the insurance cost. 

The matplotlib visualisation and Dashboard page clearly showed the patterns and I was able to identify the factors that impact insurance cost. 

This project allowed me to develop my data analysis skills and put it into action in VS code and create a dashboard page using PowerBI. I learnt data cleaning, using data visualisation tools and making data driven conclusions. 

## Main Data Analysis Libraries
I used the following libraries for data analysis: pandas, numpy, matplotlib and seaborn. 

## Reflective Evaluation and Methodological Adaptation
* Challenges Encountered During the Analysis
Several challenges were encountered throughout the data analysis and machine learning process. These challenges required modifications to the original analytical approach in order to improve data quality, model reliability, and interpretability.
* Data Quality Issues
One of the primary challenges involved inconsistencies within the dataset, including duplicate records, missing values, and uneven data formatting. Initially, removing all duplicate entries was considered; however, further investigation showed that some duplicated observations represented legitimate repeated records rather than errors.
To address this issue, the preprocessing strategy was adapted so that only unnecessary duplicates were removed while representative observations were retained. This approach reduced data redundancy without compromising the integrity of the dataset.
Missing values also presented difficulties because eliminating all incomplete rows significantly reduced the available training data. Instead of removing large portions of the dataset, alternative preprocessing techniques were considered to preserve as much useful information as possible while maintaining analytical reliability.
________________________________________
* Adaptation of Analytical Techniques
Refinement of Statistical Analysis
During exploratory analysis, it became evident that relying solely on descriptive statistics was insufficient to validate patterns within the data. Although measures such as mean and standard deviation provided useful summaries, they did not demonstrate whether observed relationships were statistically significant.
To address this limitation, inferential statistical methods and hypothesis testing principles were incorporated into the methodology. This adaptation strengthened the analytical process by supporting conclusions with statistical evidence rather than descriptive observation alone.
Adjustment of Machine Learning Approach
Initially, multiple machine learning approaches were considered, including Decision Trees and more advanced predictive models. However, early experimentation indicated that some complex models reduced interpretability and introduced unnecessary complexity for the problem context.
As a result, the methodology was adapted to prioritise Linear Regression because:
	the target variable was continuous, 
	relationships between variables appeared approximately linear, 
	and model interpretability was important for explaining outcomes. 
This adjustment improved transparency and made the analytical findings easier to interpret and evaluate.
The Linear Regression model is represented by:
y=β_0+β_1 x_1+β_2 x_2+⋯+β_n x_n+ε
________________________________________
* Improvements to the Workflow
Another challenge involved maintaining a clear logical flow between preprocessing, statistical analysis, and machine learning stages. Early iterations of the notebook focused heavily on implementation code, which reduced clarity regarding the reasoning behind methodological decisions.
To improve the workflow:
	additional Markdown explanations were introduced, 
	methodological justifications were added before key analytical steps, 
	and explanatory commentary was included after statistical tests and model evaluation outputs. 
These changes improved readability and ensured that the progression of the analysis could be followed more clearly.
________________________________________
* Skills and Knowledge Developed
This project contributed to the development of both technical and analytical skills, including:
	data preprocessing and ETL techniques, 
	statistical analysis and hypothesis testing, 
	machine learning model selection, 
	data visualisation, 
	and methodological evaluation. 
The project also improved understanding of how analytical decisions must be justified within a research context rather than simply implemented technically.
________________________________________
* Future Improvements
Although the final methodology produced meaningful results, several improvements could be explored in future work:
	testing additional regression and ensemble learning algorithms, 
	applying feature engineering techniques, 
	performing cross-validation for improved model robustness, 
	and expanding the use of probability distributions and inferential statistics. 
These improvements could further strengthen predictive performance and analytical reliability.

## Credits 

* Kaggle was the source of the raw data.
* PowerBI was used to create a interactive dashboard page.  
* The use of Co-Pilot helped in generating code and providing explanations.
Additionally, support was provided when required by Code Institute course monitor (Vasi) 

## Acknowledgements
Thank you to Vasi for all the help during the project.