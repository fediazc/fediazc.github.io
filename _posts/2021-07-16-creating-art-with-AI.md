---
title: "Tutorial: Creating Art with AI"
layout: post
---

The art you see below was created completely by AI. All I had to do
was input the prompt **"Lake \| Mountainside \| Watercolor"** into a program and
the AI took care of the rest. This will be a very quick tutorial for how to make this
kind of art. If you want to learn more about AI art and what's possible 
with it I recommend reading 
[this article by Charlie Snell](https://ml.berkeley.edu/blog/posts/clip-art/).

![Lake \| Mountainside \| Watercolor](/assets/images/creating-art-with-AI-post/Lake-Mountainside-Watercolor.png)

## Setting the Prompt

We are going to be using [**this Google Notebook**](https://colab.research.google.com/drive/1_4Jl0a7WIJeqy5LTjPJfZOwMZopG5C-W?usp=sharing) originally created by [Katherine Crowson](https://github.com/crowsonkb).
(it's been modified since by others). If you're not familiar with notebooks, 
they're similar to google docs but for code/programs. The program will run in a 
remote computer and you won't have to download anything to your PC. 

Make sure you're logged in into a google account so that you're 
able to run the program later. 

After opening the notebook, scroll down to **Implementation tools > Parameters** section. 
Here, you will be working mainly with the "prompts" parameter. Messing with the 
other parameters is not really necessary if you want to get started right away. 
You could try increasing the width and height of the image, but I've found that 
this causes the program to run out of memory.

<img src="/assets/images/creating-art-with-AI-post/parameters.png" width=200 height=170/>

Now change the "prompts" parameter to whatever you'd like. I'm going to try
"cityscape at night" but you can get as creative as you want.

## Running the Program

After you've set the "prompts" parameter, you can run the program by clicking 
**Runtime > Run all** on the toolbar. It will take a while to run as it has
to do some downloads, but after about 2 to 3 minutes you should see a brown image
show up under the **Implementation tools > Execution** section. Every minute or 
so you should continue to see updates as the AI works on creating the image 
(shown below).

<img src="/assets/images/creating-art-with-AI-post/updates.png" width=280 height=526/>

You can keep track of the progress with the blue bar in the **Execution**
section. You should see updates at iterations 50, 100, 150... and so on, as
long as you didn't change the "display_frequency" parameter.

<img src="/assets/images/creating-art-with-AI-post/progress.png" width=488 height=29/>

When you're happy with the images created, click **Runtime > Interrupt execution**
on the toolbar. If you want to create a video with all the frames created by the
AI, you can wait a couple more seconds. If not, click **Runtime > Interrupt execution**
again.  And that's it, now you can save the image(s).

If you want to create another, simply change the "prompt" parameter again and 
click the "run" button next to the **Parameters** section and then the one next to the
**Execution** section. Whenever you close and reopen the notebook, you will
have to do **Runtime > Run all** to redo the downloads.

<img src="/assets/images/creating-art-with-AI-post/run-button.png" width=215 height=50/>

That's it. Have Fun! If you want a more in-depth guide for how to use the
other parameters and more information about creating prompts I recommend 
[this tutorial](https://docs.google.com/document/d/1Lu7XPRKlNhBQjcKr8k8qRzUzbBW7kzxb5Vu72GMRn2E/edit).