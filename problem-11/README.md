## Let Σ = { 0, 1 }

### Problem 11:

Design a NFA M such that L(M) = {string s| the 2nd to last bit is 1 }

### Design:

<img src="../Screenshots/n11.png">
<h3>Which problem(s) gave you the most trouble?</h3> 
This was the first JFLAP design I did. It was relativley easy. At first when running test strings all my cases kept getting <strong>rejected</strong>.
<br><br> When I added a transition between states that would accept one or more elements in Σ, I would format it as "1,0". This did not seem to work. It started to work when I made the transitions seperate rather than together.
