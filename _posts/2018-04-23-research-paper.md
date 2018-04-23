# A Large-Scale Study of Mobile Web App Security

## Summary
Mobile web applications are highly popular as they can replace OS-specific apps, but have many security concerns and 
vulnerabilities that are not seen in “traditional web apps or mobile apps.” Out of nearly one million mobile web apps tested, 
“28% of the studied apps have at least one vulnerability…a conservative underestimate of the true vulnerability…” 
This is concerning as popular apps were amongst the 28% and app libraries themselves contain security problems. 
The most notable vulnerabilities which apply to desired functionality within our app are: Inter-App communication, 
which notifies a user about new messages or calls, and controlling navigation, which is what would load a user’s profile page, 
but may be blocked by WebView. These issues are concerning because they directly apply to the tasks we want users to complete. 

## Application to College Connect
We want to appeal to as many users as possible without platform discrimination with emphasis on Android and iOS as they are the
most popular mobile devices in the market. However, because users will enter personal information, the application needs to be 
extremely secure with minimal vulnerabilities. After reading this research paper, it is quite clear that creating a mobile web 
application is not the best solution. Building separate apps for iOS and Android devices is a better idea as it will allow us 
to have more control over certain functionalities - such as messaging and profile security - which will make users more 
comfortable using the app. It is important users know and understand the potential issues within our app. The importance of
effectively and clearly communicating this is nicely described by Dylan [here](https://dylan-martin.github.io/report/).

*Citation*

https://adamdoupe.com/publications/large-scale-study-of-mobile-web-app-security-most2015.pdf
