---
hide:
    - toc
---

# Prototyping for Design

## Week 1

### Electronics & Coding

During this course we learned about how to approach making a proof of concept using electronic boards. In order to start prototyping, the board is dependent on the size and capacity needed to power the desired functions. It is important to review the datasheet of your microcontroller to make sure that it has the appropriate memory and power. 

The topic of open sourcing was discussed because Arduino is an example of opening up black boxes by making their technology available and shareable. This is through making the software easy to access by beginners, the use of community to contribute and share their knowledge, and the amount of general documentation across multiple languages and platforms for how to use this tool. Open sourcing requires you to also make your work open sourced if you modify the tool itself, however with permissive open source licenses you can use the tool without sharing your own. 

I have not had experience using Arduino or electronics in the past, so for the challenge to produce a song I needed to first understand how to attach the wires and pins to the board. I watched multiple videos and tried to follow diagrams of ESP32 with a buzzer. Once I understood how to follow the diagram and attach the pins it was more clear. 

I was able to follow the ESP32 Feather diagram to hook up the positive to the GND and negative to a designated pin. However, after placing the code for the pacman song into the Arduino, there were many errors and even though I changed the ports it still would not go through. I tested the board on a classmate’s computer to see if it was the wiring on the board or the code and it was able to play their song easily. We played around with which port and board was selected, and eventually got the right combination. I modified the duration and pitch to see how the song would be manipulated. The videos below show the two changes.  
 

Some resources I used:

https://esp32io.com/tutorials/esp32-piezo-buzzer

https://www.circuitbasics.com/how-to-use-active-and-passive-buzzers-on-the-arduino/

https://www.robotique.tech/robotics/control-a-buzzer-by-the-esp32-card/


<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZuBmHvdk&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

### 2D, 3D Parametric Design Tools 

Today we learned about the basics of parametric design with 2D and 3D software. The difference between CPU versus GPU and how they relate to the types of image processing needed to run certain programs. CPU allows for heavier mathematical equations and GPU can calculate many small equations. This relates to how vectors and pixels process information as well. Vector can scale without losing definition and is CPU processed, while Pixels are located on a x, y, z grid are GPU processed. Similarly to vectors and pixels, there are mesh versus nurbs, which are also distinguished by the type of processing. Mesh is defined by points and uses polygons, it is mostly used for STL 3D printing files, but is not good for scaling like pixels. Nurbs is used in surface modeling because it allows you to modify smooth and fluid shapes. 

I have a lot of experience in 3D modeling with Solidworks and using Keyshot as a rendering software. I wanted to spend the day learning Rhino because it uses Nurbs and is good for modeling organic shapes. I mainly used Solidworks for surface modeling as well, but it is more difficult to make organic shapes. After using it for the day I realized that Rhino is easy to model quickly, however it is difficult to change past decisions because of the feature tree. There was a plate design with water ripples on it that I was trying to replicate. I worked with Paige to think about the shape we wanted to create, because it is something we found for inspiration for our Bio Deisgn Dinner group who is focusing on making tableware that has water elements. At first I drew the outlines of the ripples, but then found the pipe tool that allowed me to build off of some organic lines. I then added some fillets around the edges after combining the separate pieces. Through this exercise I was able to learn about scaling, fillets, manipulating lines and combining solid geometry. I would like to make another version that can be made into a mold that we can use to fill with biomaterial.

**Explorations:**
<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbBGjpdMk&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

## Week 2

### 2D Fabrication (Laser, Vinyl)

Today we learned about Laser and vinyl cutters and the components that make up these machines. A laser cutter is categorized as a CNC machine because it also uses a 3+ axis, and it uses subtractive methods to engrave, mark and cut. We learned about a variety of applications that can be used such as creating living hinges, molds, laminating, and soldering. I am interested in seeing how we can laser cut biomaterials and solder them in order to eliminate glues and stitching. We received a demo for using a vinyl cutter, where we saw an application of it for copper foil to create circuit shapes. Also it can be used as a drawing tool by swapping out the blade for a pen to create computer aided drawings. The cut vinyl can also be used as a simple screen print or masking. 

