# friendly_chat_app
GOALS

understand firebase features
underMstand firebase tools & APIs
build a full-fledged Firebase-driven app
understand how to build iOS, Android & web versions

PRE-REQUISITES

understanding of what a mobile app is
comfortable using command line
comfortable calling web / cloud APIs
PROTOTYPE
Login screen (Google/Email)
View messages
Real-time send/receive

REQUIREMENTS

Database ==> to store messages
File Storage ==> to store media/attachments in message
App Server ==> to coordinate all these functions
Authentication ==> to know sender / receiver identity
Analytics ==> e.g., understanding user behaviors
Engagement ==> e.g., push notifications
Monetization ==> e.g., showing advertisements
All of this is plumbing. You really want to focus on the front-end and the user experience. Can you outsource the plumbing?

FIREBASE FEATURES

Firebase Realtime Database
Firebase Storage
Firebase Authentication
Firebase Analytics
Firebase Notifications
Firebase Remote Config (A/B testing)


SCAFFOLDING

Download Android Base Project or iOS Base Project and set up as follows:

Download zip file from one of the above links (here we cover Android)
Unzip into your local directory (creates directory and-nd-firebase... ) and rename to something simple (firecamp-friendlychat)
Open it in Android Studio (as an existing project) - make sure you fix any missing dependencies.
Run the emulator once to make sure the scaffolded app works
Now set up Firebase

Create new project in [Firebase Console] (https://console.firebase.google.com/?pli=1) -- I used firecamp-friendly-chat
Walk through the wizard for "Add Firebase to your Android App"
