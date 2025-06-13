## Video Script (Template)

Filename: **FL-course-stepnumber-steptitle**  

Presenter: **Name**  

***

>#### 1. 👤 TALKING HEAD 👤 
> *Add comments/notes on direction here*  

This is example text for a video script

Here is more text

***
>#### 2. 🔴 SCREENCAST (video-in-video) 🔴  
> *direction notes*  
> ![alt-text](url of reference screenshot image)


This is where screencast text goes.

Here is some more text  

***

>#### 3. ▶️ VOICEOVER with ANIMATION ▶️  
> *direction notes*  
> [A link to a storyboard for the animation](url)  

This is where voiceover text goes.  
Here is some more text  
and again

***  
***

*Here are some useful snippets you can add to VS code to quickly generate sections of scripts for each format:*
```
"talkinghead": {
    "prefix": "talkinghead",
    "body": [
        ">#### ${1:X}. 👤 TALKING HEAD 👤",
        "> *${2:direction notes}*\n"
        "${3:insert script text here}\n"
        "***\n"
    ],
    "description": "talking head"
},

"screencast": {
    "prefix": "screencast",
    "body": [
        ">#### ${1:X}. 🔴 SCREENCAST (video-in-video) 🔴 ",
        "> *${2:direction notes}*  ",
        ">![${3:desc}](images/${4:path})\n"
        "${5:insert script text here}\n"
        "***\n"
    ],
    "description": "screencast"
},

"voiceover": {
    "prefix": "voiceover",
    "body": [
        ">#### ${1:X}. ▶️ VOICEOVER with ANIMATION/ILLUSTRATION ▶️  ",
        "> *${2:direction notes}*  ",
        ">[Link to animation storyboard](${3:url})\n"
        "${4:insert script text here}\n"
        "***\n"
    ],
    "description": "voiceover"
},
```