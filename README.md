# FCM-with-dynamic-fuzzifier

Hello everyone,

I would like to present this version of the well known Fuzzy C-Means (FCM) algorithm which is implemented based on the research papers listed below. 

1. http://vlxxtv.lnkiy.in/The_range_of_the_value_for_the_fuzzifier_of_the_fuzzy_c-means_algorithm
2. http://vlxxtv.lnkiy.in/On_the_selection_of_m_for_Fuzzy_c-Means

FCM is one of the most prominent algorithms for fuzzy clustering developed by J. C. Bezdek. But this algorithm suffers from two drawbacks, first is the selection of the no of clusters apriori and the next is the selection of the fuzzifier value, also known as ‘m’. This fuzzifier value is very important as it determines the level of fuzziness of any clustering. But selecting a value of the fuzzifier beforehand is not possible all the time. On the other hand, the quality of clustering depends on the value of this fuzzifier to a great extent.

This version of the FCM algorithm solves the above-mentioned problem. Based on the membership value of the cluster centers and mass center it determines a range of the fuzzifier value. Then it checks the clustering quality( we are using xie-beni index for quality check) through out the range and outputs the best clustering results along with the optimal value of the fuzzifier.

If any further clarification is needed, please reach out to me on Linkedin or github.

Linkedin profile link : www.linkedin.com/in/koustav-pal-aa60b01a1
