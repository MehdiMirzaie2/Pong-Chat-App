[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=false&width=435&lines=Pong+%2F+Chat+Web+App)](https://git.io/typing-svg)

# :sparkles: What is This Project?

The aim of this project was to create a full-stack application with the following requirements:
<ul>
    <li>Responsive for all screen sizes</li>
    <li>Pong game with single and multiplayer modes</li>
    <li>Blockchain to store multiplayer game results</li>
    <li>OAuth 2 for user authentication</li>
    <li>Live chat for one-to-one and group conversations</li>
    <li>Allow users to update their profiles</li> 
</ul>

# Samples

<p>When users sign in, they are greeted with a welcome page:</p>

<img src="./images/welcome.png"></img>

<p>By navigating to the Home page, users are directed to their profile page. Here, they can view their friends, blocked users, and more:</p>

<img src="./images/profile.png"></img>

<p>Users can search for other users by navigating to the Search page and typing a friend's username. The search is handled in the backend, and each letter typed triggers an API call to update the friend list:</p>

<div style="display: flex; flex-direction: row; justify-content: space-between;">
    <img src="./images/firstfriend.png" width="500" height="400"></img>
    <img src="./images/listusers.png" width="500" height="400"></img>
</div>

<p>By navigating to the Messages page, users can view their messages for both one-on-one and group chats. If a room is one-on-one, the room name will be the friend's name. Group chats can have custom names, which the group can update. </p>

<p>As WebSockets power the chat system, it is possible to track when friends are online. For example, if users are active in a group, the group name turns green:</p>

<div style="display: flex; flex-direction: row; justify-content: space-between;">
    <img src="./images/chatnoroomselected.png" width="500" height="400"></img>
    <img src="./images/chat1-1.png" width="500" height="400"></img>
    <img src="./images/chatgroup.png" width="500" height="400"></img>
</div>

<p>All users in a group chat can update the group name and image. However, only the group admin can remove members or delete the group:</p>

<img src="./images/groupchatupdate.png"></img>

<p>By navigating to Local, users can play a Pong game locally. Player 1 uses the W and S keys, while Player 2 uses the O and L keys to play the match:</p>

<div style="display: flex; flex-direction: row; justify-content: space-between;">
    <img src="./images/pongstart.png" width="500" height="400"></img>
    <img src="./images/pongingame.png" width="500" height="400"></img>
</div>

# :computer: Tech Stack

<div style="display: flex; align-items: flex-start;">
    <img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="TypeScript" width="65" height="65" />
    <img src="https://techstack-generator.vercel.app/django-icon.svg" alt="Django" width="65" height="65" />
    <img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="REST API" width="65" height="65" />
    <img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="Docker" width="65" height="65" />
    <img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="Nginx" width="65" height="65" />
    <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="65" height="65" />
    <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" width="65" height="65" />
    <img src="https://user-images.githubusercontent.com/25181517/117208740-bfb78400-adf5-11eb-97bb-09072b6bedfc.png" width="65" height="65" alt="PostgreSQL" title="PostgreSQL"/>
</div>

# :construction_worker: How to Run

<ul>
    <li>Ensure Docker is installed on your machine.</li>
    <li>Clone this repository and navigate to the folder:</li>
</ul>

```bash
git clone https://github.com/MehdiMirzaie2/Pong-Chat-App
cd Pong-Chat-App
