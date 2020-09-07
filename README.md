# HackAttack
## Inspiration
Cybercrime is the use of a computer as a weapon for committing crimes such as committing fraud, identity theft, or breaching privacy. It is abominable to see that the same technology which has been a boon to humankind is also being misused by cybercriminals. In today's time with data being the biggest leverage. We have tried to combine Machine learning and AI-powered techniques to develop data-driven solutions for Cybersecurity problems by building a web-based application - HackAttack to tackle cyber crimes.

## What it does
HackAttack focuses on three different cyber attacks.
Anomaly detection - Used machine learning techniques like SVM along with python Voila to create a dashboard that alerts network administrators and security experts when a network is potentially under attack.
Password strength - Uses an advanced algorithm created in JavaScript that takes a password as an input and returns how long that password could be used before it is considered unsafe.
Phishing URL detection - Used Machine techniques like feature extraction that extracts features from the URL to help classify them into phishing and legitimate URL.
How we built it
This web page runs the python program consisting of machine learning models for phishing URL and anomaly detection and JavaScript program for detecting password strength in the back-end via flask App The front-end of this application has been built using HTML, CSS and JavaScript.

## Challenges we ran into
While working on Anomaly Detection,we were dealing with unlabeled data which turned out to be a challenging task. Training and optimization for anomaly detection was a time-consuming process.Figuring out which model works the best for anomaly detection was also demanding. We also had to brainstorm a way to determine how strong a password is correlating it to number of days. While working on phishing detection, we had to decide which features should be taken into account while classifying it into phishing or legitimate URL's. Also,we encountered a few obstacles while deploying flask app and voila dashboard on Heroku app.

## Accomplishments that we are proud of
We learned a couple of things starting from integrating HTML,CSS and JavaScript to create a functioning site. It was the first time we worked on Voila dashboard and how quickly we were able to deploy it. We are also proud of the fact that for many of us it was our first hackathon, and all that we learned truly helped in expanding our knowledge!

## What we learned
Throughout the development of this project, we learned a lot. On technical aspect, we learned how to deployed flask app on Heroku. Also, we learned how to create a voila dashboard for anomaly detection. It also taught us how crucial security is in cyber world. Most of all, we learned that through perseverance and determination, you can make progress towards helping to solve problems in the world, even if you don't initially think you have the resources or knowledge. Working with the group helped us to identify our strengths and weaknesses, and with focus and collaboration we were able to solve all the challenges faced.

## What's next for HackAttack
mail/text alerts sent out when the password needs to be updated or creating a password manager.
For anomaly detection, our next step will be to do the detection for real-time data.
Including details like name, domain and location of the URL while detection malicious websites.

## Try out our website
http://howdycyberhack.herokuapp.com/
