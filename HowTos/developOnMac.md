# Setting up the development environment on a Mac.

## Install eclipse

+ Download eclipse from [](http:/eclipse.org/downloads/) http://eclipse.org/downloads/. Select 'Eclipse for PHP developers'.
+ Double click the tar-ball to decompress the downloaded file.
+ Copy the eclipse directory to the Application folder.

## Setting up eclipse

+ Start eclipse.
+ Select a location for your Workspace. The standard location is `/Users/wim/Documents/workspace/`.

### Install GitHub plugin
+ First update your eclipse. Select `Help`-`Check for Updates`. It is important to have all the latest updates, because without these updates, the needed plugins cannot be installed. Restart eclipse after the updates are installed.
+ Select `Help`-`Eclipse Marketplace`
+ Search for GitHub Extensions.
+ Install GitHub Extensions.
+ Also install GitHub Flavored Markdown viewer plugin in the same way.
+ Select `Help`-`Install New Software...`
+ Enter `http://download.eclipse.org/egit/github/updates/` in the 'Work with' field.
+ Select `Collaboration` and click `Next` to install the GitHub plugins.
+ Restart Eclipse after the installation of the plugins.

### Download the DeepskyLog sourcecode
+ First make sure to fork DeepskyLog in GitHub. In your browser, go to `https://github.com/DeepskyLog/DeepskyLog/` and click the fork button.

![](/lhome/wim/Documents/Astronomy/DeepskyLog/Articles/HowTos/fork1.png) 

+ You will be asked where to fork this repository. Select your own account (for example ChrisWauters).

![](/lhome/wim/Documents/Astronomy/DeepskyLog/Articles/HowTos/fork2.png) 

+ In eclipse, select `File`-`Import`.
+ Select `Projects from Git`.
+ Select `Clone URI`.
+ Enter the link tou your personal GitHub fork of DeepskyLog. For example: `https://github.com/ChrisWauters/DeepskyLog/`. Also enter your GitHub Username and Password. Click `Next`. 
+ Select the master branch and click `Next` again.
+ Keep the proposed location where to store the sourcecode (`~/git/DeepskyLog`) and click Next.
+ Select `Import using the New Project wizard` and select `Finish`.
+ Select `PHP project`.
+ Enter a project name, for example `DeepskyLog`.


### Add GitHub Task List in eclipse
+ Select `Window`-`Show View`-`Other...`. Select `Task Repositories`.
+ Right click in the `Task Repositories` view and select `Add Task Repository...`.
+ Select `GitHub Issues`.
+ Enter `https://github.com/DeepskyLog/DeepskyLog/` in the Server field. Also add your GitHub User ID and password. Press `Finish`.
+ You will get the question: `Would you like to add a query to the Task List for this repository?`. Answer `Yes`.
+ Enter the title `Open Issues`. Click `Finish`.
+ To view the Issues, select `Window`-`Show View`-`Task List`.


