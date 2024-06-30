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
-> This project analyses the whatsapp text messages. The messages analysis can be done for both group chats and chats between two individuals<br/>
-> The user should upload the file that the user wants to analyze. To Analyze the messages, click on show analysis.<br/>
-> The statistics of the chat are shown on the site<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/5d53bc3b-3a0e-4020-9ce8-55578570a7a4)<br/>
-> Group dynamics like monthly timeline, daily timeline ae shown using graph<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/44bd221b-99c8-474c-8c96-77fcb3f8fc64)![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/2e5960f0-833e-4258-97b1-44881cf5b072)<br/>
-> The busiest day of the week and the busiest month of the year can be obtained using the bar plot.<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/2ecce064-6a8a-44f3-a466-9d88dc72826a)<br/>
-> seaborn library is used to obtain the weekly activity of the chat. The weekly activity map tells about when the members are more active in the chat and when they are least active<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/1cd76ff1-ab7d-4ef2-92c3-4dca32b16a13)<br/>
-> Most active members of the group can also be obtained and is presented in the form of bar graph. <br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/5f208630-51cc-4854-b3a9-aa9f079a3b4d)<br/>
->wordcloud library is used to get the image of most common words used in the group and display it in the form of the picture<br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/b947c368-365e-4769-8d42-4a6e95701ede)
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/b56255d6-0e3c-4b74-8738-6b3d869b129a)

->** __Note__ : I have used the 'app.py' code to deploy the app on streamlit as the 'app.py' did include the code for emoji analysis because stream does not support the emoji.UNICODE_EMOJI. But to get the emoji analyis, use the 'appEmoji.py' code as it works fine with any version of Python in the Pycharm environment**<br/>
-> the appEmoji.py contains the code of emoji analysis, which produces the result as follows:<br/><br/>
![image](https://github.com/sxnyx/Chat-Analyzer/assets/112766278/47e56489-5229-4d0e-8dd1-10d1ab740751)














