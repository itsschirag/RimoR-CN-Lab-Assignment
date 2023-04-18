# RimoR-CN-Lab-Assignment
## How to Commit Files to GitHub
GitHub is a popular platform that allows developers to collaborate on code and share their projects with the world. In this README file, we will discuss the steps involved in committing files to GitHub.

### Prerequisites
Before you start committing files to GitHub, you will need the following:

- A GitHub account
- A local Git repository
- Git installed on your computer


### Step 1: Create a Repository
To commit files to GitHub, you need to create a repository. A repository is a place where you can store and organize your code. Here are the steps to create a repository:

- Log in to your GitHub account.
- Click the "+" icon in the top right corner of the screen.
- Select "New repository" from the dropdown menu.
- Give your repository a name and a description.
- Choose whether you want your repository to be public or private.
- Click the "Create repository" button.

### Step 2: Clone the Repository
Now that you have created a repository, you need to clone it to your local machine. Cloning creates a local copy of the repository on your computer. Here are the steps to clone the repository:

- Go to your repository's page on GitHub.
- Click the "Code" button.
- Copy the HTTPS URL provided.
- Open a terminal or command prompt on your computer.
- Navigate to the directory where you want to clone the repository.
- Type git clone followed by the URL you copied in step 3.
For example:

'''
git clone https://github.com/your-username/your-repository.git
'''
### Step 3: Add Files to the Repository
Now that you have cloned the repository, you can add files to it. Here are the steps to add files to the repository:

- Create a new file or copy an existing file into the repository directory on your local machine.
- Open a terminal or command prompt on your computer.
- Navigate to the repository directory.
- Type 'git add .' to stage all files in the directory or 'git add <filename>' to stage a specific file.
For example: 
  
'''
git add .
'''
or
  
'''
git add index.html
'''

### Step 4: Commit the Changes
After adding files to the repository, you need to commit the changes. Committing records the changes you made to the repository with a message describing what you did. Here are the steps to commit changes:

-Open a terminal or command prompt on your computer.
-Navigate to the repository directory.
-Type git commit -m "your commit message".

For example:

'''
git commit -m "Added index.html file"
'''

### Step 5: Push the Changes to GitHub
The final step is to push the changes you made to the repository to GitHub. Pushing updates the repository on GitHub with the changes you made. Here are the steps to push changes:

-Open a terminal or command prompt on your computer.
-Navigate to the repository directory.
-Type git push.
For example:
'''
git push
'''

### Conclusion
In this README file, we discussed the steps involved in committing files to GitHub. Remember to add, commit, and push your changes regularly to keep your repository up-to-date. With these steps, you can easily collaborate with other developers and share your projects with the world.
