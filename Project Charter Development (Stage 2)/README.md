# FocusRobot — Project Charter

## 1. Project Objectives

### Project Purpose

FocusRobot is a physical robot paired with a mobile application that helps people maintain focus during study or work sessions. The robot uses a camera and Computer Vision to detect focus-related behaviors and provides real-time feedback. Users can also earn rewards for completing focus sessions.

The project aims to combine Computer Vision, mobile development, hardware, and gamification into a practical prototype that can help users build better focus habits.

## SMART Objectives

1. **Real-Time Focus Detection:** Build a robot that uses a camera and Computer Vision to detect whether a user is Focused, Distracted, or Away during a focus session. The system should identify the correct state in at least 80% of test cases across 5 different users. This should be completed during the development phase of the project, so users can become aware of losing focus and get back on track.

2. **Mobile App and Rewards:** Deliver a mobile app connected to the backend that lets users start and end a focus session with a timer, view a session summary (duration and percentage of focused time), and earn coins after each completed session, with all three core flows working without critical bugs before the integration phase ends. This gives users visible progress and motivation to keep building the habit.

3. **Integrated MVP:** Integrate the 3D-printed robot, Computer Vision module, mobile app, and backend into one MVP that completes a full session (start, detection, robot feedback, reward, progress view) in at least 9 out of 10 test runs, and reaches an average usefulness rating of 4 out of 5 from at least 5 test users by the end of the testing phase, followed by a live demo at the final presentation. This proves the concept works end to end and that users find it valuable.

---

## 2. Stakeholders and Roles

### Stakeholders

| Stakeholder                        | Role / Interest                                                                                                                                |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Project Team**                   | Designs, develops, tests, and documents the FocusRobot MVP.                                                                                    |
| **Users**                          | Students, employees, and other people who want to improve their focus. They provide feedback about the usability and usefulness of the system. |
| **Project Supervisor / Holberton** | Provides guidance and evaluates the project based on the project requirements and deliverables.                                                |

### Team Roles

| Team Member | Role                  | Main Responsibilities                                                                          |
| ----------- | --------------------- | ---------------------------------------------------------------------------------------------- |
| **Shahd**   | Project Manager       | Coordinate the team, organize meetings, track progress, and help manage project tasks.         |
| **Gheed**   | Computer Vision / AI  | Develop the Computer Vision component and focus-detection logic.                               |
| **Lama**    | Backend / Database    | Develop the backend, database, and communication between the application and other components. |
| **Noura**   | Mobile App / Frontend | Develop the mobile application interface and user experience.                                  |

The team will collaborate through GitHub, project management tools, regular meetings, and shared documentation.

---

## 3. Scope

### In-Scope

The following features and activities are included in the MVP:

* A physical robot prototype.
* A simple 3D-printed robot body.
* Camera integration.
* Basic Computer Vision for detecting focus-related behaviors.
* A mobile application.
* User focus sessions and timers.
* Displaying focus-session information and progress.
* A basic reward system using points or coins.
* Basic robot feedback through expressions or a small screen.
* Communication between the robot, application, and backend where required.
* Testing the system with users and collecting feedback.
* Project documentation and demonstration.

### Out-of-Scope

The following features are outside the scope of the initial MVP:

* Detection of basic states such as:

  * Focused
  * Distracted
  * Away
* Advanced human behavior recognition.
* Full emotional recognition.
* Voice-based personal assistant features.
* Complex robot movement or navigation.
* Large-scale production hardware.
* Integration with commercial meeting or productivity platforms.
* Storing or uploading users' raw camera recordings.
* Advanced AI personalization.
* A large-scale commercial deployment.

These features may be considered for future versions if there is enough time and resources.

---

## 4. Risks and Mitigation Strategies

| Risk                               | Potential Impact                                                            | Mitigation Strategy                                                                                                                         |
| ---------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Computer Vision accuracy**       | The robot may incorrectly detect whether the user is focused or distracted. | Start with simple and measurable behaviors such as face presence and head orientation. Test the system with different users and conditions. |
| **Hardware integration problems**  | Hardware issues could delay development and testing.                        | Use simple hardware components and test each component separately before integration.                                                       |
| **Limited development time**       | The team may not complete all planned features.                             | Prioritize the core MVP and implement additional features only if time allows.                                                              |
| **Integration between components** | The robot, mobile application, and backend may not communicate correctly.   | Define interfaces early and test communication between components throughout development.                                                   |
| **Limited hardware resources**     | The team may face limitations with available components or equipment.       | Build a simple prototype using readily available components and avoid unnecessary hardware features.                                        |

---

## 5. High-Level Plan

The project will be developed in several phases:

| Phase                      | Main Activities                                                                                         |
| -------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Phase 1 — Planning**     | Finalize requirements, define user stories, assign responsibilities, and create the technical plan.     |
| **Phase 2 — Design**       | Design the mobile application, robot structure, system architecture, and Computer Vision approach.      |
| **Phase 3 — Development**  | Develop the mobile application, backend, Computer Vision component, and robot prototype.                |
| **Phase 4 — Integration**  | Connect the robot, Computer Vision system, mobile application, and backend.                             |
| **Phase 5 — Testing**      | Test the system, identify problems, improve accuracy, and collect user feedback.                        |
| **Phase 6 — Finalization** | Fix remaining issues, complete documentation, prepare the final demonstration, and present the project. |

### High-Level Timeline

| Period        | Focus                                                        |
| ------------- | ------------------------------------------------------------ |
| **Weeks 1–2** | Requirements, user stories, system design, and planning      |
| **Weeks 3–5** | Computer Vision, backend, and mobile application development |
| **Weeks 6–7** | Robot prototype and component integration                    |
| **Weeks 8–9** | Testing and improvements                                     |
| **Week 10**   | Final integration, documentation, and presentation           |

---

## Project Success Criteria

The FocusRobot MVP will be considered successful if the team can demonstrate a working system in which:

* A user can start a focus session.
* The camera can detect basic focus-related behaviors.
* The robot provides feedback based on the detected state.
* The user can view their focus-session progress through the mobile application.
* The user can receive rewards after completing focus sessions.
* The main components work together as one demonstrable MVP.
