<br>__PROJECT:__ IEABOX 
<br>__PROGRAM:__ TURING FE
<br>__TERM:__ MODULAR 1a
<br>__DATE:__ 04/12/2020
<br>__TEAM:__ PAIRED
<br>__MEMBERS:__ CORBIN MARCH  

## 1. PROJECT OVERVIEW
- just one partner and I Corbin March, went well, we were able to get through iteration 4
- Everything done REMOTELY
- given a set of guidelines for each iteration but we built the html css, and Javascript from scratch.  
- Objective: Incorporation of the Data Model as the source of all information, saving and retrieving from local storage, updating the dom and introduction to the filter method are what stand out to me 
- Instructions for the website: we were given statements through the eyes of a user.  We were told what the user would see, or do, and we were expected to create the website's responses accordingly.

## 2. OVERALL
- I will fufill whatever role needs to be filed. 
I can be the peacekeeper, or the leader, but no metter which role, I take pride in consistently fufilling the role as the reliable and competant teammate that other teammates can count on.
- I believe everyone can make a meaningful impact if their strengths are utilized.  

## 3. TECHNICAL CHALLENGE

- Biggest challenge: 
    - Filtering and Targeting specific key value pairs of an array of instantiated objects.
    - We did not initially include the star or id in our parameters when we created the ideaCard class because our star value was a boolean and the id was ustilizing the Date.now() method.  
    - We rely on the id's value because it was how we indexed our Array but when we tried to utitilize it, the Date.now() method would return us the current value.  
    - Corbin March's 'rock' came to our rescue and helped us troubleshoot our code.  With his help we were able to target the issue and once we added 'id' as a perameter in our constructor method, everything began to fall into place. (see below):
    
          - BEFORE:   this.id = Date.now()       - AFTER:   this.id = id || Date.now()  


## 4. REFLECTION:
- Personal takeaway: 
    - Don't make things more complicated than they need to be.  Some times the simplist way works.
    - Say what you're thinking out loud, I might not have a full idea, but others can build upon your ideas and real solutions and/or methods can emerge from the fragments of thoughts
    - Continue to work on the small things, like typing skills and keyboard shortcuts
- Technical takeaway:
    - ASK FOR HELP!
    - Walk away from a problelm, the answer might come when you least expect it.  
- Focus for next project:
    - Do only one task ata time, if you try to do too many different tasks at once, it becomes really hard to build organized, readible code, and trouble shooting becomes very difficult as well.
    - Have a plan before you start to build the code.  Do a little research and figure out the most efficient method using the skills or knowlege I have aquired instead of trying to learn things I have never tried or studied before.