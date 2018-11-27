---
layout: default
title: "CS411: Non-Standard Computing"
course_description: "An exploration of several prominent 'unconventional' computational methods and theories, including quantum computation, DNA and molecular computation, genetic algorithms, and cellular automata."
next: ../Unit06
previous: ../Unit04
---
**Unit 5: The Theory of Quantum Computation: An Introduction** <span
id="5"></span> 
*In this unit, we start with the review of basic logic elements.  Then,
we will study quantum notation and how arbitrary logic gates may be
constructed for quantum bits. Next, we show a description of a simple
model for a quantum computer based on a classical computer.  The second
part of this unit consists of video lectures by David Deutsch.  These
lectures cover an introduction to quantum theory, the quantum theory of
computation, physical systems, and the simplest quantum physical
system.  Also, in the lectures you can see a single-photon interference
experiment and learn how to analyze pairs of interacting quantum
systems.  Other topics include the Schroedinger picture, density
matrices, state vectors, pure states, the Schroedinger equation, and the
Deutsch algorithm.*

**Unit 5 Time Advisory**  
This unit will take approximately 37 hours to complete.

☐    Subunit 5.1: 18 hours

☐    Subunit 5.1.1: 2 hours  
  
 ☐    Subunit 5.1.2: 2 hours  
  
 ☐    Subunit 5.1.3: 2 hours  
  
 ☐    Subunit 5.1.4: 2 hours  
  
 ☐    Subunit 5.1.5: 2 hours  
  
 ☐    Subunit 5.1.6: 2 hours  
  
 ☐    Subunit 5.1.7: 2 hours  
  
 ☐    Subunit 5.1.8: 2 hours  
  
 ☐    Subunit 5.1.9: 2 hours

☐    Subunit 5.2: 18 hours

☐    Subunit 5.2.1: 3 hours  
  
 ☐    Subunit 5.2.2: 3 hours  
  
 ☐    Subunit 5.2.3: 3 hours  
  
 ☐    Subunit 5.2.4: 3 hours  
  
 ☐    Subunit 5.2.5: 3 hours  
  
 ☐    Subunit 5.2.6: 3 hours

☐    Unit 5 Assessment: 1 hour

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:

-   Explain how reversible computation works.
-   Describe conceptually FANOUT and ERASE gates.
-   Define the elementary quantum notation.
-   Describe how arbitrary logic gates may be constructed for quantum
    bits.
-   Describe a simple model for a quantum computer based on a classical
    computer.
-   Describe an algorithm which makes use of the quantum parallelism.
-   Conceptually describe the simplest quantum physical system, the
    qubit.
-   Describe a single-photon interference experiment.
-   Explain the Schroedinger equation.
-   Explain the workings of the Deutsch algorithm and Grover’s search
    algorithm.

**5.1 Quantum Computation** <span id="5.1"></span> 
-   **Reading: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “Quantum Computation: a Tutorial”**
    Link: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “[Quantum Computation: a
    Tutorial](https://resources.saylor.org/archived/wp-content/uploads/2011/06/CS411-5.1-1.pdf)”
    (HTML or PDF)  
        
     Instructions: From the site, click on the link for “Quantum
    computation tutorial” to open the HTML version.  You may also access
    the PDF version of this resource from this website.  Read the
    webpage about a survey made by Keyes in 1988 and reversible
    computation.  Then, review the basic logic elements and FANOUT and
    ERASE gates.  This reading covers subunits 5.1.1 through 5.1.4.  
        
     <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Terms
    of Use: The linked material above has been reposted by the kind
    permission of </span> <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Samuel
    L. Braunstein, and can be viewed in its original from
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/comp.html).</span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span>  </span></span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Please
    note that this material is under copyright and cannot be reproduced
    in any capacity without explicit permission from the copyright
    holder.</span><span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span> </span></span>

