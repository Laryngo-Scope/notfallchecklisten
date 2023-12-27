# notfallchecklisten
#### Video Demo:  
#### Description:
This is a simple yet important app for me and my colleagues. I work at a university hospital in germany as a doctor. I also work as one of many emergency physicians in our municipalty of Tübingen. We have a on-call emergency doctor service, where we get called for certain difficult or special pre-hospital emergencies. 
I know from my expirience, that it is very important to use checklists, especially in emergency cases with changing teams (we never know who the paramedics are, we will work with in any case). 
I wanted to build an easy to use and easy to maintain app for having certain checklists always with me on my phone.
The most important goals were:
- easy to use!
- easy maintainance, even for non techy colleagues (for example, you can add and change checklists only by changing the corresponding database table with a GUI-Tool of my web-hosting-service like phpmyadmin)
- offline availiability (can not be just a web-app. there needs to be an offline "container" which is getting the most recent web-app-site version once a week or so)
- simple design, no bugs!

This prototype version contains two parts:
- The Web App
- An Android App serving as the offline version on my phone

In future versions I plan to implement following features:
- An iOs version of the Offline App
- A checklist editor with login/security
- Having a second site per checklist with schematics, flow-charts and so on
