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

At the start of the game, the player is greeted with a welcoming sign at the entrance of a building. Upon clicking the "Continue" button, the player is transported into the building to start the museum tour.

The image below is a link to a video recording of the museum tour. Please click on the image to play the video.

[![](https://img.youtube.com/vi/q2bZ7hpQXsE/0.jpg)](https://www.youtube.com/watch?v=q2bZ7hpQXsE "VR Experience on iPhone")

## Design Process

The design process started with building a persona for whom the application is targeted. Having established the persona, sketches of different settings of the gallery were made. Each room of the gallery was designed with a rough placement of objects. Objects not found in the asset store were built in SketchUp.

### Persona

![](media/persona.png?raw=true "Persona")

**Marissa**, 45, Healthcare Business Director

>I am always on the lookout for new ways to improve patient experience at our healthcare facility.

Marissa is an experienced business director who is passionate about improving patient outcomes. She is seeking to invest in technologies that have the largest impact on quality of care provided by healthcare professionals. 

**VR experience**: Intermediate

### Sketches

I made sketches of different settings of the gallery, and settled on a simple and modern layout. I sketched a rough placement of furniture within each room.  
![](media/sketch.png?raw=true "Sketch")

The gallery walls were designed and built in SketchUp.  
![](media/gallerywalls.png?raw=true "Gallery")

I also built 3D models of a VR headset and a custom spin bike in SketchUp.  
![](media/headset.png?raw=true "Headset")

![](media/spinbike.png?raw=true "Spinbike")

The remaining objects in the gallery were obtained from the Unity Asset Store, SketchUp Warehouse and Udacity Apartment Project.

### User Testing

I performed user testing at different stages of building the application. Initial user testing involve adjusting the scale of the gallery and the placement and sizes of objects.   

Many iterations of user testing were performed to improve the interactivity of the gallery tour. Some questions that were addressed during user testing include:

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

Once the player clicks on the start button, the instructions disappear. There is a gallery map on the wall of the lobby. Classical music with drumbeats is playing in the background.  
![](media/gallerymap.png?raw=true "Map")

From the lobby area, the player is presented with three options for navigation. If the player chooses the path to the left, he or she will enter the surgical planning room. Calming music is playing to simulate an operating room.  
![](media/room1.png?raw=true "Room1")

There is a doorway from the surgical planning exhibit which leads to the fitness display. Upbeat workout music is playing in the background.  
![](media/room2.png?raw=true "Room2")

Upon exiting the fitness room, the player enters the pain management and rehabilitation room. In this room, the player can hear music mixed with waves sound effects.  
![](media/room3.png?raw=true "Room3")

From the pain management and rehabilitation room, the player has two options - one doorway goes back to the lobby while another doorway leads to the stress management exhibit, located at the back of the gallery. Nostalgic classical music is playing in the background.  
![](media/room4.png?raw=true "Room4")

Finally, the player enters the education exhibit which leads back to the lobby and concludes the tour. Lively classical music is playing in the background.
![](media/room5.png?raw=true "Room5")

## Conclusions 

This project was challenging because it was the first Udacity project where there were no starter models provided. Every aspect of the project took longer than expected to complete. Once again, I learnt that going in early and often is the most efficient technique to discover and resolve issues. I learnt valuable skills in:
- application design
- model building and placement
- player navigation
- feedback effects
- creating an experience with interactivity, music and lighting

## Future Improvements

Many aspects of the museum tour can be improved, including:
- more realistic wall decorations
- better navigation techniques (besides waypoints)
- adding some animated human models