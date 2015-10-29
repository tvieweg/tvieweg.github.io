---
published: true
title: App Design - Bartleby
layout: post
---
<img src="https://github.com/tvieweg/tvieweg.github.io/blob/master/post_images/Bartleby.jpg?raw=true" alt="Bartleby" width="800">

Bartleby was my second app. I had read a bit about Apple's Multipeer Connectivity Framework and wanted to create a chat app that didn't require a network. There are apps that let you connect openly with others (Firechat, etc), but not create private conversations. I wanted to create an app that allowed this, and the result was Bartleby. 

The Multipeer Connectivity Framework is an interesting beast, but Apple provides an excellent basic app to reference some of the functionality. In my case I started with this, but quickly created a custom available peer list and chat views. I also connected to Parse to create unique usernames and accounts and added some functionality around this. 

Ultimately, the Multipeer Connectivity Framework didn't seem to provide robust connectivity between peers, and didn't provide an easy way to reconnect with peers after losing a connection. Because of this, I stopped the app in the prototype phase. That said, I was pretty happy with the result. Some screenshots are below, and the source code is here. 

