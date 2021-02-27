# Projects-for-Graduate-School
Writing samples &amp; projects for graduate school application

Hello! This is the guide about my two research projects: a study about Universal Basic Income (UBI) and its effects on crime rates; 
and a data analysis & policy advising paper about a NYC community with deviant infectious data of COVID-19 in early 2020. 
They are accomplished with my acknowledgement to Prof. Daniel Kapust and Prof. Christopher McKelvey & Omer Arain, respectively.

If you are interested in the UBI study, you can get the paper at [Writing Sample-UBI study](https://github.com/hjiangAnthony/Projects-for-Graduate-School/blob/main/Writing%20Sample-UBI%20and%20Crime%20Rate.pdf).

If you are interested in the Data Analysis projects about NYC COVID-19, you can get the report at 
[EconEX Report](https://github.com/hjiangAnthony/Projects-for-Graduate-School/blob/main/Writing%20Sample-EconEX%20Data%20Analysis.pdf)
and the slides at [EconEX Slides](https://github.com/hjiangAnthony/Projects-for-Graduate-School/blob/main/Writing%20Sample%20-%20EconEX%20Han%20Jiang%20Slides.pdf).

I provide brief summaries of the two projects as below:

## Project I: EconEX-Data Analysis

About the EconEX project:

>After learning that many summer internship programs were cancelled due to COVID-19, the Economics
>Department developed project ideas in collaboration with alumni and recruited alumni and
>faculty to serve as mentors so our students can explore potential careers and build skills for future jobs and
>internships. The goal of the program is to offer structured, professional learning opportunities for economics
>students to build marketable skills, knowledge, and experience under mentorship and guidance.

About my data analysis project: **COVID-19 Early Outbreak in NYC: Factors in High Community Infection Rate**

The main focus is on a neighborhood called `Corona` at early 2020. Despite the unfortunate coincidence of name with the Coronavirus, Corona has the 7th highest infection rate per capita among other areas in New York City, as well as a relatively high death rate. The demogrpahic information by race made this area noticeable, which also drew attention from the press such as the Guardian's report ([Corona in Corona](https://www.theguardian.com/us-news/2020/jun/15/coronavirus-corona-queens-ny-virus-shook-neighborhood)).

I spotted Corona by both sources from the press and data visualization. By comparing the distribution of ethnic minority and COVID-19 data, it indicated that non-white community had high rates of death, infection and hospitalization. 

<img width="800" height="400" src="https://github.com/hjiangAnthony/Projects-for-Graduate-School/blob/main/IMAGES/IMG-1.png"/>

Figure 1: COVID-19 data by ZIP code

<img width="500" height="400" src="https://github.com/hjiangAnthony/Projects-for-Graduate-School/blob/main/IMAGES/IMG-2.png"/>

Figure 2: Predominant race by tract

(As for programming tools, I used python for mapping and Stata for OLS regression.)

I argued that the contributors of this pandemic are not race but poverty, reliance on public transportation, lack of health insurance for employed labor, and community-wise inequality. The entire paper can be summarized as:
- Performed data visualization methods to estimate the impact from COVID-19 to NYC
- Developed OLS regression models to verify factors of certain high community case rates
based on independent research with methods like IV, DID and Partialling-out 
- Provided data analysis and a policy alternative matrix for NYC government

Based on my analysis, I also provided a policy alternative matrix (a common tool in public policy) for the NYC government, including short-term and long-term policy decisions.

<div align="center" >
<img width="500" height="300" src="https://github.com/hjiangAnthony/Projects-for-Graduate-School/blob/main/IMAGES/IMG-4.png" />
</div>

Data can be so deciptive that people might even draw opposite conclusions based on the same data. Through this project, I explored how to use statistical methods to test hypothesis and utilize regressional analysis for policy advising. This is a primary case of data analysis, which means it could get more complicated if the data reaches the level of Big Data. It is interesting and exciting to practice such analysis because it provides valuable information for policy decisions. I thus hope to proceed studies like this with a more advanced toolbox in data science. 

## Project II: Universal Basic Income and Its Effects on Economic Crime Rate

The background of this study is that:
>The Universal Basic Income (UBI) has been proposed since decades ago. As a proposal forcurrent redistribution system which is a reform of previous welfare policies. The goal of it is to reduce income gap, promote individual liberty, and alleviate the tensions from issues due to social-economic inequality in the society—especially the issue related to income inequality.

The author believed that UBI has positive effect in reducing the crime rates (i.e., robbery, illegal hunting, and burglar) by lessening the income gap, improving good future expectancy, and strengthening trust in the government & judiciary. The argument was supported with a mathematical tool called `UEC (UBI Effect on Crime Rates)`, which used linear regression method such that its mathematical expectation can be verified by existing studies about UBI.

The UEC model is designed based on the statistical models from Prof. Gary Becker and Fajnzylber et al. in their studies of crimes and economics.

One big challenge of this study was that there were limited empirical studies as a large sample to perform casual analysis. Countries like Namibia, Canada, India, and the U.S. had their own experiments, however, couldn't be simply compared together due to the diverse social-economic and cultural differences. In addition, the impact from UBI to crime rates also required tools in time-series analysis. The author used the first difference method to address the influence from time trends, and performed seperately to each experiments.

The conlusion is that: 
>Overall, the UBI effect predicted by UEC model is verified both in terms of economic conditions and different time scales. In developing countries, UBI seems to have relatively more instant and obvious effect in reducing poverty and economic crime rates. In long period, UBI is believed to be helpful in lessening poverty crime, though the amount of UBI is also a crucial factor to consider.

Indeed, the UBI study still lacks universal acknowledgement because it doesn't have sufficient empirical data--it is difficult, by nature, since UBI trails requires enormous investment. However, institutions like the United Nation Development and Programme (UNDP) is calling for methods of [Temporary Basic Income (TBI)](https://www.undp.org/content/undp/en/home/news-centre/news/2020/Temporary_Basic_Income_to_protect_the_worlds_poorest_people_slow_COVID19.html) to act against the COVID-19 for developing countries. I feel that my study can be of some help to their efforts to alleviate sufferings due to COVID-19, with knowledge of data science, economics and politics.

Thank you for your consideration in my application!
