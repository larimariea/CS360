# CS360
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

For my CS 360 project, I developed an Android event-tracking application designed to help users organize upcoming events, manage important dates, and keep track of their schedules in one convenient place. The primary goal was to create an application that was functional, approachable, and easy to navigate, particularly for individuals who may already feel overwhelmed by the number of responsibilities they manage throughout the day.

When I first began working on this project, I thought of event tracking as a relatively simple concept. Users would enter information about an event, save it, and return to the application whenever they needed to review their schedule. However, as I progressed through the development process, I started recognizing how many small decisions influence whether an application is genuinely useful. Something as simple as entering an event should not require unnecessary steps, and users should not have to search through multiple screens to find information they previously saved.

I wanted the application to reduce the mental effort involved in keeping track of important commitments rather than introduce another responsibility for users to manage. This meant focusing on clear navigation, straightforward event management, and an interface that made information easy to locate.

The application was developed to meet the course requirements for user authentication, persistent data storage, event management, and SMS notification permissions. Beyond fulfilling these technical expectations, I wanted to create something that resembled an application someone might realistically choose to use.

One of the most valuable lessons I learned was that meeting a list of technical requirements and creating a satisfying user experience are not necessarily the same thing. A feature can function exactly as intended while still being confusing or inconvenient. Recognizing that difference changed how I approached the remainder of the project.

What screens and features were necessary to support user needs and produce a user-centered UI? How did my designs keep users in mind, and why were they successful?

Designing the user interface was one of the parts of this project that most noticeably changed my perspective on application development. Before taking this course, I primarily evaluated interfaces based on their appearance. I appreciated applications that looked clean and visually appealing, but I rarely considered the amount of planning required to make navigation feel natural.

While developing my event tracker, I realized that a successful interface needs to do more than look attractive. It should communicate what users can do, guide them through common tasks, and minimize opportunities for confusion.

The application required several essential screens, including a login and registration interface, an event management screen, and forms for entering or modifying event information. These screens needed to work together so users could move between tasks without losing track of where they were or what they were trying to accomplish.

The authentication interface was designed to provide a clear starting point. I wanted users to understand immediately how to access their accounts without being distracted by unnecessary elements. The event management interface served as the central location for reviewing saved information, while the event forms provided a structured way to enter relevant details.

Throughout the design process, I paid attention to the organization of information, the placement of buttons, and the consistency of visual elements across screens. I wanted the application to feel cohesive rather than like a collection of unrelated features.

I also began thinking more carefully about how users might interact with the application under less-than-ideal circumstances. Someone may be adding an event while distracted, checking a date in a hurry, or returning to the application after several days without using it. In those situations, clear labels and predictable navigation become especially important.

Another consideration was providing useful feedback when users performed actions. An application should communicate whether information was saved successfully or whether additional input is required. Without that feedback, users may become uncertain about whether their actions were completed.

I consider my interface design successful because it reflects a shift in how I define usability. Instead of focusing exclusively on appearance, I began making decisions based on how easily someone could complete a task. I learned that visual simplicity is not necessarily the absence of features, but the thoughtful organization of those features so they do not overwhelm the user.

How did I approach the process of coding my app? What techniques or strategies did I use, and how could those techniques be applied in the future?

My approach to coding changed considerably throughout this project. Initially, I was tempted to think about the application as one large assignment that needed to be completed. However, I quickly realized that trying to implement multiple interconnected features at once made troubleshooting more difficult.

I began approaching development by breaking the application into smaller, more manageable components. Instead of concentrating on the finished product immediately, I focused on understanding what each part of the application needed to accomplish and how it would interact with the rest of the system.

Working in Android Studio required me to become more comfortable navigating between Java code, XML layouts, and the Android project structure. One of the challenges was understanding how the visual components of an application connect to the underlying logic. A button may appear correctly on the screen, but that does not mean its behavior has been implemented properly.

