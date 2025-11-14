---
editor_options: 
  markdown: 
    wrap: 72
---

# Tech Lab 1: Team Collaboration Setup

*Use this document as your editable team workspace. Each section may be
filled in collaboratively during the activity or afterward for
submission. Between Sections 1 through 6, each team member must make at
least 4 edits to this document using Git, providing a Commit message
explaining briefly what the edit was and pushing your changes. For
Section 7, each member must provide their own reflections.*

## 1 Client Brief

**Client:** Andrew Sandall (Aditude)\
**Project:** Oregon Ad Bidding Dataset\
**Deliverables:**

-   Identify and document issues in data as well as corrections and
    transformations
-   Provide a Clean dataset
-   Carry out extensive Exploratory Data Analysis (EDA), including
    visualizations & summary insights
-   Share with client reproducible project folder

------------------------------------------------------------------------

## 2 Team Charter

### Roles & Responsibilities (these are just some examples, create roles as you see fit)

| Role                   | Name   | Responsibilities                       |
|------------------------|--------|----------------------------------------|
| Project Manager        | Nick   | Coordinates work, updates board        |
| Data Engineer          | Atefeh | Manages data imports, cleaning scripts |
| Analyst / Communicator | Henry  | Summarizes findings, writes reports    |

### Collaboration Policies

Specify your collaboration policies here -- your decision-making process
(e.g., majority vote tech choices, consensus deliverables), WIP
limits/person, Definition of Done (e.g., documented, peer-reviewed,
reproducible), who reviews the work, etc.

1)  Any decisions that create conflict/disagreement will be resolved
    through a majority vote.
2)  A task is considered "done" if it is peer-reviewed and reproducible.
3)  Each team member will have no more than two active WIP items.
4)  Throughout the process, it is important that we follow all data
    privacy and confidentiality requirements.

### Communication means and cadence

1)  The primary channel of day-to-day communication will be through
    discord.
2)  Communication will be supplemented through weekly stand-up meetings.

### Performance metrics

1)  Track the average cycle time it takes from task start to task
    completion for each team member.
    -   Increasing cycle time indicates over commitment or unclear
        requirements.
2)  Track the percentage of code that pass peer review without major
    revisions
    -   Our target rate is 90% passing rate.
3)  Create a biweekly anonymous survey to be completed by teammates.
    -   High scores reflect a healthy team dynamic.

### Completion Rituals

We will write a weekly or biweekly recap for our team's progress that
celebrates completed tasks, regardless of how big or small the "win" is.
------------------------------------------------------------------------

## 3 Board Setup

### Columns

Backlog → To Do → In Progress → Review → Done

### Sample Tasks

*These are just some examples, specify your own -- use some of them if
you'd like*

1.  Import raw bid data from `parquet` file
2.  Check data structure and column consistency
3.  Clean missing bid prices
4.  Remove duplicates based on URL + timestamp
5.  Convert timestamps to Oregon time zone
6.  Summarize bids per advertiser
7.  Visualize bid frequency by hour of day
8.  Explore geographic bidding density
9.  Create a data dictionary
10. Write EDA summary and client memo

------------------------------------------------------------------------

## 4 Daily Stand-Up Simulation Log

### Purpose

A 10-minute synchronization ritual to share progress, identify blockers,
and plan next steps.

| Team Member | Last Week | This Week | Blockers |
|------------------|------------------|------------------|-------------------|
| Henry | Cloned repo, pushed commit, merged branch | Wrote charter | Had trouble pushing commit |
| Nick | Cloned repo, pushed commit, merged branch, made Kanban board | Made Kanban Board | N/A |
| Atefeh | Cloned repo, pushed commit, merged branch | Pushed commit | Had trouble merging branch |

### Guidelines

-   Keep responses under 1 minute per person.
-   Discuss blockers **after** the stand-up.
-   Update the board live as items move through stages.

------------------------------------------------------------------------

## 5 Retrospective & Recalibration

**Discussion Prompts:**

1.  Which tasks got stuck or delayed? Why?

-   Although we aren't into the meat of the project yet, some tasks have
    already been delayed slightly. The main issues we had early were
    fixing the conflicts that arose when teammate's tried to push
    changes to the same line of code. Additionally, one team member
    struggled with creating and merging a branch. Most of these issues
    arose because two of our team members are not nearly as familiar
    with git as the other, but we were able to resolve these issues
    without too much strain.

2.  Did your “Definition of Done” work? If not, what will you change?

