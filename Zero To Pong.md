Install Rust https://www.rust-lang.org/
Install VSCode https://code.visualstudio.com/
 - Rust Analyzer
 - Error Lens
 - Better TOML
 - Crates
 - _Bevy Snips_
 - _formatter_
 - ..Ext
Cargo Init project
Add bevy to cargo.toml
Add [[prelude]] to main
create [[App]]
add_plugins([[DefaultPlugins]])
create [[System]] spawn_camera([[Commands]])
create [[Component]] Paddle(Up [[KeyCode]], Down [[KeyCode]])
create  [[System]] spawn_paddle([[Commands]])
create [[System]] move_paddle([[Query]], [[Transform]], [[Query Filter]], [[Input]], [[Resource]])
create [[Component]] Ball(Velocity)
create  [[System]] move_ball([[Query]], [[Transform]], [[Query Filter]], [[Input]], [[Resource]])
create [[Event]] GameEvents
create [[System]] score_and_reset([[Query]], [[Event]], [[Transform]], [[Query Filter]])
create [[System]] display_score([[Commands]])
create [[System]] update_score([[Resource]], [[Local]], [[Event]], [[Query]], [[Query Filter]])

# Script
hello and welcome to Zero to pong, in this video ill be showing you how to go from a fresh windows install to a functional, if simple game of pong.

this video is hopefully to be the first in a series I'm calling bevy 0.14 where I plan to redo my bevy basics videos so they are upto date with the latest version of bevy, this whole series will be planed out and kept in a document referred to as [[The Vault]]. it is an obsidian vault that I hope will grow and expand with this series to make a web of interconnected concepts and ideas that will represent all the knowledge that can be gained from my bevy 0.14 series.

so why am I starting from a fresh windows install? well that's simple my compute bricked its self and i needed to reinstall windows in order to get if working again, but this still leaves the question why make a video starting from a fresh windows and not just install everything I need and start from there?

this comes down to one thing I have noticed with tutorial series and that is they all seem to start with an assume ton you have a basic understanding of the topic at hand and I have decided to push that assumed starting knowledge back one step.
this video is targeted at people who have never used rust or maybe even an IDE like VSCode so I am starting there. What you need to install and how one goes about creating the bare minimum required to start making something with bevy.

the series will hopefully branch out from there expanding the concepts I present in early videos to a point you can explore and experiment yourself.

So lets get started with what do you need to install..
First you are going to want to install rust, this is done by going to the rust lang website and installing rust for your respective operating system.

// record segment A

after installing rust, and its requirements that are automatically installed when you select quick install. you will now need to download and install VSCode, the link to the download page can be found in the description.
this can all be done while rust is installing in the background.

once VSCode is download and installed its time to get some extensions..
adlib this shit




