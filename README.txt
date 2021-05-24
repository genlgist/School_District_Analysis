# PyCity_Challenge_Analysis

Regina Negrycz 
genglist@yahoo.com 
Module 4 Challenge 
Submitted 23 May 2021 
Due 23 May 2021 
https://github.com/genlgist/School_District_Analysis/blob/main/Resources/schools_complete.csv 
https://github.com/genlgist/School_District_Analysis/blob/main/Resources/students_complete.csv
README.md

# Overview of School District Analysis
I needed to use the Pandas loc method and conditional statements with comparison and logical operators to select the ninth-grade reading and math scores for Thomas High School. I then had to use the Pandas NumPy module to change the reading and math scores to NaN.

# School District Results

• How is the district summary affected?
	Thomas High School had 461 students in the 9th grade.  The replacement of those grades with NaN had the following changes:
	Average math score went from 79 to 78.9
	Average reading score went from 81.2 to 81.9
	The % passing math went from 75.0 to 74.8
	The % passing reading went from 85.8 to 85.7
	The % overall passing went from 65.1 to 64.9
With Thomas High School 9th grade:
	Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	39170	24649428	78.985371	81.87784	74.980853	85.805463	65.172326

Without THS 9th grade: 
	Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	39,170	$24,649,428.00	78.9	81.9	74.8	85.7	64.9

• How is the school summary affected?
o	THS’s passing math % went to 93.185690 from 66.911315.
o	THS’s passing reading % went to 97.018739 from 69.663609
o	THS’s passing overall % went to 90.630324 from 65.076453.
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	93.185690	97.018739	90.630324

• How does replacing the 9th graders' math and reading scores affect Thomas High School's performance relative to the other schools?
	THS went from being in the 60th percentile for math, reading and passing to the 90th percentiles for the 3 categories.
	
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Bailey High School	District	4976	$3,124,928.00	$628.00	77.048432	81.033963	66.680064	81.933280	54.642283
Cabrera High School	Charter	1858	$1,081,356.00	$582.00	83.061895	83.975780	94.133477	97.039828	91.334769
Figueroa High School	District	2949	$1,884,411.00	$639.00	76.711767	81.158020	65.988471	80.739234	53.204476
Ford High School	District	2739	$1,763,916.00	$644.00	77.102592	80.746258	68.309602	79.299014	54.289887
Griffin High School	Charter	1468	$917,500.00	$625.00	83.351499	83.816757	93.392371	97.138965	90.599455
Hernandez High School	District	4635	$3,022,020.00	$652.00	77.289752	80.934412	66.752967	80.862999	53.527508
Holden High School	Charter	427	$248,087.00	$581.00	83.803279	83.814988	92.505855	96.252927	89.227166
Huang High School	District	2917	$1,910,635.00	$655.00	76.629414	81.182722	65.683922	81.316421	53.513884
Johnson High School	District	4761	$3,094,650.00	$650.00	77.072464	80.966394	66.057551	81.222432	53.539172
Pena High School	Charter	962	$585,858.00	$609.00	83.839917	84.044699	94.594595	95.945946	90.540541
Rodriguez High School	District	3999	$2,547,363.00	$637.00	76.842711	80.744686	66.366592	80.220055	52.988247
Shelton High School	Charter	1761	$1,056,600.00	$600.00	83.359455	83.725724	93.867121	95.854628	89.892107
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	93.185690	97.018739	90.630324
Wilson High School	Charter	2283	$1,319,574.00	$578.00	83.274201	83.989488	93.867718	96.539641	90.582567
Wright High School	Charter	1800	$1,049,400.00	$583.00	83.682222	83.955000	93.333333	96.611111	90.333333

• How does replacing the 9th grade scores affect:
	Math & reading scores by grade
		THS went from being in the 60th percentile for math, reading and passing to the 90th percentiles for the 3 categories.
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	93.185690	97.018739	90.630324

	Scores by school spending
		THS’s average spending per student is $638 which puts it in the $616-$645 range.   It was previously in the $630-$644 range.
o	From:
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.418349	83.848930	1525	1591	90.948012	$630-644

o	To:
	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Spending Ranges (Per Student)					
<$585	83.455399	83.933814	93.460096	96.610877	90.369459
586−586−615	83.599686	83.885211	94.230858	95.900287	90.216324
616−616−645	79.067990	81.899294	71.274736	81.499026	61.800133
646−646−675	76.997210	81.027843	66.164813	81.133951	53.526855


	Scores by school size
o	From:
	Student ID	reading_score	math_score	School ID	size	budget
school_name						
Thomas High School	38352.0	83.848930	83.418349	14.0	1635.0	1043130.0
o	To:
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	93.185690	97.018739	90.630324

		Scores by school type
o	From:
	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Type					
Charter	83.473852	83.896421	1428.250000	1473.125000	90.432244
o	To:
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	93.185690	97.018739	90.630324



##Summary - Four changes after replacing THS 9th with NaNs
Average math score went from 79 to 78.9
	Average reading score went from 81.2 to 81.9
	The % passing math went from 75.0 to 74.8
	The % passing reading went from 85.8 to 85.7
	The % overall passing went from 65.1 to 64.9