-   Our definition of done defined in our team's charter is that work is
    peer-reviewed and reproducible. This definition has worked so far as
    it allowed us to identify mistakes made when attempting to push
    commits and merge branches. By asking other team members to review
    work on git, we were able to get past the roadblocks we've
    encountered. Therefore, our definition of "done" has worked well.

3.  Were communication channels effective?

-   Our communication channels have been effective. The charter outlines
    that our primary channel of day-to-day communication will be through
    a team discord, which has already been effective. We held our first
    weekly stand-up meeting on discord, and in this meeting we were able
    to discuss the blockers we've been dealing with. We were actually
    able to all of the initial blockers during the meeting, so
    communication channels have definitely been effective so far. One
    caveat to consider is that as the intensity of work increases, it
    may be necessary to increase the frequency of communication to
    ensure we stay organized. Overall, communication has been effective
    thus far, but we may need to make some adjustments.

4.  How will you update your workflow next time?

-   Our team has updated our workflow in an organized way, so there
    isn't many changes we need to make. However, one small thing to
    focus on in the future is to make sure our commit messages are
    slightly more descriptive and clear so other teammates can easily
    tell which changes have been made.

**Action Items:**

-   Adjust WIP limits or column layout.
-   Update team charter accordingly.

------------------------------------------------------------------------

## 6 Submission Checklist

☐ Screenshot of final Kanban board\
<img width="1906" height="940" alt="image" src="https://github.com/user-attachments/assets/0b2ab8e1-c325-4d67-9d56-3b16227f4c29" />

☐ Finalized Team Charter (with revisions)\
☐ Reflection responses (Section 5)\

------------------------------------------------------------------------

## 7 Reflection Questions (Individual)

1.  What was your role and what did you learn about team coordination?

-   Henry: My role is the analyst/Communicator. Although we're early on
    in the project stages, it is already clear to me that having defined
    roles makes it far easier to coordinate, which in turn allows team
    members to work effective on individual tasks as well as group
    tasks. In the future I would like to see us have slightly more
    structured communication so we're able to identify and solve
    blockers quickly.

-   Nick: My offical role is the Project Manager, though our roles may be more
          fluid than they would be in a corporate setting. Having worked on many
          teams in the past, I think that our team coordination is outstanding
          so far. I am always happy to make myself available to discuss the
          project or any technical blockers. 

-   Atefeh: My role is Data Engineer. From this project, I’ve learned how much easier
            team coordination is when everyone is clear about their responsibilities
            but still flexible when the team needs it. I’ve also noticed that
            open, frequent communication—especially about small uncertainties or
            blockers—really helps keep problems from piling up later.

2.  How did the Kanban system help (or hinder) your progress?

-   Henry: A very important aspect to keeping the project manageable is
    to structure the workflow. Although we haven't worked through many
    tasks yet, it is clear to me that the Kanban board will be an
    essential tool to keep the necessary structure. Not only is the
    board an organization tool, but it also provides a secondary method
    of communication because it allows us to see the progress of other
    team members.

-   Nick: Kanban is a great method to organize tasks, track progress, and 
          visualize the work that needs to be done. It allows each team 
          member to visually see the work that they have assigned to them,
          and can provide an overview of progress for the entire team. 

-   Atefeh: I don’t really have any negative comments about using Kanban so far.
    It’s been helping us keep things organized and in order. We can easily keep
    track of the process, see what everyone is working on, and even be more prepared
    for the next steps. I also like that it makes it clear what’s a priority and what’s
    still waiting, which makes coordinating as a team a lot smoother.

3.  What’s one improvement you would apply in a real consulting project?

-   Henry: The main improvement I would apply in a real consulting
    project would be to make communication structures slightly more
    rigid. Although I think our communication has been effective, we do
    not have a specific scheduled time for our weekly stand-up meetings,
    and we could probably update each other slightly more through our
    discord or Kanban board. In a real consulting project, having very
    defined communication processes between team members and with
    clients will be helpful.

-   Nick: This general methodology of teambuilding is extremely similar
          to teams that I have worked on both academically and professionally, 
          I would not make any substantial improvements.

-   Atefeh: One improvement I’d like to apply is setting a regular schedule to
            meet—either in person or online—to talk through the project progress.
            Having consistent check-ins would give us a better understanding of our
            teammates’ priorities, help us catch any misunderstandings early, and make
            sure we’re all aligned on next steps and deadlines.

------------------------------------------------------------------------


