# CapstoneProject

**Overview**

This is a cyperpunk themed text based game that will allow the user to go on an adventure to defeat a boss or two. This focuses on allowing muilitple ways to get through something or fight someone. There is no wrong way, just different paths.

**Backend Models**

Not all properties of the model will be used but are included if time permits usage

*User Model*
- username:
- password:
- arr_of active characters
- arr_of inactive characters
- achievements

*Character Model*
- name:
- stats_arr
- item_arr
- xp:
- equipment_arr
  - name:
  - mod1:
  - mod2:
  - mod3:
- game_ver
- secret_arr
- quests_arr
- time:
- score:
 
 **MVP**
 
 - Home page with login
 - about page
 - guide/instruction page
 - create character page
 - exploration area
 - power plant location
 - 'first' Boss
 - easy mode
 - simple story
 - some easter eggs
 
 **Post MVP Part 1**
 
 - medium mode
 - Modding Equipment
 - smelter/forge area
 - 'second' Boss
 - more easter eggs
 
 **Post MVP Part 2**
 
 - Hard Mode
 - Modding Character
 - 'crusher' area
 - 'third' Boss
 - even more easter eggs
 
 **Post MVP Part 3**
 
 - story depth
 - Factory area
 - Final Boss
 - score system
 - make a new model on the backend for high scores
 - I think I'm going to need more easter eggs
 
 ## Components

Will have more conponents depending on needs of the App. These are general aspects or base conponents with many children; its going to be more complicated with many components.

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include Base React Router| 
| Log-in | This is the home page | 
| Nav-Bar | This will have links to non game pages | 
| About | Gives information about me and what tech was used in the app | 
| Information | Gives information about game mechanics | 
| List of Characters | This becomes the new home page after log in | 
| Create Character | User creates a character here |
| Tutorial/Start | Basic user choice and set up the game and user enters the scapyard | 
| Scrapyard | Exploration/home location where character can find supplies and mod things | 
| Power Plant | 'first' boss is located here, electric themed battles | 
| Smelter | 'second' boss is located here, fire themed battles | 
| Crusher | 'third' boss is located here, physical themed battles |
| Factory | Final boss is located here, don't want to spoil surprise |
| Battle | Battler conponent for basic fights |
| Backend | Will host data and some functions |

| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| App | H | 1 hrs|  hrs |
| Log-in | H | 1 hr| hrs |
| Nav-Bar | H | .5 hrs |  hrs |
| About | H | 2 hrs | hrs |
| Information | L | 4 hrs | hrs |
| List of Characters | M | 2 hr| hrs |
| Create Character | H | 3 hr| hrs |
| Tutorial/Start | M | 2 hr| hrs |
| Scrapyard | H | 10 hr| hrs |
| Power Plant | H | 20 hr| hrs |
| Smelter | L | 12 hr| hrs |
| Crusher | L | 8 hr| hrs |
| Factory | L | 12 hr| hrs |
| Battler | M | 4 hr| hrs |
| First Boss | H | 4 hr| hrs |
| Second Boss | L | 3 hr| hrs |
| Third Boss | L | 3 hr| hrs |
| Final Boss | L | 6 hr| hrs |
| Backend | L | 3 hr| hrs |
| Backend: User Data | L | 3 hr| hrs |
| Backend: Functions | L | 3 hr| hrs |
| Total | H | 106.5 hrs|  hrs |

| Objective | Day | Actual Day |
| --- | :---: |  :---: |
| Gatsby Reasearch | - 2 | 1 |
| Component Setup | 1 | 1 |
| Balance Functionality | 2 | x |
| Stoich Functionality | 3 | x |
| SCSS for Site | 4| x |
| Wiki | 4 | x |
|Bug Fixing/try to break | 5 | 5 |

**Additional Libraries**
-React
-Firebase
