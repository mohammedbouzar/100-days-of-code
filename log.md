# 100 Days Of Code - Log

### Day 0: October 31, 2025

**Today's Progress**: Started a MediaKit using Next.js and Tailwind CSS. Focused on setting up the project structure and initial configurations.

**Thoughts:** Excited to kick off this new project! Next.js and Tailwind CSS are powerful tools, and I'm eager to see how they can enhance my development workflow.

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)

### Day 1: November 1, 2025

**Today's Progress:**  
Built the global layout for MediaKit with reusable components — Navbar, Footer, and Sidebar.  
Integrated responsive design using TailwindCSS and configured the color palette.

**Thoughts:**  
It feels great to see the app starting to take shape visually. Next.js and Tailwind make structuring and styling really efficient. Tomorrow I'll start working on the Home Page hero section and feature grid.

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)

### Day 2: November 2, 2025

**Today's Progress:**  
Made major progress on MediaKit's core tools — Subtitle Automation, Audio Editor, and Background Removal.
Integrated features:
- Subtitle Automation: upload → simulated transcription → SRT export  
- Audio Editor: waveform via Wavesurfer.js, draggable regions, trimming, and MP3/WAV export  
- Background Removal: BodyPix segmentation → transparent PNG output  

Fixed navbar issues, optimized exports for GH Pages, and solved multiple hydration bugs.
Project is now feature-complete for its MVP phase.

**Thoughts:**  
The foundation is solid — moving from prototype to polished tools now feels within reach. Excited to refine, test, and optimize performance next!

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 3: November 3, 2025

**Today's Progress:**  
Added a fully designed **authentication UI** (Sign In / Sign Up) with dedicated layouts for a clean, user-friendly experience.  
Included placeholders for **social OAuth** (Google, Facebook, etc.) to prepare for future integrations.  
Also worked on **client-side connections** and **dynamic imports** for heavy libraries to improve performance and reduce bundle size.  

**Thoughts:**  
It's starting to look and feel like a real app now!  
Designing a smooth authentication experience makes everything come together visually and functionally.  
Excited to integrate OAuth next and make sign-ins lightning fast.  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 4: November 4, 2025

**Today's Progress:**  
Started building the **backend API** using **Node.js** and Express.  
Set up the project structure, environment configuration, and initial endpoints.  
Defined routes and controller patterns for handling tool operations. 
Prepared the API for future integrations with authentication and media processing.

**Thoughts:**  
Feels great to switch gears from UI to backend logic! 

**link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 5: November 5, 2025

**Today's Progress:**  
- Integrated **Node.js API** with a **Python microservice** using **OpenAI Whisper** for AI-powered transcription.  
- Connected MediaKit's **frontend and backend**, enabling real **subtitle generation** directly from uploaded media.  
- Improved API flow for audio upload, processing, and returning transcription results to the client.  

**Thoughts:**  
Super excited today! 🚀 Seeing AI and full-stack integration come together feels incredibly rewarding.  
This marks a huge step — MediaKit is officially creating real, usable subtitles with the power of AI.  
Onward to refining accuracy and expanding to more tools!  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 6: November 7, 2025

**Today's Progress:**  
- Implemented **background removal** on the **server side** instead of only frontend.  
- Integrated **Python** backend tools — **Pillow** and **rembg** — to handle accurate background segmentation and transparent image output.  
- Linked this new Python service with the **Node.js API**, enabling the frontend to send images and receive processed results seamlessly.  
- Improved performance and stability by offloading heavy image processing from the browser to the server.

**Thoughts:**  
Really satisfying progress today! 🎨  
Seeing the background removal feature running entirely on the backend feels like a big step forward for MediaKit.  
Server-side processing opens the door for faster, more reliable, and scalable tools. Excited to keep refining it!  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 7: November 8, 2025  

**Today's Progress:**  
- Refactored backend logic for **background removal** to enhance performance and readability.  
- Integrated **Sequelize ORM** and created a **User model**.  
- Implemented **authentication system** (sign-up, sign-in).  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 8: November 9, 2025  

**Today's Progress:**  
No coding today - I caught a fever and took time to rest and recover.  

**Thoughts:**  
Sometimes the best way to move forward is to stop and rest.
Tomorrow I'll be back to the challenge stronger than ever! 🚀 💪  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 9: November 10, 2025  

**Today's Progress:**  
- Learned more about **Next.js**, especially SSR vs CSR.  
- Explored **Prisma** ORM and **NextAuth** integration.  
- Refactored backend code from Node.js to Next.js API routes.  
- Kept a minimal **Python microservice** for AI tool processing.  

