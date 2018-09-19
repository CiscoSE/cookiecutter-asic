# cookiecutter-asic

A submission template for the Americas SE Innovation Challenge (ASIC)

This template was created using
[cookicutter](https://github.com/audreyr/cookiecutter)


# Getting Started - Initial Submission

### 1. Create your project from this template.

  ```
      $ pip install cookiecutter
      $ cookiecutter https://github.com/CiscoSE/cookiecutter-asic.git
  ```

  You will be asked about your basic info (name, project name, app name, etc.). This info will be used in your new project.

  #### Sample Output

  ```
  $ cookiecutter https://github.com/CiscoSE/cookiecutter-asic.git
  project_name [my-awesome-python-project]: my-awesome-app
  project_description [PoC code for doing something really awesome]:
  author_name [John Smith]: Cisco SE
  author_email [jsmith@company.com]: ciscose@cisco.com

  $ cd my-awesome-app
  $ tree
  tree
  .
  ├── AUTHORS.md
  ├── CODE_OF_CONDUCT.md
  ├── CONTRIBUTING.md
  ├── LICENSE
  └── README.md

  ```

  **NOTE:** make sure to remember what directory you run the previous commands in
  as your new project directory will be created here.

### 2. Update your projects README with pertinent information for submission phase.

  These are outlined as **TODO** items in the generated [README.md](https://github.com/kecorbin/cookiecutter-asic/blob/master/%7B%7B%20cookiecutter.project_name%20%7D%7D/README.md)

  **TIP:** If you are unfamiliar with Markdown some good resources are located here:

  * https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf
  * https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

### 3. Commit and push your project to github.

  Once you've completed the required changes to your projects README.md file, create a repository on github and push your work

  ```
  git init
  git add .
  git commit -m 'initial submission'
  git remote add origin https://github.com/<your github id>/<your project name>
  git push -u origin master
  ```

#### 4. TBD - Submit your project to program

Provide link to connections page / smartsheet

# ASIC Background

### Program Structure:

The SE Innovation challenge will be a quarterly challenge. Each SE team must build a complete solution in a given quarter that incorporates the programmability/API interfaces of existing Cisco platforms to solve a real customer business/technical challenge.

### Team Structure

Minimum of 2 SE’s representing a minimum of 2 segments (Geographic exceptions may be considered). Any SE role in the Americas SE organization is eligible to participate

### Focus

SE teams will form to develop solutions based on identified customer/technical challenge/opportunity. Solutions should be developed based on leveraging existing programmability interfaces in current platforms

### Goals

Drive Cross platform innovation- SE teams will develop complete, customer focused solutions that incorporate multiple technology stacks, I,e. Spark+DNAC, NSO+APPD, etc

### Judging:

The completed SE Innovation Challenge projects will be judged and stack ranked by a cross-segment panel of SE leaders and programmability experts.
