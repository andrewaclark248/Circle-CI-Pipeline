#### Step 1: Software Engineer
A software engineer has a github repository to which is submits code.

### Step 2: Github Repo
Github has a branch named main/master that Circle CI uses to run builds against. The github repo has a .circleci/config.yml that contains instructions on how to execute the app in CircleCI

### Step 3: Circle CI
Circle CI looks for a .circleci/config.yml in the root directory that contains info on how to excutre the pipeline. Everytime a commit it made to the master/main branch a new build is start in Circle CI. 

### Circle CI Runs the Follows steps

### Step 4: Install Front end dependenies
Install all front end dependencies via npm install

### Step 5: Install API dependenies
Install all api dependencies via npm install

### Step 6: Front end linting
Linting is used to ensure your application code is formatted in a way that is standarized. This peforms linting on all the front end code.

### Step 6: Front end build
Build the front end code so that it is formmated in a way the is both optomized and readable to a server.


### Step 6: Back end build
Build the front end code so that it is formmated in a way the is both optomized and readable to a server.


### Step 6: Deploy
Build both the front end and backend code to server.


### Step 7: Approval
Approval step required to deploy

