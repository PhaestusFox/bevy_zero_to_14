# Title
Advancing Pong Part A: With Physics Using Bevy Rapier 

# Steps
change gen to gen_range
set [[Window Plugin]] settings 
```rust 
	app.add_plugins(DefaultPlugins.set(
	WindowPlugin{
		primary_window: Some(Window {
            resizable: false,
            resolution: WindowResolution::new( 1280., 720.),
            ..Default::default()
        }),
        ..Default::default()
    }));
	```
add [[Bevy Rapier]]3d to dependencies
add [[Plugin]] [[Bevy Rapier]]
create [[Event]] GameEvents
create [[System]] score_and_reset([[Query]], [[Event]], [[Transform]], [[Query Filter]])
create [[System]] display_score([[Commands]])
create [[System]] update_score([[Resource]], [[Local]], [[Event]], [[Query]], [[Query Filter]])

# Chapters
Part A
00:00 Intro
01:00 Fixing Bugs
01:40 Make Window Fixed Size
05:40 Add Bevy Rapier to project
11:10 Tie our systems into Rapier
15:23 The bevy rapier wiki is a resource
16:36 Using Our New Knowledge
20:55 Cosmetic Upgrades
23:17 Adding Resets
34:17 Outro

Part B