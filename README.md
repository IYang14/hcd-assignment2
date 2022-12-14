# hcd-assignment2
For this assignment, I checked the data bias that occurred in the toxic comments dataset. Specifically, I selected the 'toxic' and 'insult' subset and would like to check whether writing comments in lowercase or uppercase would affect the toxic score the comments in this subset got from the model. 

As people generally prefer using uppercase to show off their strong emotions in online conversation, usually for expressing feelings, conveying opinion or arguing with others, my hypothesis for the test is that uppercase form toxic comments would get a higher toxic score from the system.

**Test description**:\
The test is divided into two parts. In the first part, I tested the most popular swearwords being used in tweets that contain toxic and insult content on Twitter. I checked their toxic score in lowercase and uppercase forms. \
 Resource: https://www.fastcompany.com/3026596/140-characters-of-fck-sht-and-ss-how-we-swear-on-twitter

The second part is to test some samples from the subsets I targeted to check. By randomly choosing 10 samples from the subset, the sample comment would go through the toxicity test in both lowercase and uppercase form. 

**Result**:\
Among the total of 20 samples, most of them had a higher toxicity score when writing in the uppercase. Some of the sample even over the threshold (0.919526) after it switched to the uppercase, which had a lower score than the threshold in the lowercase. 

But there is still a false rate of 25%, that the some numbers have a different result than what I predicted in the hypothesis. I found out that swearwords that less common and are not that direct insulting have a much lower score (around 0.3~0.4), comparing with others like f word (0.9017833). The comments that contain such swearwords would also have a lower score in uppercase writing compared with what they got in lowercase form. 

However, since the sample number in the test is pretty small, the result may not be very accurate. To improve the test, one way could be to expand the numbers of samples. 
