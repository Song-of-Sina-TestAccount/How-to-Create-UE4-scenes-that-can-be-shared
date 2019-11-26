# How-to-Create-UE4-scenes-that-can-be-shared
This is a detailed instructions on how to create new UE4 scenes from scratch which can be uploaded to Github and shared wth others.

### Note:
For now this only works for brand new UE4 scenes not pre-existing ones with location folders not already connected to a repository. If you haven't already pushed your own branch to 'Clone_UE4Repo_Test1' repository then do so before attempting this.

## Setup:
Visit the Song of Sina Organization here https://github.com/Song-of-Sina-TestAccount (you may need to request access from Jake). Once you have access you will receive an email to confirm this and select above the Song of Sina Organization link.

## Instructions:
1: Start by creating a new repo on on the Song of Sina organization. To do this select the green 'New' button. Under the 'Owner' dropdown select the Song-of-Sina Organization. Then under 'Repository Name' give a name, preferebly of what your project will be about. Select 'Public' then select 'Initialize this repository with a README'. Then select 'Add .gitignore' and from the drop down type and select 'UnrealEngine'. Finally press Create repository.

2: Now clone your repository by clicking the green clone button and select 'Open in Desktop'. Your Github Desktop app will open where you create a new folder for your repository to be saved in on your local machine and select 'Clone repository'.

### Important step
3: Now open Unreal engine and create a new project. You will have to select a location for your UE4 project to be stored to do this go to the 'Folder' section you must select the 3 dots on the side and select the folder you just created prior where your cloned repository is located. This links up your new UE4 project to the repository on your computer via your Github Desktop. Not selecting the same location folder as your cloned repository will give errors when trying to push your UE4 project back up to Github later on.

4: Name your Unreal project and select 'Create Project'. Now edit and change your new UE4 project and once your ready to upload to Github, save your project by pressing 'Save Current'.

5: Check Github Desktop and all your files changed will be displayed on the left. Add a Commit title and a comprehensive description of all changes you made and select 'Commit to Master'.

6: Now select Push to Origin (This current save of your UE4 project has become your master branch). Now check your Repository on Github and it should contain your files.
