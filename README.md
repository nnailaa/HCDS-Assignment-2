# HCDS-Assignment-2

I have learned about the perspective API and how to use it to score tests to better know how people will interpret them online. With the API, I noticed certain words and phrases that I personally would find particularly offensive had very little effect on the API. Many of the threats comments were related to forms of physical and sexual assault, but the score was about the same as just profanities. I believe this might have to do with the training data for the APi - it might not include as many strings of words for threats as for other toxic content online - profanities were significantly more frequent in the regular dataset.

This assignment raises several questions over data testing, such as what approach would we use if we wanted to look at the difference with capitalizing words? I wasn't sure if just using ASCII and capitalizing the entire comments to test them again was the best solution, it seemed rather inefficient. 

My results showed that there is a difference in the commonly found words in the content considered threatening and hatefull towards particular identities. It also showed that, while the API algorithm is often close to predicting the toxicity score, it overlooks certain words or phrases or considers them not as harmfull.


I have unfortunately also learned the limits of my computer capabilities - Jupyter Notebook freezes Chrome or Microsoft Edge after about 60 iterations through the loop with 1 second sleep time (the app stops responding).
