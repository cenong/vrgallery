# A Night At The Museum Project
A VR application made by Cen Ong

## Introduction 
A Night At The Museum is a gallery tour which showcases the impact of VR in the healthcare industry. On this tour, the player moves through 5 rooms, each room featuring companies offering VR technology in different segments of the industry. The specific areas that are exhibited in this tour are:
- surgical planning
- fitness
- pain management and rehabilitation
- stress management
- education

The following sections display the final results of the project, explain the design process, illustrate different components of the game, provide conclusions and explore future improvements.

## Results

## Design Process
 
### Persona

![](media/persona.png?raw=true "Persona")

**Marissa**, 45, Healthcare Business Director

>I am always on the lookout for new ways to improve patient experience at our healthcare facility.

Marissa is an experienced business director who is passionate about improving patient outcomes. She is seeking to invest in technologies that have the largest impact on quality of care provided by healthcare professionals. 

**VR experience**: Intermediate

### Sketches

![](media/sketch.png?raw=true "Sketch")

![](media/gallerywalls.png?raw=true "Gallery")

![](media/headset.png?raw=true "Headset")

![](media/spinbike.png?raw=true "Spinbike")

### User Testing

**Question: What do you think about the waypoint navigation?**  
The crosses used as waypoints are somewhat 2D in nature, and difficult for the gaze to focus on, it would be better if the collider is 3D.  
*Action: Changed the collider component for waypoints from mesh to sphere collider.*

**Question: What do you think about the text popups?**  
It is annoying how the text disappears when the gaze is shifted away from the objects. They are also difficult to read from different angles.  
*Action: Moved text popups closer to objects that trigger them. Fixed some text and made popups more compact.*

**Question: What do you think about the overall feel of the gallery?**  
The gallery looks good and spacious, however, it would be nice if there is a map on the wall indicating my location and labeling the location of each exhibit.  
*Action: Added a map to the main lobby of the gallery.*  

## Scene Breakdown

When the player first enters the gallery, he or she will be greeted with a screen explaining the different areas that are exhibited at this gallery. Additionally, there are instructions for navigation, and the option to exit the tour. 
![](media/instructions.png?raw=true "Instructions")

Once the player clicks on the start button, the instructions disappear. There is a gallery map on the wall of the lobby.
![](media/gallerymap.png?raw=true "Map")

From the lobby area, the player is presented with three options for navigation. If the player chooses the path to the left, he or she will enter the surgical planning room.
![](media/room1.png?raw=true "Room1")

There is a doorway from the surgical planning exhibit which leads to the fitness display.
![](media/room2.png?raw=true "Room2")

Upon exiting the fitness room, the player enters the pain management and rehabilitation room.
![](media/room3.png?raw=true "Room3")

From the pain management and rehabilitation room, a doorway leads to the stress management exhibit, located at the back of the gallery.
![](media/room4.png?raw=true "Room4")

Finally, the player enters the education exhibit which leads back to the lobby and concludes the tour.
![](media/room5.png?raw=true "Room5")

## Conclusions 

## Future Improvements