**5.1.1 Computing at the Atomic Scale** <span id="5.1.1"></span> 
**5.1.2 Reversible Computation** <span id="5.1.2"></span> 
**5.1.3 Classical Universal Machines and Logic Gates** <span
id="5.1.3"></span> 
**5.1.4 FANOUT and ERASE** <span id="5.1.4"></span> 
**5.1.5 Computation without ERASE** <span id="5.1.5"></span> 
-   **Reading: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “Computation without ERASE”**
    Link: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “[Computation without
    ERASE](https://resources.saylor.org/archived/wp-content/uploads/2011/06/CS411-5.1.5.pdf)”
    (HTML or PDF)  
        
     Instructions: From the site, click on the link for “Quantum
    computation tutorial” to open the HTML version and scroll down to
    access the above listed section.  You may also access the PDF
    version of this resource from this website.  Read the material from
    the webpage to see why primitive ERASE is not absolutely essential
    in computation.  
        
     <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Terms
    of Use: The linked material above has been reposted by the kind
    permission of </span> <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Samuel
    L. Braunstein, and can be viewed in its original from
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/node5.html#SECTION00050000000000000000).</span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span>  </span></span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Please
    note that this material is under copyright and cannot be reproduced
    in any capacity without explicit permission from the copyright
    holder.</span><span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span> </span></span>

**5.1.6 Quantum Notation and Logic Gates for Quantum Bits** <span
id="5.1.6"></span> 
-   **Reading: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “Elementary Quantum Notation” and “Logic
    Gates for Quantum Bits”**
    Link: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's [“Elementary Quantum Notation” and “Logic
    Gates for Quantum
    Bits”](https://resources.saylor.org/archived/wp-content/uploads/2011/06/CS411-5.1.6.pdf)
    (HTML or PDF)  
        
     Instructions: From the site, click on the link for “Quantum
    computation tutorial” to open the HTML version and scroll down to
    access the above listed sections.  You may also access the PDF
    version of this resource from this website.  Read the material on
    the webpage to learn about quantum notation and how arbitrary logic
    gates may be constructed for quantum bits.  
        
     <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Terms
    of Use: The linked material above has been reposted by the kind
    permission of </span> <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Samuel
    L. Braunstein, and can be viewed in its original from
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/node6.html) and
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/node7.html).</span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span>  </span></span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Please
    note that this material is under copyright and cannot be reproduced
    in any capacity without explicit permission from the copyright
    holder.</span><span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span> </span></span>

**5.1.7 Model Quantum Computer and Quantum Code** <span
id="5.1.7"></span> 
-   **Reading: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “Model Quantum Computer and Quantum Code”**
    Link: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “[Model Quantum Computer and Quantum
    Code](https://resources.saylor.org/archived/wp-content/uploads/2011/06/CS411-5.1.7.pdf)”
    (HTML or PDF)  
        
     Instructions: From the site, click on the link for “Quantum
    computation tutorial” to open the HTML version and scroll down to
    access the above listed section.  You may also access the PDF
    version of this resource from this website.  Read the webpage for a
    description of a simple model of a quantum computer based on a
    classical computer instructing a machine to manipulate a set of
    spins.  
        
     <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Terms
    of Use: The linked material above has been reposted by the kind
    permission of </span> <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Samuel
    L. Braunstein, and can be viewed in its original from
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/node8.html).</span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span>  </span></span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Please
    note that this material is under copyright and cannot be reproduced
    in any capacity without explicit permission from the copyright
    holder.</span><span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span> </span></span>

**5.1.8 Quantum parallelism: Period of a Sequence** <span
id="5.1.8"></span> 
-   **Reading: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “Quantum Parallelism: Period of a Sequence”**
    Link: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “[Quantum Parallelism: Period of a
    Sequence](https://resources.saylor.org/archived/wp-content/uploads/2011/06/CS411-5.1.8.pdf)”
    (HTML or PDF)  
        
     Instructions: From the site, click on the link for “Quantum
    computation tutorial” to open the HTML version and scroll down to
    access the above listed section.  You may also access the PDF
    version of this resource from this website.  Read the webpage for a
    description of an algorithm which makes use of the quantum
    parallelism.  
        
     <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Terms
    of Use: The linked material above has been reposted by the kind
    permission of </span> <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Samuel
    L. Braunstein, and can be viewed in its original from
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/node9.html).</span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span>  </span></span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Please
    note that this material is under copyright and cannot be reproduced
    in any capacity without explicit permission from the copyright
    holder.</span><span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span> </span></span>

