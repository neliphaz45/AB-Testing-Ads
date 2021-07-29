# AB-Testing-Ads
This is a Machine Learning project on using A/B Hypothesis Testing technique to evaluate Ad campaign performance 

This project is about the advertising company that is running an online ad for a client with the intention of increasing brand awareness. The advertiser company earns money by charging the client based on user engagements with the ad it designed and serves via different platforms. To increase its market competitiveness, the advertising company provides a further service that quantifies the increase in brand awareness as a result of the ads it shows to online users. The main objective of this project is to test if the ads that the advertising company runs resulted in a significant lift in brand awareness. 

The two categories are: 
Control: users who have been shown a dummy ad
Exposed: users who have been shown a creative (ad) that was designed by SmartAd for the client. 


The data collected for this challenge has the following columns: 
auction_id: the unique id of the online user who has been presented the BIO. In standard terminologies this is called an impression id. The user may see the BIO questionnaire but choose not to respond. In that case both the yes and no columns are zero.
experiment: which group the user belongs to - control or exposed.
date: the date in YYYY-MM-DD format
hour: the hour of the day in HH format.
device_make: the name of the type of device the user has e.g. Samsung
platform_os: the id of the OS the user has. 
browser: the name of the browser the user uses to see the BIO questionnaire.
yes: 1 if the user chooses the “Yes” radio button for the BIO questionnaire.
no: 1 if the user chooses the “No” radio button for the BIO questionnaire.
