

# GameDev_HomeworkThree

**Question 5**
**a**
With Unity's physics engine, it can detect when two objects box colliders come into contact. There are several methods to detect contact, but to detect initial collition we use OnCollisionEnter in a script. The method takes in 'other' as a parameter which we can use to see which object has collided with it. 

**b**
TRUE, each object uses the script in its own context, so it will only detect collisions for that specific object.

**c**
The GetComponent method is used to get and possibly edit certain properties of a game object. In this scenario we use it to get the MeshRenderer for the floating object and enable it again so we can see the object in the game when it falls. 
