# School_District_Analysis

**Overview of the school district analysis**
The purpose of this analysis was to determine average math & reading test scores, in addition to exam passing rates, at 15 high school in the district.  To provide further context, the budget, size (number of students), and type of school were taken into consideration.  Lastly, exam scores for ninth graders at Thomas High School appeared to be altered, so the affected data was deleted and re-analyzed.

**Results**
In the original analysis of data (with altered Thomas High School ninth grade scores), the following metrics were calculated for the entire district:
![image](https://user-images.githubusercontent.com/99574730/156948752-b702afca-6061-4035-b3d6-215e2ec4fc54.png)

However, after removing suspect scores, the following metrics were obtained for the district:
![image](https://user-images.githubusercontent.com/99574730/156948774-694072a1-0bbd-4285-8daa-1e211d7a1463.png)

Although there is a small difference (65.17% passing with the suspect scores vs. 65% with the suspect scores removed), it is negligible due to the small proportion of Thomas High School ninth-grade students in the entire population of high schoolers in the district.

For Thomas High School, the average test scores (including altered scores) are shown below:
![image](https://user-images.githubusercontent.com/99574730/156948006-b88246c0-3aaa-487a-9781-5de44b3e56af.png)

After removing suspect scores, however, the following Thomas High School metrics were obtained:
![image](https://user-images.githubusercontent.com/99574730/156948204-ff4e0b28-dc84-4d2a-b7bb-9dbd8e364815.png)


When reducing our scope to Thomas High School rather than the entire district, the true impact of removing altered test scores can be observed.  While Thomas High School originally had an overall 90.94% passing rate, the adjusted overall pass rate is ~65%.  More specifically, Thomas High School had an average math pass rate of 93.3% and reading pass rate of 97.3% originally.  After removing altered scores, however, Thomas High School's average math pass rate was 66.9% and reading pass rate was 69.7%.  In other words, removing the suspect scores caused a 27.6% drop in the reading pass rate, and a 26.4% drop in the math pass rate.  Although Thomas High School was previously included in the five highest-performing high schools in the district, its adjusted pass rate of 65% removes it from that category.

**Summary**
After replacing the altered Thomas High School scores, the following four changes were observed:
1. As seen above, Thomas High School's pass rate decreased significantly from 91% to 65%.
2. More specifically, reading pass rates and math pass rates were significantly reduced.
3. Thomas High School was no longer ranked in the top-performing high schools.
4. All ninth-grade students at Thomas High School have "NaN" listed as their math and reading scores, rather than actual scores.