I learned to treat the interface and the functionality as related but distinct responsibilities. The layout needed to present information clearly, while the application logic needed to respond appropriately to user actions.

I also worked with local data storage to support event management and preserve information between application sessions. This helped me better understand the importance of separating information management from the interface itself.

Another strategy I found useful was making changes incrementally rather than modifying large portions of the application without checking the results. When something stopped working, smaller changes made it easier to identify the cause.

This project also reinforced the importance of reading existing code carefully before changing it. I learned that understanding how different components depend on one another can prevent unnecessary errors and make development more efficient.

Moving forward, I plan to continue using a structured development process that begins with understanding requirements, organizing functionality into manageable tasks, and testing features as they are implemented.

I also want to become more intentional about documenting my decisions. Throughout this project, I realized that it is easy to remember why something was implemented a particular way while actively working on it, but that reasoning can become less obvious when returning to the code later.

These are habits I can apply to future software projects regardless of the programming language or platform involved.

How did I test to ensure my code was functional? Why is this process important, and what did it reveal?

Testing was one of the most important and sometimes most frustrating parts of developing my application. Before this course, I generally thought of testing as something that happened after most of the coding was complete. My experience with Android development showed me why that approach can create unnecessary problems.

As I worked on the application, I learned the value of checking functionality throughout development rather than waiting until the end.

My testing process involved reviewing the behavior of individual features, checking navigation between screens, and examining how the application responded to different user interactions. I focused on whether the application performed the actions users would reasonably expect, including accessing the login interface, entering event information, managing saved events, and handling notification permissions.

I also considered situations where users might provide incomplete information or attempt actions that the application could not complete successfully. These scenarios are important because real users do not always interact with software in the exact way developers anticipate.

One lesson that became clear was that code compiling successfully does not guarantee that an application provides a good experience. An application can launch without errors while still containing confusing navigation, unexpected behavior, or features that do not respond appropriately.

Troubleshooting also required patience. There were times when correcting one issue revealed another, and I had to revisit earlier decisions to understand how different components interacted.

Although those moments could be discouraging, they helped me become more comfortable with debugging. I gradually learned to approach errors as information rather than simply obstacles preventing me from finishing the project.

Testing revealed how important it is to consider the application from the perspective of someone who has never seen the code. As developers, we know what a button is supposed to do and where certain information should appear. Users do not have that background knowledge, so the application needs to communicate those expectations through its design and behavior.

This experience has changed how I intend to approach testing in future projects. Rather than treating it as a final requirement, I want to incorporate it throughout development and use the results to guide improvements.

Consider the full app design and development process from initial planning to finalization. Where did I have to innovate to overcome a challenge?

One of the biggest challenges I encountered was bringing together the different parts of the application into a cohesive experience.

During the earlier stages of the course, I could focus on individual requirements, such as designing a screen or understanding a particular Android component. However, completing the final project required those pieces to work together.

I found that implementing a feature in isolation was often much easier than integrating it into an application that already contained other functionality. Changes to one screen could affect navigation, data handling, or the way information appeared elsewhere.

This required me to become more flexible in how I approached development. Instead of assuming that my initial design decisions would always translate directly into functional code, I had to reconsider certain choices as I gained a better understanding of the platform.

One area where I had to think creatively was balancing the technical requirements with my goal of creating a visually appealing, user-friendly application. I did not want the interface to feel like a basic collection of buttons and text fields simply because those were the easiest components to implement.

At the same time, I learned that adding visual details or additional functionality can introduce complexity. Every design decision has to be supported by code, and every new feature creates another opportunity for something to behave unexpectedly.

I had to consider which improvements would genuinely benefit users and which might make the application more complicated without providing meaningful value.

This process helped me understand innovation differently. I used to associate innovation primarily with creating something entirely new or introducing advanced technology. Now I recognize that innovation can also involve finding a more intuitive way to present information, simplifying a complicated interaction, or developing a practical solution to a problem that initially seemed difficult.

