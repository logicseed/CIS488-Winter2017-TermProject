Game Design II - CIS488 Winter 2017
======
>The second semester of Game Design tasked our team with learning a new game engine (Unreal Engine)
>and creating a playable game. The design that was chosen for our team was a demolition racing game
>where the player tried to destroy as many crates as possible within the time allowed. The player's
>vehicle was outfitted with several features to assist in that goal; invulnerability, impulse bombs,
>solid-holographic ramps, speed boost, enveloping airbags, and more. Since one of the contraints of
>this project was to implement the gameplay features using the engine's [Blueprints Visual Scripting]
>the "source code" cannot be viewed on GitHub.

[Blueprints Visual Scripting]: https://docs.unrealengine.com/en-US/Engine/Blueprints

### Details

__Students:__ Marc King, Rodney Lewis, Harrison Telfer

__Professor:__ Dr. Bruce Maxim

__School:__ University of Michigan - Dearborn

__My Contributions:__ Implementation, logo, UI, vehicle and crate modeling, vehicle gameplay mechanics

__Timeline:__ 8 weeks

### Technologies

* Unreal Engine 4.14

### Screenshots

*Upon loading the game, the user is presented with the main menu where they can play unlocked level,
view their score on those levels, view help for playing the game, and adjust gameplay settings.*

[![MainMenu](Screenshots/MainMenu.gif?raw=true "MainMenu")](Screenshots/MainMenu.gif?raw=true)

*While playing the game, the pause menu presents the same options as the main menu except that you
can return to the main menu instead of quiting the game.*

[![PauseMenu](Screenshots/PauseMenu.gif?raw=true "PauseMenu")](Screenshots/PauseMenu.gif?raw=true)

*The player takes the role of the Bashdozer; a former mining rig refitted for demolition.*

[![Bashdozer](Screenshots/Bashdozer.gif?raw=true "Bashdozer")](Screenshots/Bashdozer.gif?raw=true)

*The primary goal of the game is to destroy as many crates as possible within the alloted time.
Destructable behavior has been implemented for the crates to provide more visceral feedback.*

[![Crates](Screenshots/Crates.gif?raw=true "Crates")](Screenshots/Crates.gif?raw=true)

*Some crates are in hard to reach locations or being carried by mobile enemies. This requires that
the player spend a large amount of time mid-air.*

[![HighFlying](Screenshots/HighFlying.gif?raw=true "HighFlying")](Screenshots/HighFlying.gif?raw=true)

*To assist in changing direction while mid-air, the player's vehicle is equipped with impulse bombs
that apply a forces in fixed directions. The bombs require a cooldown period before they can be used
again.*

[![Bombs](Screenshots/Bombs.gif?raw=true "Bombs")](Screenshots/Bombs.gif?raw=true)

*A recharable speed boost assists the player in making longer jumps and reaching remote locations.*

[![Boost](Screenshots/Boost.gif?raw=true "Boost")](Screenshots/Boost.gif?raw=true)

*A player-spawned solid-holographic ramp can be used to launch the player in the air where there are
no landscape features to use.*

[![SholoRamp](Screenshots/SholoRamp.gif?raw=true "SholoRamp")](Screenshots/SholoRamp.gif?raw=true)

*Expandable airbags allow the player to increase the effective size of the vehicle prior to landing
in groups of crates, or to bounce when falling from great heights.*

[![Airbags](Screenshots/Airbags.gif?raw=true "Airbags")](Screenshots/Airbags.gif?raw=true)

### Development

*Early concept art for the player's vehicle created in Adobe Illustrator.*

[![BashdozerEarlyConcept](Screenshots/BashdozerEarlyConcept.gif?raw=true "BashdozerEarlyConcept")](Screenshots/BashdozerEarlyConcept.gif?raw=true)

*In an attempt to save time, the curve data from the early concept art was imported into a modeling
program and them extruded. This resulted in a model with far too many polygons and poor distribution
of those polygons.*

[![BashdozerEarlyModel](Screenshots/BashdozerEarlyModel.gif?raw=true "BashdozerEarlyModel")](Screenshots/BashdozerEarlyModel.gif?raw=true)

*A more uniform and efficient model was created using the early concept art as a reference.*

[![BashdozerCleanModel](Screenshots/BashdozerCleanModel.gif?raw=true "BashdozerCleanModel")](Screenshots/BashdozerCleanModel.gif?raw=true)

*An early version of the crate destructable featured an unrealistic forward explosion of the resultant
pieces.*

[![CrateEarly](Screenshots/CrateEarly.gif?raw=true "CrateEarly")](Screenshots/CrateEarly.gif?raw=true)
