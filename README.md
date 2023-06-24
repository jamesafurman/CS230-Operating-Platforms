# CS230-Operating-Platforms

• Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room is a small video game developer that had created an online game, Draw It or Lose It, for mobile Android devices. They wanted to expand their game to other platforms and so required client applications to run the game as well as a server application to function as a platform for the game. 

• What did you do particularly well in developing this documentation?

In this document, I did well in researching options for development, paring out irrelevant information, and thoroughly representing relevant information. 

• What about the process of working through a design document did you find helpful when developing the code?

Working through a design document was helpful for developing and solidifying a concept of the program's structure before beginning implementation. This conceptualization helped with development by providing clear knowledge of what function I needed to develop at a given moment and allowing me to direct my work with focus. It also helped by giving me a clear self-location at any point during development ("You are here" on a map); it's easy to get lost at sea when developing a program of greater complexity or with an unfamiliar structure compared to what the developer is familiar with, and that is a poor psychological state for attentively completing detailed work. 

• If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I should have represented concepts more concisely and more accessibly for a lay audience. While technical language has a place in design documents, and The Gaming Room is a development company, since they are not working with the same development tools as us, I should have placed more emphasis on plain-language representation. 

• How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I incorporated the user's needs holistically. Their business and technical requirements factored into my decisions about operating system selection and the particular architectural structuring of this client-server system, and their technical requirements guided my design of the software in conference with the structure of its client-server deployment, leading me to use certain design patterns (e.g. implementing a GameService class as a singleton) and security practices (e.g. authentication and authorization for users accessing the web application). 

Part of this process is straightforward; an explicit requirement that only one GameService instance should exist at a time clearly indicates the singleton implementation. But part of it is more complex, requiring that the developer draw inferences from the client's explicit requirements as well as from what is known about their company, their users, the present state of whatever product they have developed, etc., and examine how those inferences relate to one another as well as to the client's explicit requirements. It is crucial to consider the client's needs because only by appraising them attentively can a developer create a product that is genuinely useful to the client. 

• How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached designing the software mainly through research, as I mentioned previously. I already had When designing a system of an unfamiliar sort, it is reasonable to research the nature of such systems and the tools available for their implementation and to actively compare the researched information with one's own prior knowledge, thereby integrating the research as new expertise. In the future, working on another similar problem, I would make use of my own expertise but also respond to the new circumstances (which would likely differ in some points) through my broader experience as well as through research.
