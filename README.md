# DATRO Consortium: 'gh-pages' Branch 

Welcome to the DATRO Consortium Monorepo.
Our Monorepo contains [Datro's Branches](#DATRO's Branches) in total, this one is entitled: 'gh-pages'.

### Detailed Structure

The table below shows the content of this branch includes all the websites, the Hβnβ Dashboard(gui), the technical documents and some media e.g. academy videos etc
    
| Path                      | Details                                                                             |
|:--------------------------|:------------------------------------------------------------------------------------|
|gh-pages/                  | Top level directory - mainly stuff to make things to work e.g. CNAME, index etc     |
|gh-pages/static/gui        | Serves as both the online demo and the end-users (localhost) dashboard              |
|gh-pages/static/files      | All the documents, this is our document library                                     |
|gh-pages/static/datro      | The [DATRO Consortium](https://datro.world "DATRO Consortium") Homepage             |
|gh-pages/static/hbnb       | The [Hotspotβnβ Software](https://hbnb.datro.world "Hotspotβnβ Software") Homepage  |
|gh-pages/static/slides     | All the slides, this is our slideshow library                                       |
|gh-pages/static/wave       | The Wave DApp website (JSECoin + Althea.net = Free Internet)                        |
|gh-pages/static/evr-network| The [EVR-Network](https://evr-network.datro.world "EVR-Network") Homepage           |


  - Everything above is hosted for free on github (gh-pages)
  - This branch, alongside other branches, means everyrthing can be stored in the same repo
  - Serverless: Makes the business very resilient to physical/ cyber attacks:
     - anyone wanting to collaborate on the website can easily grab a local offline copy and make changes
     - git pull/ sprase-checkout the directories/websites you want to work on:

         `mkdir /var/www/html` # if it doesn't already exist
         `git remote add origin https://github.com/unclehowell/datro.git`
         `git checkout -b my-custom-mods` # make new branch for your changes
         `git pull origin gh-pages'

  - the corresponding dynamic server-side files allow the cms for the website to be locally hosted e.g. run offline
  - the DATRO persistent-live USB disk image is also provided, to turn any PC into a fully-configured local workstation
  - Make changes, follow the sites COLLABORATE.md guide e.g. directly edit the source code or use the cms and its html export feature)
  - once you're done making changes, upload your changes to github and make a pull request to the `gh-pages-dev' branch.

#Datro's Branches

You are viewing the [gh-pages branch](https://github.com/unclehowell/datro/tree/gh-pages "gh-pages branch").
DATRO's 3 other branches are displayed in the table below:

| Branch                    | Details                                                                             |
|:--------------------------|:------------------------------------------------------------------------------------|
|[Net-Installer](https://github.com/unclehowell/datro/tree/net-installer "DATRO Net-Installer Branch") | Autonomous compiler script (creates fresh autonomous, self-building disk image e.g. Hotspotβnβ) |
|[Netlify](https://github.com/unclehowell/datro/tree/netlify "DATRO Netlify Branch") | A modified version of the HBnB Dashboard, used to showcase our collection of websites |
|[SubRepos](https://github.com/unclehowell/datro/tree/subrepos "DATRO SubRepos Branch") | Stores subrepos, giving DATRO a staging server of sorts, between users and developers |


To create anchor links that jump down to different sections of a README (as in an interactive table of contents), first create a heading:  
`#Real Cool Heading`  
  
The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading. Copy everything starting at the #:  
`#real-cool-heading` 
  
Wherever you want to link to your Real Cool Heading section, put your desired text in brackets, followed by the anchor link in parentheses:  
`[Go to Real Cool Heading section](#real-cool-heading)`  
  
    
      
        
          
      
    
      
See! Easy: [Go to Real Cool Heading section](#real-cool-heading)  
  
  
  
  
  
#Real Cool Heading  
This is a real cool heading with some real cool content.
