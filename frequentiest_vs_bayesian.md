## Which statistical approach to use to run an A/B test?  
Post learning about four different types of A/B testing experimentation methods, it’s equally important to understand which statistical approach to adopt to successfully run an A/B test and draw the right business conclusion.  
Ideally, there are two types of statistical approaches used by A/B/n experimenters across the globe: Frequentist and Bayesian. Each of these approaches has its own pros and cons.  

**Frequentist approach:**  
The frequentist approach of probability defines the probability of an event with relation to how frequently (hence the name) a particular event occurs in a large number of trials/data points.  
When applied to the world of A/B testing, one can see that anyone going with the frequentist approach would need more data (a function of more number of visitors tested and over longer durations) to come to the right conclusions.  
This is something that limits you in scaling up any A/B testing effort.  
According to the Frequentist approach, it is essential to define your A/B test’s duration based on sample size to reach the right test conclusions. The tests are based on the fact that every experiment can be repeated infinite times.  
Following this approach calls for a lot of attention to detail for every test that you run because for the same set of visitors, you’ll be forced to run longer duration tests than the Bayesian approach.  
Hence, each test needs to be treated with extreme care because there are only a few tests that you can run in a given timeframe.  
Unlike Bayesian statistics, the Frequentist approach is less intuitive and often proves difficult to understand.  

**Bayesian approach:**  
As compared to the Frequentist approach, Bayesian statistics is a theory-based approach that deals with the Bayesian interpretation of probability, where probability is expressed as a degree of belief in an event.  
In other words, the more you know about an event, the better and faster you can predict the end outcomes. Rather than being a fixed value, probability under Bayesian statistics can change as new information is gathered.  
This belief may be based on past information such as the results of previous tests or other information about the event.   
Unlike the frequentist approach, the Bayesian approach provides actionable results almost 50% faster while focusing on statistical significance.  
At any given point, provided you have enough data at hand, the Bayesian approach tells you the probability of variation A having a lower conversion rate than variation B or the control. It does not have a defined time limit attached to it, nor does it require you to have an in-depth knowledge of statistics.  
In the simplest of terms, the Bayesian approach is akin to how we approach things in everyday life.  
For instance, you misplaced your mobile phone in your house.  
As a frequentist, you would only use a GPS tracker to track it and only check the area the tracker is pointing to.  
While as a Bayesian, you will not only use a GPS tracker but also check all the places in the house you earlier found your misplaced phone.  
In the former, the event is considered a fixed value, while in the latter, all past and future knowledge are utilized to locate the phone.  

Analysis Process with Bayesian Approach  
<img width="500" src="https://user-images.githubusercontent.com/125619716/230523468-abad39df-36ec-459b-8754-76e47e541f19.png">  


### Difference between Frequentist and Bayesian  

| Frequentist | Bayesian |
| ------ | -------- |
| Frequentist Statistics follow the ‘Probability as Long-Term Frequency’ definition of probability. | Bayesian Statistics follow the notions of ‘Probability as Degree of Belief’ and ‘Logical Probability.’ |  
| In this approach, you only use data from your current experiment. The frequentist solution is to conduct tests and draw conclusions. | In this approach, you use your prior knowledge from the previous experiments and try to incorporate that information into your current data. The Bayesian solution is to use existing data to draw conclusions. |  
| Give an estimated mean (and standard deviation) of samples where A beats B but completely ignores the cases when B beats A. | It takes into account the possibility of A beating B and also calculates the range of the improvement you can expect. |  
| Requires the test to run for a set period to get correct data from it but can’t figure out how close or far A and B actually are. It fails to tell you the probability of A beating B. | Gives you more control over testing. You can now plan better, have a more accurate reason to end tests, and get into the nitty-gritty of how close or far apart A and B are. |  









