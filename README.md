<section id="header">
  <div align="center" id="header">
 
  # How to Write a README

  **Written by [Amar Pan](https://www.linkedin.com/in/profpan396/)** 
  <br>
  Sr. Instructional Associate
  </div>
  
  <div align="center" id="socialbuttons">

  [![Portfolio Badge](https://img.shields.io/badge/-profpan396.github.io-magenta?style=flat&logo=)](https://profpan396.github.io)
  <br>
  [![LinkedIn Badge](https://img.shields.io/badge/-@profpan396-blue?style=flat&logo=Linkedin&logoColor=black)](https://www.linkedin.com/in/profpan396/)
  <br>
  ![Stars](https://img.shields.io/github/stars/profpan396/how-to-write-a-readme?style=social)
  ![](https://visitor-badge.laobi.icu/badge?page_id=profpan396.how-to-write-a-readme)
  ![Forks](https://img.shields.io/github/forks/profpan396/how-to-write-a-readme?style=social)
  <br>
  ![Version](https://img.shields.io/badge/version-2.0-gold)

  ### If you find this tutorial helpful, please consider giving it a :star:

  </div>

  <div align="center" id="intro">

  This tutorial describes how to write a coding bootcamp project README in GitHub Flavored Markdown and HTML in 30 minutes or less.

  </div>

  <div id="before-you-begin">

  ## Before You Begin

  Complete the following steps prior to getting started:

  ### 1. Visit the README gold standards:
  - [P1 Simon](https://github.com/profpan396/simon-memory-game)
  - [P2 Review My Project](https://github.com/profpan396/review-my-project)
  - [P3 GA HW Tracker](https://github.com/profpan396/ga-hw-tracker)
  - [P4 Meet Your Classmates](https://github.com/profpan396/meet-your-classmates)


  ### 2. Complete the following Introduction to Markdown tutorial (10 mins):
  - [Markdown Tutorial](https://www.markdowntutorial.com/)

  ### 3. Read (skim) through the official GitHub Flavored Markdown documentation:
  - [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

  </div>

  <div id="header-1">

  ## Header

  <u>Requirements:</u> 

  1. A banner representing your app

  | Description | Screenshot | 
  |:-----------:|:----------:| 
  | <h3> **Example Header** </h3> | <img src="./images/OPTIONAL-PROJECT-BANNER.png"> |

  <div align="center">

  ### **Copy and paste the following:**

  </div>

  ```html
  <div id="header" align="center">

    <img src="https://i.imgur.com/y2SPx4E.jpg" width="800" height="400">

  </div>
  ```

  ### Tips - Header 

  1. Royalty-free stock photos can be found on [Pexels](https://www.pexels.com/), [Pixabay](https://pixabay.com/), or [Unsplash](https://unsplash.com/).                              
  2. Use a free photo editing tool like [Photopea](https://www.photopea.com/) to streamline the editing process by importing images from URLs and exporting your finished banner directly into [imgur](https://imgur.com/). 

  </div>

  <div id="description">

  ## Description

  <u>Requirements:</u> 
  1. App name
  2. What problem the app solves and how
  3. How to win (if app is a game)

  | Description | Screenshot | 
  |:------------:|:---------:| 
  | <h3> **Example Description** </h3> | <img src="./images/GOOD-DESCRIPTION-SOLO.png" width="800"> |

  <div align="center">

  ### **Copy and paste the following:**

  </div>

  ```html
    <div id="description" align="center">

    # Meet Your Classmates
  
    ### [CLICK TO DEMO](https://meetyourclassmates.herokuapp.com/)
  
    ##### Amar Pan

    [![LinkedIn Badge](https://img.shields.io/badge/-@profpan396-blue?style=flat&logo=Linkedin&logoColor=black)](https://www.linkedin.com/in/profpan396/)

    ## :pencil: Description

    Meet Your Classmates is a hub where students can get to know and relate to their peers via completion of short 3-question
    mini-surveys. By learning about others' backgrounds, previous experiences, and
    interests, an atmosphere of community is created that is conducive to higher
    levels of learning and success.

    </div>
  ```
  
  ### Tips - Description            
                    
  1. Add your deployed link directly to the top - most users won't scroll all the way down to find it.                                                                                                                                            
  2. Use emojis by typing in `:emojiname:` 

      a. Visit the following resource for a full list of available GitHub emojis:  

        [GitHub Emojis Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md). 

  3. In version 1.0 of this tutorial, I suggested to add emojis around your `h1` tag. However, this is bad practice for Search Engine Optimization (SEO). 

  #### **<u>Note</u>**: 

  Install the following extension to see GitHub emojis in VS Code:

  - [Markdown Emoji](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji)

  </div>

  <div id="screenshots">

  ## Screenshots

  **<u>Requirements</u>**: 
  1. Screenshots of your app's home page and any other pages of interest

  | Description | Screenshot | 
  |:------------:|:---------:| 
  | <h3> **Example Screenshots** </h3> | <img src="./images/GOOD-SCREENSHOTS-SOLO.png"> |
  
  <div align="center">

  ### **Copy and paste the following:**

  </div>

  ```html
    ## :camera_flash: Screenshots 

    |   Description | Screenshot | 
    |:-------------:| -----------|
    | <h3>Feed Page</h3> | <img
      src="https://github.com/profpan396/meet-your-classmates/blob/main/public/Screenshots/FeedPage.png?raw=true"
      width="700"
    /> |
    | <h3 align="center">Profile Page</h3> | <img
    src="https://github.com/profpan396/meet-your-classmates/raw/main/public/Screenshots/ProfilePage.png"
    width="700"
    /> |
  ```
  ### Tips - Screenshots 

  1. Whatever is placed in between `<details></details>` will be hidden beneath a closed drop-down menu until its arrow is clicked on. The caption for this should be placed in between `<summary></summary>`.
  2. To have a drop-down menu display as open by default, (without the user having to click it) add the word 'open' to the details tag.                                                                                    
  </div>

  <div id="technologies-used">

  ## Technologies Used

  **<u>Requirements</u>**: 
  1. List of the technologies used

  | Description | Screenshot | 
  |:------------:|:---------:| 
  | <h3> **Example Technologies Used** </h3> | <img src="./images/GOOD-TECHNOLOGIES-USED-SINGLE.png"> |

  <div align="center">

  ### **Copy and paste the following:**

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

  ### Tips - Technologies Used

  1. Additional badges of this style can be found at the following resource: 
      - [Shields.io Website](https://shields.io/)          
  2. Alternative badges of a more colorful style can be found at the following resource:
      - [Badges 4 README](https://github.com/alexandresanlim/Badges4-README.md-Profile) 

  </div>

  ## Getting Started

  **<u>Requirements</u>**: 
  1. A link to the deployed app
  2. A link to the Trello board used for the project's planning that includes:
      - a. user stories
      - b. wireframes
      - c. entity relationship diagram (ERD)

| Description | Screenshot | 
|:------------:|:---------:| 
| <h3> **Example Getting Started** </h3> | <img src="./images/GOOD-GETTING-STARTED-SINGLE.png"> |

<div align="center">

### **Copy and paste the following:**

</div>

```html
## :fire: Getting Started

<details open>
  <summary> How to Create a Post </summary>
    1. Type in your answers to each of the 3 randomly-generated mini-survey questions.
    2. Click on "Add Survey" to post your responses so others may see them.
    3. Click on the "X" in the bottom-right corner to delete a post.
</details>

<details>
  <summary> How to Interact With Others' Posts </summary>
    1. Posts may be "liked" or "disliked" by clicking on the thumbs up or down button on their card.
    2. To reveal the author of a post, hover over the `Who could it possibly be?` button.
    3. To see more posts by the same user, click on the revealed username and profile picture.
</details>

<details open>
  <summary> Trello Board </summary>
  <a href="https://trello.com/b/x4ViComX/meet-your-classmates-project-4"
    > https://trello.com/b/x4ViComX/meet-your-classmates-project-4 </a
  >
</details>

<details open>
  <summary> Deployed Link (Heroku) </summary>
  <a href="https://meetyourclassmates.herokuapp.com/"
    > https://meetyourclassmates.herokuapp.com/ </a
  >
</details>
```

### Tips - Getting Started

1. Use numbered lists as opposed to lengthy paragraphs to make sure this section is easily readable.                             
2. Put your links in more drop-down menus using `<details open>` and `<summary>`. 
3. Try to choose something simple and memorable when choosing your URL / link name.

## Upcoming Features

**<u>Requirements:</u>**
1. Planned future enhancements (icebox items)

| Description | Screenshot | 
|:------------:|:---------:| 
| <h3> **Example Upcoming Features** </h3> | <img src="./images/GOOD-NEXT-STEPS-SINGLE.png"> |

</div>

<div align="center">

### **Copy and paste the following:**

</div>

```markdown
## :satellite: Upcoming Features

- [:star:] Animations on sliding buttons

- [:x:] Comment functionality on posts to encourage discussion

- [:x:] ~~Tinder API Integration~~
```

### Tips - Upcoming Features

1. Avoid using the word `icebox`, as most non-technical users probably won't know what this means.                            
2. Use bullet points rather than paragraphs to make it immediately clear what each new feature would be.
3. Just for fun, add an easter egg joke using double tildes (~~) for a crossout 

## The Final Product

| Description | Screenshot | 
|:-----------:|:---------:| 
| <h3> **Example Final Product** </h3> | <img src="./images/GOOD-FULL-README.png"> |

<div id="hall-of-fame" align="center">

<section id="footer">

  ## README <br> HALL OF FAME <br> :trophy::star2::trophy:

  | Designer | Project | School | Location | Date
  |:--------:|:-------:|:------:|:--------:|:---:
  | [Nisha Yadav](https://www.linkedin.com/in/nisha-yadav09/) <br> :india: | [Minesweeper](https://github.com/nisha-yadav09/minesweeper) | General Assembly | Denver, Colorado, USA | Apr '22 
  | [Ronald Portalatin Jr.](https://www.linkedin.com/in/ronaldportalatinjr/) | [Blackjack](https://github.com/coltonsaywhatt/GA-Blackjack-Project) | General Assembly | Lakeland, Florida, USA | Apr '22 
  | [Jordan-Christopher Garcia](https://www.linkedin.com/in/jctgarcia20/) | [Shoe Collector](https://github.com/jctgarcia20/shoe-collector) | General Assembly | Seattle, Washington, USA | May '22 
  | [Stevie Militello](https://www.linkedin.com/in/stevie-militello/) | [Tavern Brawl](https://github.com/steviemilitello/tavern-brawl) | General Assembly | Boston, Massachusetts, USA | May '22 
  | [Dani Diaz](https://www.linkedin.com/in/danidiaz8/) <br> :peru: | [Dino Amigo](https://github.com/dani-diaz/dino-amigo2) | General Assembly | El Cerrito, California, USA | Jun '22
  | [Illerdon Ballinger](https://www.linkedin.com/in/ilerdon-ballinger/) | [Turbo Disco](https://github.com/iballinger/turbo-octo-disco) | General Assembly | San Mateo, California, USA | Jun '22 
  | [Joseph Caputo](https://www.linkedin.com/in/josephcaputo44/) | [Vinyl Stash](https://github.com/jcaputo44/vinyl-stash) | General Assembly | San Diego, California, USA | Jun '22 
  | [Maroof Khan](https://www.linkedin.com/in/maroofkhn/) <br> :india: | [Crypto Sniffer](https://github.com/MaroofKhan1/CryptoSniffer) | General Assembly | Minneapolis, Minnesota, USA | Jun '22 
  | [Matthew Suzuki](https://www.linkedin.com/in/mattsuzuki/) | [Community Market](https://github.com/mattsuzuki/community-market) | General Assembly | Los Angeles, CA, USA | Jun '22 
  | [Parker Samuels](https://www.linkedin.com/in/parkersamuels/) | [Checkers](https://github.com/prkrsamuels7/checkers) | General Assembly | Detroit, Michigan, USA | Jun '22 
  | [Roger Davila](https://www.linkedin.com/in/roger-davila/) | [Solitaire](https://github.com/Toastito/solitaire) | General Assembly | San Francisco, California, USA | Jun '22 
  | [Sophia Best](https://www.linkedin.com/in/sophiabest/) | [ThreadUp](https://github.com/sophiabest/ecommerce) | General Assembly | Louiseville, Kentucky, USA | Jun '22 
  | [Joba Aladeselu](https://www.linkedin.com/in/joba-a-ja11/) | [Oja](https://github.com/jobaa11/product-design-app) | General Assembly | Los Angeles, California, USA | Sep '22 
  | [Alex Houston](https://www.linkedin.com/in/alexehouston/) | [Sailor Moon Concentration](https://github.com/alexehouston/concentration) | General Assembly | Houston, Texas, USA | Oct '22 

  </div>

  <div id="footer" align="center">

  ## Contributions
 
  |  Name | Title | Contribution |
  |:------|:-----:|:------------:|
  | <a href="https://www.linkedin.com/in/jimclarkfullstack/"> Jim Clarke <br> :goat: </a> | Distinguished Global Lead Instructor @ General Assembly | Teaching <br> :man_teacher:
  | <a href="https://www.linkedin.com/in/profpan396"> Amar Pan, M.Ed. <br> :india: </a> | Sr. Instructional Associate @ General Assembly <br><br> Technical Writer @ <a href="https://www.linode.com/docs/guides/"> Linode </a>  <br><br> House Pan Founder | Writing <br> :pencil:
  | <a href="https://www.linkedin.com/in/mariorrecinos/"> Mario Recinos <br> :guatemala: </a> | Sr. Instructional Associate @ General Assembly <br><br> Coach @ <a href="https://www.careerkarma.com"> Career Karma </a> <br><br> House Rec Founder | Outreach <br> :teacher:
  | <a href="https://www.linkedin.com/in/skimalee/"> Stephanie Lee, M.Ed. <br> 🇰🇷 </a> | Sr. Instructional Associate @ General Assembly <br><br> House Lee Founder | Support <br> :woman_teacher:
  | <a href="https://www.linkedin.com/in/neilitalia/"> Neil Italia <br> :philippines: </a> | User Interface Developer @ Lennox International | UI <br> :paintbrush:
  | <a href="https://www.linkedin.com/in/olivia-emery/"> Olivia Emery <br> :crown: </a> | Technical Writer @ Google | Editing <br> :pen:
  | <a href="https://www.linkedin.com/in/isaac-ferraro/"> Isaac Ferraro <br> :beetle: </a> | Front-End Developer @ Helium | Quality Assurance <br> :ballot_box_with_check:

  ### If you found this tutorial helpful, please consider giving it a :star:

  Copyright :copyright: 2021-2022 <br> Pan You Can

  ## More Tutorials from Amar Pan

  [How to Create a GitHub Profile](https://github.com/profpan396/how-to-create-a-github-profile)

  [How to Change Themes in Z Shell](https://github.com/profpan396/how-to-change-themes-in-zshell)

  [How to Use the Vim Text Editor in the Terminal](https://github.com/profpan396/how-to-use-the-vim-text-editor)

  </div>

</section>