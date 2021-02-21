# wilsonHACK
UofTHacks VIII

Authors: Abinab Kumar Shresha, Adam Stecklov, Christina Ma, Daniel Wijaya

## Inspiration

As the quarantine has dragged on, more than a few of us discovered the unfortunate ability of time to act like a gas, escaping the neatly ordered confines of hours and days. In fact, nearly 40% of Canadians say they experienced a mental health decline due to COVID. In order to combat this, we sought to create an assistant to help people find some structure in their lives to maintain and improve mental health.

## What it does

Wilson’s aim is to keep your head above water during this global pandemic. He’s named after the volleyball that Tom Hanks talks to in the film Cast Away because he fulfills that same purpose. He keeps track of the friends you want to talk to, and the habits you want to keep. Wilson pushes you to stay in continual contact with each of these friends, and to pursue the habits that keep you mentally strong. He rotates through all your friends and habits, and urges you to contact different ones. On top of that, Wilson has an extensive voice script that makes him feel alive. He might say something sarcastic or even crack a joke, so watch out!

## How we built it

We used a web program called Voiceflow, which assists the rapid and collaborative design of voice applications for Google Assistant. We chose this medium because we wanted to make it as easy as possible for people to access and use - anyone with Google Assistant can easily access the assistant, with no downloads or additional signups. The application was constructed using Voiceflow code blocks, along with custom javascript code to add additional functionalities not fulfilled by Voiceflow. It was deployed using the Google Actions Console.

## Challenges we ran into

We faced many challenges while working on Wilson. 

Our biggest challenge as a team was learning to use Voiceflow. It took quite a bit of time to learn and then be able to develop a solid plan for the project since Voiceflow was a new tool to everyone on the team. 

The next challenge was testing our product on Google Assistant. We ran into issues that we did not have on Voiceflow. Substantial amount of time was spent running tests, identifying the causes of the issue and finding resolutions to these issues.

 An unexpected issue we encountered was deploying Wilson onto Google Assistant. We did not take into consideration that to publish for public use that it must be reviewed by the Google Team during our planning, so this would not be done in time during the judging process. We found a workaround which is to deploy as an Alpha option where only particular individuals can use it but we encountered issues on the site when completing this as well.

## Accomplishments that we're proud of

Overall, we are very proud of what we were able to accomplish in such a short time. Our team has very little experience with hackathons, and were able to work very well together, despite our different disciplines and levels of education. Moreover, we learned a lot - none of us had used the google voice platform nor the Voiceflow emulator, and despite this we were able to deploy a well-functioning product.

## What we learned

The main difficulty we faced was the different ways that the Voiceflow emulator and Google emulator runs the code. Most of our debugging was done directly on the Voiceflow platform, but there were numerous issues when we tested the system with the Google Actions Console Simulator. In the future, we know it is critical to test the system on the intended deployment platform.

## What's next for WilsonHACKS

Due to the time constraints, we were not able to completely flesh out all of our ideas. 

We wanted to make WIlson be more dynamic when responding to the user to simulate a person-to-person interaction. In the future, we would like to generate more natural responses for Wilson to say and be able take in free-form responses from the user. 

Moreover, we would have liked to be able to specify the frequency at which the user would like to be reminded of a specific habit or to talk to a certain person.

Another idea we could not complete was to keep track of the user’s progress in completing their habits and contacting their friends. In implementing this tracking system, we can extract various data to help the user by developing personalized suggestions or reminders that assist them in achieving their goals. 

Our next Major step for Wilson would be to track the users mood, as well as their “mental health” level. Based on this, we could specify different activities to complete or even suggest contacting professional help if required.

Another next step is to deploy Wilson for public use so that any individual that has Google Assistant can use Wilson. 
