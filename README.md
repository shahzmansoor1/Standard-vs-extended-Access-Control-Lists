# Standard-vs-extended-Access-Control-Lists
In this lab, I go over how to configure Access Control Lists, and the main difference between them.


Let's get started!

When it comes to access-control, the main thing to implement on a network is an access-control list. This security method consists of two different types of access-control lists. Standard and Extended.


**Standard Access-Control Lists**

Standard access-control lists, when implemented block a specific device or nework from gaining any sort of access to a specific resource.

For example, I implented an access-control list that denies one specific ip address in a network rom gaining access to another network, while allowing every other to get access:

<img width="542" height="140" alt="image" src="https://github.com/user-attachments/assets/09123e14-e0c0-4c8c-8272-a98e4d3f44e1" />

This pc was in a network that consisted of two different PCs. One was unable to ping PC's in the network connected to the specified interface, while the other was able to get access:

<img width="505" height="175" alt="image" src="https://github.com/user-attachments/assets/74f0026a-8c87-4327-a6ce-0e1c30bf2ffb" />


<img width="497" height="182" alt="image" src="https://github.com/user-attachments/assets/e7240ef0-9c36-4888-8bb3-1be7488f29f9" />


See that is a good way to allow or block traffic. However, what if yo have a server that hosts multiple resources and you want to eny only one specific one while allowing allowing every other service to be accessible?

This is where Extended Access-Control lists come in!


**Extended Access-Control Lists**

An extended access-control list allows you to specify which port(s) and on which network you want to allow or deny for a specific ip address. This can be very useful if you want a server to not have access to a web page hosted on a server, but be able to access that server for a separate resource:

<img width="640" height="125" alt="image" src="https://github.com/user-attachments/assets/90c7aafb-ecf8-47ad-9deb-9f4191bc7616" />

