---
layout: post
title: webspraping
---


As already explained in the course unit what we need were those 2  links:

http://www.perseus.tufts.edu/hopper/text?doc=Perseus%3atext%3a2006.05.0001
http://www.perseus.tufts.edu/hopper/dltext?doc=Perseus%3atext%3a2006.05.0001

with those in a txt file I opend power shell and got into the same folder as the txt file and the wget.exe

next i used the following command in powershell:

wget -i homework.txt -P -c subfolder http://www.perseus.tufts.
edu/hopper/text?doc=Perseus%3atext%3a2006.05.0001

I was unsure why it didn´t work out, since in the last unit it seemed to work just fine.



