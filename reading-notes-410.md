# Reading Notes for Class 13

- Explain to a non-technical recruiter what the Chat Example (above) does. The above exmaple works how AIM (AOL Instant Messenger) use to work. It enables you to chat in real time with someone.
- What proof of life are we getting on the backend from the above app? The backend it letting us know that a new user has connected. This can be done with a message saying "user connected" or "new user connect"
- Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket? This snippet  socket.broadcast.emit('hi'); allows us to send that message of hi to everyone but gives us the abiliy to choose which user we dont want to send the message to.

- What is a room and how might a room be useful? It is a virtual space where people can gather and talk in a group setting without having their conversation go server wide. It is very helpful when doing group projects, study groups or even for people playing the same game! 
- How do you join a room? You just need the socket for the specific room so that you can access it.
- How do you leave a room? There is nothing more than just leaving the room, the socket will disconnect itself.

- What is a Namespace and what does it allow you to do? A namespace is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it. Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries.
- Each namespace potentially has its own what? (hint: 3 things) EventHandlers, Middlerwares, and Rooms
- Discuss a possible use case for separate namespaces. It could make it more personalized for a company or maybe even for a group. That way only people that are associated or authorized to use that namespace can access it.

## Additional Information
