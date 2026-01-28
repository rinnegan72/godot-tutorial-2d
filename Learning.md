# Godot 2D game tutorial

This is the first thing that shows up when searching godot 2d game tutorial
its a verbose, step by step guide to building a simple 2D game called `Dodge the creeps!`

## Steps Covered

1. Project setup
2. Player Scene
3. Coding the Player


### Project Setup

1. Setup viewport size to portrait aspect ratio (480 x 720)
2. Set Stretch option items, `Mode` = `canvas_items` and `Aspect` = `keep` (helps with scaling)
3. Copy all #[dodge the creep assets](https://github.com/godotengine/godot-docs-project-starters/releases/download/latest-4.x/dodge_the_creeps_2d_assets.zip) to the project directory

### Player Scene

1. Add Area2D node
2. Add child node AnimatedSprite2D
3. Create two animations walk and up for the node (walk and up)
4. Add a CollisionShape2D as a child of the first node
5. save the scene as player.tscn
