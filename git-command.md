# Git Commands

## Basic concepts

### Remote Repository / Repo

Remote repository is your repo / project in the web / cloud. That's your main location for you projects/repo.

### Local Repository

Local repository is your repo / project inside your local machine.

### Clone

Cloning is downloading / copying your project from the remote repo to your local machine, thus making newly cloned repo a local repo. Files and folders from your remote repo is copied.

Before you can edit a repo / project from the remote location, you must clone it first to your local machine.

### Commit

If you have any changes to your project files in your workspace and wants to override the previous remote files with the new one, you must first commit those changes. It's like saving all those files you modified and include those files to the new modified remote repo.

### Push

Push is uploading your new or modified files to the remote repo to override. Remember commit is *NOT* sending your modified files to the remote repo, it only saves and includes the file(s) to be finally pushed.

### Pull

If someone other than you push their commits so that the remote repo are now modified, and you want to have those changes in your local repo also before committing or pushing, then you must pull those changes to your local repo.

## Initializing a repository / creating a project

`git init`

From inside your chosen directory, where your project is currently located, initialize to make that directory your repository.

## Staging

Staging means preparing your files to be committed / save. You can't commit / save files you didn't stage. Therefore, before committing your files you must stage them. But how?

`git add index.html`

The command above tells git to put the `index.html` to the stage, meaning we want that specific file to be prepared so we can
