# BrickBreaker
Brick breaker game using Java Graphics

GAME DESCRIPTION: I used different ball, brick, and player objects to operate the game, and it works by
generating a brick object layout that is contained in a list with the areas of their hitbox
being held within the object. As the ball moves with general ball physics, it detects whether the top left corner of
the ball comes into contact with any of the hitboxes of the brick objects by looping through each box object and checking
whether the location of the ball is within the space of a brick. If so, the brick object is deleted and the score counter is
incremented. The ball has physics that reacts to how far it hits the player's platform which influences its velocity and direction. 
Apart from these aspects, there is a score counter that takes into account how many bricks were broken by the ball, and a ball
spawner with the letter b that starts the game.
