# Discussion application for roleplaying
Course project for University of Helsinki, course: Database application project. The application is a web based discussion forum, with features meant specifically for roleplaying purposes.

### Core features:
* The forum is divided into separate sections, ie games
  * A game has a public name and a short description
  * Each game is further divided into scenes, comprised of a chain of messages
* There are three roles: admin, game master (GM) and player
  * Admins have the power to moderate the games, as well as remove them or players
  * A player can start a new game, making them its GM
  * A GM is in charge of maintaining the structure of the game by creating new scenes, as well as approving new players who want to join
  * A player can send messages to the scenes and GM
* A person doesn't need to be signed in to view/read through the games
  * Unless the GM marks the game as private, in which case only players of that game can view it
  
### Other planned features:
* Players can also send pictures into the scenes
  * A GM can decide to have pictures moderated, to make sure no one sends anything inappropriate
* A player can befriend other players
* Players can send messages directly to other players
  * A player can opt to only recieve pms from friends
* Each player has a profile page with a short bio, list of the games they're in and a list of their characters
  * By default, the games and characters are only shown to the player's friends and the other members of the game in question

Other features may be added as needed.