I decided to make a 2D mold in acrylic for molding biomaterials. Since most biomaterials need non-stick surfaces, I chose this material and a 5mm thickness so that there could be enough height for the mold. The outlined shape will be able to be filled as a mold, and the subtracted negative space can be used as a stencil or stamp. I created the file in Illustrator and for the machine we use Rhino for printing and preparing the file. There was some trouble shooting needed to be able to cut through the material thickness, it needed multiple passes because it was 5mm. Also in order to read the file, the program was having a difficult time reading the lines to cut. Overall we were able to cut successfully and gain more confidence in using Rhino, printing software, and the laser cutter. 

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFaXpFWVaM&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>


### Inputs & Outputs
During this course we learned about inputs and outputs, and how we can use them to sense an environment. Depending on how we change the inputs, it can produce different outputs. For closed loop systems, the device can regulate its output and make decisions based on the new inputs around it without interference. We also learned about sensors and how they are being used in all our devices to collect data. Even if the sensor itself is cheap, the data that it is collecting holds the value. The companies now that own those data sets have the most power. An example of data collection through sensors is biometric data. This can be through collecting our heart rates and how our body might be reacting in certain environments. And also our biometric fingerprint, where they can detect our own personal movements of how your body and hands interact with a device through movement and gestures.  

Our phones are collecting so much personal data and we are also freely giving access because they are addicting to use. This week instagram asked me to give access to all my photos and videos, and when I chose not to, it was very difficult to use the app without giving consent. When looking closer at what they want, it is for access to your microphone, camera, location and “depth” information. Even if you have control over what photos are being posted to the public, they have control over all your photos and are now part of their collective dataset. As well as any new data from the sensors on your phone. 

For the exercise, I worked mostly on the LDR light sensor to be able to detect the amount of light in the room. I was able to modify the code to have less parameters so that the sensor would be mainly detecting dark or light, versus a spectrum of light. There was some difficulty getting the sensor to detect quickly. Since our ESP32 board is 3v and the Arduino is 5v, I tried using different ohm amounts for the resistor to see if it would read better. Below in the videos you can see that the sensor was detecting all the small variables from dim to very bright. We worked together to make another board have a switch to turn on and off the LED. We had difficulty running the code on each computer, so were unable to have them talk to each other. However they were able to work separately for the most part. 

Some links I used:
https://arduinogetstarted.com/tutorials/arduino-light-sensor?utm_content=cmp-true

https://esp32io.com/tutorials/esp32-light-sensor


<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFaNTcf8iM&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

## Week 3

### Micro Challenge I

The documentation of our process can be found here:
https://github.com/PaigePerill/gotaplatemold-


**Project Explanation:**

For the micro challenge this week, our team worked together to create a biopress mold that could be used to produce a set of biomaterial plates quickly. These plates are to be used for our intervention of an ocean-themed dinner where the tableware and food courses are made of the same ingredients with a special focus on food waste and regenerative resources.

We went through multiple rounds of iterations to figure out what type of mold and plate shapes we wanted to create. Originally we wanted to make a press that could have interchangeable parts to reduce the material impact that molds can create. Our objective was also to create a design that could be easily replicable by others, using just a laser cutter and screws. In order to create a successful 3D shape, we needed to iterate quickly to understand how we could use 2D prototyping to make a 3D object. We did this by iterating with cardboard and wood prototypes before cutting in acrylic. 

We wanted to make the most out of one mold, so we updated the design from one shape to three shapes that could be modular within themselves. We also did some material tests with calcium carbonate to see how it would stick to acrylic. We tested with parchment paper, cornstarch, and vaseline. To make the design as smooth as possible without wrinkles, we were able to use vaseline and cornstarch as a mold release. 

