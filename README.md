# Open Source Contirbuting Steps
All the steps required to contribute to open source projects in one place.

## Setup

**1.** Read the Contributing guide for the project.

**2.** Fork the original("upstream") repository into your own GitHub account by clicking the
"fork" button at the top of the page.

![image](https://user-images.githubusercontent.com/90851899/195864012-11bf207c-abb7-418e-8f90-7f4be42984da.png)

**3.** Clone your forked repository onto your local machine by running something like
following command in your terminal/cli:
```bash
git clone https://github.com/your_username_here/project_name_here.git
```

**4.** Since you cloned the project to you local machine now you are connected with your forked
repositroy you did in step 2, you'll also want to connect to the original repository "upstream"
to your local machine to be able to pull new changes directly to your local machine. Do this by
running something like:
```bash
git remote add upstream https://github.com/original_repo/project_name.git
```