For me, the challenge was not necessarily inventing a completely original concept. It was taking a familiar idea and working through the decisions required to turn it into a functional application that reflected my own approach to design.

In what specific component of my mobile app was I particularly successful in demonstrating my knowledge, skills, and experience?

The component I am most proud of is the event management interface and the way it connects user interactions with the application's underlying functionality.

I chose this component because it represents the central purpose of the application. Authentication and navigation are important, but the ability to organize and manage events is what ultimately makes the application useful.

Developing this functionality required me to think about several aspects of software development simultaneously. I needed to consider how users would enter information, how that information would be stored, how it would be displayed, and how users could interact with it later.

This component helped me connect concepts that previously felt separate. User interface design, application logic, data management, and testing all became parts of the same process rather than individual topics covered in different assignments.

I am particularly proud of the progress I made in understanding how the visual interface communicates with the underlying code. At the beginning of the course, I had a much more limited understanding of Android development, and even relatively simple interactions could feel intimidating.

By the time I reached Project Three, I was more comfortable examining the relationship between XML layouts, Java classes, and user actions. I had also developed a stronger understanding of how to organize application functionality so that different components could work together.

What makes this accomplishment meaningful to me is not that the application is the most advanced software I could ever create. It is that I can look at the finished project and recognize how much more I understand than I did when I started.

I can identify the decisions I made, explain the purpose behind different components, and recognize areas where I could continue improving the application.

That ability to evaluate my own work is something I value because I know professional development will require continuous learning and refinement.

Final Reflection

Completing this project has given me a much greater appreciation for the work involved in mobile application development. Before taking CS 360, I understood that applications required programming, but I had not fully considered how many decisions take place before, during, and after the code is written.

I now understand that creating a functional application is only part of the responsibility. Developers also need to consider how people will experience the software, how information will be managed, how errors will be handled, and whether the final product actually addresses the problem it was intended to solve.

One of the most meaningful changes in my perspective has been learning to think beyond the immediate technical requirements. Earlier in my education, I sometimes approached assignments by concentrating on what needed to be implemented to meet the rubric. While those requirements remain important, this project encouraged me to think more critically about the purpose behind them.

I began asking myself whether certain design choices would make sense to someone using the application for the first time, whether a feature could be simplified, and whether the interface communicated information as clearly as I intended.

I also learned that development is rarely as straightforward as it appears from the outside. There were moments when I felt confident about a feature only to discover an issue during implementation. Other times, something I expected to be difficult turned out to be manageable once I broke it into smaller steps.

Those experiences reminded me that becoming a stronger developer is not about avoiding mistakes. It is about learning how to respond to them, understanding what caused them, and applying that knowledge moving forward.

As I approach the completion of my computer science degree, I find myself reflecting on how much my confidence has changed. I still encounter unfamiliar concepts, and I know there are many areas of software development I have yet to explore. However, I no longer view that uncertainty as evidence that I am unprepared.

Instead, I recognize that learning new technologies, working through unexpected challenges, and adapting to unfamiliar environments are fundamental parts of being a computer scientist.

This project represents more than an Android application in my portfolio. It reflects my ability to take an idea through the stages of planning, design, implementation, and evaluation. It also demonstrates how my understanding of software development has expanded beyond writing code to include usability, organization, and the responsibility of creating technology that serves a meaningful purpose.

If I were to revisit this application in the future, I would want to continue refining the interface, exploring additional accessibility improvements, and considering features that could make event management more personalized and convenient. I would also want to conduct more extensive testing with users who had no involvement in the development process, since their experiences could reveal issues I might overlook.

I am proud of the progress this project represents, but I also appreciate that it is not the end of my learning. It is a foundation I can continue building upon.

Perhaps the most important thing I will take away from CS 360 is that good software development requires both technical ability and empathy. Understanding how to build an application matters, but understanding the people who will use it is what gives that work meaning.
