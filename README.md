# a-walk-in-the-park
![alt text](image.png)
## project purpose
 A site for local walkers or visitors to the area of Greater Manchester. The sites main purpose is to get people to sign up to the newsletter by engaging those who are interested in finding both popular walks and the hidden gems for those seeking a more quiet and natural atmosphere. The aim of the site's design will be to engage users by giving them easy viewing and finding of walks with a gallery to entice them to sign-up and walk in the area. Walks will be rated, give estimated walk distance, location and show an images in each card.
## User Stories
Who, Why, Because...

1. A visitor to the area of Manchester wants to find a list of walks accompanied with images created by locals to pick a walk before investing travel time.
- Bootstrap cards provide an image, location text and button which opens to show a google maps pin of the location.
2. A new visitor to the site wants to find local curated walks which highlight how long and difficult a walk is to ensure it is appropriate for their level of fitness.
- Bootstrap cards contain walk length and difficulty rating in stars
3. A Frequent site user wants to view more/ new walks in a date of post format added to the listings before picking one for the weekend.  
4. A frequent user wants to see if the walks suit their families fitness or accessbility level when viewing walk cards.
5. A returning user wants to sign up for the newsletter so they can be kept informed of any newly added walks and also to send a list of selected walks to their inbox.
- a fixed signup button is in the bottom right corner. Clicking this opens a modal form which requires validated Name and Email to subscribe.
6. A returning user wants to be able to provide feedback by contacting the site admin in a Contact Us section.
- The contact us page has a form where free text can be entered along with selecting a reason for contact in a drop down box.
7. A frequent user wants to be kept up to date and sign up to the newsletter so they do not need to visit the site to check for updates daily.
## Features
### Homepage
 The site landing page. Utilises Bootstrap grids, navbar and cards. Large title with an autoplay, looped and muted video followed by an aerial shot of Manchester city with the bee overlayed on top. A large button "Sign up to Newsletter!" opens a Bootstrap Modal form. The first thing a new visitor sees is the banner title and a short looping video of a person walking into the distance. The signup button remains in a fixed position in the bottom right corner so a user can easily choose to open the form from anywhere on the homepage. An image of Manchester City is overlayed with a bee - synonamous with Manchester since the MEN disaster - and is used to contrast with the following natural imagery in the walk cards. The cards contain a relevant image, card title, distance, difficulty rating, walk type and location. Common icons were chosen to easily show intent without a descriptive word. The card button will open a new tab and direct the user to a googlemaps dropped pin where the area resides.
 #### Modal form
 The modal opens on clicking the signup button. It shows a form for the user to complete and requires the following: First and Last name as text. Email address with format checking ( @ symbol in an email). Submit button which only works when all information is valid.
 ### Gallery 
 This page contains a masonry styled image gallery. On mouse hover, some image text is overlayed.
### Design
#### Colour scheme
![alt text](assets/images/22-4-25-new-clr-palette.png)
Coolors was used to help generate a pleasing, natural feeling colour palette consisting of earthy tones. The Dark Cyan and Apple Green feature heavily as background colours. Eerie black is the main font colour.
#### Fonts

Fonts were chosen on GoogleFonts.
Rubik Dirt is used for H1 headings and card titles.
Montserrat Alternates is used for smaller headings and sub-headings.
Main block text font uses Amiko.
#### Imagery

Images used are of local areas around the Greater Manchester area and other than the video are all genuine images. Images were selected to highlight the areas of natural beauty and to insipire site visitors to want to experience the areas shown themselves. 
### Wireframes


## Technology
Bootstrap 5.3* used to assist with the styling and responsiveness. In particular, it was required for the gallery and Walk cards.

GoogleFonts used to acquire appropriate friendly fonts to give a welcoming and casual feel to the sites text. (link them)

FontAwesome used to get some outdoor and walking related icons for use throughout the headings

Coolors was used to generate contrasting colour palettes: https://coolors.co/

To create documentation imagery, AmIResponsive can display the site on different media sizes: https://ui.dev/amiresponsive

For the landing video, Coverr was used: https://coverr.co/

Microsoft's Copilot AI was used to help generate the bee image. 
## Testing

## Deployment
Deployment is done using Github and Github Pages. 

### Repo
The project repository is here:
https://github.com/RSapsford89/a-walk-in-the-park

The repository consists of the main branch and one merged branch 'new-homepage-layout'. Midway through the project, feedback suggested a more spacious and better colour palette would suit the site's design better. Once the new page layout and colours had been built and tested on it's own branch it could then be merged to the Main branch.

Github Projects was used to log some bugs and feature changes through the development of the site. This is the kanban style visual layout to help monitor tasks an also mark off completed ones:
 https://github.com/users/RSapsford89/projects/1



### Page Hosting

The page link is:
https://rsapsford89.github.io/a-walk-in-the-park/

Hosting is carried out via Github Pages. The creation of this is done by choosing which branch of the project you wish to be made live in the Project > Settings > Pages area. By selecting Main, the most recently pushed 'main' branch is made the live, viewable page.

## Future Improvements



* signup btn should change to better contrasting colour
* signup btn initial state colours need setting
* add img alt texts
* sort out the buttons! Colors once highlighted/pressed should not be blue.
* add table styles if keeping -looks ok in white, but need to scale for mobile
* get rid of accessiblity card section?

* fix footer colour issues
* overlay first line to the embed video in sm view?
* semantics need adding/checking
* are img titles req? y
* reduce max vp width at large sizes - its too wide!
* AmIResponsive
* HTML and CSS validation
* need a FAVICON!!!
* cards need hidden descriptive words for accessibility reasons! (distance for the map icon etx)



