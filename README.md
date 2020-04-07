<div align="center">
    <img src="/assets/beatsharer.png" width="200"/>
</div>
<h1 align="center">Beatsharer</h1>

<p align="center">
Beatsharer is a platform where creative individuals are able to collaborate together to create unique and interesting songs. Users are able to listen to whatever combination of tracks they want to listen to. 
</p>

<h2>Functional Requirements</h2>
<ul>
    <li>Login/Register</li>
    <li>Create Collaborations</li>
    <li>Upload Audio Files to Contribute to Collaborations</li>
    <li>Mix and Match Different Combinations of Contributions</li>
    <li>Create User Profiles</li>
</ul>
<h2>Non-Functional Requirements</h2>
<ul>
    <li>Error Handling and Validation</li>
    <li>Password Encryption</li>
    <li>Support Various Screen Sizes</li>
</ul>

<h2>Technologies and DevOps Used</h2>
<ul>
    <li>PERN (PostgreSQL, ExpressJS, ReactJS, and NodeJS)</li>
    <li>Utilizes Heroku for web hosting</li>
    <li>Utilizes AWS S3 for file hosting</li>
    <li>Source Control with Git and pushed to Github</li>
</ul>

<h2>Diagrams</h2>
<img src="/assets/auth.png"/>

<h2>Risks and Challenges</h2>
<ul>
    <li>
        redux-persist: I had a lot of trouble getting this library to work in my application and was able to fully incorporate it by furiously searching Google and ultimately found what I was looking for.
    </li>
    <li>
        react-beautiful-dnd: This library allows the application to click and drag elements and took me two weeks to realize that I mispelled an attribute which was constantly crashing my application.
    </li>
    <li>
        Hosting: Hosting the application in Heroku was fairly easy, but getting the production database up and running was frustrating. I had realized that my local machine was running PostgreSQL v.11 and Heroku uses v.12. So I had to delete the production DB and create a new one with a reverted version.
    </li>
</ul>

<h2>The Road Ahead</h2>
<p>
    There are many features that I still want to add into this application that could not be added during the duration of my last semester. Some of the features that were taken out of scope temporarily were commenting on collabs, favoriting collabs and contributions, liking contributions, and user roles. There are also plans to make the user interface look and function more like a traditional Digital Audio Workspace (DAW).
</p>
<p>
    Each of these functionalities has their own possible issues but could be solved by having more time than I do now.
</p>
