# S.W.A.T. Website
  This is the FRC 1806 S.W.A.T. repository for the official website. This website has the ability to clock in students and 
  track their time data. This also has a newsletter system allowing for super easy updating of timely newsletters.
  
## Set Up (Installs)
  To get setup with working on this project you will need to download the repo, Git, Node, and the Firebase CLI
  
  * Git: https://git-scm.com/
  * Node: https://nodejs.org/en/
  * Firebase CLI ``` npm install -g firebase-tools ``` 
  > reference: https://firebase.google.com/docs/cli#windows-npm

## Set Up (Modifying | Contributing | Deployment)
  1. Download repo ``` git clone [repo url] ```
  2. Login to firebase through terminal ``` firebase login ``` 
  > In able to deploy you will need your google account to be added to the Firebase Console

### Basic procedure to follow when contributing
  1. Checkout a new branch to make your changes on
  2. Make changes to code base
  3. Commit and push changes to branch
  4. Create Pull Request (PR) in Github
  5. Do code review, ask for reviewers, etc.
  6. Squash and Merge into master

### Deploying
  **Please Be Cautious, this part should be done by someone who is knowledgeable in deploying, as these steps are for pushing changes to _LIVE_ website**
  
  1. Ensure you are added to Firebase Console
  2. Make sure there has been testing on changes
  3. Make sure on machine that you have latest pull from master
  4. To deploy changes ``` firebase deploy ```
  5. Wait and ensure website recieved deployment

  **There is still some things that can make the deployment process easier and automated, should be looked into.**

## File Structure
  
  * /public - Main directory containing website files
    - /css - All styling components
    - /pictures - All photos and images
      - /pictures/images/_u - Slide Show Images
    - /src - All backend and .js files
  
  

## Built with
 * This was made by scratch in **Github's** IDE **Atom**
  
 * The backend was made with *Javascript* and the powered by the **[Firebase SDK](https://firebase.google.com/)**
  
 * The frontend was made with *HTML5* and *CSS3*
  
 * The notifications you see while registering or clocking is **[Toastr](https://codeseven.github.io/toastr/)** by **[CodeSeven](https://github.com/CodeSeven)**
  
 * The slideshow on the homepage was built with **[Image Slider Maker](https://imageslidermaker.com/v2#doc-intro)**
  
 * The codebase also uses some **[jQuery](https://jquery.com/)**
  
## Authors
  * **Christian Sheridan** - *concept, design, and programming* - [Github Profile](https://github.com/casheridan)
  
  See also the list of [contributors](https://github.com/casheridan/swat-website/contributors) who participated in this project.
  
## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/casheridan/swat-website/blob/master/LICENSE.md) file for details
  
 ## Acknowledgments
* All of this was made possible by Google Firebase

* [FIRST | For Inspiration and Recognition of Science and Technology](https://www.firstinspires.org/)

* I got this idea from the fact that we just had paper signing in and the way to get off the books wasn't 
  efficient and we would miss people and or not know how many hours they had put into actually attending robotics. 
  Also we needed to get the name of Team 1806 S.W.A.T. out to the public and a way to give people that support S.W.A.T. 
  and easier way to keep in contact or information.
