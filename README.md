# Top Secret
**Author:** quizjack 
**Category:** OSINT 
**Difficulty:** easy

## Description

>When gathering informations, sometimes we need several sources to get the answers we need. Not all informations come from our first search and we might have to gather information from different sources to achieve our goals. To get this flag, start from one picture and try to answer all questions. The initials of each answer, will give you your flag.

>1- Where did this aircraft became famous?
>2- What is the scientific family to which the animal that made this aircraft famous belongs?
>3- Who was the founder of the place where this plane now rests? 

## Solve

This is just a simple OSINT we several steps.

For the first question, if reverse search don't work, registry number can be used. In this case "N106US".

[![N106US](https://github.com/gcsuaveiro/citeforma-ctf/blob/master/osint/aircraft/solve/1-%20Famous.jpg)]

From there we can see that was the aircraft that ditched the Hudson river. And that is our first answer, "H".

For the second question, we need to read wikipedia article for [US Airways Flight 1549](https://en.wikipedia.org/wiki/US_Airways_Flight_1549) and get the first part of our info.

[![Bird Strike](https://github.com/gcsuaveiro/citeforma-ctf/blob/master/osint/aircraft/solve/1-%20Famous.jpg)] CORRECT THE LINK

And now we can find the scientific family with a simple Google search.

[![Goose](https://github.com/gcsuaveiro/citeforma-ctf/blob/master/osint/aircraft/solve/1-%20Famous.jpg)] CORRECT LINK

We get that Canadian Geese belong to "Anatidae" family and an "A" for our flag.

To our third question, we go back to [US Airways Flight 1549](https://en.wikipedia.org/wiki/US_Airways_Flight_1549) and find the first step, which is [Carolinas Aviation Museum](https://www.sullenbergeraviation.org/about-us/). And there we get the final clue "FSW" from [![Fouders](https://github.com/gcsuaveiro/citeforma-ctf/blob/master/osint/aircraft/solve/1-%20Famous.jpg)] CORRECT LINK

## Flag 
```
CTFUA{H_A_FSW}
```
