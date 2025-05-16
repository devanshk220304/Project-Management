# Peerstack: Revolutionizing Group Studying
**Shweta Dhar**

**IS 340 Final Paper**

**16 May 2025**

## Background
Team collaboration is a formative tool in learning, especially amongst college and post-secondary students. However, it is easy to not utilize group study sessions properly because of the overwhelm that can come with choosing how to effectively study and go through the entire group’s resources. Oftentimes the lack of organization leads to redundancy of concepts, choice paralysis from overwhelm, and wasted time while trying to meet a deadline. Unfortunately, the current tools offered to help team collaboration in educational spaces lack efficiency and usability, only exacerbating these symptoms.

PeerStack is an open-source organizer for study sessions that allows students to ‘stack’ together their resources to create concise study material and streamline collaboration and academic prep. The application allows users to visualize concepts in real-time by collaboratively creating mind-maps with different nodes that can be tagged with: tasks, notes, or flashcards. A real-time live chat feature is offered on the side to supplement mind-map making and simplify team communication.

## Purpose and Objectives
PeerStack’s primary objective is to provide an easy-to-use interface that can help effectively organize team resources and optimize group study sessions. Collaboration is an essential soft skill that many students strive to harness and apply to their educational and professional roles, but it is difficult for students to stay motivated and engaged in team settings when there are many frustrations and obstacles coming with it. Luckily, PeerStack can aid in minimizing these negative experiences and allow students to strengthen their team-building by simplifying communication and morale. Coupling the succinct nature of PeerStack’s mind-maps with its real-time chat feature allows students to finally reap the benefits of effective and intuitive team communication, and create a flourishing educational space.

## Platform Features
PeerStack’s features enable users to:
* Customize mind maps using nodes to go with different study topics
* Tag nodes with tasks, notes, flashcards
* Assign specific nodes/tasks to team member(s)
* Collaborate with peers and gain feedback in real-time using the live chat feature
* Access chat history to ensure all previous feedback has been implemented
* See version history to track mind maps and outline progress
* Export mind maps to PDF or convert into Anki cards
* Securely protect mind-maps with 2FA (Google or GitHub)
* Access the PeerStack community to gain inspiration from previously-made templates or mind-maps, all from users around the world

  
<h1 align="center">
  
