# 2.Introduction to Team Design Project

  
## 2.1 Introduction to Team Design Project
### 2.1.1 Project Task
In teams you design and test the behavioural algorithms for 2 competing robot soccer teams and the playing environment. This will involve a two-stage process
1. Develop a simulation of your teams and their playing environment, and 
use this simulation to design and develop the behavioural algorithms 
for your team members
2. Test your behavioural algorithms on hardware (humanoid robots)
For this project we will follow the RoboCup Humanoid Kidsize Team rules

### 2.1.2 Problem Specification
1. The Teams
   In this project the robot players shall be humanoid robots based on the construction, actuation, dynamics and kinematics of a **NAO6 robot**, each team will consist of 4 humanoid robots. Within each team the robots will exhibit different types of behaviour depending on the function of the robot within the team and the state of play. These are:
   - Striker: This behaviour focusses on scoring points by **kicking the ball** into the opposing team’s goal. The strikers could **exhibit more aggressive behaviour** and will be **goal focussed** when the team has the ball. When the team does not have the ball then the striker behaviour will **seek to intercept and gain control** of the ball.
   - Defender: This behaviour focusses on defending their team’s half of the pitch and the goal area. The defender behaviour could be defensive in nature in that its primary function is to **prevent the opposing team** from getting the ball near to the defending team’s goal. The range of the defender could **extend depending on the current situation** of play.
   - Goalkeeper: This behaviour focusses on **guarding the goal** and **preventing the opposing team** from scoring.
   
   Whether your team has specific **set formations**, i.e. specific behaviours are assigned to particular robots within the team and this does not change, or there is a **dynamic allocation of behaviour**, i.e. behaviours change depending on the position of the robot on the pitch, all depends on your design for the team. In addition, **the team must follow the general rules of soccer as outlined by RoboCup**.
2. Control Guidance of Robots
   The control, guidance and navigation of the robots must be totally autonomous with **no input from an external operator**. The robots should react to the state of play during a match and adopt an appropriate behaviour. The specification of the control system is determined by the **performance requirements for each playing behaviour** and **how the robot responds to the current state of play**.
3. The Pitch or Field of Play
   The dimensions of the Pitch for the KidSize Humanoid competition are 9m by 6m. The line spacing and configuration is shown in Guidance Book.
4. The ball

## 2.2 Stage 1: Simulation Task
In the stage 1, the team need to create a simulation of 2 competing robot soccer teams and the playing environment.

For this project, the team is advised to sumulate the robot soccer teams using **MATLAB** and associated packages, or **ROS**. This will allow **behavioural algorithms** to be developed and implemented for the different team members. As well as developing simulated robots and implementing their behavioural algorithms, there should some **visualisation** of the pitch and players.

## 2.3 Stage 2: Hardware Task
Once your team has developed the behavioural algorithms for the constituent members of your teams, you will have to implement these algorithms on hardware teams.

The team will only be able to progress on to this second stage if the first stage is completed. And the team have to develop <font color=red>test schedules</font> in order to request access to the hardware from the supervisor.



## 2.4 Design Schedule & Review <font color=red>(Important)</font>
The project will consist of the following design stages:
- Development of a simulation of a humanoid robot for soccer based on the <font color=red>NAO6 robot</font> (parameter?)
- Development of simulated environment for 2 teams of 4 robots to play soccer
- Develop a multi-agent simulation of the RoboCup Humaniod Kidsize Soccer Team
- Development of algorithms to implement playing strategies for each of the robot teams
- Evaluation of the simulated robot soccer teams
- Test your behavioural algorithms on hardware
- A Design Review (DR) will be performed at the end of the simulation stage

## 2.5 Project Management
Your team should consider the following:
- You will have a supervisor assigned to help supervise and monitor your team.
- The management structure for your team – **every member has to contribute**
- The division of workload – every member has to contribute
- One member of your team should be assigned as the communication officer who will email your supervisor
- The subject for all emails should begin **“ENG5325 …”** so that your supervisor can safely filter your emails

## 2.6 Project Meetings
- Each team will have 1 scheduled meeting per week **with your supervisor (take minutes!)**, These meetings will be used to provide help and guidance on the technical aspects of the project
- <font color=red>Technical progress and Team work will be assessed during the meetings</font>
- <font color=red>Time Allocation Records (TARs)</font> to be kept through project and presented at the supervisor meeting every 2 weeks.
- <font color=red>Additional meeting</font> should be charged as Expert help
- **Meeting with Manager every month**
- **Pitch Presentation in February**
- **Final report and final presentation are due at end of project**

## 2.7 Time and Costs
- <font color=red>Time and cost estimates will be made by each team at the beginning of the project</font>
- Records of time spent on each element of the project will be kept and reported by each team – **using the Time Allocation Record** (TAR) provided
- Staff cost £200 per team-member per hour
- Expert help cost £1000 per hour (the weekly meetings are not to be considered as expert help)
- Time and costs figures have to be presented every 2 weeks at the meeting with supervisors using the TAR provided, <font color=red>which represent a formal declaration of how the team worked in the period.</font>

## 2.8 Initial Project Tasks
- Arrange a team meeting
- Arrange meeting with your supervisor during this week
- Get acquainted with your group members
- Determine your <font color=red>Team Management Structure</font>
- **Plan your project design activities** in terms of time management using a suitable timing diagram (e.g. a Gantt Chart)
- Include the <font color=red>DR</font> in your timing diagram
- **Estimate the cost of your project based on utilisation of staff time** (this will be compared against the actual time/cost recorded during the project) – this has to be determined in the first week of the project
- Present **group capabilities**, **project plan**, **time schedule** and **cost estimate** at first meeting with your supervisor

## 2.9 V-Model Approach
1. System Design:
   1. Specification: 
      1. Project statement
      2. System Characteristics
      3. Operational Costs
   2. Requirements:
      1. Define input and ourput of your design
      2. Project planning
      3. Time management
   3. Modelling & Validation:
      1. Mathematical model
      2. Simulation environment for design and testing
   4. Control & Behaviour
      1. Automatic control
      2. Behavioural algorithms
2. Software Design of Soccer Team
      1. Critical design review
      2. Signing off stage
      3. Simulations and simulation based design (pitch presentation)
      4. Only if satisfactory, the project can move on
3. System Integration
   1. Hardware Implementation
      1. Access to the facility for tests
   2. System Test
      1. Implementing behavioural algorithms on real hardware
      2. Control shall be modefied accordingly
   3. Field Test
      1. Evaluation of performance
   4. Operation
      1. Ready to go and present your design
      2. Report and presentation