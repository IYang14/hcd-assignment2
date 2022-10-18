# hcd-assignment2
For this assignment, I checked the data bias that occurred in the toxic comments dataset. Specifically, I selected the 'toxic' and 'insult' subset and would like to check whether writing comments in lowercase or uppercase would affect the toxic score the comments in this subset got from the model.

As people generally prefer using uppercase to show off their strong emotions in online conversation, usually for expressing feelings, conveying opinion or arguing with others, my hypothesis for the test is that uppercase form toxic comments would get a higher toxic score from the system.

**Test description**:\
The test is divided into two parts. In the first part, I tested the most popular swearwords being used in tweets that contain toxic and insult content on Twitter. I checked their toxic score in lowercase and uppercase forms. \
 Resource: https://www.fastcompany.com/3026596/140-characters-of-fck-sht-and-ss-how-we-swear-on-twitter

The second part is to test some samples from the subsets I targeted to check. By randomly choosing 10 samples from the subset, the sample comment would go through the toxicity test in both lowercase and uppercase form. 

**Result**:\
Among the total of 20 samples, most of them had a higher toxicity score when writing in the uppercase. But there is still a false rate of 25%, that the some numbers have a different result than what I predicted in the hypothesis. However, since the sample number in the test is pretty small, the result may not be very accurate. To improve the test, one way could be to expand the numbers of samples. 
