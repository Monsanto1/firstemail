# Lesson notes

## Lesson 1: October 17, 2018

We started pretty late at 2 AM setting up our workstations.

Step 1. Set up GitHub account.

  - URL: [github.com](github.com)
  - Purpose: Host our code projects or "repositories"

Step 2. Set up SSH key

  - Purpose: Create a secure connection to GitHub to be able to add commits.

  1. [Generate an SSH key on your computer](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#platform-windows). The "private key" will be called `id_rsa` and it will have a "public key" that will be called `id_rsa.pub`. Note: Obviously keep the private key secret. If you ever lose `id_rsa` or someone takes it, they can use your GitHub account without your permission. 
  2. [Add your SSH key to GitHub](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) Copy the contents of `id_rsa` and put it in the GitHub settings

Step 3. Install and configure Git on your computer

  - Purpose: Git is the software that will allow you to:

    1. Code collaboratively by sharing files (on GitHub)

    2. Track code changes for projects

  1. Install Git: [git-scm.com/downloads](https://git-scm.com/downloads)

  2. If on Windows, you may need to open a terminal that has Git open. (TODO: Document how to do this)

  2. Configure Git `user.name` and `user.email` to tell Git locally who you are.

Step 4. Install VSCode

Step 5. Create a code folder

Step 6. Clone Git repository into the code folder

Step 7. Open the repository folder in VSCode

Step 8. Make a change, commit it.

Step 9. Push your change and verify it made it to GitHub.