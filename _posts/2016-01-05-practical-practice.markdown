---
layout:     post
title:      "From Practice to Practical"
date:       2016-01-05 20:27:00
author:     "Amy McKnight"
header-img: "img/about-bg.jpg"
---
So today I needed to do a calculation. I needed to calculate the raw cost to make a book and then figure out the wholesale price. I needed to do it in a way that would allow me to just enter in the number of books and get all the info in a neat package.

So I was telling my husband what I needed to do and I was like, "If I knew ruby better I know I could write a program for this."

And then it hit me. I totally knew enough to make a basic little program to do that for me. Here it is: 

    numberofbooks = gets.chomp
    number = numberofbooks.to_i
    rawcost = ((number * 0.75) + 75)/number
    wholesale = rawcost * 2 + 1.25
    profit = (wholesale - rawcost) * number
    markup = (rawcost * 2) - rawcost

    puts rawcost
    puts wholesale
    puts profit
    puts markup

I know I could have done a method or two but I was sure of this and I was able to code it up faster than I could tweet about it on twitter. 

That made me feel so good. Slowly but surely I'm getting it. I'm becoming a developer.

What was the first thing you build as you were learing to code to help you solve a problem? I'd love to hear about it in the comments!
