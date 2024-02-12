![image](https://github.com/EloiStree/HelloEloiTeachingModule/assets/20149493/93038c07-c0f9-40c1-8246-2a9c6e7c2ad4)


⚠️ This page is a resume of a workshop that took place in the context of a formation about Unity and virtual reality for the gaming industry in Belgium focus on the Oculus Quest. ⚠️
--------------------------------


# Technifutur - AR/VR Game Developer
_Step in VR by praticing_
- [The Only Rule](https://github.com/EloiStree/CodeAndQuestsEveryDay/wiki/TheOnlyRule)
- [Workshop structure](LetsGoForSomeQuestsInVirtualReality)
- [Skills cool to learn](LetsGoForSomeQuestsInVirtualReality_Skills)

_To Do Today_  
- [Students](StudentsTechnifuturAugust2019) 
- Week 1
- [2019_08_06: Let's jam](2019_08_06_ToDoToday)
- [2019_08_07: Draft Game](2019_08_07_ToDoToday)
- [2019_08_08: Finish line](2019_08_08_ToDoToday)
- [2019_08_09: Play VR](2019_08_09_ToDoToday)
- Week 2
- [2019_08_14: Hello Android](2019_08_14_ToDoToday)
- [2019_08_16: Hello Pack Manager](2019_08_16_ToDoToday)
- Week 3
- [Group for next weeks](TwoWeeksQuestGameJamGroup)
- [2019_08_19: Try, Pitch & Plan](2019_08_19_ToDoToday)
- [2019_08_20: VRTK & Other](2019_08_20_ToDoToday)
- [2019_08_21: Rotation](2019_08_21_ToDoToday)
- [2019_08_22: ADB](2019_08_22_ToDoToday)
- [2019_08_23: Publish](2019_08_23_ToDoToday)
- Week 4
- [2019_08_26: Optimization](2019_08_26_ToDoToday)
- [2019_08_27: Rewired](2019_08_27_ToDoToday)
- [2019_08_28: Clean Code](2019_08_28_ToDoToday)
- [2019_08_29: Hardware](2019_08_29_ToDoToday)
- [2019_08_30: Deathline](2019_08_30_ToDoToday)
- Week 5
- [2019_09_09: AR/VR Jam](2019_09_09_ToDoToday)
----------------------------------------------------------------


2019_08_06_ToDoToday

# What we do today
## Objectifs
_Le 6: Be ready !_
_Scope scope scope 😊 !_
- [ ] Introduction de la structure du cours
- [ ] Création du projet Git
- [ ] Définition de 4 mots piliers de votre jeu
- [ ] Répartissions des tâches (2x2 maximum par personne)
- [ ] Coder le début de votre jeu.
- [ ] Un "Daily scrum" en fin de journée

## Links
- Unity3D basic: https://github.com/EloiStree/HelloUnity/wiki
- Git reminder: https://github.com/EloiStree/HelloUnity/wiki/TF%23004

## What can we create in 20 hour ?!
- http://0hgame.eu/
 - [2018](http://0hgame.eu/games.php?year=2018)
 - [2017](http://0hgame.eu/games.php?year=2017)
 - [Some of my projects](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/370)
- https://www.bbq.extra-coin.org/ 
  - [Games 2018](https://itch.io/jam/bbq-game-jam-2018/entries) [Typing God](https://eloistree.itch.io/2018-09-22-typinggod)
  - [Games 2017](https://itch.io/jam/bbq-game-jam-2017/entries) [Tin Yang](https://itch.io/jam/bbq-game-jam-2017/rate/171294)   
  
[![JCVD](https://img.itch.zone/aW1hZ2UvMjAyNzMvNzkzODAucG5n/original/t2X%2Fmb.png)](https://primd.itch.io/jcvd-)
Video: https://youtu.be/F3eeq8l5OuI



## Reminder 
[![](http://img.youtube.com/vi/o8NPllzkFhE/maxresdefault.jpg)](https://youtu.be/o8NPllzkFhE?t=433)         
[Linus Torvalds: Linux, Opensource & Git](https://youtu.be/o8NPllzkFhE?t=433)   
[Git was not created to collaborate with others... But to not have too](https://youtu.be/o8NPllzkFhE?t=555)

- [GitIgnore.io for Unity](http://gitignore.io/api/unity)
  - git clone http...yourrepo.git
- Classic commands
  - git add .
  - git commit -m "Description"
  - git pull
  - git add .
  - git commit -m "Conflit or merge description"
  - git push



2019_08_07_ToDoToday


# To Do Today
_Le 7: First steps_   
- [ ] Exécution des deux premiers tâches
- [ ] Deux "Daily scrum" sur la journée
- [ ] Jouer sur un brouillon fonctionnel en fin de journée   

## Cool to learn
- [ ] Deal with Quaternion 
- [ ] Some function 
  - [ ] InverseTransfrom
- [ ] Recentre your axis 
- [ ] Quaternion != Commutatif
## Rotatoin the basic
- Cool link
  - [Learn what is the Quaternion](https://eater.net/quaternions/)

- Rotation
   - [Matrix](https://www.youtube.com/watch?v=RqZH-7hlI48)
   - [Euler & Gimbal Lock](https://www.youtube.com/watch?v=zc8b2Jo7mno)
   - [Quaternion](https://www.youtube.com/watch?v=3BR8tK-LuB0)
   - [Playlist](https://youtu.be/RqZH-7hlI48?list=PLFAQMlaJo92LC1kmQL8qYWyeS4lxiWZY0)
- Quaternion Utility
   - [Quaternion.identify](https://docs.unity3d.com/ScriptReference/Quaternion-identity.html)
   - [Euler()](https://docs.unity3d.com/ScriptReference/Quaternion.Euler.html)
   - [Angle()](https://docs.unity3d.com/ScriptReference/Quaternion.Angle.html)
   - [Dot()](https://docs.unity3d.com/ScriptReference/Quaternion.Dot.html)
   - [Cross()](https://docs.unity3d.com/ScriptReference/Vector3.Cross.html)
   - [FromToRotation()](https://docs.unity3d.com/ScriptReference/Quaternion.FromToRotation.html)
   - [Lerp()](https://docs.unity3d.com/ScriptReference/Quaternion.Lerp.html)
   - [Inverse()](https://docs.unity3d.com/ScriptReference/Quaternion.Inverse.html)
   - [LookRotation()](https://docs.unity3d.com/ScriptReference/Quaternion.LookRotation.html)
- Classic
  - Transform.Rotate()
  - Transform.forward
  - [Quaternion * DirectionVector](https://answers.unity.com/questions/186252/multiply-quaternion-by-vector.html) 
- Transform Utility
  - [Transform.LookAt](https://docs.unity3d.com/ScriptReference/Transform.LookAt.html)
  - [TransfomrPoint](https://docs.unity3d.com/ScriptReference/Transform.TransformPoint.html)
  - [Transform.InverseTransformDirection](https://docs.unity3d.com/ScriptReference/Transform.InverseTransformDirection.html)
  - [Transform.InverseTransformPoint](https://docs.unity3d.com/ScriptReference/Transform.InverseTransformPoint.html) 

- Cross product [Wiki](https://fr.wikipedia.org/wiki/Produit_vectoriel) [Unity](https://docs.unity3d.com/ScriptReference/Vector3.Cross.html)
- Dot product [Wiki](https://en.wikipedia.org/wiki/Dot_product) [Unity](https://docs.unity3d.com/ScriptReference/Vector3.Dot.html)


___________________
# Learned
Blender to Unity
- Rotate -90 x
- Space -> Apply Transfrom
- Rotate 90 x

2019_08_08_ToDoToday

## To Do Today
_Le 8: "Deathline: Finish & Publish"_
- [ ] Exécution des deux derniers tâches
- [ ] Un "Daily scrum" sur la journée
- [ ] Présentation d'un prototype fonctionnel en fin de journée

## Installation 
- Android pour le Quest
- Oculus, Vive et autre.

### Publish
- [Itch.io](https://itch.io/)
- [Sideload](https://github.com/the-expanse/SideQuest/releases)
- [Google Play Store](https://play.google.com/apps/publish/signup/)

### Game Jam 
- [Global Game Jam](https://globalgamejam.org/)
- [Ludum Dare](https://ldjam.com/)
- [BBQ Game Jam](https://www.bbq.extra-coin.org/)
- [My History](https://github.com/users/EloiStree/projects/3)
- EventBrite: Hackathon


2019_08_09_ToDoToday


# To Do Today
"La règle numéro 1: il est futile d'expliquer ou de parler de la réalité virtuelle à une personne qui n'y a jamais expérimenter une des casques. De ce fait, il vous faut d'abord y jouer avant de pratiquer." 
- [ ] Court introduction à la VR, ses modèles, son histoire.
- [ ] Une première compréhension d'ALVR
- [ ] Installer l'Android SDK pour Unity et le module Unity
- Tester la réalité virtuelle
  - [ ] Tester Homidio Mini ou un Cardboard
  - [ ] Tester l'Oculus Go ou le Gear VR
  - [ ] Tester l'Oculus Quest
  - [ ] Tester Oculus Rift ou le Vive ou le Window Mixed Reality
  - [ ] Tester un video 360 et une video 360 stereo

## VR
### Video
- What is VR [part 1](https://www.youtube.com/watch?v=wRCS2-AAyNM) [part 2](https://www.youtube.com/watch?v=8rVnkWbLnk8)
- [Web VR catalog](https://www.youtube.com/watch?v=lfu0QF8CRbo&t=3754s)
### Slide
- Introduction: [V1](https://docs.google.com/presentation/d/1X9EGTp2brfUrhXHbxRmtjNG-ZmBA3ZfKqmobidP_fgU/edit?usp=sharing) , [V2](https://docs.google.com/presentation/d/1bnoubk_OTe0xsOX5Hry9eEKFBwzrsI4VAcCn3jV5gN4/edit?usp=sharing)
- [Headsets](https://docs.google.com/presentation/d/12jUnK69IXJHHdJyTyVmaayfdgkEIuzoSXc8ULkvxNHY/edit?usp=sharing)
- [Arcade](https://docs.google.com/presentation/d/1WxhoNamEvsillu7XM8YJRB6__8FUPMsS5FZybJjJ6PU/edit?usp=sharing)
 - [360 Camera](https://docs.google.com/presentation/d/1V_saEViG0dRuhtudEEceqNzmUrNS3AGmu-JnLRHwVA0/edit?usp=sharing)
## Store  
- [Cardboard](https://play.google.com/store/apps/details?id=com.google.samples.apps.cardboarddemo)
- [Gear VR](https://www.apkmirror.com/apk/samsung-electronics-co-ltd/gear-vr-service/gear-vr-service-2-7-33-release/)
- [Oculus Go/Quest](https://play.google.com/store/apps/details?id=com.oculus.twilight)
- [Oculus Rift/S](https://www.oculus.com/setup/)
- [Steam VR: Vive, WMR](https://store.steampowered.com/steamvr)

## Quest out
- [SideQuest](https://github.com/the-expanse/SideQuest)
- [AlVR](https://github.com/polygraphene/ALVR/releases)
- [Virtual Desktop](https://www.vrdesktop.net/) / [Rift Cat](https://riftcat.com/vridge)
- Bug: [ADB Utility](https://mega.nz/#F!TLYU2ACZ!tnHWwkUZchU04DstunNUUA) 
- Bug: [Web VR Catalog](https://mega.nz/#F!WDIRnAha!zTqJYlrsTM5BVao2_mhqSg)
## Devices
- Cardboard
  - Check if your phone have a Gyroscope  ([Tutorial](https://github.com/EloiStree/2018_11_16_2AM/wiki/M%230005))
    - [Elixir](https://play.google.com/store/apps/details?id=com.bartat.android.elixir&gl=BE)
  - Game
    - Store Search: [Cardboard](https://play.google.com/store/search?q=cardboard&c=apps) , [VR](https://play.google.com/store/search?q=vr&c=apps)
    - [The Sister](https://play.google.com/store/apps/details?id=com.otherworld.Sisters)
    - [Design Lab](https://play.google.com/store/apps/details?id=com.google.vr.cardboard.apps.designlab)
    - [Cardboard Camera](https://play.google.com/store/apps/details?id=com.google.vr.cyclops)
- [Gear VR](https://www.oculus.com/experiences/gear-vr/) 
  - Do you have a Galaxy: Not4, S6, S7, S8 ? -> Gear VR is above 100€
  - Game 
    - Drift
    - ...
- [Oculus Go](https://www.oculus.com/experiences/go)
  - Game
    - Drift
    - Jurassic World: Blue
    - Thrumper
    - Titans of space $
    - Perfect Moon
    - Ocean Rift $
  - Tool
    - Pigasus
    - Youtube / Browser
- [Oculus Quest](https://www.oculus.com/experiences/quest)
  - Game
     - [Beat Saber](https://www.oculus.com/experiences/quest/2448060205267927)
     - [Dark Vader Immortal](https://www.oculus.com/experiences/quest/2108775495884888)
     - [Bogo](https://www.oculus.com/experiences/quest/1893756264000446)
     - [Moss](https://www.oculus.com/experiences/quest/1654565391314903) $ - [Fujii](https://www.oculus.com/experiences/quest/2033429253367669)$
     - [Tennis Table Eleven](https://www.oculus.com/experiences/rift/989106554552337)
     - [Oculus First contact](https://www.oculus.com/experiences/quest/2188021891257542)
     - [Please, Don't Touch anything](https://www.oculus.com/experiences/quest/2706567592751319/) 
     - Quest Intro
  - Tool Must
     - [Gravity Sketch](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230006) Q
     - [Tilt Brush](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230002) Q
- [Oculus Rift](https://www.oculus.com/experiences/rift)
  - Game
     - Keep talking nobody explode
     - [The Lab](https://store.steampowered.com/app/450390/The_Lab/)
     - NVidia Exploration
  - Tool Must
     - [Medium](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230004)
     - [Kingspray](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%2300014)
     - [Blocks](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230005)
     - [Gravity Sketch](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230006) Q
     - [Tilt Brush](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230002) Q
     - [Quill](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230003)
  - Tool
     - [A-Painter](https://github.com/EloiStree/HelloPaintingJam/wiki/JAM%230007) Q
     - [Makebox](https://github.com/EloiStree/HelloPaintingJam/wiki/Makebox)
     - [In Block](https://github.com/EloiStree/HelloPaintingJam/wiki/InBlock)
     - [Kodon](https://github.com/EloiStree/HelloPaintingJam/wiki/Kodon)
     - [Masterpiece VR](https://github.com/EloiStree/HelloPaintingJam/wiki/MasterpieceVR)
     - [Vox VR](https://github.com/EloiStree/HelloPaintingJam/wiki/VoxVR)   
     - [Anim VR](https://github.com/EloiStree/HelloPaintingJam/wiki/AnimVR)

## 360 video 
- Video Stereo: [Watch](https://www.youtube.com/playlist?list=PLfOULzCct2SIRcGmXQMwJfzeK9W00sqIB)     
- VR 360 : [Watch](https://www.youtube.com/playlist?list=PLfOULzCct2SL-Q0BELXYmpVPH0te6WhAK)          
- VR Stereo 360 : [Watch](https://www.youtube.com/playlist?list=PLfOULzCct2SLnlfJaSbkejFpRaZ4ilALl)      
- VR Stereo 180 : [Watch](https://www.youtube.com/playlist?list=PLN_4SqVDVM7jCAt9RPKNrOzpa8FDhFxWp)       
- In Game 360:  [Watch](https://www.youtube.com/playlist?list=PLfOULzCct2SLMUY2ts3A_RDLDJ4Z7cdiG)    
- VR Stereo 8K: [Watch Ghost In The Shell](https://www.youtube.com/watch?v=C1iAi2yvSZE)   

2019_08_14_ToDoToday

# To do today
_Le 14: Create your first hello world in Oculus Quest (under Android)_

[Where to start ->](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/93)   
[Oculus Light](https://gitlab.com/eloistree/2019_07_23_OculusQuestLight/blob/master/OculusIntegrationLight.unitypackage)  
- [x] Installer Java et Android
- [x] Set [phone as developer](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/377) and [Quest as developer mode](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/28)
- [x] Configure and compile classic Android Application
- [ ] Workshop: Create android application
- [x] Configure and compile Oculus Quest application
  - [ ] Create the [AndroidManifest.xml](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/376)
- [x] Explore OVRPrefab, OVRMAnager, OVRInput
  - [x] [Oculus Input](https://docs.unity3d.com/Manual/OculusControllers.html)
- [ ] Workshop: What do you want to see become real by using VR?
- [ ] Demo: Use of ALVR with Steam VR
- [ ] Demo: Use of VRidge with Steam VR
- [ ] Challenge: Make the Oculus Rift work on the formation center PC
- [ ] Workshop: Use AlVR or VRidge on your Quest or on your phone.

## Links
- [ALVR](https://github.com/polygraphene/ALVR/releases)
- [SideQuest](https://github.com/the-expanse/SideQuest/releases)
- [Rift Cat](https://riftcat.com/vridge)
  - [On Google](https://play.google.com/store/apps/details?id=com.riftcat.vridge2&gl=BE)
- [Virtual Desktop](https://www.vrdesktop.net/)
- [Video: AlVR and Rift cat](https://www.youtube.com/watch?v=PD_MobYv7-o)

## Workshop reminder



``` cs
//VR
        float isTriggerDownValue = OVRInput.Get(OVRInput.Axis1D.PrimaryIndexTrigger, OVRInput.Controller.RTouch);
        Vector2 joystick = OVRInput.Get(OVRInput.Axis2D.PrimaryThumbstick, OVRInput.Controller.RTouch);
        if(joystick==Vector2.zero)
            joystick = OVRInput.Get(OVRInput.Axis2D.PrimaryTouchpad, OVRInput.Controller.RTouch);
        bool isTriggerDown = OVRInput.Get(OVRInput.Button.PrimaryIndexTrigger, OVRInput.Controller.RTouch);
//ANDROID
        Vector3 accelerometer = Input.acceleration;
        int numberOfFingerOnScreen = Input.touchCount;
        // If you want to say the user he don't have luck.
        bool hasGyro = SystemInfo.supportsGyroscope; 
        Quaternion gyroDirection = Input.gyro.attitude;
        Vector3 gravityApplied= Input.gyro.gravity;

        Touch touching = Input.GetTouch(0);
        Vector3 screenPosition = touching.position;
```


2019_08_16_ToDoToday

# To do today
_Abat les Spaghettis ! Vive les boites à outils._  
"Le travail de groupe est un challenge extrême difficile. Mais étonnamment, importer et utiliser le code de dizaines de personnes depuis l'asset store est simple comme bonjour. Le but de la journée est d'apprendre à créer un unitypackage partagé à partir du package manager dans le but de créer des outils utilisables en groupe. Cela pour lutter contre le code spaghetti et simplifier le travail de groupe"

- [Package manager introduction >](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/326)
- [Package Manager Facilitator Installation >](https://gist.github.com/EloiStree/27951f13eec1f45b0130d720d0f1f1bb)

# Objective:
- Morning: Create your first toolbox
  - [ ] What is a Unitypackage & how it works
  - [ ] [What is the Unity package manager](https://docs.unity3d.com/Packages/com.unity.package-manager-ui@1.8/manual/index.html)
  - [ ] [How to create Unity Package by hand](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/326)
  - [ ] Workshop: everybody create a unity package (no exception ̿' ̿'\̵͇̿̿\з=(◕_◕)=ε/̵͇̿̿/'̿'̿ ̿ )
- Afternoon: The 24 doors project
  - [ ] Demo of how to auto-build a unity package ( /!\ code in development)
  - [ ] Create Unity Package for the manager that reference to [required one](#)
    - [ ] You will found a main room and a room pattern. Create your world/portfolio around it
    - [ ] Give your "namespace":"publicgitlink" to this google sheet
  - [ ] Build the 24 doors project with all participants in it
- Brainstorm a bit on the next weeks projects


## Example
- Pref Them All 
  - ["be.eloiexperiments.unityprefsthemall":"https://gitlab.com/eloistree/2019_06_10_unityprefsthemall.git"](https://gitlab.com/eloistree/2019_06_10_unityprefsthemall.git)
- Android Volume Override
  - ["be.eloiexperiments.overrideandroidvolume":"https://gitlab.com/eloistree/2019_06_30_overrideandroidvolume.git"](https://gitlab.com/eloistree/2019_06_30_overrideandroidvolume.git)

## Tutorial
### Explanation of the structure of Unitypackage for manager
[![Default Alt](https://img.youtube.com/vi/vtNuQn6kS28/mqdefault.jpg)](https://youtu.be/vtNuQn6kS28)  
https://youtu.be/vtNuQn6kS28

### Full demonstration of the today exercise with Unity Package manager
[![Default Alt](https://img.youtube.com/vi/nA7rfKUSrQE/mqdefault.jpg)](https://youtu.be/nA7rfKUSrQE)  
https://youtu.be/nA7rfKUSrQE


2019_08_19_ToDoToday

# To Do today
1. _Start to code as soon as the project start is the best way to fail by miscommunication_  
2. _"The biggest mistake is you think you have time"_
3. _"90% startup fail because they are not fitting a need."_

- Be able to pitch your idea in 4 words & 30 seconds
  - [Feel the gap](https://docs.google.com/document/d/1o2ntgIW57bmzmtvIIwd7ImXKFV9YSA9Qi1Ppqkh389I/edit?usp=sharing) (Example: [Macro Triggering](https://docs.google.com/document/d/19EZ4Ox148D6cnN_ZAA06e56Z-WzZfOkgwG872R8GUQg/edit?usp=sharing) - [Ano Nymus](https://docs.google.com/document/d/1IhKljGevjUN4B7s9QRYAnJCK37e-7Pz1uUCsWRsiCwA/edit?usp=sharing))
  - If you plan to sell it: 
    - Small idea of the [BMC](https://en.wikipedia.org/wiki/Business_Model_Canvas#/media/File:Business_Model_Canvas.png) - [Value Canvas](https://www.ashtonmcgill.com/wp-content/uploads/2018/04/the-value-proposition-canvas.jpg)
    - Small look to ["Pocket Coach"](https://docs.google.com/document/d/10xk_kAYaAWpAKv89NOMqkw_6iy01OTS6CFEKBFbyCMc/edit?usp=sharing)
    - Small look at ["Ready to be invested"](https://docs.google.com/spreadsheets/d/1fbLTgk2ejgTJqreBfxvGk5eF-UVjvmew7lMtAyiX2D4/edit?usp=sharing)
- Provide a at least one page GCD
  - Game Name, 4 pillars,  Small description
  - Some graphics reference of your game
  - Example: [Rubik Cube Story](https://docs.google.com/document/d/1mojD1YjD4JLC6stRxIcl9wooiBfaj08uxH0iLRHrRB8/edit?usp=sharing) - [Devis/Accord (Old)](https://docs.google.com/document/d/1RcQ9Ig2KUEAUeDZsibsvjSis7fqdT1H2GftiCAYTw3E/edit?usp=sharing)
- Priority & Scheduling
  - Two "A" goals per member to work on this week.
  - Identify the risk of failure / explain how you will deal with them
  - Be able to explain, write down or show a demo of your "CCC"
- Prototype 
  - your fear of the weak points.
  - Play your game even if it is with paper or fictive role play.

-----------------------------------------------
# Knowledge to help you
- Safeguard & communication
  - Pitch & Goal
  - GCD: Game Concept Document & 4 pillards
- Don't work on what you should not now
  - Scope & Priority (A B C D)
  - Scrum, Agile or Lean
  - CCC: Character Camera Controller
- Don't reinvent the wheel except if you need too or want to
  - VRTK, MRTK, Oculus API
  - UDP/TCP vs UNet, P2P, Photon, TNet, MQTT, OSC 


---------------------------------------------------
# Reminder
### Semaine 1: Principe de base
**Objectifs conseillés:**   
- Le 19: ~~Définir les groupes et brainstorming sur le jeu à mettre en place~~
- Le 20: Définir le "Game Concept Document" et mettre en place les bases du projets
- Le 21: Commencer à mettre en place les premiers briques du projet
- Le 22: Commencer à lier les premiers briques du projet
- Le 23: Mise en commun du travail de l'équipe pour un prototype jouable

### Semaine 2: Optimisation
**Objectifs conseillés:**   
- Le 26: Mise au points des taches de la semaine
- Le 27: Amélioration graphique et sonore du brouillon de la première semaine
- Le 28: Levée des crayons et finition de la scène
- Le 29: S'assurer que le jeu est à l'épreuve des gens stupides
- Le 30: Publication et présentation des projets de groupe


-------------------------------------
![Scrum, Agile ...](https://assets.toggl.com/images/software-development-methods-explained-with-cars-toggl-infographic-02-f2f4bdec9eeed1a4d20b6b4f0ce9b3b7.jpg)

2019_08_20_ToDoToday

- VRTK  [Links & Tutorials](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/113)
  - Others
    - [MRTK](https://github.com/microsoft/MixedRealityToolkit-Unity) - [On Quest ?](https://github.com/microsoft/MixedRealityToolkit-Unity/issues/4549)
    - [Steam VR](https://github.com/ValveSoftware/steamvr_unity_plugin)
    - [Cardboard](https://developers.google.com/vr/develop/unity/get-started-android)
- [Rewired for VR too](https://assetstore.unity.com/packages/tools/utilities/rewired-21676)
  - [XR Default](https://github.com/EloiStree/2019_04_04_XR2RewiredSpaceshipExercise): [Hololens](https://github.com/EloiStree/2019_04_04_XR2RewiredSpaceshipExercise_Hololens), [Go](https://github.com/EloiStree/2019_04_04_XR2RewiredSpaceshipExercise_OculusGo)
    - [Code Example](https://github.com/EloiStree/HelloHololens/wiki/CustomRewired), [Video](https://youtu.be/asjYwOx-Ybc)
- [Curved UI](https://assetstore.unity.com/packages/tools/gui/curved-ui-vr-ready-solution-to-bend-warp-your-canvas-53258)

Git=  [HelloVRTK](https://github.com/EloiStree/2019_08_19_HelloVRTK/tree/TryToLight) - [APK VRTK Try it](https://github.com/EloiStree/2019_08_19_HelloVRTK/blob/TryToLight/BuildTestLightAllScene.apk)

2019_08_21_ToDoToday

## Cool to learn
Acces code: https://github.com/EloiStree/2019_08_06_HelloTechnifutur
- [ ] Deal with Quaternion 
- [ ] Some function 
  - [ ] InverseTransfrom
- [ ] Recentre your axis 
- [ ] Quaternion != Commutatif
## Rotatoin the basic
- Cool link
  - [Learn what is the Quaternion](https://eater.net/quaternions/)

- Rotation
   - [Matrix](https://www.youtube.com/watch?v=RqZH-7hlI48)
   - [Euler & Gimbal Lock](https://www.youtube.com/watch?v=zc8b2Jo7mno)
      - Curved Rotation: https://youtu.be/zc8b2Jo7mno?t=189
      - Locked axis: https://youtu.be/zc8b2Jo7mno?t=274
      - Gimbal lock: https://youtu.be/zc8b2Jo7mno?t=408
   - [Quaternion](https://www.youtube.com/watch?v=3BR8tK-LuB0)
   - [Playlist](https://youtu.be/RqZH-7hlI48?list=PLFAQMlaJo92LC1kmQL8qYWyeS4lxiWZY0)
- Quaternion Utility
   - [Quaternion.identify](https://docs.unity3d.com/ScriptReference/Quaternion-identity.html)
   - [Euler()](https://docs.unity3d.com/ScriptReference/Quaternion.Euler.html)
   - [Angle()](https://docs.unity3d.com/ScriptReference/Quaternion.Angle.html)
   - [Dot()](https://docs.unity3d.com/ScriptReference/Quaternion.Dot.html)
   - [Cross()](https://docs.unity3d.com/ScriptReference/Vector3.Cross.html)
   - [FromToRotation()](https://docs.unity3d.com/ScriptReference/Quaternion.FromToRotation.html)
   - [Lerp()](https://docs.unity3d.com/ScriptReference/Quaternion.Lerp.html)
   - [Inverse()](https://docs.unity3d.com/ScriptReference/Quaternion.Inverse.html)
   - [LookRotation()](https://docs.unity3d.com/ScriptReference/Quaternion.LookRotation.html)
- Classic
  - Transform.Rotate()
  - Transform.forward
  - [Quaternion * DirectionVector](https://answers.unity.com/questions/186252/multiply-quaternion-by-vector.html) 
- Transform Utility
  - [Transform.LookAt](https://docs.unity3d.com/ScriptReference/Transform.LookAt.html)
  - [TransfomrPoint](https://docs.unity3d.com/ScriptReference/Transform.TransformPoint.html)
  - [Transform.InverseTransformDirection](https://docs.unity3d.com/ScriptReference/Transform.InverseTransformDirection.html)
  - [Transform.InverseTransformPoint](https://docs.unity3d.com/ScriptReference/Transform.InverseTransformPoint.html) 

- Cross product [Wiki](https://fr.wikipedia.org/wiki/Produit_vectoriel) [Unity](https://docs.unity3d.com/ScriptReference/Vector3.Cross.html)
- Dot product [Wiki](https://en.wikipedia.org/wiki/Dot_product) [Unity](https://docs.unity3d.com/ScriptReference/Vector3.Dot.html)


## Additional
- [Layer belong to layer mask](https://answers.unity.com/questions/50279/check-if-layer-is-in-layermask.html)
  - layermask == (layermask | (1 << layer))
``` cs
//https://answers.unity.com/questions/50279/check-if-layer-is-in-layermask.html
    public static bool IsInLayerMask(int layer, LayerMask layermask)
    {
        return layermask == (layermask | (1 << layer));
    }

```


2019_08_22_ToDoToday

# To do Today
[![Default Alt](https://img.youtube.com/vi/TJqpjwhUBKI/mqdefault.jpg)](https://youtu.be/TJqpjwhUBKI)  
Download: [ADB Utility](https://eloiexperiments.page.link/2019_06_03_adbutility)
- How to build with Wifi ?
- How to use profiler ?
  - How to use profiler with wifi ?
- How to stream screen of the Quest ?
- [How to use ADB Command ?](https://github.com/EloiStree/CodeAndQuestsEveryDay/wiki/AdbCommands)
- Sideload
  - Install APK
  - Change the resolution
- [Trouver l'IP local du Quest](http://www.mon-ip.com/adresse-ip-locale.php)

## Reminder ADB
- adb devices -l
- adb tcpip 5555
- Get Local Ip:  ```adb  -s e4aeda5e shell ip addr show wlan0```
- adb connect 192.168.137.39:5555
----------------------
## Other subject
- Extract APK of Go and phone for the Quest
[![Default Alt](https://img.youtube.com/vi/8mK8rpMA_nA/maxresdefault.jpg)](https://youtu.be/8mK8rpMA_nA)  
https://youtu.be/8mK8rpMA_nA
- Optimisation in VR must watch video
[![Default Alt](https://img.youtube.com/vi/w0n4fuC4fNU/maxresdefault.jpg)](https://youtu.be/w0n4fuC4fNU)  
https://youtu.be/w0n4fuC4fNU
- Debugging in VR
[![Default Alt](https://img.youtube.com/vi/AtOX6bXcQJE/maxresdefault.jpg)](https://youtu.be/AtOX6bXcQJE)  
https://youtu.be/AtOX6bXcQJE
- [Other ADB subject](https://github.com/EloiStree/CodeAndQuestsEveryDay/wiki/UnityQuestAdvanceTopic)

## Seen
- Canvas
  - Canvas Classic
    - PX vs Pourcent
  - Canvas World
    - Scale
  - Collider
  - Curved UI



2019_08_23_ToDoToday

## To Do Today
- [ ] Finish a playable prototype
- [ ] Publish it on Side Quest for 15h30
- [ ] At 16h play the game of other
- [ ] At 17h Prototype post-mortem in team

## Git
- Example [2019_05_23_EloiExperimentsSideQuest](https://gitlab.com/eloistree/2019_05_23_EloiExperimentsSideQuest.git)
- Where to share your APK: [Technifutur Demo For Sidequest](https://gitlab.com/eloistree/technifuturdemoforsidequest.git)
  - Find information [here](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/381)
- Repo of EloiExperiments: https://gitlab.com/eloistree/2019_05_23_EloiExperimentsSideQuest/raw/master/
## Publish
- Store
  - [Itch.io](https://itch.io/)
    - [Dashboard](https://itch.io/game/new)
  - [Google Play](https://play.google.com/)
    - [Dashboard](https://play.google.com/apps/publish/)
    - Tutorials
      - https://youtu.be/I1K6q3SItiA
  - [Side Quest](https://github.com/the-expanse/SideQuest/releases)
    - [How to publish](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/381)
  - [Oculus Store](https://www.oculus.com/)
    - [Dashboard](https://dashboard.oculus.com/my-apps/)
    - [How to publish](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/49)
- Set the quest as Developer mode
- [Sideload with ADB](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/10)
- [How to record video](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/25)
## How to publish on Side Quest
 [Info](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/381)  
 

# Next
- Interface vs Inheritance vs Modular Inheritance
- Tag vs Layer vs TagScript

## reminder
- [Layer belong to layer mask](https://answers.unity.com/questions/50279/check-if-layer-is-in-layermask.html)
  - layermask == (layermask | (1 << layer))
``` cs
//https://answers.unity.com/questions/50279/check-if-layer-is-in-layermask.html
    public static bool IsInLayerMask(int layer, LayerMask layermask)
    {
        return layermask == (layermask | (1 << layer));
    }

```

2019_08_26_ToDoToday

### Semaine 2: Optimisation
**Objectifs conseillés:**   
- Le 26: Mise au points des taches de la semaine
- Le 27: Amélioration graphique et sonore du brouillon de la première semaine
- Le 28: Levée des crayons et finition de la scène
- Le 29: S'assurer que le jeu est à l'épreuve des gens stupides
- Le 30: Publication et présentation des projets de groupe

## To Do Today
- [ ] [Check what optimisation we can use for our game](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/204)
- [ ] [Certification & Optimisation](https://docs.google.com/spreadsheets/d/1TI_-X7T4Dh67LKkINNmpfvuofxn3RCUhHVNInaRRUsw/edit?usp=sharing)
  - [ ] [Info about certification](https://github.com/EloiStree/HelloUnity/wiki/TF%23024)


2019_08_27_ToDoToday

# Rewired
[![Default Alt](https://img.youtube.com/vi/xH9vaPMFg1o/maxresdefault.jpg)](https://youtu.be/xH9vaPMFg1o)  
https://youtu.be/xH9vaPMFg1o
- [Tutorial and info](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/383)
- https://github.com/EloiStree/2019_04_04_XR2RewiredSpaceshipExercise_OculusGoAndQuest
- git clone https://github.com/EloiStree/2019_04_04_XR2RewiredSpaceshipExercise_OculusGoAndQuest.git
- Download Rewired: https://we.tl/t-dnHI7fiEOk

## Smartbe.be
_Rappel de ce qu'est la Smart et démo de l'interface_
- [ ] Check what is SMartBE
- [ ] Check the interface
- [ ] Understand why it is important to use it in any case in Belgium for video game industry.


2019_08_28_ToDoToday
## Clean code
![Book](https://user-images.githubusercontent.com/20149493/63813819-03729e80-c92f-11e9-8975-a9ad89bba13d.png)
![Clean code](https://user-images.githubusercontent.com/20149493/63815532-3e77d080-c935-11e9-9774-dfa2a40b2f83.png)
**[Access the To Do Today content](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/384)**
- [ ] Clean Code ?
  - Meaningful names
  - Comment vs No-comment
  - Error Handling
  - Functions
  - Objects and data structure
- Inheritence by composite
- State machine (Responsibility pattern)
- MVC vs MVVM
- Bad code is a silent assassin
- Unity Drag and drop philosophy
- UML: Class diagram & User case
- [ ] Why you will create bad code and how to avoid ?
- Tester, tDD vs TGD vs BDD
- Unity Test
- Refactoring and Design pattern
- Workflow of Git
_________________________
PS: [Unity Editor Tricks](https://github.com/EloiStree/HelloUnity/wiki/TF%23014)
## Unity Best practices and tips

- Manual: [M: Guides](https://docs.unity3d.com/560/Documentation/Manual/BestPracticeGuides.html), [M: Tutorials](https://unity3d.com/fr/learn/tutorials/s/best-practices)
- [Google Search](https://www.google.be/search?q=unity+best+practices&oq=unity+best+practices&aqs=chrome.0.0j69i60l3j0l2.4080j0j7&sourceid=chrome&ie=UTF-8): [DevMag](http://devmag.org.za/2012/07/12/50-tips-for-working-with-unity-best-practices/), [Gamasutra](https://www.gamasutra.com/blogs/HermanTulleken/20160812/279100/50_Tips_and_Best_Practices_for_Unity_2016_Edition.php), [Glen](http://www.glenstevens.ca/unity3d-best-practices/), [Toptal](https://www.toptal.com/unity-unity3d/tips-and-practices)
- Unity: [Y: 2D Best Pract.](https://www.youtube.com/watch?v=HM17mAmLd7k)
__________________

## Reminder
- [Brotaru ? Lundi 2 septembre](https://www.facebook.com/events/716089242152598/)


2019_08_29_ToDoToday

# Research , Development and Service
_You can produce game for the store but most of the industry is based on the r&d, advertising and industry service._
_To be able to make VR application for those fields, you need to overcome the hardware and API on your way._

## Mission AR VR: the 9-13th September
- The goal of the week is to train yourself to work on a technology you don't know about. 
- Choose a subject that you don't master at all but you want to experiment for the week.
- No need to finish the game. But it is required to prove that you tried to master the technology you are working on.
- Team from 2-5 people.
- The game must be AR or VR (Can be both)

## To do today
- [ ] Main: Work on the end of your project.
- [ ] Secondary: Think / Brainstorm about which hardware or API you want to use during the AR/VR Jam. To check what equipment will be reserved and bring to the formation.
- [ ] Learn that you can be a wizard with Unity and basically do almost anything.
- [ ] [Learn about what hardware are often linked to virtual reality](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386)

### Why the wheel chair ?

[![Default Alt](https://img.youtube.com/vi/6IIBTTXEt7M/maxresdefault.jpg)](https://youtu.be/6IIBTTXEt7M)  
[Learn about it ;)](https://github.com/EloiStree/Portfolio/issues/2)


------------------------------------------------------------
## Hors Sujet
### Create small company: Curious Craft
[![Default Alt](https://img.youtube.com/vi/t3nykp2RunQ/maxresdefault.jpg)](https://youtu.be/t3nykp2RunQ)  
https://youtu.be/t3nykp2RunQ

### Post mortem: Painting Jam
[![Default Alt](https://img.youtube.com/vi/FXjOdNDqr_U/maxresdefault.jpg)](https://youtu.be/FXjOdNDqr_U)  
https://youtu.be/FXjOdNDqr_U

### Hard drive are doom to break
[Show case](https://github.com/EloiStree/Portfolio/wiki)

------------------------

- [Arcade Center](https://docs.google.com/presentation/d/1WxhoNamEvsillu7XM8YJRB6__8FUPMsS5FZybJjJ6PU/edit?usp=sharing)
2019_08_30_ToDoToday

## Death Line

Check:
- [ ] Do you have a build ready to be test for 15h ?
- [ ] Did you take some screenshot of the game ?
- [ ] Did you record some game play ?
  - [Open Broad Cast ?](https://obsproject.com/fr)
  - [How to record your Quest Game ?](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/25)
- [ ] Did you publish a version on Itch.io or a private SideQuest ?
- [ ] What is your next steps for the game ?

Tool Box:
- Do you have assets or code that can be reuse ?
- Is it hard to extract it ?
  - Unity Package Manager ?
  - Unity asset store ?

Post-mortem:
- [ ] What went smooth in your project ?
- [ ] How did you deal the workflow of your team ?
- [ ] What went bad in your project ?
- [ ] What did you learn from it that you want to share to the group ?

--------------------------------------
## Reminder
- Don't forget to put a date on your project
- Don't forget to Zip your project to keep an archived
  - Project has an expiration date
- [Keep contact](https://forms.gle/C3dqdjWu44pQYXbW7)
- [Archived and mirror your work](https://github.com/EloiStree/Portfolio/wiki)
  - [Unity Package](https://gitlab.com/eloistree/2019_07_21_UnityPackageFacilitator)

## Additional
- Check your LinkedIn and Facebook public state... Because your future boss will... And everybody else in deed.

  - If you add someone on Linked-In, you must write a message. Else you will be consider as spam.
  - If your name is not on Linked-In and you are in computer technology. That weird for your contractor.
  - Linked-In is most of the time better that a visit card.
  - If you don't like Linked-In don't use it. But at least put a photo, your first name and last name.
  - Feel free to add me if you want to stay in contact out of the formation.

- [Publish on SideQuest](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/381)


2019_09_09_ToDoToday
# To Do today
*"The goal in this workshop of the week is to teach you how to use a manual and explore a technologies that you don't master in a short time!"* 
  
Lot's of virtual reality clients are going to ask you to create a game or an application based on a specific technologies. That is one of the most easier way to start in the industry of a young start-up or independent developer (compare to launch a game or an application on the store that will pay the end of the month.)

## Main Objective
- [ ] Explain the objective of the workshop
- [Workshop Question: Cool stuffs available for the hardware workshop?](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386)
- [ ] Reminder of the technologies available
  - [ ] Bring by me
    - [ ] [Theta S](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-525712862) ([Tutorial 360](https://github.com/EloiStree/2017_04_11_HowToUse360Camera/wiki))
    - [ ] [Zed Mini](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-525712651) 
    - [ ] 2 [Arduino](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-529235290) + 1 Raspberry PI + 1 Leonardo
      - [ ] Lost of cables and resistances
      - [ ] [Three type of infrared Light](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-529235925)
      - [ ] Component: Relay, Button 
      - [ ] Sensor: Light, Magnet
      - [ ] HC-06 Bluetooth transmitter
        - [Remote Firework example](https://github.com/EloiStree/HelloRemoteFirework/wiki)
    - [ ] [Wing Mang Attack 2 for Rewired](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-529236385)
    - [ ] [Oculus DK1 & DK2 (legacy)](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-529240646)
    - [ ] [Tap With Us](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-529235703)
    - [ ] [Flic Buttons](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-529235712)
    - [ ] [Window Mixed Reality](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-529235755)
    - [ ] ...
  - [ ] Small EON Technology
    - [ ] HTC Vive
    - [ ] 3D Scanner for small object
    - [ ] 6 [Kinects](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-525709543)
    - [ ] 6 [Leap Motion](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/386#issuecomment-525711045)    
  - [ ] Big EON Technology
    - [ ] Stereo Cinema Camera
    - [ ] Fix and mobile stereo Cubic Camera
    - [ ] Infrared Tracking Camera
    - [ ] Screen that track pencil 
- [ ] Gather group on hardware for VR or AR subject
- 12h30: Fix the teams and technologies to study
- PS: Bring you hardware if you want for the exercise
- PS: You can link AR and VR projects

## Secondary
- [ ] Teach the first step of the Arduino to those you want to explore this subject during the week.
  - [ ] How to light a led ?
  - [ ] Electricity ?
    - V , I, Am, Ohm, W [Electricity Basic](https://github.com/EloiStree/HelloRemoteFirework/wiki/ElectricityBasic)
  - [ ] Install and use of the Arduino ?
  - [ ] Read a button from USB ?
  - [ ] Leonardo and Keyboard input ?
  - [ ] How to use bluetooth to communicated the Quest ?
  - [ ] Bluetooth to keyboard input ?

# Good example of company requiring those skills
[![Default Alt](https://img.youtube.com/vi/6yAbSh1G4aE/maxresdefault.jpg)](https://youtu.be/6yAbSh1G4aE?t=4) 
- https://pxlbbq.com/vr-hackathon-bruxelles/

## Jam reminder
- [Creative](http://www.mons.be/culture/creative-jam)
- [KISS](https://www.digitalwallonia.be/fr/publications/kissyourteacher2019)
- [Ludum Dare](https://ldjam.com/)
- KISS vs Ludum Dare
- [Brotaru: 7 octobre](https://www.facebook.com/bxl.otaru/)

## Kinect One
[![Default Alt](https://img.youtube.com/vi/VnLcTnvMDOk/maxresdefault.jpg)](https://www.youtube.com/watch?v=VnLcTnvMDOk)  
- Runtime https://www.microsoft.com/en-us/download/details.aspx?id=44559
- Asset store https://assetstore.unity.com/packages/3d/characters/kinect-v2-examples-with-ms-sdk-and-nuitrack-sdk-18708


## Rewired for specific controller 
[![Default Alt](https://img.youtube.com/vi/VkYVkRnjgjk/maxresdefault.jpg)](https://www.youtube.com/watch?v=VkYVkRnjgjk)  
- Custom control https://www.youtube.com/watch?v=VkYVkRnjgjk
- How to C# https://guavaman.com/projects/rewired/docs/HowTos.html
- [WingMan Attack 2 for Rewired](https://gitlab.com/eloistree/2019_09_09_WingManAttack2)
## Hack official bluetooth controller
![Fruit](https://cdn.instructables.com/F4G/LA5W/J9YJH7RE/F4GLA5WJ9YJH7RE.LARGE.jpg?auto=webp&frame=1&width=1024&height=1024&fit=bounds)

T0 | T1  
:- | -:  
![Image](https://images-na.ssl-images-amazon.com/images/I/61A8fx8p%2B4L._SL1024_.jpg)[360 Mini Controller](https://www.amazon.fr/manette-Bluetooth-Controller-Joystick-william-lee/dp/B07MKR2DD6/ref=sr_1_fkmr2_1?__mk_fr_FR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=controller+360+mini+bluetooth&qid=1567968763&s=gateway&sr=8-1-fkmr2) | ![Image](https://images-na.ssl-images-amazon.com/images/I/61%2BH%2BL74cxL._SL1000_.jpg)[360 Mini for finger](https://www.amazon.fr/ACGAM-Gamepad-Bluetooth-T%C3%A9l%C3%A9commande-Joystick/dp/B01NBDM4AJ/ref=sr_1_fkmr2_2?__mk_fr_FR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=controller+360+mini+bluetooth&qid=1567968763&s=gateway&sr=8-2-fkmr2)   


## HC 06 Bluetooth connecteur
[![Default Alt](https://img.youtube.com/vi/RwZCdfHIJs0/mqdefault.jpg)](https://www.youtube.com/watch?v=RwZCdfHIJs0)  
https://www.youtube.com/watch?v=RwZCdfHIJs0

## Idea
### Remote control
[![Default Alt](https://img.youtube.com/vi/jqT1DtLRAPk/maxresdefault.jpg)](https://youtu.be/jqT1DtLRAPk)  
- 360 Camera remote control https://youtu.be/jqT1DtLRAPk
- Rover https://youtu.be/G5m42Idke3Q

## Restream chat
![Image](https://restream.io/updates/img/posts/2018-09-26-new-restream-chat.png)
- [Holostream Channel 6](https://github.com/EloiStree/Portfolio/issues/4)
- [Moles Kingdom](https://github.com/EloiStree/Portfolio/issues/3)





2019_09_10_ToDoToday

https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/388
## Previous workshop
[![Default Image](https://raw.githubusercontent.com/wiki/EloiStree/2018_12_21_HelloHC06/Image/y5jrmxp4ahvl64ihe5a7e33eoj0pdo3m.png)](https://github.com/EloiStree/HelloRemoteFirework/wiki)
https://github.com/EloiStree/HelloRemoteFirework/wiki

## Keyboard for Leonardo
https://gitlab.com/eloistree/2019_08_10_helloarduinoaskeyboardhack

2019_09_11_ToDoToday

# To do today
"Apply only to those how learn to use the Arduino"

https://www.tinkercad.com/learn/circuits

Multimeter
  - [ ] Measure voltage 
    - [ ]  of a battery
  - [ ]  Measure intensity
    - [ ]  of a circuit 
  - [ ]  Measure resistance of resistor
    - [ ]  of a light sensor
  - [ ]  Check if a cable is broken or not ?
Arduino 
  - [ ] Light a led with a resistance
  - [ ] Use a button
  - [ ] Use a dynamiter resistance (light, move ore dimmer) 
  - [ ] Install the IDE
    - [ ] Make blink a led from the Arduino
    - [ ] Read a signal from digital pin
    - [ ] Read a signal from analog pin
## Electric basic reminder
[![Diode](https://github.com/EloiStree/HelloRemoteFirework/wiki/Image/fy649svz9p46tyl24k0l28y3xlv5k52s.PNG)](https://github.com/EloiStree/HelloRemoteFirework/wiki/ElectricityBasic)
[Electricity reminder](https://github.com/EloiStree/HelloRemoteFirework/wiki/ElectricityBasic)
# Formula
_6.240000.000000.000000 e-_
A = Amp = I = Intensity =  6.24 e- * 10^18 / second  
V = Volt   Generate Force to move e-   
J = Joules = Energy measure  
C = coulomb = the amount of excess charge  
Ω = R = Ohm = Resistance  
W = P = Watts = Light/Heat created by voltage and power  

## Formula
- R = V / I
- I = V / R
- W = V * I
- W = 4 J/S = 2 J/C * 2 C/S  
- C = 1 Farad / V  
- V = I * R
- I = V / R
- P =V^2/R  

## ElectromBOOM 
[![Default Alt](https://img.youtube.com/vi/GPHrSDnH6JI/mqdefault.jpg)](https://youtu.be/GPHrSDnH6JI)  

[![Default Alt](https://img.youtube.com/vi/jhvrfyjtOgU/maxresdefault.jpg)](https://youtu.be/jhvrfyjtOgU)  
https://youtu.be/jhvrfyjtOgU
- [AC vs DC](https://youtu.be/n2iPFZWe7uk) 
- [Speed of Electron](https://youtu.be/IOb3-JZPY0Y)
- [Taser](https://youtu.be/CkGVMWK10qU)

[![Default Alt](https://img.youtube.com/vi/MMzU66IHe-k/mqdefault.jpg)](https://youtu.be/MMzU66IHe-k)  
- [Pain and frequency](https://youtu.be/MMzU66IHe-k)
- [Kill from electricity](https://youtu.be/DQJ8JX17J58)


## Questions
- After the workshop ? Does you have access to the online course ?
  - Yes ;)

## Thanks for your patience
![harderFasterBetterStronger](https://media2.giphy.com/media/3oz8xtBx06mcZWoNJm/source.gif)




2019_09_11_ToDoTonight


![](https://github.com/EloiStree/CodeAndQuestsEveryDay/raw/master/WebRef/WorkInProgress.png?raw=true)

# Hello Oculus Quest (2 hours)
_Welcome to this workshop. The goal here is to answer your questions about the Oculus Quest (working under Android). And so to build your first Unity game/application_
- Feel free to bring your own Quest. Mine, three of them, are going to be available for group of participants.  

## Pre-Required
- Speak French (be able to read in English)
- Install Unity 2019.1 3D for Android ( Step By step tutorials ->)
- Use a Window 10 PC ( you can use your Mac if you don't have one)
_No coding skills is required to this session._
_If you have any code questions, I will be delight to answer them._

## Previous workshop on the subject
- [General, Where to start with Android and the Quest](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/93)
- [Technifutur, Hello Oculus Quest](https://github.com/EloiStree/CodeAndQuestsEveryDay/wiki/2019_08_14_ToDoToday)


# Workshop Step by step
Before the workshop  
- [Download Unity 2019.1.14](https://unity3d.com/fr/get-unity/download) ([Information](https://unity3d.com/fr/unity/whats-new/2019.1.14))
  - [Be sure to install the Android option](https://youtu.be/t8T75Aebl0U)
[![Android Option](https://user-images.githubusercontent.com/20149493/64278349-ce78d400-cf4c-11e9-998d-8856fd6acb90.png)](https://youtu.be/t8T75Aebl0U)
- [Unity what ? Install what ?](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/93)

During the workshop  

1. Install Unity 2019.1.14 / Android
2. Configure Unity setting
3. Add an asset to a scene
4. Build a version without Oculus Integration
5. Add Oculus Integration
6. Build a version with Oculus Integration
7. Add the [Android Manifest](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/376)
8. Add a script to rotate the asset in the scene
9. Answer the general question about Unity & the Quest
10. Practice ;)


# Note
More information and tutorials are going to be add 1-2 days before the workshop.
Feel free to look around on this wiki to find plenty of additional information.

---------------
### If you are totally new

Link | Where to start
:- | :-
[![https://github.com/EloiStree/CodeAndQuestsEveryDay/blob/master/WebRef/OculusQuestNewbie_64x64.png](https://github.com/EloiStree/CodeAndQuestsEveryDay/blob/master/WebRef/OculusQuestNewbie_64x64.png)](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/387) |  [If you are totally new in virtual reality or/and in Unity. Please, feel free to learn about the both of them here first.](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/387)  




2019_09_12_ToDoToday

### On store
Arduino: [Free](https://assetstore.unity.com/packages/tools/input-management/simpleserialport-53594?price=0-0&q=arduino&orderBy=0) [All](https://assetstore.unity.com/packages/tools/input-management/simpleserialport-53594?q=arduino&orderBy=0)  
Android [Micro Controller for Android](https://assetstore.unity.com/packages/tools/input-management/android-microcontrollers-bluetooth-16467)  

## Android Application
![Img](https://lh3.googleusercontent.com/Mhq_C_8zPLGMQShGLKHNSYIvhqDKRqoJIhhmt1rYqQB3as06f7juVqgF9C68aTwZGRg=w720-h310-rw)
- [Bluetooth Electronics](https://play.google.com/store/apps/details?id=com.keuwl.arduinobluetooth&gl=BE)
- [Arduino to HC06](https://play.google.com/store/apps/details?id=com.giumig.apps.bluetoothserialmonitor&gl=BE) 
- [Bluetooth Terminal](https://play.google.com/store/apps/collection/cluster?clp=ggEUChJibHVldG9vdGggdGVybWluYWw%3D:S:ANO1ljKWTu8&gsr=CheCARQKEmJsdWV0b290aCB0ZXJtaW5hbA%3D%3D:S:ANO1ljIOsmE&gl=BE)

# HC 06
[![Default Alt](https://img.youtube.com/vi/Iyd4gX0AR54/mqdefault.jpg)](https://youtu.be/Iyd4gX0AR54?list=PLFAQMlaJo92K0k4YKAiYOLfknGS2fe_w-)  
https://youtu.be/Iyd4gX0AR54?list=PLFAQMlaJo92K0k4YKAiYOLfknGS2fe_w-

[![Ressitance](https://lh3.googleusercontent.com/roHfSWfJNjhR9YXn40-ifPlvW2fNKKBv4fE1yzN81NKLrgyfLdCzlC_-w3OTPZpWUXzxE8dRW4v1JIZsJukFt4YVewoYmECo3IlIO3HvYRbmpYXlMrFtJU58CTHziNr5h6YK1Pktat5pvO65tDq9uETXZUKw2o7P6ndUXHDZ9bv2gtW6roeco3d4gmvW7o9HPaNeffPZQ7SoMlczEuaAMAe21FSPdCp6CUJuuJd4a7rQaZjNZf_QukF4pc8OpfogHB0EFSySAViJNlGuNKO14jmOpGSw_Fx7L2TdeHqrerrqQPEcj4c3nfSOdfF_0J73KLGMBTMHSKtxiHWFduuAArXj7hJen7T_o1OkAe52lBIWctcVCI5BGLkYan4ghNoXN276y0pwK1NvFoBtu0CYMF0gzhwdF1mjwEwexG6FcIO8JsttK9CZj_pjI-Pxv1S2JqJfeedhtCXb9KaJwbWSHCrJ_L5CKwQ3MjscxuGj6DagxJ24A8_iHZ1ja6Xnfib0vOLxj3_50VWy6sIBYUAM-t5aj6_y3cJqCzdPZi75x957XnOvT0gTBU5_RcDpay0iychr1t9m1ONepHrVSQjaKwSW7ECZ68p7V8HbUjD8plp697or_bgsgAqHHKP-RV2Tr4npusFssGxS0CyT1HwstudgWC_m8df8AQx3RGlgz5wtaGaUI_V5YkjpTZxwOQMYS4ihNpyWjFGODP9_-SMUn8SiwQEXVnrxUbO2hQ9JW-Mwo37J=w1081-h608-no)](https://photos.google.com/share/AF1QipNB0LWtPjp6X9IJ3oJTQ52dRa-JrSvJwhaFPM02sZgnj16u373Rvuo44LJko5N8uQ?key=WVhGWkhJd3BxMWNwSG1kdjA3Uy1GaHJSaFZBakN3)
- [XMas Firework](https://photos.google.com/share/AF1QipNB0LWtPjp6X9IJ3oJTQ52dRa-JrSvJwhaFPM02sZgnj16u373Rvuo44LJko5N8uQ?key=WVhGWkhJd3BxMWNwSG1kdjA3Uy1GaHJSaFZBakN3)
- [HC 06 January](https://photos.google.com/share/AF1QipND-TI6QWSyT1ms4u_m57-HECp4uUWKc3AKZaZZe7I4YQmz7jcSALD0W40rt8SMog?key=MXRCZ2dUa0VEdWU5bnRnd0UtZmdnOUNxeDF2dW1R)


``` c
/*
 * Bluetooth HC-06 (SLAVE) control from your Android phone RSB May 2016
 */
#include "Arduino.h"
#include <SoftwareSerial.h>

// Instantiate our BT object. First value is RX pin, second value TX pin
// NOTE: do NOT connect the RX directly to the Arduino unless you are using a
// 3.3v board. In all other cases connect pin 4 to a 1K2 / 2K2 resistor divider
/*
 * ---- pin 6-----> |----1K2----| to HC06 RX |----2K2----| -----> GND
 *
 * See my video at www.youtube.com/c/RalphBacon for more details.
 */
 SoftwareSerial BTserial(4, 6); // RX , TX

// Our output indicator (could drive an opto-isolated relay)
byte LEDpin = 8;

// -----------------------------------------------------------------------------------
// SET UP   SET UP   SET UP   SET UP   SET UP   SET UP   SET UP   SET UP   SET UP
// -----------------------------------------------------------------------------------
void setup() {

  // LED output pin
  pinMode(LEDpin, OUTPUT);

  // Serial Windows stuff
  Serial.begin(9600);
  Serial.println("Set up complete");

  // Set baud rate of HC-06 that you set up using the FTDI USB-to-Serial module
  BTserial.begin(9600);
}

// -----------------------------------------------------------------------------------
// MAIN LOOP     MAIN LOOP     MAIN LOOP     MAIN LOOP     MAIN LOOP     MAIN LOOP
// -----------------------------------------------------------------------------------
void loop() {

  // If the HC-06 has some data (single char) for us, get it
  if (BTserial.available() > 0) {

    // Get the char
    char data = (char) BTserial.read();

    // Depending on value turn LED ON or OFF (or error message)
    switch (data) {

    case '1':
      Serial.println("ON");
      digitalWrite(LEDpin, HIGH);
      BTserial.write("ON");
      break;

    case '0':
      Serial.println("OFF");
      digitalWrite(LEDpin, LOW);
      BTserial.write("OFF");
      break;

    default:
      Serial.print("NOT RECOGNISED: ");
      Serial.println(data);
      BTserial.print("Error!");
    }
  }
}
```
// [How to set the resistance ? Y>](https://youtu.be/Iyd4gX0AR54?list=PLFAQMlaJo92K0k4YKAiYOLfknGS2fe_w-&t=120)  


## Easy plug-in for Unity
[![Plugin](https://assetstorev1-prd-cdn.unity3d.com/key-image/bd47cae5-1492-4c93-a23c-11e3132ac9f0.jpg)](https://assetstore.unity.com/packages/tools/input-management/android-microcontrollers-bluetooth-16467)
https://assetstore.unity.com/packages/tools/input-management/android-microcontrollers-bluetooth-16467    
[Hey Mon Ami !](https://we.tl/t-OIkPXJQrPL)   

_Example:_
``` cs
using UnityEngine;
using System.Collections;
using UnityEngine.UI;

using TechTweaking.Bluetooth;

public class BasicDemo : MonoBehaviour {

	private  BluetoothDevice device;
	public Text statusText;
	// Use this for initialization
	void Awake () {
		BluetoothAdapter.enableBluetooth();//Force Enabling Bluetooth
		device = new BluetoothDevice();
		device.Name = "HC-06";
		//device.MacAddress = "XX:XX:XX:XX:XX:XX";
		}
	public void Connect() {
		statusText.text = "Status : ...";
		device.connect();

	}
	public void Disconnect() {
		device.close();
	}

    public void SendOn()
    {
        if (device != null)
        {
            device.send(System.Text.Encoding.ASCII.GetBytes("1\n"));
        }
    }
    public void SendOff()
    {
        if (device != null)
        {
            device.send(System.Text.Encoding.ASCII.GetBytes("0\n"));
        }
    }
    /* Please note that this way of reading is only used in this demo. All other demos use Coroutines(Unity offers many tutorials on Coroutines).
	 * Just to make things simple
	 */
    void Update() {
		if (device.IsReading) {

			byte [] msg = device.read ();


			if (msg != null ) {
				string content = System.Text.ASCIIEncoding.ASCII.GetString (msg);

				statusText.text = "MSG : " + content;

			} 
		}
	}
}

```

--------------------
## Forgot
[Info](https://www.devonbuy.com/checking-battery-voltage-levels/) | Good | Middle | Bad
:- | :-: | :-: | -:
 AA/AAA |  1.35+ |  1.2-1.3 |  1-1.2
 9V | 9  |  7.2 |  5.4
 12V |  10 |  9.6 |  7.2
 _Use 150 Ohm resitor to check the battery_
_Death =60% Weak 80%_

-----------------------------------
(Reminder: Don't use versioning control, Git or alternative, is a professional fault.  
And you need to be crazy or stupid to not use it... With all my respect ;) )


2019_09_13_ToDoToday


# To Do Today

- Train to meet and speek for the 3 November and the 6 December
  - [Reminder](https://github.com/EloiStree/CodeAndQuestsEveryday/wiki/2019_08_19_ToDoToday)
    - 4 Words Pitch   …   |   …   |   …   |   …  
    - One Sentence Pitch: "My startup <name> is working on <offering> to help, <target customer> to solve their <pain-point> by your <secret sauce>"
  - Add your words here: [Let's others be your ambassadors](https://docs.google.com/spreadsheets/d/1dVBeHZT1lLIf4nOrAwqomUegW0mJCogNsYP7t9HVmtE/edit?usp=sharing) 
  - Role play exercise 1 vs 1
  - Role play exercise 1 vs random
- Post-research: Pecha Kucha
  - 20 images  x 20 seconds
    - what you want to share to the group
    - what did you learn if a client ask you to work on this new field
- Speak about yesterday news about Liège new center
  - Q&A about what it means
  - Try the MSI Backpack
  - Check what is the other backpack
  - Q&A about the backpack

## Pitch
### Challenge: Junior
Tool : ["Pocket Coach"](https://docs.google.com/document/d/10xk_kAYaAWpAKv89NOMqkw_6iy01OTS6CFEKBFbyCMc/edit?usp=sharing)
Reminder: [Add your 4 words here](https://docs.google.com/spreadsheets/d/1dVBeHZT1lLIf4nOrAwqomUegW0mJCogNsYP7t9HVmtE/edit?usp=sharing)
- Define your 4 words pitch and try yourself on the group or me 
### Challenge: Expert
- Define you 4 words and one sentence. Try to make me want to hire you.

## Pecha Kucha
- [What is a pecha kucha ?](https://www.pechakucha.com/)
  - [Where ?](https://www.pechakucha.com/nearest)
- How ? [Google Slide](https://www.google.com/intl/fr_BE/slides/about/)
### Challenge: Junior
- Define the story you want to share with the group (based on your research)
### Challenge: Expert
Tool: ["Ready to be invested"](https://docs.google.com/spreadsheets/d/1fbLTgk2ejgTJqreBfxvGk5eF-UVjvmew7lMtAyiX2D4/edit?usp=sharing) - ["Pocket Coach"](https://docs.google.com/document/d/10xk_kAYaAWpAKv89NOMqkw_6iy01OTS6CFEKBFbyCMc/edit?usp=sharing)
- Define the story you want to share but with the aim to ask/require something to the audience, or me, to go forward.



2019_10_07_ToDoTonight
See: [Oculus Quest in 2H](https://github.com/EloiStree/CodeAndQuestsEveryDay/wiki/2019_09_11_ToDoTonight)
---------------
![WIP](https://github.com/EloiStree/CodeAndQuestsEveryDay/blob/master/WebRef/WorkInProgress.png?raw=true)
---------------
### If you are totally new

Link | Where to start
:- | :-
[![https://github.com/EloiStree/CodeAndQuestsEveryDay/blob/master/WebRef/OculusQuestNewbie_64x64.png](https://github.com/EloiStree/CodeAndQuestsEveryDay/blob/master/WebRef/OculusQuestNewbie_64x64.png)](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/387) |  [If you are totally new in virtual reality or/and in Unity. Please, feel free to learn about the both of them here first.](https://github.com/EloiStree/CodeAndQuestsEveryDay/issues/387)  

