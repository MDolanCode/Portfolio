---
layout: post
title:  "Building My Portfolio Website"
date:   2021-11-09 14:42:00 -0700
categories: Jekyll
---
### How did I do it, and my lessons learned.

<img src="../images/philipp-katzenberger-iIJrUoeRoCQ-unsplash.jpg" alt="Picture of computer" width="100%"/>

Photo by <a href="https://unsplash.com/@fantasyflip?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Philipp Katzenberger</a> on <a href="https://unsplash.com/s/photos/computer?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

<br>
  
I am currently looking for a new role as an iOS Developer and was updating my resume recently, so it got me thinking, should I have a portfolio? I wasn't sure if having one was even necessary, but I am a newer developer with two years of experience, so I thought I would ask those who had more experience than I what they thought. I posed this question in one of the iOS Developer communities I belong to on Slack to see what others would say, and some thought it wasn't necessary, but a few did. Then later, I spoke with a friend, and she said that early in her career, her portfolio site helped land some jobs, so I thought about it and then decided to build a portfolio site. After lots of trial and error, I eventually used [Jekyll][jekyll], and I will show you how I got to this place and all the factors I considered, so hopefully, it will help you when you decide to build your own. 

<br>

Before building my portfolio site, there were many things I had to think about, such as do I want to code it myself? After all, I have a static portfolio site that I created for web development a few years back, and maybe I could convert that. Or, since I have hosting already, maybe create one using WordPress? Then, I thought about React. When I had posed the question in the Slack group, a couple of people mentioned [Jekyll][jekyll] and hosting on GitHub [Pages][github-pages], and I was also kindly given a Jekyll theme that one of them created. There was also a mention of using Squarespace to get you up and running fast. So what did I do, you ask? I tried them all! 

<br>

First, I started by looking at my homegrown option, the static site I built three years ago for web development, and when I looked at the HTML5, Bootstrap3 and CCS3, I was thinking, can I make this work for my needs? Well, what are my needs? I knew I wanted a portfolio, an about, a contact, but what about a blog or selling merchandise? Hmm. With those questions, I then knew that the static site I had created wasn't going to cut it, so I looked at React but found the same thing because I needed a backend, and I don't know how to program that yet. 

<br>

I like to think BIG, so I moved on to WordPress since I already have a hosting package with Namecheap. I wanted to pick a theme, customize it with Elementor, the WYSWYG plugin, and have a portfolio, blog and store for merch, BUT having to go through endless settings and backend menus to set everything up was frustrating and a buzz killer. Plus, the upkeep of the theme and all the installed plugins I use would have been too much to maintain for me right now. I felt similar things when I tried out Squarespace next and then gave up because the number of hidden menus was annoying. 

<br>

Next up was [Jekyll][jekyll], and from my understanding, many developers love and use it. I looked at the theme I was kindly given and looked at many other free ones too. I decided to go with [minima][minima] which is Jekyll's base theme, and then started to go through the tutorials. I tend to want to go deep and customize everything, and sometimes my expectations of myself are more than what I am capable of at that moment, so I started customizing my portfolio. When you customize Jekyll, you need to know Yaml and Liquid programming languages, both of which I am not familiar with, so I ended up getting lost and gave up on Jekyll and went back to WordPress. Now you are probably saying, I thought you built your portfolio with Jekyll? I did, and I will get to that.

<br>

So, as I said, I went back to WordPress, and as I was trying to get it going, a reply came into the thread where I asked my question in the Slack group. The blog title was ["How to start a blog or portfolio website for developers"](https://www.jessesquires.com/blog/2021/11/01/how-to-start-a-blog/) by Jesse Squires, and when I read the post, one line hit home for me since I think BIG and sometimes have abandoned projects because of that. Here is the line I am talking about, "Keep in mind that you can stop at any point when you reach a level with which you are comfortable. You can always progress to something more advanced later."  Reading Jesse's post made me stop and think, do I need that merch shop right now? No! Do I need to customize everything right now? No! I then decided to scale it back to what I am comfortable with, and I used the minima Jekyll theme and created simple markdown pages to start. While doing this, I kept in mind the words from Jesse's post, which helped me stay focused, and then two days after my portfolio site was complete.

<br>

My takeaways from this project are that it is good to have BIG ideas but know your limits and start small because you can advance later. And also, the simple option is sometimes the best option to get you going. 

<br>

One more thing, when I read the book ["Big Magic: Creative Living Beyond Fear"][big-magic](Amazon link) by Elizabeth Gilbert some years back, she had one point I connected with and would like to share with you. That point is that "Done is better than perfect." That is what I have done with my portfolio site, and I will iterate on what I have and work on my BIG ideas little by little. 

<br>

Hopefully, my blog post has helped you, and if you would like to share feedback or have any questions, I would love to hear from you, so feel free to [contact][contact] me. Also, if you want to make a portfolio site, I recommend you check out Jesse Squires's [post][post] because it is well laid out, helpful and will get you going!

<br>

Do you have a portfolio site? If so, I would love to hear how you built yours.

<br>

[jekyll]: https://jekyllrb.com
[minima]: https://github.com/jekyll/minima
[post]: https://www.jessesquires.com/blog/2021/11/01/how-to-start-a-blog/
[big-magic]: https://amzn.to/3FaYTph
[github-pages]: https://pages.github.com
[contact]: https://www.mdolancode.com/contact