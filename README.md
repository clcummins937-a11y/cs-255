DriverPass Portfolio Reflection (README)
1. Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
The DriverPass project was built for a local driving school client who wanted a modernized digital platform to handle everything in one place. They needed a system where student drivers could log in, register profiles, access online training modules, take practice tests, and schedule road lessons, while admins and instructors could easily manage class availability, track student progress, and keep user accounts organized.

2. What did you do particularly well?
I nailed the requirements gathering and system design mapping. Breaking down the core features into clean business requirement docs and detailed UML diagrams made the whole architecture feel cohesive and actually usable rather than just a theoretical textbook exercise.

3. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could tweak one thing, I'd flesh out the error-handling workflows and edge cases on the payment processing and DMV synchronization side. I'd add more robust fallback states and clearer user feedback notifications for when a third-party API call times out or fails.

4. How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
I translated user needs by putting myself in the shoes of both the student and the instructor—figuring out what bottlenecks slow people down when trying to schedule a lesson or sign up. Considering user needs is everything because if a system is a pain to navigate, people will just abandon it; software has to solve actual friction, not add to it.

5. How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
My approach is all about starting with a solid foundation: mapping out use cases and data flows before writing a single line of code so you don't paint yourself into a corner. Moving forward, I want to lean more heavily on modular design patterns and iterative prototyping to test user workflows early.