**5.1.9 Factoring Numbers and Prospects** <span id="5.1.9"></span> 
-   **Reading: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's “Factoring Numbers” and “Prospects”**
    Link: The University of York’s Department of Computer Science:
    Samuel L. Braunstein's [“Factoring Numbers” and
    “Prospects”](https://resources.saylor.org/archived/wp-content/uploads/2011/06/CS411-5.1.9.pdf)
    (HTML or PDF)  
        
     Instructions: From the site, click on the link for “Quantum
    computation tutorial” to open the HTML version and scroll down to
    access the above listed sections.  You may also access the PDF
    version of this resource from this website.  Read the two webpages
    to see an example of factoring a number and to learn about the
    prospects for quantum computation.  
        
     <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Terms
    of Use: The linked material above has been reposted by the kind
    permission of </span> <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Samuel
    L. Braunstein, and can be viewed in its original from
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/node10.html) and
    [here](http://www-users.cs.york.ac.uk/schmuel/comp/node11.html).</span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span>  </span></span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">Please
    note that this material is under copyright and cannot be reproduced
    in any capacity without explicit permission from the copyright
    holder.</span><span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span> </span></span>

**5.2 Lectures on Quantum Computation** <span id="5.2"></span> 
**5.2.1 The Qubit** <span id="5.2.1"></span> 
-   **Lecture: Hewlett-Packard: David Deutsch’s Lectures on Quantum
    Computation: "Lecture 1: The Qubit”**
    Link: Hewlett-Packard: David Deutsch’s *Lectures on Quantum
    Computation:* "[Lecture 1: The
    Qubit](http://www.hpl.hp.com/breweb/quiprocone/Protected/Lecture1.htm)"
    (Windows Media Player)  
        
     Instructions: Click on the hyperlink titled “Click to Launch
    Lecture 1” to download the video.  Watch this video lecture about
    the introduction to quantum theory, the quantum theory of
    computation, physical systems, observations, and the simplest
    quantum physical system, the qubit.  Repeat watching the sections of
    the video that are hard to follow.  When necessary, pause the video
    to take the notes.  This should take approximately 3 hours of study
    time.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the web page above.

**5.2.2 Interference** <span id="5.2.2"></span> 
-   **Lecture: Hewlett-Packard: David Deutsch’s "Lecture 2:
    Interference”**
    Link: Hewlett-Packard: David Deutsch’s "[Lecture 2:
    Interference](http://www.hpl.hp.com/breweb/quiprocone/Protected/Lecture_2.htm)"
    (Windows Media Player)  
        
     Instructions: Select the “click on to launch” hyperlink to download
    the video.  Watch this video to see a single-photon interference
    experiment.  Repeat watching the sections of the video that are hard
    to follow.  When necessary, pause the video to take the notes.  This
    should about take 2 hours of study time.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.3 Measurement** <span id="5.2.3"></span> 
-   **Lecture: Hewlett-Packard: David Deutsch’s "Lecture 3:
    Measurement”**
    Link: Hewlett-Packard: David Deutsch’s "[Lecture 3:
    Measurement](http://www.hpl.hp.com/breweb/quiprocone/Protected/Lecture_3.htm)"
    (Windows Media Player)  
        
     Instructions: Select the “click on to launch” hyperlink to download
    the video.  Watch this video to learn how to analyze pairs of
    interacting quantum systems.  You may benefit from viewing certain
    sections of this video more than once; repeat watching the sections
    of the video that are hard to follow.  It may also be useful to take
    the notes as you watch the video.  This should take approximately 2
    hours of study time.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.4 The Schroedinger Picture** <span id="5.2.4"></span> 
-   **Lecture: Hewlett-Packard: David Deutsch’s "Lecture 4: The
    Schroedinger Picture”**
    Link: Hewlett-Packard: David Deutsch’s "[Lecture 4: The Schroedinger
    Picture](http://www.hpl.hp.com/breweb/quiprocone/Protected/Lecture_4.htm)"
    (Windows Media Player)  
        
     Instructions: Select the “click on to launch” hyperlink to download
    the video.  Watch this video about the Schroedinger picture, density
    matrices, state vectors, pure states, and the Schroedinger
    equation.  This video may require multiple viewings.  Repeat
    watching the sections of the video that are hard to follow.  Also,
    pause the video, when necessary, to take the notes.  This should
    take about 2 hours of study time.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.5 A Quantum Algorithm** <span id="5.2.5"></span> 
-   **Lecture: Hewlett-Packard: David Deutsch’s "Lecture 5: A Quantum
    Algorithm”**
    Link:Hewlett-Packard: David Deutsch’s "[Lecture 5: A Quantum
    Algorithm"](http://www.hpl.hp.com/breweb/quiprocone/Protected/Lecture_5.htm)
    (Windows Media Player)  
        
     Instructions: Select the “click on to launch” hyperlink to download
    the video.  Watch this video to learn about the Deutsch algorithm. 
    This video may require multiple viewings.  You may benefit from
    reviewing sections of this video multiple times; repeat watching any
    sections of the video that are hard to follow.  When necessary,
    pause the video to take the notes.  This should take approximately 2
    hours of study time.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.6 Grover's Search Algorithm** <span id="5.2.6"></span> 
-   **Lecture: Hewlett-Packard: David Deutsch’s "Grover's Search
    Algorithm”**
    Link: Hewlett-Packard: David Deutsch’s "[Lecture 6: Grover's Search
    Algorithm](http://www.hpl.hp.com/breweb/quiprocone/Protected/Lecture_6.htm)"
    (Windows Media Player)  
        
     Instructions: Select the “click on to launch” hyperlink to download
    the video.  Watch this video to learn how to use quantum computation
    to search through N possibilities in a time proportional to the
    square root of N.  You may benefit from viewing this video more than
    once.  Repeat watching the sections of the video that are hard to
    follow.  When necessary, pause the video to take the notes.  This
    should take about 2 hours of study time.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: The Saylor Foundation's "CS411: Unit 5 Quiz"**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)


