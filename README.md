# BJS-Developement-Task            
src="C:\Users\octor\Downloads\BJS Development Task Pack\MDB5-STANDARD-UI-KIT-Free-3.10.1\img\first_image.png"


use rem instead of px for size
imported evelen clean and     erical weight doesnt seem to work
unable to streach the image to make it fully blck, i think its beucase of the 100% width of the image container, this makes may make it impossible to make it bigger
cant add gradient to image for 4th slide
had to edit image since bg was white instead of blue on 2


havent added indicators
no shadow to carousel nav bar
not added nav bar lines 
arrows on slide cant change colour instead the bg changes colour
boring animation on slides
realised later only used divs
havent put any js for animation changes or color changes of 

## Heroku link 
- Please read the Errors section, before going on the link.
- https://larafavouritemovies.herokuapp.com/

## Setup/Use:
- shows a working slide carousel
- adequet comments and indentation in html and css file - improve readibility
- 

## Technologies:
- Languages : HTML, CSS

## Functionality:
#### users can:
- login
- add and remove movies
- do a show more about a movie (see more details of a movie)
- can see all favourites 
- unauthenticated users cannot access user views
#### other functionality
- adequte error reporting , all redirects have status/error messages
- use of layouts
- use of bootstrap to make application responsive
- use of css to make web app simple and minimalistic

## Things i missed/ need to be imroved:
#### Code
- carousel is not resposive, since no bootstrap responsive methods have been used
- used px instead or rem or percentages - bad for responsiveness
- 
#### Design

## Struggles
i attemped to fix the heroku app, however i found myself not knowing where to begin, alot of the documentation seems to be very vague and chat room solutions have not worked. As a final resort i have contacted laracasts and join a laravel discord server to hopefully find someone that can help.

## Security concerns
- the add movie form had not been html sanitised to remove potential code injection
- the field has not been type checked to ensure that the ID entered is in the OMDB format - will allow users to add all kinds of inputs potentially breaking the favorites list
- also no character limit has been put in the add movie id input variable - will allow users to add all kinds of inputs potentially breaking the favorites list/ causing an error
