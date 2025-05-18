[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zon3mdIg)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18801932&assignment_repo_type=AssignmentRepo)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/new/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Notes

> You can use this section of the file to keep notes about your project as you work on it.

# Project Summary

> Knitting can be complicated, especially to a beginner such as myself. Instructions may be difficult to follow when they look like a jarred mess of letters and numbers. To help myself with the process, I usually use pen and paper to figure out how the pattern will look. This takes a pretty long time. To save time and apply my new-learned JavaScript skills, I've created a tool to help turn the not-so-often intelligeble instructions into visually represented patterns. The point of that is exact the same as the pen and paper trick - to resemble the look of the finished fabric in real life. Knitting is a sort of programming after all, and Knitter helper is a program created with a very specific usecase in mind. Thus, it maybe a little hard to understand at the beginning, especially if one's not familiar with the art of knitting.

> To make this was a rollercoaster. I started at the wrong end of trying to do things with table manipulations and wasted about 10 hours there. I also learned that I know very little, and that there is not enough space in my head to squeeze in all the information I wanted to learn in the short time that I had. I regret staring at the program for way too many hours, and giving myself nightmares about arrays. It was fun hidden somewhere amidst all of it. Turns out that coding feels like putting together a good puzzle. But you gotta give yourself breaks, or your brain will temporarily turn into potato mash like mine. 

> Things to be improved:
  -  Add an example instruction to get the user started.
  -  Allow for "flipping" the rows.
  -  Allow adding new rows as needed.
  -  Allow to repeat the entire output pattern to get a better understanding of the finished fabric.
  -  Give feedback to the user when the pattern has gaps, indicating that there might something wrong with the input.
  -  The amount of variables can probably be improved (read: reduced). Right now I have about 30 variables which is way too much for something this small. 
  -  The important part of the array manipulations are made with .concat method which I've learned is not the proper way to do this. Can probably be improved with .splice, so this is something I would need to look into.

> I could not stick to the budget. I spend too many hours trying to find ways to do this the way I wanted to, instead of trying to use what I have already learned.

# User Guide

> To understand how the Knitting helper works, one needs to first and foremost be familiar with the knitting-specific terminology.

> "CO" stands for "Cast On". This means the number of stitches that we are *casting on* to the knitting needles. The cast on number will determine the length of the fabric on the needle.

> "K" stands for "Knit", and "P" stands for "Purl". They are the two basic knitting stitches. They look different, and in the program we represent them as "v" for "knit" and "-" for "purl", resembling their appearence in real knitted fabric.

> Usually the pattern also indicates edge stitches, at the beginning and at the end of the row.

> This is what the program invites us to enter: the CO number, the starting edge, the part the repeats (usually indicated by being placed between parenthesis () or stars ** in the pattern), and the end edge.
>
> ![knitterhelper3](https://github.com/user-attachments/assets/beca75d3-ff5e-439c-b65b-817edaf83d3f)


> Now let's look at an example instructions from So Woolly:
>
> ![alternatingdot](https://github.com/user-attachments/assets/d5f22c52-7e88-4016-8b7a-2e452139042e)

> The pattern calls for an odd number of stitches. Let's try casting on (CO) 21 stitches, and following the instructions:
>
> ![knitterhelper1](https://github.com/user-attachments/assets/d48aba43-1f17-4103-9ceb-e641a971654a)

> Entering the instructions will give us this pattern:
> 
> ![knitterhelper2](https://github.com/user-attachments/assets/b2a8bed0-b6e1-477e-9133-6fcd2d4fcbdb)

> Which would looks something like this, knitted:
> 
> ![alternatingdot2](https://github.com/user-attachments/assets/a7c179f9-ac4d-4c13-8e37-d989e0f51d0c)

> Currently, only four rows are supported.


