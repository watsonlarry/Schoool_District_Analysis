# School District Testing Analysis

## Overview

After preforming an analysis of standardized test scores and funding data for a school district (wish I could be more specific), the work is invalidated by evidence of academic chicanery. The reading and math scores for Thomas High School 9th graders seem to have been edited post-examination. To remedy this complication, we'll remove the Thomas High School 9th graders' test scores from the data and re-perform the analysis.

### Results

District Summary (w/ tainted Thomas High School data)

![district sum dirty](https://github.com/watsonlarry/Schoool_District_Analysis/blob/main/Resources/district%20data%20tainted.png)

District Summary (w/o tainted Thomas High School data)

![district sum clean](https://github.com/watsonlarry/Schoool_District_Analysis/blob/main/Resources/district%20data%20clean.png)
  
  Changes in the district summary after removing the compromised data are minimal. The overall passing percentage for students is only lowered by .3%. Not a surprise when only 460 students are removed from a data set of nearly 40,000 students.
  
Thomas High School Summary (w/ 9th Grade test scores)

![thomas dirty](https://github.com/watsonlarry/Schoool_District_Analysis/blob/main/Resources/thomas%20dirty.png)

Thomas High School Summary (w/o 9th grade test scores)

![thomas clean](https://github.com/watsonlarry/Schoool_District_Analysis/blob/main/Resources/thomas%20clean.png)

Looking at just the data from Thomas High School, the effects of the fraudulent tests are much more noticeable. The overall passing percentage drops 25% after the 9th grade scores are removed from the data set. It seems unlikely the removal of a quarter of the schools scores could have that immense an impact without some form of academic dishonesty. As a result, Thomas High School is no longer one of the top five schools in the district with regards to overall student passing rate. In fact the school plummets to the a performance postion near middle of the pack.