![Image](https://github.com/user-attachments/assets/680471d6-3bd2-4c36-af40-22749fa0b530)

</h1>

The image above displays a conceptual, low-fidelity mockup of PeerStack’s website design. On the left, a biology mind-map with four nodes is created, with ‘DNA’ being a sub-node. The real-time live chat is displayed on the right so team members can collaborate and receive/give feedback cohesively, all on one screen. A second tab labelled ‘History’ is accessible to see any feedback from past team sessions, ensuring no feedback is overlooked. Users are able to assign tasks and flashcards to each node. Tasks can be assigned to team members as well – for example, if Emily offered to upload her notes into the evolution node, she can be assigned to it as a task. On the top right, a community tab is placed to access previously made templates or mind-maps from other PeerStack users.

## Target Audience
PeerStack is primarily designed for:
* Students in high school and college who are preparing for midterms and finals and are interested in working with their peers to prepare
* Students in high school and college who are outlining deliverables for group projects 
* Individuals that are studying for standardized testing (SAT)
* Individuals studying for post-grad admission testing (MCAT, LSAT, GMAT)
* Educators wanting to implement collaborative learning into their curriculum

While these customer segments are the targets, PeerStack will be useful for anyone who is seeking to improve their team’s collaboration – regardless of whether or not they are in an educational setting.

## Workflow and Process Map
![Image](https://github.com/user-attachments/assets/7cfa8a1d-45fc-466c-96fb-1a6a0148dd59)

The process map above displays a thorough breakdown of how PeerStack plans to develop its platform. The project is broken down into six phases over the span of eight months:
1. **Research and Planning (Month 1)**: setting up project vision and success metrics, creating low-fidelity UI mockups, recommending architecture for the tech stack, drafting initial testing criteria 
2. **Design and Architecture (Month 2)**: approving high-fidelity UI prototypes and tech stack, set up Node and Express servers/schemas
3. **Development (Months 3-4)**: build React UI and connect to back-end APIs, ensure OAuth and MongoDB frameworks are set up, begin unit testing of front and backend features and track their progress (raise issues in Jira if needed), remove incomplete features from beta version before release
4. **Pilot Testing (Month 5)**: ensure beta version is ready for release, track analytics and feedback from users, refine UI based on user feedback, log any defects or bugs in Jira, track features’ final completion and ensure they match user stories in Jira
5. **Feedback Implementation (Months 6-7)**: display proper popups or messages that were missing in the beta version, conduct final testing and acceptance tests, update team on launch readiness
6. **Final Launch and Marketing (Month 8)**: launch PeerStack website and coordinate with marketing team to start campaigning, monitor post-launch usage for minor bug fixes

The PeerStack team is broken down into: project management, UI/UX (design), front-end developers, back-end developers, quality assurance (QA) analysts, and the users/testing team.

## Addressing Technical Debt
PeerStack’s technical architecture was intentionally built with scalability, long-term maintainability, and low technical debt as our top priorities. We selected a cohesive set of technologies that stack on top of one another strategically, to provide proper functionality and ensure a smooth experience between our front-end, back-end, and design teams. The development teams were mindful about choosing technologies that are sustainable under long-term development. 

### Frontend
The frontend of PeerStack was developed using React.js frameworks, chosen for its ability to build highly dynamic and user-friendly interfaces. React’s component-based architecture promotes reusability, making it easier to scale the codebase and maintain it long-term. React has strong community support, making it the most reliable to ensure that PeerStack remains maintainable over time. With students and collaboration at the center of PeerStack's experience, React was the most fitting choice to deliver a fluid and user-friendly experience.
### Backend
PeerStack’s back-end is supported by Node.js and Express.js, both of which are well-suited for handling real-time collaboration features. These technologies allow the development team to build scalable APIs that interact efficiently and smoothly with the frontend React frameworks. PeerStack’s document-based data (supporting nodes and relationships within mind-maps) is managed using MongoDB, a document-oriented NoSQL database. As mind maps, nodes, and relationships are inherently hierarchical and loosely structured, MongoDB is the best database to provide flexibility in storing and retrieving the data. To power PeerStack’s defining real-time communication feature, Socket.io is integrated into the backend, allowing for seamless communication between clients. This ensures that collaboration features, such as live chat and real-time mind-map editing, are responsive even under high concurrency. Finally, authentication is handled via OAuth for both Google and GitHub, providing a secure and familiar login experience for students to secure PeerStack’s mind maps. The system has been proven to be more advanced than its counterparts, with its ability to support two-factor authentication (2FA) and multi-device login to enhance account security and build trust with our users to ensure they feel safe using the website. 
### Design Tools
PeerStack’s design process follows user-centered design principles, and is supported by the use of Figma for the website’s front-end design. Figma enabled the team to create wireframes, high-fidelity prototypes, and user personas to speed up development early in the product cycle. These mockups ensured that the user experience was continuously refined in alignment with user needs and feedback.
### Journey to Minimizing Debt
According to the Project Management Institute, most technical debt is sneaky as for most projects the repercussions of changing a technology stack are unknown until it happens (PMI 1). Therefore, PeerStack’s priorities of researching which technologies are highly scalable and maintainable will surely minimize as much technical debt for the project’s future.

## Emphasizing Community 
The heart of PeerStack lies in community, collaboration, and team cohesion – all of which are already embedded in a successful project management journey. A project is nothing without its team, and leadership plays a large role in improving the success of a project (Juli 1). 
###Agile and Scrum Practices
Through adopting an Agile framework and implementing scrum practices, the PeerStack teams are able to work in a highly dynamic environment and remain engaged, not just with the project itself, but with one another. The project is structured using two-week sprints, daily stand-ups, and sprint reviews to ensure that all teams are communicating transparently through giving and receiving periodical feedback. Retrospectives are used for regular iteration and improvement of code, and creates a safe space for team members to properly reflect and receive feedback. Creating a healthy and consistent feedback loop will introduce positive change to employee morale. Teams will be able to adapt more quickly and feel valued through consistent feedback.
###Jira and GitHub
PeerStack uses Jira for clearer role delegation between design, development, and quality assurance (QA) teams. GitHub is used for issues and pull requests to enhance overall code collaboration, specifically between frontend and backend developers. Coupling both of these platforms together enhances knowledge sharing through easier collaboration. Creating a simplified approach for feedback and collaboration amplifies unity and increases motivation amongst team members.
###Documentation
Open-source projects are notoriously difficult to keep up with due to its fast pace. Employees can quickly become overwhelmed and burnt out out of fear of not being able to keep up. For this reason, documentation is crucial in strengthening team morale and supporting the PeerStack teams’ efforts in creating the tool. Only 4% of companies are known to consistently document their work (Atlassian 1), and this can take a harsh toll on the overall project. Documentation is essential for quality assurance and keeping developers aligned. PeerStack uses a documentation-first approach to support both the project’s success and to decrease duplication or repetition within roles. Repetition can easily make employees feel undervalued, and avoiding it will only benefit the team. Furthermore, documentation ensures that new contributors on the project stay up-to-date on the architecture and stay aligned with the rest of the team.

## Long-Term Vision
PeerStack aims to revolutionize and re-define the dynamic of group study sessions. The aim is to reduce stress, choice paralysis, and other common frustrations that many students feel and dread when it comes to academic prep in group settings. Beyond this, PeerStack’s long-term vision includes:
* Build a stronger study community through allowing students from around the world to add their creations to PeerStack
* Evolve PeerStack into a widely-used educational tool
* Relieve stress from professors and educators that have trouble integrating collaboration into their classrooms and curriculum
* Align with the ongoing development of LLMs and AI to refine and improve PeerStack’s organization of study tools

## References
- Alicea, B. (2025). Lecture 14 [PowerPoint Slides]. Canvas. www.canvas.illinois.edu 

- Atlassian. (n.d.). The importance of documentation. Atlassian. https://www.atlassian.com/work-management/knowledge-sharing/documentation/importance-of-documentation 

- Juli, T. (2011). The five team leadership principles for project success. Paper presented at PMI® Global Congress 2011—North America, Dallas, TX. Newtown Square, PA: Project Management Institute.

- Project Management Institute. (n.d.). Technical debt in agile. https://www.pmi.org/disciplined-agile/agile/technicaldebt 
