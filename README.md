# Web Streaming Application
A multiple window video streaming and chatting application.


# *Creating a Session*
 When you connect to an OpenTok session on an app, you specify the session you want to connect to using an OpenTok session ID. Each session ID identifies a unique OpenTok session. You can think of a session as a room in which participants meet and chat.

The number of sessions you create and how clients connect to them depend upon the requirements of your app. If your app connects users with one another for a one-time , create a unique session for that meeting. However, if your app connects users over various days in the same "room," then you can create one session and reuse it. If one group of users meet with each other, while other groups meet independently, create unique sessions for each group.

OpenTok sessions do not expire. However, authentication tokens do expire. Also note that sessions cannot explicitly be destroyed.
