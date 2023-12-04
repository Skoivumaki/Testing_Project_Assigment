
## Summary (Summarize the bug encountered concisely)

Bug locks create project page form after one successful creation in a frozen state. 

## Steps to reproduce     

User must be logged in
Navigate to https://gitlab.com/users/sign_up/groups/new#blank_project
Enter any Group Name
Enter any Project Name
Submit Form to create new project
Go back in browser to last page (Go back one page (USED FIREFOX))

## What is the current bug behavior?

Entering any Group Name and any Project Name. After submiting and reversing back one page form freezes, unable to create a new project.

## What is the expected correct behavior?

Create new project form should expect user the ability to create multiple projects in one session and after backing one page back. User should be able to create a new project without issues.
     
## Relevant logs and/or screenshots

      https://photos.app.goo.gl/fLPFj7ypNGQqKGRC6
      Image shows entire form to be locked in frozen state.
      No matter what input fields user changes the form will not be accesible again. Form is completly frozen.
      "Create project" button greyed out

## Possible fixes

Message the user that they are unable to create new additional projects this way.
Tell the user to goto new create new project page again.

## Whom do you report/ Assign To/ Tags

Developers, Web designers, Backend

## Priority

Not essential since bug is easy to bypass by double backtracking to earlier page.
