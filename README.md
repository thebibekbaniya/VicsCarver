# VicsCarver 

VicsCarver is built to carve images and videos using Encase (Enscript Programming Language).  

### Terms and Conditions of use

The software/script is provided "as is", without warranty of any kind, express or implied including but not limited to the warranties of merchantability, fitness or a particular purpose and non-infringement. In no event shall developers be liable for any claim, damages or any other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with software/script or the use or other dealings in the software/script.

#### This software/script is subject to continued development; if you experience any issues with this software, please advise the developers.

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

### History

The initial script was handed to us (Allen LaFontaine and Bibek Baniya) by Simon Key. We changed the script from C4ALL to project VIC data output.

### Resources
* Export JSON Schema- [Project VIC](https://www.projectvic.org/contact/)
* Enscript Programming Language - [OpenText](https://developer.opentext.com/)
* Encase Forensic Software - [OpenText](https://security.opentext.com/encase-forensic)

## Create a pull request

* Sign into your GitHub account, or create a free GitHub account if you don't have one.
* "fork" the repo by clicking the Fork button in the upper right corner. This creates a copy of the project repository in your GitHub account.
* While still in your repository, click the green Clone or download button and then copy the HTTPS URL. ```git clone https://github.com/[your username]/VicsCarver.git```
* Check that your fork is the "origin" remote. If you don't see an "origin" remote, you can add it. To view, ```git remote -v``` and to add, ```git remote add origin https://github.com/[your username]/VicsCarver.git```
* Add the project repository as the "upstream" remote. ```git remote add upstream https://github.com/thebibekbaniya/VicsCarver.git```
* Before you start making any changes to your local files, it's a good practice to first synchronize your local repository with the project repository. ```git pull upstream main```
* Rather than making changes to the project's "main" branch, it's a good practice to instead create your own branch. This creates an environment for your work that is isolated from the main branch. ```git checkout -b [your username]_[purpose of pull]```
* Use a text editor or IDE to make the changes you planned to the files in your local repository. Because you checked out a branch in the previous step, any edits you make will only affect that branch. 
* After you make a set of changes, use git add -A to stage your changes and git commit -m "DESCRIPTION OF CHANGES" to commit them. To add files ```git add -A ``` and to commit  ```git commit -m "[Description of Changes]"```
* When you are done making all of your changes, upload these changes to your fork using git push origin BRANCH_NAME. This "pushes" your changes to the "BRANCH_NAME" branch of the "origin" (which is your fork on GitHub). ```git push origin [your username]_[purpose of pull]```


``` 
git clone https://github.com/[your username]/VicsCarver.git

cd VicsCarver

git remote -v

git remote add origin https://github.com/[your username]/VicsCarver.git

git remote add upstream https://github.com/thebibekbaniya/VicsCarver.git

git remote -v

git pull upstream main

git checkout -b [your username]_[purpose of pull]

git branch

git add -A

git commit -m "[Description of Changes]"

git push origin [your username]_[purpose of pull]
```
