# ArtificialIntelligence

## Game of Tanks

##### by Tomás Carreras and Núria Lamonja

### The Game and AI

This game is based on Unity's tutorial of Tanks by X and Y. You can find it [here]().

The goal is to improve its AI and create behaviours for the tanks, as well as improvements and innovative features.

It is developed under the MIT License.

- _To go to the Game's **RELEASES** click [here](https://github.com/Needlesslord/StrawberryEngine/releases)._

- _To go to the **GITHUB REPOSITORY** click [here](https://github.com/Needlesslord/StrawberryEngine)._

- _To go to the **WEB PAGE** click [here](https://needlesslord.github.io/StrawberryEngine/)._


	+ [HERE]() you can find the report on the game's design
	+ [HERE]() you can watch a short video of the red tank wandering
	+ [HERE]() you can watch a short video of the blue tank patrolling
	+ [HERE]() you can watch how one tank shoots the other
	+ [HERE]() you can watch a short gameplay of the game with instructions
	+ [HERE]() you can watch a complete game
	+ [HERE]() you can find the release and [HERE]() you will find the .unitypackage file




### The Team
_List of team members and GitHub and Linkedin accounts._

This project is developed by:

- Tomás Carreras 
	+ [Linkedin](https://www.linkedin.com/in/tom%C3%A1s-carreras-a96a99177/) 
	+ [GitHub](https://github.com/tomascarreras1000)
- Núria Lamonja 
	+ [Linkedin](https://www.linkedin.com/in/needlesslord/) 
	+ [GitHub](https://github.com/Needlesslord)




### Controls








### Features

Since we are adding realism to the asset, there won't be any kind of interaction between the player and the environment.

The shells shot by the tanks follow the Projectile Motion rules, with the initial starting force constant.
The shell motion is controlled by the angle of the tank's turret, calculated with:

		tan(Â) = { v^2 ± [v^4 - g ( g * x^2 + 2 * y * v^2)]^(1/2) } / ( g * x )

		with Â being the angle [º], v the speed [m/s], g the gravity [m/s^2] and (x, y) [m] the target position of the impact.


The game's design and movement follows has the following constraints:
	- The red tank **wanders**
	- The blue tank **patrols**
	- The turret of both tanks always points at the other tank and shoots when a suitable angle occurs
	- There is a delay between each shot

It also has an UI with the following:
	- Button to activate patrolling for each tank
	- Button to activate wander for each tank
	- Pause/Play the game
	- Options: Audio volume, Game modes (activate player 1 with game buttons, activate player 2 with game buttons, activate both players with game buttons, deactivate players (AI, general/main setup) with game buttons and deactivate players (AI) without game buttons), Quit
	- Create a unit (smaller tanks that will attack the enemy's base and enemy units -there are two types-). You earn gold when the tank hit's the enemy's

It also features everything taught in the tutorial mentioned above.




### Other information





