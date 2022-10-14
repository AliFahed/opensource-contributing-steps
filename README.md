# Open Source Contirbuting Steps
All the steps required to contribute to open source projects in one place.

<details open>
  <summary><h2>Setup</h2></summary>
  
  
**1.** Read the Contributing guide for the project.

**2.** Fork the original("upstream") repository into your own GitHub account by clicking the
"fork" button at the top of the page.

![image](https://user-images.githubusercontent.com/90851899/195864012-11bf207c-abb7-418e-8f90-7f4be42984da.png)

**3.** Clone your forked repository onto your local machine by running something like
following command in your terminal/cli:
```bash
git clone https://github.com/your-username-here/project-name-here.git
```

**4.** Since you cloned the project to you local machine now you are connected with your forked
repositroy you did in step 2, you'll also want to connect to the original repository "upstream"
to your local machine to be able to pull new changes directly to your local machine. Do this by
running something like following command:
```bash
git remote add upstream https://github.com/original-repo-name/project-name.git
```
</details>

<details open>
  <summary><h2>Workflow</h2></summary>
  
- Whenever you want to contribute always do it in a new branch not the main code base, then
after you finish adding/modifying whatever you want to do you will merge it with main.
  
### Steps to Create New Branch

**1.** Create new branch by running the following command:
```bash
git branch branch-name
```

**2.** Switch to the new branch you just created, and start work on whatever you want:
```bash
git checkout branch-name
```

**3.** When you are done with your work, odds are that someone has made changes to the
original repository "upstream", that means you need to pull/fetch new changes from "upstream"
by running:
```bash
git fetch upstream
```

**4.** Now switch to main branch by running:
```bash
git checkout main
```
and then run the following command to merge new changes in "upsteram" to origin your forked
repo.
```bash
git merge upstream/main
```

**5.** Now that your main branch is up-to-date with upstrem, merge main branch into your new
branch you created in step 1, switch to your created branch:
```bash
git checkout branch-name
```
then merge main into it:
```bash
git merge main
```
  
</details>

<details open>
  <summary><h2>Make a Pull Request</h2></summary>
  
**1.** To send your created branch to "upstream" you need first to push the branch to
your forked repo, by running:
```bash
git push origin branch-name
```

**2.** Finally, Submit the pull request in GitHub Interface. Go to your forked repo
you will notice a notification that have a make pull request button, click it and follow
the steps, make sure to follow the instructions if the project have a pull request template,
and write good description on what you did to make it easier for mentors to understand your
changes.

### OSS Contributer 
</details>
