# XSD-JAXP-JAXB

## Cloning a Git Repository

To get a copy of an already existing Git repository, you need to clone it. Make sure you know the Git repository URL before starting the Clone Repository wizard in the IDE.

1.  Choose Team > Git > Clone from the main menu. The Clone Repository wizard displays.
    
    [![Clone Repository wizard](https://netbeans.org/images_www/articles/74/ide/git/clone-wizard-small.png)](https://netbeans.org/images_www/articles/74/ide/git/clone-wizard.png "Clone Repository wizard")
    
2.  At the Repository page, specify the path to a Git repository location, user name and password (you can save them for the future if required).
3.  (Optional) Click Proxy Configuration to display the Options dialog box and set the proxy server settings. Click OK when finished.
4.  Click Next to switch to the next step of the wizard.
5.  At the Remote Branches page, select the repository branch(es) to be fetched (downloaded) to your local repository. Click Next.
6.  At the Destination Directory page, specify the following:
    -   In the Parent Directory field, the path to the directory intended for the cloned repository on your hard drive (alternatively, click the Browse button and navigate to the directory).  
        The Parent Directory field is pre-filled with the path to the default NetBeansProjects directory where all NetBeans projects are stored.
    -   In the Clone Name field, the name of the local folder where the original project will be cloned to.  
        By default Clone Name is filled out with the actual Git repository name.
    -   In the Checkout Branch field, select the branch to be checked out into the working tree.
    -   In the Remote Name field, the name that represents the original repository being cloned.  
        origin is the default alias of the repository being cloned. It is a recommended value.
    -   Leave the Scan for NetBeans Projects after Clone checkbox selected to activate after-scanning right after the clone finishes. (The plugin searches for NetBeans projects in the cloned resources and offers to open the found projects.)
7.  Click Finish.  
    After a Git repository is cloned, the metadata .git folder is created inside the folder you selected in the wizard.

# Activity ONE - Clone this repository using NetBeans
# Activity TWO - Do The Workshops deescribed in the PDF using netbeans on your computer
# Activity Three - Commit the changes to github once you are done