**Thoughts:**  
Refactoring helped streamline the architecture and make the app more flexible. Clean code design not only improves scalability but also sharpens problem-solving skills — you learn to think structurally, not just syntactically.  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 10: November 11, 2025

**Today's Progress:**  
- Completed authentication system using **NextAuth**  
- Added **Google, Facebook, X (Twitter)**, and **Credentials** providers  
- Implemented middleware for route and session protection  
- Refactored code for better scalability and structure

**Thoughts:**  
Authentication is a key building block for secure apps.  
It forced me to think about user flow, security, and session handling — a great exercise in problem-solving and backend logic.  
Super happy with today's progress!  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 11: November 12, 2025

**Today's Progress:**  
- Finished full **code refactor**  
- Migrated backend logic entirely into **Next.js** (no more separate Node.js server)  
- Verified fullstack functionality — API routes, database, auth, and AI integrations  
- Project is now running seamlessly under one stack  
- Gained deeper knowledge about **Next.js fullstack capabilities**, **API routes**, and **maintainability**

**Thoughts:**  
This refactor was a turning point! It improved performance, simplified deployment, and made the project easier to scale and maintain.  
I learned a lot about structure, abstraction, and fullstack integration — it feels awesome to see everything come together! 🙌  

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 12: November 13, 2025

**Today's Progress:**  
- Started Dockerizing the full project (Next.js fullstack + Python microservice)  
- Set up production-ready Docker configurations  
- Cleaned up environment configs and deployment structure

**Thoughts:**  
Moving into the deployment phase feels amazing. Making it easier to ship consistent builds and streamline development. Great step toward launching MediaKit!

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 13: November 14, 2025

**Today's Progress:**  
- Ensured all features are functional and stable  
- Finalized project cleanup, structure, and Docker configuration  
- Reached the end of this project's development phase

**Thoughts:**  
It feels great to reach this milestone. I learned a lot from this project about NextJS architecture, SSR/CSR , problem-solving, Dockerization and CI/CD .
Stopping here for now and moving forward to new learning paths and projects!

