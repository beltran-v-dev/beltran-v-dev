<div id="header" align="center">
  <h1 align="center"> It's me! Beltrán 😁</h1>
 
  <h4 align="left">I'm an enthusiastic game developer with a passion for video games that carry powerful messages. I've participated as a project manager and as a programmer in two projects in Unity: 'Element Killer' and 'Catch it!'. Currently, I'm more focused on Unreal Engine.
  </h4>
  <img src="https://i.postimg.cc/fTVtGbYR/talking-Image.png" align="center" width="300" />
  <h4 align="left"> At the moment, I'm working on an Unreal Engine project where I'm trying to write as much code as I can in C++. The project is titled 'Hospital Project', and the main theme revolves around our main character finding her way out of a hospital crawling with zombies. Sounds exciting, doesn't it?
  </h4>
</div>

<div id="badges" align="center">
  <a href="https://twitter.com/bDevGames93" target="_blank">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/bDevGames93?style=for-the-badge&logo=twitter&color=blue"> 
</div>

#### Languages and Tools I'm working or I worked recently 

- **Unreal Engine**
- **Unity**
- **C#**
- **C++**
- **Game Development**

#### Languages and Tools I worked with some time ago

- **PHP**
- **HTML**
- **JAVA**
- **SQL**
- **Android Studio**

---

### Project I am currently working on 🧑‍💻:

- ***Hospital Project***: Hospital Project is the project in which I am currently working alongside a classmate. In this project, our main character will have to find her way out of a hospital crawling with zombies. This project will be finished in December 2023.

  You can follow every week the new updates (Every Saturday) 
  
  [Twitter Thread](https://twitter.com/bDevGames93/status/1685200083187326976)
  
  [Source Code](https://github.com/beltran-v-dev/HospitalProjectCode)

  ---


### Projects I've worked on 🧐

- ***Element Killer***: Element Killer is a 2D platform video game in which our main character has to defeat different enemies and reach the end of the level. To do so, the player has to combine different elements such as fire, water, and plant to complete the level in just over a minute.

  Do you want to play it?
  
  [Element Killer](https://bdev93.itch.io/element-killer)
  
  [Source Code](https://github.com/beltran-v-dev/ElementKillerUnity)

- ***Catch It!***: Catch It! is an online video game PVP. You can choose between two teams: the dog team or the cat team. The main objective is to pick up the item you'll see at the opposing team's base and bring it to your base. To win, you should steal their item and bring it to your base 3 times. If you want to prevent your opponent from picking up your item, you can shoot them and try to kill them.

  Take a look at it!
  
  [Youtube Video](https://www.youtube.com/watch?v=4sbd7RYDFqs)
  
  [Source Code](https://github.com/beltran-v-dev/CatchItScripts)

  ---

### My love for Unreal Engine Materials 🌈
  
- Snow never falls: To achieve this, I have used a technique called Triplanar Mapping. Three material functions have been used to create the rock part, the snow part, and the Triplanar Mapping
  
   [Video](https://twitter.com/bDevGames93/status/1491720381740335105)

  Source code:
  
     [MF_Triplanarmapping](https://blueprintue.com/blueprint/lwwn82gi/)
  
     [MF_BasicRock](https://blueprintue.com/blueprint/_vp-lq7t/)
  
     [MF_BasicSnow](https://blueprintue.com/blueprint/ihnbo93k/)
  
     [M_SnowyRocks](https://blueprintue.com/blueprint/y-89948g/)

 - Lake: To achieve the creation of the water material, I have worked with nodes that help us to measure the distance to create the foam, I have worked with different normal maps and how to mix them, I  have worked with the panner node, also the texture coordinate node so that the different textures have different uvs and look more realistic. We have also worked with a height map to create a slight tide, we are not in the sea, but it will be subtle and will give more life, I have worked with the height Lerp node and with the pixel depth and scene colour nodes among others.
  
   [Video](https://twitter.com/bDevGames93/status/1624067567479300096)

    Source code:
  
   [M_Water](https://blueprintue.com/blueprint/yk88i8ap/)

 - Landscape Project A: This was the first attempt to create a material autolandscape, I used PixelDepth to control the tiling between different textures,
employed different textures with various UVs, a macro texture variation to avoid even more repetition between textures, and in this project, I decided to use the WorldAlignedBlend node in order to create a bleen between texutres more realistic, although using this node I don't have as much control as I would like.

 
    Appart from that, I used assets from Megascans and Lumen to improve the final scene
 
  
     [Video](https://twitter.com/bDevGames93/status/1652938509857030144)

    Source code:
  
     [M_Automaterial_Landscape_ProjectA](https://blueprintue.com/blueprint/m7z4ihu3/)

  
  - Landscape Project B: To create this new landscape, I decided to create different material functions in order to keep the main material cleaner. This
material has four textures: grass, soil, slope, and snow. Two of them are connected to MF_LandscapeMaterialProcess, while slope and snow textures are connected
to MF_TriplanarLandscapeMaterialProcess (this MF is identical to MF_LandscapeMaterialProcess, but inside MF_TriplanarLandscapeMaterialProcess, we are using
an MF used to take advantage of the triplanar mapping technique in order to make the sloped parts look better).

    MF_MacroVariation: We use this MF to create darker parts in the final texture. As its name suggests, we are implementing a macro variation.
    
    MF_CameraDepthFade: We use this MF to set different UVs for the same texture, this technique tricks the human eye, and it seems there is no
    repetition at all.

    MF_TriplanarMappingProjection: We use this MF to take advantage of the TriplanarMappingProjection technique. What does it do? This technique is used to 
      eliminate possible visual distortion that can occur when we are using 2D UVs.

    MF_SlopeMask: We use this MF to create a transition between the grass texture and the slope texture.

    MF_HightMask: We use this MF to create a transition between the MF_SlopeMask and the snow texture

 
 
 
  
     [Video](https://twitter.com/bDevGames93/status/1680529698319654912)

    Source code:
  
     [M_Automaterial_Landscape_ProjectB](https://blueprintue.com/blueprint/_nv_4_a-/)
    
     [MF_LandscapeMaterialProcess_ProjectB](https://blueprintue.com/blueprint/hma-gpx4/)

     [MF_TriplanarLandscapeMaterialProcess_ProjectB](https://blueprintue.com/blueprint/9ab46zm4/)

     [MF_CameraDepthFade_ProjectB](https://blueprintue.com/blueprint/eo5zxtsr/)

     [MF_MacroVariation_ProjectB](https://blueprintue.com/blueprint/r78j7b1p/)

     [MF_TriplanarmapinProjection_ProjectB](https://blueprintue.com/blueprint/pm-q4su8/)

     [MF_SlopeMask_ProjectB](https://blueprintue.com/blueprint/mf_1n8w3/)

     [MF_HightMask_ProjectB](https://blueprintue.com/blueprint/o6wzjn83/)
  
