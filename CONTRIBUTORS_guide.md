# Contribution Guide 

Make you and the world better again, welcome all to keep contribute and help on Bug-Bountry-Resources!

For people who successfully PR(Pull Request) will be add on `CONTRIBUTORS.md`.

## Table of Content

- [Contributors](#contributors)
- [Adding to the list](#adding-to-the-list)
- [To remove from the list](#to-remove-from-the-list)
- [Getting Started](#getting-started)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Helpful Resources](#helpful-resources)

 Contributors
--

- NAME:  [Your Name](Github URL)
   - PLACE:  your CITY, your COUNTRY
   - BIO: your bio! 
   
 Adding to the List
--

- Please add the resources to the `README.md` file and make sure that the edited list is in alphabetical order.
- Submit a pull request.
- [For more details](#getting-started)

 Removing from the List
--

- If you have any issues accessing any of the resources listed here, please let us know.

Getting Started
--

-  If you are new to Git and Github, it is advisable you go through [this
    link](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)
    before moving to the next step.

-  Fork the project on Github, [Help Guide to Fork a repository](https://help.github.com/articles/fork-a-repo/).
-  Clone the project.
-  Create a branch specific to the issue you are working on.

    ```shell
    git checkout -b update-readme-file
    ```

    - For clarity to yourself and others on the issue you're working on,   
      name your branch something like:  
      `update-xxx` or `fix-xxx` where `xxx` is a short description of the changes you're making.  
      For example `update-readme` or `fix-typo-on-contribution-md`.  

-   Open up the project in your favourite text editor, select the file you want
    to contribute to and make your changes.

  -  If you are making changes to the `README.md` file, you would need to have
     Markdown knowledge. Visit [here to read about Github Markdown](https://guides.github.com/features/mastering-markdown/) and [here
     to practice](http://www.markdowntutorial.com/)  

      - If you are adding a new project/organization to the `README.md`, make sure
             it's listed in alphabetical order.
      - If you are adding a new organization, make sure you add an organization
             label to the organization name. This would help distinguish projects
             from organization projects.

-  After making your changes in the new git branch then add your modified
   files to git, [How to add, commit, push an go](http://readwrite.com/2013/10/02/github-for-beginners-part-2/)

    ```shell
    git add path/to/filename.ext
    ```

    You can also add all unstaged files using:

    ```shell
    git add .
    ```

    Note, using a `git add .` will automatically add all files. You can do a
    `git status` to see your changes, but do it before `git add`.

-  Commit your changes using a descriptive commit message.

    ```shell
    git commit -m "Brief Description of Commit"
    ```

-  Push your commits to your Github Fork:

    ```shell
    git push -u origin branch-name
    ```

-  Submit a pull request.

    - Within GitHub, visit this main repository and you should see a banner
    suggesting to make a pull request. While you're writing up the pull
    request, you can add `Closes #XXX` in the message body where `#XXX` is the
    issue you're fixing. So an example would be `Closes #42` would close issue
    `#42`.  
    
Submitting a Pull Request
--

- What is a pull request?  
  [Visit link](https://yangsu.github.io/pull-request-tutorial/)

- If you decide to fix an issue, it's advisable to check the comment thread in
case there's somebody already working on a fix. If no-one is working on it at
the moment, kindly leave a comment stating that you intend to work on it so
other people don't accidentally duplicate your effort.

- In a situation where by somebody decides to fix an issue but doesn't follow up
for a particular period of time, say 2-3 weeks, it's acceptable to still pick
up the issue but make sure to leave a comment.

- *Note*: Every open-source project has a **`CONTRIBUTING.md`** file, please make
sure to read theirs before you open up a pull request, otherwise your pull
request may be rejected. However if you do not see any contributing.md file,
you can send a pull request but do it in a descriptive manner.

Helpful Resources
--

- [Pro GIT Book](https://git-scm.com/book/en/v2)

- [Try Git](https://try.github.io/)
