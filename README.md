# Setup Visual Studio Code for Angular

## Why i created this guide?

i was researching the net about a simliar guide. There were some guys who also switched from WebStorm to Visual Studio Code but i missed some things. Maybe there are more people out there with same problems. I am a developer since 10 years and hope that this document will maybe help someone.

## Is smooth Angular developing possible with VS Code?

✅✅✅✅ Yes, definitly it is!

FYI: I switched from WebStorm to Visual Studio Code. The target was that i can work as smooth as with WebStorm or even better. The decission for switching was based on the lightweight of vs code and the whole ecosystem (And yeah, its free 😇). I guess there is an extension for everything you need. If not, develop your own.

I worked a lot with big Angular projects. From my current point of view you can use vs code as your number one IDEA for Angular. WebStorm is looking stronger at the moment but if you take a deeper look vs code is maybe the winner for you.

But there is one point you may don't like. In WebStorm you have much buttons, fancy windows and so on compared to vs code you'll use more shortcuts or type in the actions you are looking for.

## Extensions for Angular

Yes, everything in vs code is based on extenions. But why not? I like the idea behind. Deliver a blank software and extend it based on your needs. So, here we go!

### Must haves

✅ Angular Language Service  
↪ Some AI features for angular.

~~✅ angular2-inline  
↪ If you use inline template you have to install this extentsion cause vs code does not support inline templates.
.~~
Update: 2020-02-25 . 
This feature is now included by Angular Language Service - Awesome

~~✅ Auto Import  
↪ When the Project will be bigger, the auto import from vs code is not as good as you think. VS Code will insert wrong paths 👀. So i recommend you to disable the vs code one and install this extension. I had no problems until now. Maybe microsoft will fix this (2019-08-20).~~

Update 2019-11-12 . 
Theres already a fix. In my case i need relative Import Parts. You can easly activate that. Just open the Settings and search for "typescript.preferences.importModuleSpecifier". Set this value to "relative". Thats it, extension no more needded!  

✅ GitLens  
↪ Switching branches? annoate files? other nice git features? use this extension.

✅ IntelliJ IDEA Keybindings  
↪ Yeah, i mentioned that i came frome WebStorm so...

✅ Move TS  
↪ Already renamend a folder which is containing tousends of files which are used in other files imports? This extensions is really great if you need an auto update of the imports when you rename a folder/file.

✅ Prettier  
↪ Basic

✅ TSLint  
↪ Basic

### Optional for Angular

✅ VSCode Great Icons  
↪ nice icons i like

✅ Theme you Like 😝  
↪ if you find a good one tell me

✅ Emoji  
↪ yes, emoji's are awesome. As you can see in this document. I created the emojis with this extension.

✅ ng-refactor  
↪ maybe you want to swtich from inline templates to external? Or backwards? No Problem this extension will do this for you.

## Other hints

### Git Merge Conflicts

I came from WebStorm and the git merge dialog is really smooth. But you can have a similar functionality in vs code, just try it out. This guy knows it good:  
https://www.youtube.com/watch?v=kBIMGOxqqnk

### Often needed shortcuts

As you can see i use mac. I don't know the shortcuts for windows / unix. But i think its no problem to find them out. Note that i have installed **IntelliJ Keybindings**.

Search Everywhere ⏩ `CMD + SHIFT + F`  
Find File ⏩ `CMD + SHIFT + O` (IntelliJ Keybindings 😇)  
All other Actions you need ⏩ `CMD + SHIT + P`
