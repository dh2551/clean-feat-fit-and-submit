
# Goal
Every year, approximately 7.6 million companion animals end up in shelters. While many of these animals were able to find their forever homes, just as many are not so lucky--nearly 3 millions of dogs and cats are euthanized in the US every year, according to ASPCA. 

For this project, we selected the Shelter Animal Outcomes ADS competition that aims to help shelters predict and improve the outcomes for their animals. The data we will be using comes from the Austin Animal Center, collected from October 1st, 2013 to March, 2016. We will use the code from Julien Heiduk, the bronze winner of this competition. 

The goal for this ADS is to help us understand trends in animal outcomes, and help shelters focus their energy on specific animals who need extra help finding a forever home. However, this ADS leads to some ethical concerns such as the expeditions of euthanization, or prolonged shelter/foster stay for certain types of animals. The model may encounter fairness issue such as pre-existing bias about certain dog breeds, which can be negatively reinforced by the model decision. Related topics also include missing values in the process of data cleaning, data classification and technical biases in the machine learning model. 

# Findings and Implications
We would not be very comfortable deploying this ADS in the public section or in the industry. There are some ethical concerns regarding animal welfare, as this tool can potentially decide the future of an abandoned animal. The model shows better performance for cats than dogs which brings concern to the fairness of this model. The model is also trained on data with pre-existing bias, where most dogs labeled aggressive are pit bulls. Some features should also be considered removed, such as “aggressive” which is mostly targeted towards certain breeds.  Hence, many “aggressive” behavior in animals are caused by lack of training or anxiety of a new environment, which shouldn’t be an important feature in the model. 
