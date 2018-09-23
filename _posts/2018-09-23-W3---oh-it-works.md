---
title: W3 - oh it works
layout: post
author: luke.corey
permalink: /w3---oh-it-works/
source-id: 1YWxHs6G0vL2OILQW0jCBH__hsY77WFrnRG4ZIoMFnM0
published: true
---
As the title suggests - the Caesar Cipher (yes I am still using American terminology) works! While I did have to unplug Granny, it boasts shifts 1-25, along with not breaking when you put spaces in. My end goal is to have one sheet which has the thing people want to see (being the input, the parameter(s) and the output), and other sheets (named data sheets (as of when I'm writing this the one which does the hard work for the Caesar Cipher is called caesarData)) having all the other stuff.

While that seems like it would be hard to transfer information from one sheet to another, it really isn't. You just put (name of sheet)! and then the "destination" (eg A5).

What is harder though is working out how to make a Vigenère Cipher in Google Sheets. Turns out a friend in my class made one in under an hour and showed it to me in discord, but I want to try figure it out myself.

In case you don't know what a Vigenère Cipher is, it’s basically a Caesar Cipher but instead the shift is a word that loops. So if I had the key as dog, what I want my Spreadsheet to do is (a) translate the letters d, o, and g into numbers - in this case being 5, 16, and 8 - (b) shift the letter by that many spaces (it’s 5, 16, and 8 because if it was 1 less then it doesn’t quite work), (c) loop the key phrase and then (d) spit out the final result.

On a sidenote, I just found out when you put (c) into Google Docs it turns into the Copyright Symbol (look ©!)

I'm still trying to work out how to get it to work, but eventually I should work it out.

Hopefully.

(Again, you can click <a href="https://megmefalrez.github.io/about/">here</a> to go to my about section. If you scroll for a bit you'll see the spreadsheet and a link to it.)
