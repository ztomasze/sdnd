---
aliases:
  - range
  - distances
---

Distances, weapon ranges, speeds, and areas of effect are given in 5-foot increments. 

### gridded

This is best mapped to a square grid of 5' squares. A Small or Medium creatures each occupies 1 square in combat.

When measuring movement distance on the grid, each square counts as 5' of distance, whether moving laterally or diagonally. Figures can move diagonally around trees and other figures but not around wall corners or other objects that completely fill their space (square).

### fuzzy edges

##### movement ranges
If a creature wants to move 5 or 10 feet farther than their speed would normally allow over level ground, they can make an Easy or Normal DEX(Athletics) [[check]], respectively, as part of their move to do so. This is not without some risk, though. A CF on the check means they stumble (gain a bane) on an Easy check or trip and fall prone partway there on a Normal check. 

##### weapon ranges
Similarly, you can throw or shoot a ranged [[weapons|weapon]] beyond its normal range at +1 to the AC of the target for each 5' beyond the normal range.  (If this is more than 10 or 15 feet, then it's better to accept the disadvantage of a second range increment.)

> **Design: Fuzzy edges**  
> The advantage of using a grid is that it allows players to determine for themselves what their character can see, run to, or shoot this round. However, this certainty can lead to a more plodding combat of positioning or the frustration of being just one square short of landing an epic attack.
> 
> The goal is instead to have battles feel fast, chaotic, and dramatic, rather than like a carefully planned chess match. As a character in the heat of battle, you shouldn't know *exactly* how far that orc can sprint in the next few seconds or just how hard he can pull back his bow.

### gridless

If the GM would like to forgo the grid for a given combat or in general, it is possible to adjudicate all distances primarily in terms of **adjacent**, **near**, or **far**.  Some intermediate distance categories are often useful for particular effects or situations:

| Distance     | Abbr. | Approx.    | Description / Uses                                                                                                          | Conversion range |
| ------------ | ----- | ---------- | --------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| personal     | P     | 0' - 1'    | In your space and typically in full contact; wrestling or hugging distance.                                                 | < 3'             |
| **adjacent** | A     | 5'         | Close enough to reach out and touch.  Melee attack range; touch spell; candlelight.                                         | 5'               |
| close        | C     | 10' to 15' | How far you can move in one action over difficult terrain; candlelight + dimsight. "Half near"                              | 10' or 15'       |
| **near**     | N     | 30'        | How far you can usually move with one action; range of most thrown weapons; torchlight                                      | 20' to 40'       |
| midrange     | M     | 60'        | Farthest you can move in a turn if you dash; lantern light or torch + dimsight. "Double near"                               | 50' to 80'       |
| **far**      | F     | 120'+      | How far you can shoot a ranged weapon; lantern light + dimsight; typically the full extent of vision underground or indoors | 100' to 200'     |
| distant      | D     | *          | Still in range of artillery, arching army bow shots, etc.                                                                   |                  |
| sight        | S     | *          | Beyond weapon range but still visible when outdoors.                                                                        |                  |
When converting from other sources, 45' and 90' can be rounded up or down based on the context (up by default).
##### areas

Gridless sizes are typically stated with a "-radius" postfix, such as "a near-radius area".

| Size                     | Defintion                                                                                            | <div style="width: 5em;">Radius</div> | <div style="width: 5em;">Diameter</div> |
| ------------------------ | ---------------------------------------------------------------------------------------------------- | ------------------------------------- | --------------------------------------- |
| **personal** / **space** | The **space** occupied or controlled by a typical medium-sized creature with their arms outstretched | (personal)<br>(< 5')                  | (adjacent)<br>(5')                      |
| **adjacent**             | A creature's **space +** everything **adjacent** to it                                               | adjacent<br>(5')                      | close<br>(15')                          |
| **close**                | A creature's **space +** everything **close** to it                                                  | close<br>(15')                        | near<br>(35')                           |
| **near**                 | A creature's **space +** everything **near** to it                                                   | near<br>(30')                         | midrange<br>(65')                       |
| **medium**               | A creature's **space +** everything **midrange** of it                                               | midrange<br>(60')                     | far<br>(125')                           |
| **far**                  | A creature's space + everything **far** from it                                                      | far<br>(120')                         | distant<br>(245')                       |

> **Design: Descriptor-based distance categories**  
> Early editions of SD&D favored a gridless approach and used only these descriptors for all distances, ranges, areas, and speeds. While the goal was simplicity, several practical complexities arose. For example:
> 
> - New players have to learn the new distance vocabulary.  
> - Areas were somewhat convoluted to specify, such as an close-radius burst, which has a near diameter  
> - Some monsters move faster or slower than a standard near-distance speed. Speeds specified as close, near, or midrange felt odd, but it didn’t feel much simpler to add another set of descriptors for each speed that then needed to be mentally mapped to the distance descriptors.  
> - In certain cases, any conversion from other sources loses nuance. For example, in some editions of the source game, zombies move at 20’ per move while most characters move at 30’. While it is fine to translate both of these to a near-distance move in most cases, it would be nice to track that zombies are still slower overall. This would be relevant in a chase or perhaps in a Dash situation where a zombie would still only cover a near distance (and so effectively can’t double Move in a turn). While speeds could be broken down into substeps, such as near-, near, and near+, this strays ever further from simplicity.  
> - SD&D aims to support on-the-fly conversion from different editions of the source game. This conversion is often simpler to convert to feet, especially when it comes to spell area effects, as they are already described in those terms in most sources.  
> 
 > In conclusion, support for gridless distance descriptors remains a design goal. SD&D's numerical distances all correspond to one of the descriptor categories. However, for greater clarity and support for other styles of play, those distances are stated using numerical distances. 
