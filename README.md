# Chat-Analyzer

Working model link : (https://chat-analyzer-sanyasinghproject.streamlit.app/)<br/>

**Libraries required**

-streamlit<br />
-matplotlib<br />
-seaborn<br />
-urlextract<br />
-wordcloud<br />
-pandas<br />
-counter<br />
-emoji<br />


**About The Project**<br/>
-> This project analyzes WhatsApp text messages, encompassing both group chats and individual conversations. <br/>
->Users are required to upload the desired file for analysis and click on "Show Analysis" to proceed. The statistical data of the chat is displayed on the site.<br/>
-> The statistics of the chat are shown on the site<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/5d53bc3b-3a0e-4020-9ce8-55578570a7a4)<br/>
-> Group dynamics, including monthly and daily timelines, are illustrated using graphs.<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/44bd221b-99c8-474c-8c96-77fcb3f8fc64)![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/2e5960f0-833e-4258-97b1-44881cf5b072)<br/>
-> The busiest day of the week and the busiest month of the year are determined using bar plots.<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/2ecce064-6a8a-44f3-a466-9d88dc72826a)<br/>
-> The Seaborn library is utilized to create a weekly activity map, highlighting periods of high and low activity within the chat.<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/1cd76ff1-ab7d-4ef2-92c3-4dca32b16a13)<br/>
->The most active members of the group are identified and presented in bar graph format. <br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/5f208630-51cc-4854-b3a9-aa9f079a3b4d)<br/>
->The WordCloud library is used to generate an image of the most common words used in the group.<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/b947c368-365e-4769-8d42-4a6e95701ede)
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/b56255d6-0e3c-4b74-8738-6b3d869b129a)

->**Note**: *The 'app.py' code is used to deploy the app on Streamlit, but it does not include emoji analysis due to Streamlit's lack of support for emoji.UNICODE_EMOJI. For emoji analysis, use the 'appEmoji.py' code, which works with any Python version in the PyCharm environment.*<br/><br/>
-> The 'appEmoji.py' script produces results as shown below:<br/>

![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/47e56489-5229-4d0e-8dd1-10d1ab740751)














