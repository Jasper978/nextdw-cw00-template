# ClassWork 00 For NeXT CS
### Class Period:
### Name0:  Jasper Li
### Name1: Zhixuan Yang (Lucy)
---

In this repository you will find a processing program called lightningTimed.pde. It includes new processing features we have not yet discussed. Your mission is to join your TableBuddy™ and understand the code by filling out this document, reading the questions and filling in the prompts when asked.

### Task 0
* Read the entire program (do not run it yet), make note of anything you have not seen or used before in class. 
* Copy and paste any line of code containing a new function/vairable, langauge feature below. (you may have seen these outside of class if you've done extra research into processing, if that is the case, still include them here).

void draw()
frameCount
frameRate()


---

### Task 1
* Run the program, describe, in your own words, in at most 2 sentences, generally what it does.

Strikes lightning constantly and indefinately 
---

### Task 2
Now that you have read & run the program, answer the following specific questions about the code. Use your own words, do not look these up in the processing reference manual. You may want to alter the program slightly to test things.
1. What is the purpose of the `draw` method?
It draws the lightning and it takes into account the code beneath it. (unike void setup)
3. What does the `frameRate` method do?
Speed of llightning stikes (how fast draw operates)
5. What does the `frameCount` variable represent?
Total number of frames that the program experienced so far.
6. What is the puprpose of this piece of code `frameCount % 30 == 0`?
Boolean; if it equals 0 it gives the value of true.

---

### Task 3
Modify the code so that only 1 lightning bolt can be seen at a time. Specifically, just the new lightning bolt that has been drawn. This can be done by adding a single line of code. What line of code did you add?

We added the background command so it covers up the old lightning.

---

### Task 4
Modify the code so that 5 frames before a lightning bolt is drawn, the entire screen turns white. (i.e. black screen, white screen, lightning bolt on black screen, repeat...). This will require at least 2 lines of code. What lines of code did you add?

```


```
