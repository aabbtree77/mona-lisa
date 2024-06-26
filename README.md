> Dedicated to my father.

# Introduction

This is my Mona Lisa, build in Lithuania around 1992 I believe, could have been still the USSR of late 1980s. I was around 14, building a digital clock, guided by my father.

<table>
<tr>
<th style="text-align:center"> My Mona Lisa: A Digital Clock based on the Soviet K155 series microchips</th>
</tr>
<tr>
<td>
<img src="./images/mona-main.jpg"  alt="My Mona Lisa: A Digital Clock based on the Soviet K155 series microchips" width="100%" >
</td>
</tr>
</table>

It was based on the Soviet K155-series microchips with gas discharge displays. 

# Historical Context

Personal computers were very rare at the time in Lithuania. I remember my secondary school "information technology" class teaching us how to use [ChiWriter](https://en.wikipedia.org/wiki/ChiWriter) which must have run on [Robotron](https://en.wikipedia.org/wiki/VEB_Robotron), a DOS-compatible East Germany-made personal computer. Computers were optional, most of the lessons went on with paper and pencil about Claude Shannon and Boolean algebra. We did not have access to the design of PCBs with say, P-CAD.

# Circuit Board Printing

The design was completely hand-drawn based on the electric circuit diagram.

The fun part was the printing chemistry. 

We used a single copper (Cu) plated board, the routes were drawn with a nail polish followed by the board immersion into some chemical liquid compound. This was very rough and tedious, needless to say.

At first, we have used ferric chloride (Fe2Cl3) to etch the circuit routes, but our solution was not effective and we would wait for days if not weeks for the irrelevant Cu-parts to disappear from the board's surface. A slight warming or periodic movement would not speed a chemical reaction much. The designs were flawed in that there was so much copper to remove.

I remember taking my own initiative when being alone at home once. After losing patience of watching over a never ending reaction, I decided to pour hydrochloric acid HCl on some metal shavings in a big plastic can used for sardines, to get a "stronger ferric chloride". **Do not do this at home. I nearly lost my lungs there.**

At some point we started using cupric sulfate CuSO4. This was faster, but not by much. Years later I would also see my uncle use cupric sulfate to paint the trunks of the apple trees...

We also resorted to electrolysis. The painted board is immersed into a salted water inside an iron can. I believe the cathode is attached to the can and the anode is immersed into the water in an isolated manner (by sticking it into a hole drilled in a plastic cover on top of the can to avoid a short-circuit). This would remove copper so rapidly, but the nail polish would not protect the routes well. The printed routes were never of high quality.

# ACDC

At the time it was common to build voltage transformers manually. We had a lot of varnished copper wire of old circuit relays floating around. The formula was surprisingly simple: 

The number of windings to get one volt  = 50/S, where S was an effective area of a ferrite core entering the transformer's casing, in squared centimeters.

This would work for a vast range of transformer and wire sizes. Consider an exercise to derive this formula from Maxwell's equations...

The process of hand rolling a transformer was an exercise of patience as thousands of windings were needed and a ferrite core consisted of many sheets that had to be assembled one by one. I remember placing some markings on paper in order not to get lost at counting. I remember getting so tired from this that once I even confused primary with secondary windings when connecting the transformer to the voltage source. Puff, and the whole evening's work was gone. 

This knowledge was insufficient for small transformers. A small transformer size would demand a very thin copper wire due to size limitations, and often the electric current would come out too weak to drive, say, a neighbour's portable cassette Sony player.

# Photos

<table>
<tr>
<th style="text-align:center"> My Mona Lisa: Inside the Box</th>
</tr>
<tr>
<td>
<img src="./images/mona-open.jpg"  alt="My Mona Lisa: My Mona Lisa: Inside the Box" width="100%" >
</td>
</tr>
</table>

<table>
<tr>
<th style="text-align:center"> My Mona Lisa: Circuit Board Top</th>
</tr>
<tr>
<td>
<img src="./images/mona-board-top.jpg"  alt="My Mona Lisa: Top of Circuit Board" width="100%" >
</td>
</tr>
</table>

<table>
<tr>
<th style="text-align:center"> My Mona Lisa: Circuit Board Bottom</th>
</tr>
<tr>
<td>
<img src="./images/mona-board-bottom.jpg"  alt="My Mona Lisa: Bottom of Circuit Board" width="100%" >
</td>
</tr>
</table>

<table>
<tr>
<th style="text-align:center"> My Mona Lisa: Voltage Transformer</th>
</tr>
<tr>
<td>
<img src="./images/mona-transformer.jpg"  alt="My Mona Lisa: Voltage Transformer" width="100%" >
</td>
</tr>
</table>

<table>
<tr>
<th style="text-align:center"> My Mona Lisa: Gas Discharge Displays</th>
</tr>
<tr>
<td>
<img src="./images/mona-indicators.jpg"  alt="My Mona Lisa: Gas Discharge Displays" width="100%" >
</td>
</tr>
</table>

# PS

30 years later I would come back to electrical engineering by fixing a [factory machine](https://github.com/aabbtree77/adast) with my uncle.

My father is still an avid electronics amateur who collects and sells old military radios.
