2023. 11. 09. -
    original files uploaded along with a current tilemap (made by me) and a notebook
    next steps:
        - with the Area2d node and the collision shape, make a loader for the next level
        - make a json library of the adjacency rules
        - figure out how on earth to code the actual algorhithm
        - fix tilemap if needed
        - tutorial map, text boxes and the enemy/collection system
     
2023. 11. 16. -
    - fixed publicity issue (alologies)
    - test map revamp ready for tutorial
    - next level loader correctly works
    - .txt file added with extra notes on tilesheet fixes and warning for myelf to document brainstorming on the pdf

known error:
    - game crashes when entering level loader a second time
explanation:
    - level_2 and onward doesnt exist
    - following levels will be randomly generated, thus no need to prepare and draw new ones
    - loader works, might need modifications in the future though

next step: 
    - tilesheet minor fixes
    - json library for adjacency rules

current sources:
    development so far: Godot Top-Down Action Game tutprial playlist by Coding With Russ on YouTube
        https://www.youtube.com/playlist?list=PLjcN1EyupaQkpgVN3CEeaetxxCrxo4F7v
    
    player character: Sprout Lands by cupnooble on itch.io
        https://cupnooble.itch.io/sprout-lands-asset-pack
