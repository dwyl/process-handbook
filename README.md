# Master Reference

Contains our processes, questions and journey to creating ateam.

This is very much a work in progress. Please [add an issue](https://github.com/dwyl/ateam-master-reference/issues) for anything you would like to see discussed here!

All of this is predicated on the assumption that you care about your clients and you care about delivering quality code. Go into this with a positive attitude!

## End of Sprint Process

At the end of every sprint there is a **sprint demo** with the client. In essence this involves showing the client which of the stories outlined in the sprint milestone have been successfully achieved and how you achieved them. As well as discussing which stories were not completed, why and what the next steps for dealing with these should be.

In our experience to date, this is a delicate point for teams where it is relatively easy to lose control of the demo and the client is left feeling unsatisfied even if you have made great progress in your sprint.

**Guidelines for conducting a sprint demo:**
+ **Time Boxing**   
Before the demo, set the expectation of how long you think the demo will be through a calendar invite. The demo duration includes the demo itself + any questions you think the clients (or anyone else) might have. This shows that you’re organised and it prevents any inadvertent time wasting by time boxing it. It gives you a reference point that you can point to if you notice that you’re running over time (_a passionate client can talk for hours if you let them!_)
+ **Location**  
Ensure that you're holding your sprint review/demo somewhere where you and everyone involved has good access to a screen displaying your milestone / issues on GitHub.
Unless you are *constantly* referring to the project board (*in our case the GitHub issues list*) it's *very* easy for people to get side-tracked. We/You need to ***constantly re-enforce*** the team looking at the project management ***system*** to ensure it gets used appropriately, otherwise chaos ensues rapidly...
+ **Decide who will be driving the demo**  
The demo will usually be introduced by the scrum master or the product owner (_the person with the most demo experience on the team_). The demo will then be handed over to the developers who have been working on it as they begin to go through the user flow. At any given time, the person with the most experience on a certain aspect of the application should be talking about it. This should be pre-decided before the demo so that everyone knows their responsibilities.
+ **Recap on lessons learnt from previous demos**  
It's always good to reflect on what worked well in the past and also what didn't. This can help you avoid mistakes you may have made before and also leverage the things that went particularly smoothly. Make sure you have someone taking notes for you during the demo so that you can focus on delivering it at the time, and then you can review your performance afterwards.
+ **Remind yourself of the project status**  
Review your backlog and take note of all the work you have done in the sprint.
+ **Have all changes merged into `master` at least half a day before the demo**
 The rushed changes you make in the last half a day are usually the changes that break everything and cause stress during the demo. Your last day/half a day should be for polish and bug fixing from the merges, not for functionality.
+ **Know your audience!**  
Be sympathetic to who you're delivering your demo to. If they aren't technical then they won't appreciate any of the technical detail that you could go into. Your job is to be prepared for any technical questions that may be asked but it shouldn't be the focus of the demo. Don't describe what it is, describe how what you've done adds value to their application.
+ **Link Your Scope**    
In your walkthrough try and tie all of the work you've done to the proposed scope (milestone). If you haven't completed all of the deliverables that you've agreed upon make sure that you have a think beforehand about what needs doing, and how you're going to solve this moving forward.
+ **Have prepared notes/script**   
Prepare notes/ a script which details what you're going to cover during the demo to help you feel prepared and calm during the demo and to ensure that nothing is left out.
+ **Breathe**  
This can be nerve wracking and taking some deep breaths will help slow you down!  

### Overview of Steps
1. **Context** of the sprint/demo
2. **Walkthrough** of the product
3. **Review** the stories completed in the sprint (*let the person who did the* ***work*** *do the talking*)
4. **Close** the sprint **milestone** on GitHub
5. **Wrap up** the demo
6. **Invoice** the client (*ASAP*)

#### Step 1 - Context
Start the demo by providing some introductory context such as what the aim of the sprint was and what you'll be demonstrating. The purpose here is two-fold; it sets up the demo but ***more importantly*** it allows attendees time to gently have a little time to switch their attention away from their previous tasks (or meeting they have just come from), slow down and focus on the task at hand. If the demo isn't going to look like what the client was expecting, ensure that you explain this before you start so that they have a bit of time to digest why this is the case (***reduce the shock factor***) and what you're going to do about it.

#### Step 2 - Walkthrough
Walk through the proposed demo, paying close attention to:
+ Picking up on any small niggles the client may notice, can you pre-empt the client bringing it up by proposing a solution as you're doing the demo?
+ Are there things you're actually still not 100% sure are working the way the client intends? Ask the questions during the demo so they know you're looking out for their needs
+ Mention all of the work that has been done (especially if additional work has been done that wasn't originally expected)

#### Step 3 - Review the Stories
This part of the process will be repeated for each of the stories listed under the sprint milestone. Start with one story. For each story you have a couple of possible actions to take:
- **If the issue is already closed:** talk through how the delivering the story has gone and
confirm whether the original time estimates were met (*or why the task took more time than originally predicted*).

Estimating and tracking time is the ***single*** most important factor to manage in a software project, it's how we show the Product Owner / client that we are providing value-for-money and helps us to plan future sprints with *any* degree of accuracy. This is where other teams fall down.

- **If the issue is still open:** discuss why it is still open, how long it's been taking to complete and what still needs to be done (and how long that will take). If the issue is still relevant and in need of imminent completion remove it from the current sprint milestone and label it for the next sprint milestone. When you move the issue make sure you leave a comment within it which explains the current progress on the issue and why it's being moved to the next sprint. If the issue is now no longer a priority or something is blocking it and will be for a considerable period consider placing it in the backlog milestone.

In both instances ensure you mention what was learnt along the way.

#### Step 4 - Close the Sprint Milestone on GitHub

Once the previous sprint's stories have been reviewed and moved to the relevant places your milestone should now be 100% complete. At this point you should **close** the **milestone** on GitHub:
![please-close-completed-sprints](https://cloud.githubusercontent.com/assets/194400/11141396/dd7dcafa-89dc-11e5-9b08-014af837a38a.png)

#### Step 5 - Wrap Up the Demo
Once you've completed your run-through of the demo, recap on what you've talked about and then ask if there are any questions (_from either side_). Discuss your plans for the next sprint in terms of deciding on a date to confirm a new scope of work.

#### Step 6 - Invoice the Client
As soon as the Product Owner (client) is satisfied that the agreed stories for the sprint have been delivered, prepare and send the ***invoice before anything else***.

### Sprint Planning
This may be done immediately after a sprint demo or otherwise on a time/date agreed at the end of the sprint demo.
- Discuss upcoming deadlines and agree on the next sprint duration. Generally we work in 2 week sprints however from time to time if a deadline dictates that this is no possible, we may work in a shorter sprint ie. a week. Be cautious when considering running longer sprints, sprints are called sprints for a reason and are not designed to be extremely long periods!
- Review how many/ what kinds of issues you may already have added to the milestone that were unfinished from the previous sprint.
- According to the size of your team/ length of your sprint, review your repo's issues paying attention to the priority labels. Alter the priority labels so that last sprint's priority 2 are now this sprint's priority 1 (and so on). Only assign a realistic number of issues to the sprint. If there are too many of the same priority to assign to the next sprint, discuss what can be delivered and ask the client to clarify in order to dictate what goes ahead.
- Assign time estimate labels to the issues getting input from relevant team members to improve accuracy.

TO ADD:
+ [x] Timing of demo
+ [x] Who drives? Definitely you!
+ [x] How to wrap up
+ [ ] Release notes