**Link to work:** [MediaKit](https://mediakit.mohammed-bouzar.com)


### Day 14: November 16, 2025

**Today's Progress:**  
Started a new project — a Quiz Generator web app built with Next.js, TailwindCSS, and daisyUI.  
Set up the project scaffold, configured Tailwind + daisyUI, and created the initial UI structure (layout, navbar, theme setup).  
Prepared the foundation for future features like AI-powered question generation and quiz exporting.

**Thoughts:**  
It feels great to begin a fresh project! Starting clean always brings motivation and clarity.  
I'm excited about building something useful, fast, and fun — and the tech stack already feels smooth. Can't wait to add the first real features tomorrow.

**Link to work:** *(coming soon)*


### Day 15: November 17, 2025

**Today's Progress:**  
Built the Home page for the Quiz Generator project using Next.js + Tailwind + daisyUI.  

**Thoughts:**  
A solid visual start — now I can connect the "Create quiz" flow to the backend.

**Link to work:** *(coming soon)*


### Day 16: November 18, 2025

**Today's Progress:**  
- Set up several **reusable UI components** for the Quiz Generator project.  
- Started building the **Create Quiz** page to support structured quiz creation.  
- Implemented the **Quiz Form** component with **Zod** for strong validation.  

**Thoughts:**  
💭 Feeling excited about the progress! 🚀  

**Link to work:** *coming soon*


### Day 17: November 19, 2026

**Today's Progress:**  
- Finished writing all necessary **data models** for the Quiz Generator project.  
- Successfully **dockerized the full application** to ensure consistent environments and smooth deployments.  
- Created a **CI/CD pipeline** with automated builds and deployments using GitHub Actions.  

**Thoughts:**  
Today felt like a huge step forward. Getting Docker + CI/CD in place makes the whole development flow feel clean, reliable, and professional.  
Seeing the project automatically deploy to my domain was incredibly satisfying.  
Super excited for what's coming next! 🚀

**Link to work:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 18: November 20, 2026

**Today's Progress:**  
- Refactored major parts of the codebase to follow **clean architecture and best practices**.  
- Unified the entire UI styling using **shared patterns and consistent DaisyUI components**.  
- Improved readability, component structure, and overall maintainability.

**Thoughts:**  
Today was a cleanup day — and it felt great. The codebase is now much more organized, consistent, and future-proof.  
These refactoring sessions always make everything feel lighter and more scalable. 🚀

**Link to work:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 19: November 21, 2026

**Today's Progress:**
- Built the Quiz API: users can now create quizzes (with questions & answers).
- Built the frontend component to run a simulated preview of their quiz before publishing.

**Thoughts:**  
Excited to see the core functionality coming together!

**Link to work:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 20: November 22, 2026

**Today's Progress:**
- Developed the frontend components for taking quizzes: QuizPlayer, QuestionCard, ResultModal, and ShareLink.
- Connected the frontend to the backend so users can create, fetch, submit, and score quizzes.
- Enabled users to see their scores and a summary immediately after completing a quiz.
- Allowed quiz creators to copy/share a public quiz link to invite others.
  
**Thoughts:**  
It's great to have the full loop working — create, share, take, and score. Next up: analytics, leaderboards, and improving share UX.

**Link to work:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 21: November 24, 2025

**Today's Progress:**
- Implemented full authentication using **NextAuth** with **Prisma** as the database adapter.
- Added multi-provider OAuth support: **Google**, **Facebook**, and **X (Twitter)**.
- Synced user sessions across frontend and backend for a smooth experience.

**Thoughts:**
Authentication is now rock-solid! It feels great seeing the app move closer to production-level quality. The login flow is smooth, and OAuth integration makes signup effortless. Excited to build features that rely on user identity next.

**Live Project:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 22 — November 25, 2025

**Today's Progress:**
- Built the **Quizzes Page** where users can:
  - View quizzes they created.
  - View quizzes they passed.
- Added access control so only **authenticated users** can see their quizzes.
- Improved session handling to ensure consistent user-specific data loading.

**Thoughts:**
Feels great seeing the app becoming more user-centric. Restricting access based on authentication made the experience much cleaner and more personal. The dashboard is starting to feel like a real platform!

**Live Project:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 23 — November 26, 2025

**Today's Progress:**
- Completed full CRUD operations for quizzes
- Added visibility settings (public/private) + route protection
- Improved mobile design
- Added pagination for both quiz cards and quiz lists
  
**Thoughts:**
I love how the platform is becoming smoother and more powerful day by day. Each improvement makes it feel more like a real, production-ready tool!

**Live Project:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 24 — November 28, 2025

**Today's Progress:**
- Spent some time tightening up security across the project. Nothing flashy, but definitely important.
- Added a new way to view quizzes - you can switch between a grid layout or a clean list view.
- Modified the OAuth Sign-in flow and customized some of the returned attributes.
- Created a Profile page where users can manage their personal info.

**Thoughts:**
I felt it wasn't a big progress but it was still important. These kinds of improvements make everything feel more solid.

**Live Project:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 25 — November 29, 2025

**Today's Progress:**
- Added image upload & update inside the Profile page.
- Synced profile updates directly into the active session.
- Gave the Profile UI a little cleanup.
- Cleaned up the Profile UI a little bit.
- Start working for quiz visibility: public vs private. (Private quizzes will eventually support giving access only to specific users)

**Thoughts:**
The privacy system looks like it'll be tricky, but I'm actually looking forward to building it out.

**Live Project:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 26 — November 29, 2025

**Today's Progress:**
- Added the option to set quiz visibility as public or private next is published.  
- Private quizzes now work exactly how I wanted: only specific users are allowed to access them.

**Thoughts:**
Honestly, this feature took a bit more mental energy than I expected.  
But it's done, and it works, and it feels good to see it all come together.

**Live Project:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 27 — December 2, 2025

**Today's Progress:**
- Started integrating AI into the Quiz Generator.
- Prepared the necessary foundation to automatically generate questions instead of writing them manually.
- Prepared the API so that it can communicate with the AI model and provide good quiz content.

**Thoughts:**
The project seems to have suddenly opened up. I had been wanting to introduce AI into this project for a while, and starting the integration today has given the whole application more life. It's still in its early days, and there are still some shortcomings, but it's exciting to see where it will go.


### Day 28 — December 3, 2025

**Today's progress:**
- Finished integrating AI into the Quiz Generator.
- Now users can create a quiz and let AI automatically generate questions.
- The generated questions are added directly to the form, ready to edit or save.

**Thoughts:**
It was great to see this feature come to life today. No more manually writing out each quiz — just select AI mode, wait a moment, and your questions are ready. It's simple right now, but it feels like a big step forward.

**Live Project:**[Quiz Generator](https://quizgenerator.mohammed-bouzar.com)


### Day 29 — December 6, 2025

**Today's progress:**
- I'm starting a new project: a Habit Tracker with Data Visualization.
- Set up the project structure using Next.js and Tailwind CSS.

**Thoughts:**
I'm excited to begin this new journey! Building a Habit Tracker with data visualization will not only help me improve my own habits, but also provide valuable insights to users. I look forward to diving myself in the development process and creating something impactful.


### Day 30 — December 7, 2025

**Today's Progress:**
Create ERD diagram for the database and mapped out user flows.
Spent some time planning and organizing the Habit Tracker project. Drawing diagrams and specifications helped me clarify the structure and flow before diving into development.

**Thoughts:**
I'm excited to begin this new journey! Building a Habit Tracker with data visualization will not only help me improve my own habits, but also provide valuable insights to users. I look forward to diving myself in the development process and creating something impactful.


### Day 31 — December 8, 2025

**Today's Progress:**
- Initialized the Next.js project with TypeScript, Tailwind CSS, and the App Router.
- Added core dependencies: prisma, @prisma/client, next-auth and bcrypt.
- Configured Prisma with a MySQL datasource and defined the User, Habit, HabitLog and Auth models in schema.prisma.
- Created a singleton instance of the Prisma Client in prisma/client.ts to manage database connections efficiently.
- Set up NextAuth.js with Credentials, Facebook, Google, X Twitter Providers and configured the authOptions.
- Implemented the POST /api/auth/register route, including password hashing with bcrypt and user creation in the database via Prisma.

**Thoughts:**
Setting the basics for the Habit Tracker project feels great! Setting up the database models and authentication system is crucial for a solid foundation. I'm excited to start building out the core features next.


### Day 32 — December 10, 2025

**Today's Progress:**
- Built the core authentication utilities for the Habit Tracker.
- Implemented data validation using Zod to ensure robust input handling.
- Developed the main API routes for managing habits and logging activities.

**Thoughts:**
The Habit Tracker is starting to take shape! 


### Day 33 — December 12, 2025

**Today's Progress:**
- Built core UI components: Navbar, Footer, Form, etc.
- Implemented secure proxy middleware.
- Developed full register & login pages.

**Thoughts:**
The Habit Tracker now has an interface that you can log into, as well as an authentication feature. The foundation for user interaction is complete.


### Day 34 — December 13, 2025

**Today's Progress:**
- The dashboard now shows progress through charts and streaks. 
- Users can create habits and log them every day.

**Thoughts:**
It's no longer just a UI, but a functional tool that does its job.


### Day 35 — December 14, 2025

**Today's Progress:**
- Added filters (week/month) to the dashboard.
- Enhanced habit cards with richer information.
- Implemented a heatmap to visualize activities over the year.
- Styled streaks for better user engagement.

**Thoughts:**
It's no longer just about what you've done, but understanding your patterns over time.


### Day 36 — December 16, 2025

**Today's Progress:**
- Updated Navbar with profile dropdown menu.
- Created full profile management page.
- Secure email and password update (credentials only).
- Added account deletion with confirmation.

**Thoughts:**
The quality of a tracker depends on how trustworthy its foundation is. Today, user control and security were enhanced.


### Day 37 — December 18, 2025

**Today's Progress:**
- Edit/Rename habits
- Delete individual habits
- Undo a habit log (mistakes happen!)
- Dark Mode support 🌙

**Thoughts:**
Today I improved the core experience. Giving users the ability to correct mistakes and choose their own theme makes Habit Tracker feel more complete and considerate.


### Day 38 — December 20, 2025

**Today's Progress:**
- Refined web API structure.
- Set up the Flutter environment for mobile development.
- Initialized the mobile project.

**Thoughts:**
The architecture is taking shape. One backend (Next.js API), multiple frontends (web and mobile).



### Day 39 — December 21, 2025

**Today's Progress:**
- Set up Clean Architecture
- Implemented Material Design 3 theme
- Navigated ready

**Thoughts:**
The app is organized beautifully and ready for feature development.



### Day 40 — December 22, 2025

**Today's Progress:**
- Interactive bar and pie charts
- 365-day activity heatmap with color intensity
- Streak overview
- Responsive design that adapts to all screen sizes
- Material Design 3 matching the web version

**Thoughts:**
The mobile app now displays progress through charts, year-long activity patterns, and sorted habit streaks. The foundation is ready for real API integration!



### 41 — December 23, 2025

**Today's Progress:**
- ⚙️ Settings screen
- 😊 Habit creation screen
- 🔐 OAuth ready with FontAwesome 6 icons
- 🧭 Improved navigation & profile stats

**Thoughts:**
The UI is now production-ready with Material Design 3!



### Day 42 — December 25, 2025

**Today's Progress:**
- Fixed authentication.
- Now my app works seamlessly on mobile with secure tokens.

**Thoughts:**
Progress feels good.


