[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=false&width=435&lines=Pong+%2F+Chat+Web+App)](https://git.io/typing-svg)

# :sparkles: What is This Project?
The aim of this project was to create a full stack applicaiton, with the following requierments:
<ul>
    <li>Responsive for all screen sizes</li>
    <li>Pong single, and multiplayer</li>
    <li>Block chain, to store multiplayer game results</li>
    <li>OAuth 2, for user authentication</li>
    <li>Live chat, one-to-one, and groups</li>
    <li>Enable users to update their profiles</li> 
</ul>

# Samples

<p>When users sign in, they are greated with a welcome page</p>

<img src="./images/welcome.png"></img>

<p>Navigating to Home, will take the user to there profile page. This is where the user can view their friens, blocked user list, and etc.</p>

<img src="./images/profile.png"></img>

Users can search other users with by navigating to Search, and typing their friends username. The search is done in the backend, each letter that is typed will cause an API call to update the list of friends.</p> //make the following two images side by side

<img src="./images/firstfriend.png" width="500" height="400"></img>
<img src="./images/listusers.png" width="500" height="400"></img>
    
Navigating to Messages, the user the can view their messages both one-on-one and group chats. If a room is one-on-one, the room name will be the friends name. Group chats can have any name they choose, and the group can update it.
As websockets are used to build the chat system, it was possible to track when friends were online, As seen below if users are active within a group the group name will turn green.

<img src="./images/chatnoroomselected.png" width="500" height="400"></img>
<img src="./images/chat1-1.png" width="500" height="400"></img>
<img src="./images/chatgroup.png" width="500" height="400"></img>

<p>All users within a groupchat can update the group name and image, However, only the group admin can remove others and delete the group.</p>

<img src="./images/groupchatupdate.png"></img>

<p>Navigating to Local users can play a pong game locally, meaning that player1 will user W,S keys and player2 will user O,L keys to play the match</p>

<img src="./images/pongstart.png" width="500" height="400"></img>
<img src="./images/pongingame.png" width="500" height="400"></img>

# :computer: This Project Tech Stack
<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="icon" width="65" height="65" /><img src="https://techstack-generator.vercel.app/django-icon.svg" alt="icon" width="65" height="65" /><img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="65" height="65" /><img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="icon" width="65" height="65" /><img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="icon" width="65" height="65" /><img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="65" height="65" /><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="65" height="65" /></div>

# :construction_worker: How to Run

You will need to Docker installed on your machine.
Clone this repo
```
    git clone https://github.com/MehdiMirzaie2/Pong-Chat-App
```


# :bug: Issues

Please feel free **to create a new issue** with its title and description on the issues page of the [webserv](https://github.com/MehdiMirzaie2/42-webserv/issues) Repository. If you have already found the solution to the problem, **I would love to review your pull request**!


To help me out, and if you think this repo is helpful give ⭐️
