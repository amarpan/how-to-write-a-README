 <div align="center" id="header">
   <h1>
      How to Write a <br> General Assembly (GA) <br> Software Engineering Immersive (SEI) <br> Coding Bootcamp <br> Project README <br> 
      <img src="https://emoji.slack-edge.com/T0351JZQ0/ga/bc337c95a83930af.png" width="24" height="24">
   </h1>

   <h3>
      Written by <a href="https://www.linkedin.com/in/profpan396/">Amar Pan, M.Ed.</a>
      <br> 
      Instructional Associate
   </h3>

   <div id="socialbuttons">
      <a href="https://profpan396.github.io" target="_blank">
        <img
          src="https://img.shields.io/badge/-profpan396.github.io-magenta?style=flat&logo=Blackberry&logoColor=black" />
      </a>
      <br>
      <a href="https://www.github.com/profpan396/" target="_blank">
        <img
          src="https://img.shields.io/badge/-@profpan396-junglegreen?style=flat&logo=GitHub&logoColor=black">
      </a>
     <a href="https://www.linkedin.com/in/profpan396/" target="_blank">
         <img src="https://img.shields.io/badge/-@profpan396-blue?style=flat&logo=Linkedin&logoColor=black">
      </a> 
      <a href="https://medium.com/@profpan396">
         <img src="https://img.shields.io/badge/-@profpan396-pink?style=flat&logo=medium&logoColor=black">
      </a>
      <br>

   ![](https://visitor-badge.glitch.me/badge?page_id=amarpan.readme-writing-tutorial) 
      <img alt="GitHub commits" src="https://img.shields.io/github/last-commit/profpan396/how-to-write-a-GA-SEI-README">
      <img src="https://img.shields.io/github/stars/profpan396/how-to-write-a-GA-SEI-README"/>
      <br>
      <img src="https://img.shields.io/badge/version-1.3-gold">

   </div>
   <p>
      This tutorial and template describes how to write a coding bootcamp project README in HTML and GitHub-flavored Markdown in 20 minutes or less.
   <p>
    
#### ***If you find this tutorial helpful, please consider giving it a :star:
</div>



<div id="description">

  <h2 align="center"><strong><u>Header & Description</u></strong></h2>

  <p align="center"><strong>Requirements:</strong> App name, what it does, and optional background info.</p>

  <div align="center"> 
    <img src="./images/GOOD-DESCRIPTION-SOLO.png" width="800">
  </div>
</div>

  ```html
  <div align="center">
  <h1>
  :school_satchel: :school: MEET YOUR CLASSMATES :school: :school_satchel:
  </h1>

  <h3>https://meetyourclassmates.herokuapp.com/</h3>

  <h5>Your Name</h5>

  <a href="https://www.linkedin.com/in/username/" target="_blank">
  <img
    src="https://img.shields.io/badge/-@username-blue?style=flat&logo=Linkedin&logoColor=white"
  />
  </a>

<h1>:pencil: Description</h1>

<p>
Meet Your Classmates is an Instagram-clone and hub where students can get to
know and relate to their peers via completion of short 3-question
mini-surveys. By learning about others' backgrounds, previous experiences, and
interests, an atmosphere of community is created that is conducive to higher
levels of learning and success.
</p>

</div>
```

<div align="center">

| Tips             |
|------------------|
| Integrate styling by using `<div align="center"></div>` to center text.                                                                                                       
| Add your deployed link directly to the top - many users won't scroll all the way down to find it.                                                                                                                                            
| Use emojis by typing in `:emojiname:` <br> Example: `:school:` ---> :school: <br> Check out [ this list of available GitHub emojis](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).                                                                                                                                   
| **While emojis show automatically on GitHub, to see them on VS Code one needs to install an extension like [Markdown Emoji](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji). Some emojis may also look completely different on VS Code than GitHub.**
</div>
</div>

<hr>

<div id="screenshots">

  <h2  align="center"><u>Screenshots</u></h2>

  **Requirements**: Screenshots of your app's landing page and any other pages of interest.
  <div align="center"> 
     <img src="./images/GOOD-SCREENSHOTS-SOLO.png">   
  </div>

```html
<details>
  <summary>:bar_chart: ERD</summary>

  | Description | Screenshot | 
  |:------------:|-----------| 
  | <h3>ERD</h3> | <img
    src="https://``github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/ERD.MYC.png"
    width="700"
  /> |

</details>

<details>
  <summary>:art: Wireframes</summary>

  |    Description    | Screenshot | 
  |:-----------------:|-------------| 
  | <h3>Home Page</h3>| <img
    src="https://github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/Homepage.Wireframe.MYC.png"
    width="700"
  /> |
  | <h3 align="center">Profile Page</h3> | <img
    src="https://github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/ProfilePage.Wireframe.MYC.png"
    width="700"
  /> |
</details>

<details open>
  <summary>:gear: Functionality</summary>

  |   Description | Screenshot | 
  |:-------------:| -----------|
  | <h3>Feed Page</h3> | <img
    src="https://github.com/amarpan/meet-your-classmates/blob/main/public/Screenshots/FeedPage.png?raw=true"
    width="700"
  /> |
  | <h3 align="center">Profile Page</h3> | <img
    src="https://github.com/amarpan/meet-your-classmates/raw/main/public/Screenshots/ProfilePage.png"
    width="700"
  /> |
</details>
```
| Tips 
|--------------
| To set up a table use:
| `Description \| Screenshot \|`
| `:----------:\|------------\|`
| `caption    \|    image   \|`
| Whatever is placed in between `<details></details>` will be hidden beneath a closed drop-down menu, until its arrow is clicked on. The title for this should be placed in between `<summary></summary>`.
| To have a drop-down menu display by default without the user having to click it, add the word 'open' to the details tag. <br> <u><strong>Example:<strong></u> `<details>` --> `<details open>`                                                                                                      
| Image dimensions can also be resized by specifying width and height. <br> <u><strong>Example:<strong></u> `<img src="" width="300" height="400">`                                                                                                                                                                                                                                                        |
</div>
<hr>

<div id="technologies-used">

<h2  align="center"><u>Technologies Used</u></h2>


**Requirements**: List of the technologies used.

<div align="center"> 
   <img src="./images/GOOD-TECHNOLOGIES-USED-SINGLE.png">
</div>
</div>

```markdown
## :computer: Technologies Used
A screenshot of your app's landing page and any other screenshots of interest.

![MongoDB](https://img.shields.io/badge/-MongoDB-05122A?style=flat&logo=mongodb)
![Express](https://img.shields.io/badge/-Express-05122A?style=flat&logo=express)
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)
![Node](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=node.js)
![Semantic UI React](https://img.shields.io/badge/-Semantic%20UI%20React-05122A?style=flat&logo=semanticuireact)
![AWS S3](https://img.shields.io/badge/-AWS_S3-05122A?style=flat&logo=amazons3)
![JWT](https://img.shields.io/badge/-JSON_Web_Tokens-05122A?style=flat&logo=jsonwebtokens)
![Mongoose ODM](https://img.shields.io/badge/-Mongoose_ODM-05122A?style=flat&logo=mongodb)
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)
![HTML5](https://img.shields.io/badge/-HTML5-05122A?style=flat&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=css3)
![Trello](https://img.shields.io/badge/-Trello-05122A?style=flat&logo=trello)
![Heroku](https://img.shields.io/badge/-Heroku-05122A?style=flat&logo=heroku)
![Canva](https://img.shields.io/badge/-Canva-05122A?style=flat&logo=canva)
![Markdown](https://img.shields.io/badge/-Markdown-05122A?style=flat&logo=markdown)
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)
![Github](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)
![VSCode](https://img.shields.io/badge/-VS_Code-05122A?style=flat&logo=visualstudio)
![Vim](https://img.shields.io/badge/-Vim-05122A?style=flat&logo=vim)
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)
![Django](https://img.shields.io/badge/-Django-05122A?style=flat&logo=django)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql)
![Materialize CSS](https://img.shields.io/badge/-Materialize_CSS-05122A?style=flat&logo=materialdesign)
```

   <div align="center">

| Tips |  |
|--------------|--|
| Note: | Additional custom badges can be found at [the shields.io website.](https://shields.io/)                                        |
| Note: | For a list of more colorful badges, [check out this repository.](https://github.com/alexandresanlim/Badges4-README.md-Profile) |

</div>
</div>

<hr>

<h2  align="center"><u>Getting Started</u></h2>

**Requirements**: 
- A link to the deployed app
- A link to the Trello board used for the project's planning that includes user stories, wireframes, and ERD

<div align="center"> 
   <img src="./images/GOOD-GETTING-STARTED-SINGLE.png">
</div>


```html
<h2>:fire: Getting Started</h2>

<h3>:calling: Instructions</h3>
<details open>
  <summary>How to Create a Post</summary>
  <ol>
    <li>
      Type in your answers to each of the 3 randomly-generated mini-survey
      questions.
    </li>
    <li>
      Click on "Add Survey" to post your responses so others may see them.
    </li>
    <li>Click on the "X" in the bottom-right corner to delete a post.</li>
  </ol>
</details>

<details>
  <summary>How to Interact With Others' Posts</summary>
  <ol>
    <li>
      Posts may be "liked" or "disliked" by clicking on the thumbs up or down
      button on their card.
    </li>
    <li>
      To reveal the author of a post, hover over the "Who could it possibly be?"
      button.
    </li>
    <li>
      To see more posts by the same user, click on the revealed username and
      profile picture.
    </li>
  </ol>
</details>

<details>
  <h3>:link: Links</h3>
  <summary>Trello Board</summary>
  <a href="https://trello.com/b/x4ViComX/meet-your-classmates-project-4"
    >https://trello.com/b/x4ViComX/meet-your-classmates-project-4</a
  >
</details>

<details open>
  <summary>Deployed Link (Heroku)</summary>
  <a href="https://meetyourclassmates.herokuapp.com/"
    >https://meetyourclassmates.herokuapp.com/</a
  >
</details>
```

<div align="center">

|       | Tips                                                                                      |
| ----- | ------------------------------------------------------------------------------------------------- |
| Note: | Use numbered lists as opposed to lengthy paragraphs to make sure this section is easily readable. |
| Note: | Put your links in more drop-down menus using `<details open>` and `<summary>`.                    |
| Note: | Try to choose something simple and memorable when choosing your Heroku URL / link name.           |

<hr>

<h2  align="center"><u>Next Steps</u></h2>

**Requirements** : Planned future enhancements (icebox items).



<div align="center"> 
   <img src="./images/GOOD-NEXT-STEPS-SINGLE.png"> 
</div>

</div>

```markdown
## :fast_forward: Next Steps

### Upcoming Features

- [x] Add gifs to animated sliding buttons

- [ ] Add comment functionality on posts to encourage discussion

- [ ] Add edit and update functionality for a user's profile

- [ ] ~~Add Tinder API Integration~~
```

<div align="center">

|       | Tips                                                                                           |
| ----- | ------------------------------------------------------------------------------------------------------ |
| Note: | Avoid using the word "icebox," as most non-technical users probably won't know what this means. |
| Note: | Use bullet points rather than paragraphs to make it immediately clear what each new feature would be.  |

<hr>

<h2 align="center"><u>The Final Product</u></h2>

<div align="center">
 <img align="center" src="./images/GOOD-FULL-README.png">  
</div>

<!-- <h4>Today we learned how to convert an average README into one that instantly catches the eyes of employers.</h4>
<h4>Despite not being able to use proper CSS to change colors and styles, we can actually add a lot of customization and fine-tuning with the right Markdown shortcuts.</h4> -->

<hr>

<h1 align="center">Optional Additions</h1>
<h2 align="center"><u>Header Banner</u></h2>

<div align="center"> 
   <img src="./images/OPTIONAL-PROJECT-BANNER.png"> 
</div>

</div>

```html
<div align="center">
  <img src="https://i.imgur.com/y2SPx4E.jpg" width="800" height="400" />
  <h1 align="center">plantrade</h1>
</div>
```

<div align="center">

| Tips: |  |
|---------------|--|
| Note: | Royalty-free stock photos can be found on [Pexels](https://www.pexels.com/), [Pixabay](https://pixabay.com/), or [Unsplash](https://unsplash.com/).                                                               |
| Note: | Free photo editing tools like [Photopea](https://www.photopea.com/) can streamline the editing process with their ability to import images from URLs and export images directly into [imgur](https://imgur.com/). |

<hr>

<h2 align="center"><u>Emoji Commits</u></h2>

<div align="center"> 
   <img src="./images/OPTIONAL-COMMITS.png" width="800" /> 
</div>

</div>

```console
git commit -m ":pencil2: fix typo on cart page"
```

<div align="center">

|       | Tips                                                                   |
| ----- | ------------------------------------------------------------------------------ |
| Note: | GitHub-friendly commit emojis can be found on [gitmoji](https://gitmoji.dev/). |

<hr>

<h2 align="center"><u>Horizontal Image Scroll (Carousel)</u></h2>

<div align="center"> 
   <img src="./images/OPTIONAL-CAROUSEL.png" width="800" /> 
</div>

</div>

```html
<pre>
  <img src="https://i.imgur.com/NdzHyyX.png" width="700" height="500" />
  <img src="https://i.imgur.com/XIxBAcO.png" width="700" height="500" />
  <img src="https://i.imgur.com/tYVxWvF.png" width="700" height="500" />
  <img src="https://i.imgur.com/vRjshke.png" width="700" height="500" />
  <img src="https://i.imgur.com/qap5IXS.png" width="700" height="500" />
</pre>
```

<!-- <div align="center"> -->

|       | Tips                                    |
| ----- | ----------------------------------------------- |
| Note: | This works best with images of similar heights. |

<div>
<hr >
<div align="center">
<h2 align="center"> <u> :trophy: README HALL OF FAME :trophy: </u> </h2>
</div>
</details>
 </h5>
 <details open>
<summary>   
Amar Pan - GA SEI Nov '21 - Portland, OR   
</summary>
<h4> 
 
Project #1 (P1): https://github.com/profpan396/simon-memory-game
 
<br>
 
Project #2 (P2): https://github.com/profpan396/review-my-project <br><br>
 
Project #3 (P3): https://github.com/profpan396/ga-hw-tracker <br><br>
 
Project #4 (P4): https://github.com/profpan396/meet-your-classmates 
 
</h4>
</details>

 <details open>
<summary>   
Parker Samuels - GA SEI Jun '22 - Detroit, MI
</summary>
<h4> 
 
Project #1 (P1): https://github.com/prkrsamuels7/checkers
 
</h4>
</details>

<details open>
<summary>   
Roger Davila - GA SEI Jun '22 - San Francisco, CA
</summary>
<h4> 
 
Project #1 (P1): https://github.com/Toastito/solitaire
 
</h4>
</details>

<!-- <details open>
<summary>
Neil Italia - GA SEI Oct '21 - Dallas, TX (McKinney / Frisco)
</summary>
<h4>

https://github.com/neilitalia/ilovehue

https://github.com/neilitalia/plantrade

https://github.com/neilitalia/spacex-flights


</h4> -->

<h2 align="center"> <u>Further Reading</u> </h2>

|       |                                                                                                                             |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Note: | For a quick introduction to Markdown writing format, check out [this no-nonsense Markdown tutorial](https://www.markdowntutorial.com/). |
| Note: | Read through the [official GitHub-flavored Markdown documentation](https://github.github.com/gfm/) for further reference.               |

 <!-- ## Future Updates 

 </div>
 </div>

- [x] Add contributions
- [x] Add examples from other GA students
- [x] Add code samples
- [x] Add horizontally-scrolling images how-to
- [ ] Add table of contents
- [x] Add technologies used buttons for everything learned in GA SEI
- [x] Add 'Further Reading' section with links to Markdown tutorials and documentation -->

<h2 align="center"> <u>Contributions</u> </h2>
 
|  Name | Cohort | Title | Contribution |
|-------|--------|-------|------|
| <a href="https://www.linkedin.com/in/profpan396">Amar Pan</a> | GA SEIR <br> Nov '21 <br> Los Angeles | Technical Writer @ Linode | Literally Everything
| <a href="https://www.linkedin.com/in/jimclarkfullstack/">Jim Clarke</a> | GA SEI <br> Jan '15 <br> Los Angeles | Distinguished Lead Instructor @ General Assembly | Outreach
| <a href="https://www.linkedin.com/in/olivia-emery/">Olivia Emery</a> | GA SEI <br> Nov '15 <br> San Francisco | Technical Writer @ Google | Editing
| <a href="https://www.linkedin.com/in/neilitalia/">Neil Italia</a> | GA SEIR <br> Oct '21 <br> Dallas | User Interface Developer @ Lennox International | Writing - Optional Additions

| <a href="https://www.linkedin.com/in/profpan396">Mario Recinos</a> | GA SEIR <br> Dec '21 <br> Los Angeles | General Assembly Ambassador @ Career Karma | Outreach
| <a href="https://www.linkedin.com/in/profpan396">Amar Pan</a> | GA SEIR <br> Dec '21 <br> Los Angeles | General Assembly Ambassador @ Career Karma | Outreach
| <a href="https://www.linkedin.com/in/profpan396">Amar Pan</a> | GA SEIR <br> Nov '21 <br> Los Angeles | Sr. Instructional Associate @ General Assembly | Outreach

<div align="center">
 
#### ***If you found this tutorial helpful, please consider giving it a :star:
 
 </div>
  
<!-- <details>
<summary>Amar Panjwani - GA SEI <br> Nov '21 - Los Angeles, CA (Apple Valley) - Tech Support at Summit Medical</summary>
      <h4>
      Conception, Writing, Screenshots, Organization, Code Instructions / Explanations, Search Engine Optimization, Design, Social Media Preview Banner Creation, Interviewing Other Engineers
   </h4>
   </details>

<details>
<summary> (McKinney / Frisco) </summary>
<h4> UX / UI, Code Samples, Header Banner, Emoji Commits, Carousel Horizontally Scrolling Images Slider</h4>
</details>

<details>
<summary>Olivia Emery - GA SEI Oct '15 - San Francisco, CA (Mountain View) - Technical Writer @ Google</summary>
<h4> Editing, Suggestions for Clarity of Writing</h4>
</details>


<details>
<summary>Isaac Ferraro - GA SEI Nov '21 - Seattle, WA (Bremerton)   </summary>
<h4> Suggestions, Proofreading, Editing, Quality Assurance </h4>
</details>

<details>
<summary>Miguel Urena - GA SEI Nov '21 - Los Angeles, CA (Anaheim)   </summary>
<h4> Suggestions, Graphic Design, Social Media Rich Preview Banner, Quality Assurance </h4>
</details> -->