We also wanted to incorporate technology into our mold by using a humidity and temperature sensor. Since the material would be taken out of the mold before drying, we could use the sensor to regulate the environment that the materials are in. Eventually we would like to measure the humidity of the material itself. We were able to get the sensor to read the air humidity, but are still having difficulty connecting it to an LCD screen. We tried multiple screens, but need more power in order to have the contrast show up on the screen itself. 

**Learnings:**

Some key learnings were that the press needed a significant amount of pressure to extract the excess material. Especially because calcium carbonate is a thick material with high viscosity. The screws we used were great to key the mold together, but we needed to use extra clamps to get the excess material out of the mold. 

A positive was that we were able to take the plates of the mold after forming the shape while the material was still wet. This allows the possibility to produce a lot in a short time, versus 3d printing one plate at a time over a longer period of time. However the downside is the amount of material needed to make one mold. I would still like to find a way to make a mold with minimal plastics and materials that can be reused and reformed into new shapes.. If we can make molds from plaster or ceramics that would be an option for reusable mold materials. 

**Process Photos:**
<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbBLe7AUQ&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

**Reference Links:**
https://lastminuteengineers.com/esp32-i2c-lcd-tutorial/
https://www.instructables.com/ESP32-How-to-Interface-LCD-With-ESP32-Microcontrol/
https://www.electronicshub.org/esp32-dht11-tutorial/
http://www.datasheetcafe.com/lcm1602c-datasheet-pdf/


## Week 4

### 3D Fabrication & Scanning

Today we learned about a variety of 3D printing and scanning tools and techniques. We looked at the pros and cons between materials and types of 3D printing applications. One main takeaway was the infill being a big factor of weight, movement, and strength. The infill amount can be less as long as the bottom and top layers have an appropriate thickness. The object properties can be changed by the infill pattern, depending on how isotropic the pattern is. There should also be a balance between how fast the print is versus the amount of layers. As thinner layers can print faster, however with thicker layers you need less layers. For 3D scanning, meshes are created by calculating points in space. The high number of points, the higher the resolution is.

The object I scanned was a crochet sphere I made using amigurumi, a Japanese technique for making 3D knit shapes. I wanted to see how different phone 3D scanners would be able to pick up the texture from the textile and organic shape. I tried multiple scanning apps such as Polycam, Captur3, and WIDAR. I tried with photos and LIDAR, however photo scanning was the most successful. Polycam had the most clear 3D mesh, however I used the mesh from Captur3 because they are a free program for downloading mesh. Next time I would like to capture it with better lighting and less shadows. Despite me using my phone and not a tripod, the software was still able to capture the object well.

I will 3D print the object this week and show my results. 


<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbs3uebCI&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>


### Networking

In this course we learned about what a network is, how they have been designed today and then created our own local network within our class. A network is when data is copied from one place to another, similar to a copy machine. The way they have been designed today has made it so there are multiple copies that are being sent all over the world, as most data is sent to California. Networks are helpful in doing multiple tasks at the same time and to send information quickly. However, when it comes to sending information locally, we are still sending it across multiple oceans or cities because it is how we have designed networks to be. If there were local networks for simple tasks, it would make more sense to have a collection of small networks. In the end the power goes to the companies that have the largest datasets and control over them. Even though these large companies are collecting this data, it does not mean it is necessarily diverse.    

For our exercise, we first connected our ESP32 feather boards to the local wifi network where we could see our own messages being sent. We then connected to Victor’s IP address as our local server, where we could receive his message. After each of us connected individually to our local server, we could then be assigned to each other and were able to send messages to one another. This exercise helped illustrate the complexity between sending and receiving messages but also how on a small scale you are able to point to where your information is being stored directly. You have ownership over your own information and can choose to keep or delete it. There is a need to have everything stored on a cloud, a fear of losing your information even though most of it is forgotten about by us. Every year we are storing more and creating more information than ever before. Local networks are a good way to keep track of your own data, filter and keep only what is necessary. 

The images below show the three stages of our exercise from connecting to the network, local server, and talking to each other locally.


<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbrj4k844&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>