# Note**
No specific UI instructions were provided, so I implemented a simple frontend using Django templates.
If there's a preference to use a different frontend technology like React with our backend serving as an API, I'm fully capable of making that transition.

![alt text](https://rightshero.com/public/assets/pp-assets/images/rh-logo.png)



# Software Engineer Task Assessment

This role will be part of the Rightshero software development team.

As a software engineer you are a part of a small but very efficient and multi-tasking team. 

The team is tasked with handling all the software aspects of our service.

# The task
The task will be a project contains one page have a 2 categories checkboxes
- [ ] Category A
- [ ] Category B

Unlimited subcategories of parent category (if it is hard to achieve the unlimited levels, you can set 3 levels hard-coded)
Should use Ajax

## Example
- [ ] Category A
- [ ] Category B

If user select “Category B”
The system will create another 2 checkboxes with

- [ ] SUB Category B1
- [ ] SUB Category B2

Selecting Sub Category B2 will create another 2 checkboxes

- [ ] SUB SUB Category B2-1
- [ ] SUB SUB Category B2-2
 And so on


# Notes
- We would be scoring for the below aspects of the assignment:
- DB,Architecture /Code (preferred MVC pattern), Security, Git
- You could use a framework to create the project from scratch (Laravel or Django).
- You should use MySQL or Postgresql Databases.
- Please use one table design in the database for all categories and subs.
- The code should contain comments with important information.

# Deliverables
- The project should be ready with docker compose (web service + DB).
- Once you're finished, submit a PR to this repo with your email in a commit message.
- The email should be the same as your email in the CV/Resume.
