# README Template Guide

Alyssa Comment from Google Doc: You might also want to note where the file is typically placed in the project folder and how it is displayed in GitHub/GitLab. (It's basically the front page when you visit the root folder for a project.)

To discuss with group: Going to throw a wrench into this process -- I've realized there are two types of README.  A repo has a root README which is usually an overview of the project so that makes sense.  But there is also cases where README are placed in a sub-folder within the repo with the intention of explaining the contents in the folder.  Not sure if we want to handle this delineation here in this template or provide two-templates....  
With that said, for a root readme, start with the title of the project.

Cameron's comment: +1 for having a second version of a sub-README for lower directories.
(I'd also note that while there are reasons for having a sub-README, there are usually better reasons for keeping it simple, and just having the one README. (This should be explained in a readme-theory doc.)

To discuss with group: how do we convey to readers that a README changes and evolves over time as the project matures? Specifically, should we include contact information in the README?

To discuss with group: including badges in README or not? What's the benefit?
Cameron's Comment: I'm against including badges and similar metrics. Reasons:
1. Keep to task.
2. Metrics change, and you are introducing a maintenance burden, which effectively means your README will become dated.
3. There are better places to find metrics data (E.g. from github metrics), don't repeat it here.


READMes are the first document users read. They tell users what they need to know about your project, if the project is relevant to the user, why they should be invested in the project, and how they can engage with the project. 

Users reviewing projects will expect to have a README available for review. All projects should have a README.

## The Project Logo
A project logo is optional, but helpful for users to visually identify your project. Many READMEs include a logo if the project already has an existing logo.

## The Project Name
The project name should be prominent and easy for the reader to identify. You may want to also consider adding the following to help identify the project:
- Project URL
- Name(s) of project owner(s)

    *Note: Consider that adding owners may be better suited for inclusion in a separate contact document instead*


## The Table of Contents
A Table of Contents is optional, but can be useful especially in the case of lengthy READMEs.

COMMENT FROM MORGAN: Assume TOC will eventually be built.  I believe github now will generate a TOC for a readme based on the Headers in the file if you give it a short-code

## Project description
The project description is the most critical part of your README. This is where you will describe what the project does, why the reader should care about your project, and how it will help the reader. This section should be succinct and clearly help the reader determine immediately whether the project is of use to them.  

Use active voice and strong verbs to describe your project. To help readers understand your project, you may also want to include screenshots or demo videos.

FOR VIDEOS AND SCREENSHOTS, COMMENT FROM MORGAN: This is really important, and worth indicating these assets should exist in the REPO and not on a 3rd party host.

(from Daniel Beck)
             With *(this project)* you can *(verb)* *(noun)*...
             *(This project)* helps you *(verb)* *(noun)*....
             Unlike *(alternative)*, *)this project)* *(verb)* *(noun)*... 

---

Example: 

---

## Who is the project for
State who may use the project and under what terms (preferable to state this information higher up in README - will help the reader evaluate whether the project is suitable for them).  

## Project prerequisites
List things you need to use the software and ideally include links to instructions/resources on how to install them. 

## Instructions for using project
Describe in a stepwise manner how to use the project. Include only essential information and ensure that it actually works. Steps may include:  

- How to get the project
- How to install the project
- How to configure the project
- How to run the project
- Common error messages/related details
- Tests (optional)
 
## Additional documentation
Include links (if available) and brief descriptions for more resources such as:
- Website
- Twitter handle(s) of project/project owner(s) 
- Relevant examples
- Next steps
- Features planned
- Known bugs
- Documentation files
- Man page
- Help command(s)
 
 
## How to get help
Include links and brief descriptions for avenues for assistance:
- Google group/mailing list 
- Email address(es)
- IRC, Slack, or Discord channels 
- Bug trackers
- Other support resources (such as Stack Overflow tags)
 
## Contributing guidelines
Include clear instructions on how users can help with the project.
 
- Open source projects: presence of these guidelines strongly indicates that project stakeholders have experience with working with new contributors.
  - Mode of contribution (e.g., via GitHub pull requests or patches mailed to a specific address)
  - Code style/requirements
  - Format for commit messages
- Closed source projects: instructions on how to report bugs.

## Resources
- [Daniel's Checklist](https://github.com/ddbeck/readme-checklist/blob/main/checklist.md)
- Daniel's Video ADD LINK