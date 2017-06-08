---
layout:     post
title:      "Why I'm writing this blog"
subtitle:   "Please Enjoy"
date:       2017-06-07 03:00:00
author:     "Thomas Fuller"
header-img: "img/posts/why.jpg"
comments: true
tags: [ Personal ]
---

<center><big>Who I am.</big></center>
Hi, I'm Thomas Fuller.  I'm a research engineer specializing system engineering and control theory.  I've found the trend of industry towards AI and machine learning to be too strong to ignore, so I recently have developed an interest in those topics as well.   Other than that I can say a few things about myself:  I use Linux, I really like Python, I'm learning C++. 

<center><big>Where I am</big></center>
I'm in Boston, MA. It's at minimum the 5th best city on the planet. 

<center><big>Why</big></center>
I'm writing this blog for a few reasons.  The first is to help myself think about the various research projects that I'm working on.  

The second is that I want to be producing content every week.  Maybe that's not just for this site, but in other areas as well (Youtube/Github) come to mind.  I believe that being doing the things you want to improve at is the best way to get better.  

<center><big>What</big></center>
I'm working on improving my programming abilities and the main way that I'm doing that is by trying to implement the algorithms used in the Alphago Go AI program.  I've mostly been reading the academic papers explaining the main techniques for beating humans at Go.  I'll write more about the project soon, but the basic idea is this:  Every game of perfect information can have constructed for it a data structure containing every possible outcome.  The number of nodes in that data structure is impossibly large for the game of Go.  

So MCTS can check a lot of the possibilities very quickly and decide if random sequences of moves makes you more likely to win.  Then, future iterations bias nodes on the tree so that the path that it thinks is more likely to lead to victory is searched.  

Anyways there's another part to the algorithm called a Neural Network.  It's basically a series of functions that are inputs to other functions.  They are kind of a miracle in the sense that they use "units" of simple functions and can approximate crazy ones.  Still have to read more about how it works.  The simple explanation is that they used two neural networks, a 'value' NN which evaluates board position, and a 'policy' NN that helps select moves.  

Anyways that's a lot to learn but I'm pretty sure I can build some crude amalgamation of this program by the end of this summer. 

Best,
-T


