---
layout: post
title: "August 2022 Alpha Demo Recap"
categories: demo
tags: [demo]
image: 2022augalpha/20220807233832.png
---

[6th of August 2022, I made a post on reddit](https://www.reddit.com/r/Deusex/comments/whs7ox/a_first_demo_in_my_project_to_recreate/) about a little project that I've been keeping quiet about for more than a year.

I took something that I threw together for the past month, added a camera and looked up how UE5's sequence editor works, and made this.

<iframe width="560" height="315" src="https://www.youtube.com/embed/hReMq_UZFhc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This demo in particular combines the background in the VTOL's interior as shown in the scene before you start the mission in the Manufacturing Plant and the helipad behind the SI building. The helipad set is very much a work in progress; I had to use some surfaces from the Megascans library for the helipad surface itself to make the demo look presentable.

The light used in the demo is directional, I rotated it a bit as the animation ran.

### some rendered stills

![alt](assets/img/2022augalpha/20220807233913.png)

![alt](assets/img/2022augalpha/20220807234127.png)

#### comparison shot 1

the in-game shot is from DXHR-DC

![alt](assets/img/2022augalpha/20220807234310.png)
![alt](assets/img/2022augalpha/20220807234300.png)

#### comparison shot 2
![alt](assets/img/2022augalpha/20220807234505.png)

without external lighting:
![alt](assets/img/2022augalpha/20220807234456.png)

with using a tinted spotlight 
![alt](assets/img/2022augalpha/20220808174728.png)

### blender
![alt](assets/img/2022augalpha/20220808221736.png)
![alt](assets/img/2022augalpha/20220808221523.png)

fun fact: if you run Ninja Ripper on the VTOL scene, you actually get to see Jensen's jacket just hanging there next to him. The camera doesn't show it since the entire scene focuses on the two of them, but it's there. textures and all.
![alt](assets/img/2022augalpha/20220808221553.png)

![alt](assets/img/2022augalpha/20220808221816.png)

another fun fact: the VTOL has no fourth wall
![alt](assets/img/2022augalpha/20220808221841.png)

### helipad

It's still on the very early stages so I'm still only 10% into texturing it, but I do have some shots of the meshes

![alt](assets/img/2022augalpha/20220808222003.png)
![alt](assets/img/2022augalpha/20220808222024.png)

fun fact: As far as I know, there are no scenes with Malik in the VTOL that are not pre-rendered. Now, they mention in the dev commentary that the scene where Jensen walks in the VTOL to talk to Sarif for the first mission was not supposed to be pre-rendered, but it turns out that the interior of the VTOL does come with textures, as well.

![alt](assets/img/2022augalpha/20220808222316.png)


The SI building facade looks a bit like a Borg cube with just the bare textures lmao

![alt](assets/img/2022augalpha/20220808222430.png)

### preview of other stuff in progress 

![alt](assets/img/2022augalpha/20220808222750.png)
![alt](assets/img/2022augalpha/20220808222935.png)

### bonus: a little something that's been driving me nuts

I think I got everything to look right, except for the normals. The engravings in-game look a lot deeper compared to anything I can set-up on UE5 and Blender. I tried cranking up the blue channel of the normal map to some ridiculous numbers and still nothing.

![alt](assets/img/2022augalpha/20220808223145.png)

I'm not going to dwell on it right now because it's not the main focus of this part of the project, but I still want to get it to work.

Also, yes, it's brown, according to the in-game textures.