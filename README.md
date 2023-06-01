# 911_Calls

#### to view html output, please visit: https://dgray4224.github.io/911_Calls/  

Modeling 911 calls in Montgomery County, Pennsylvania as a Poisson process

The state of Pennsylvania ranks right in the middle in crime of all 50 U.S. states. Finding data on crime in Montgomery county, Pennsylvania inspired me to further analyze the emergency 911 calls and generate reliable information for use in staffing law enforcement, 911 call operators, law enforcement administrators, and management. This analysis aims to model 911 calls as a homogenous and non-homogenous Poisson process, where we can find probabilities of 911 calls given certain conditions and accurately staff to respond promptly.  

The data used was from Kaggle.com, an online community platform where users can interact with one another, share datasets, projects, and other collaborations. The link
is here: https://www.kaggle.com/datasets/mchirico/montcoalert

The original dataset has 663,522 observations. After sub-setting by town, Lower Merion had 55,490 observations and East Greenville had 1,316 observations. The variables included latitude, longitude, description, zip code, title of 911 call, timestamp, township, address, and e. For the purposes of this study, I used only two variables: timestamp and township

The attached zip file includes: the code in R, the knitted html file, the powerpoint presentation, and the descriptive report of the project. 
