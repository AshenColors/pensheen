# Pensheen Steno Technical Specification v0.4.3

## Basics

A *stroke* is a figure consisting of multiple *key lines*, each representing a steno key or combination of keys, with defined dimensions. Multiple strokes defined as one translation make an *outline*.

The concept of center lines and outer lines from earlier versions are no longer used.

Each key line is defined in terms of *units*, or U for short. 1U is the vertical distance between ruled lines. If your paper's ruled lines are too close together, you may define it as the distance between two ruled lines, but you must be consistent.

When determining the height and width of a line, compare their start and end points relative to each other. If those points don't differ vertically, compare the outermost part of that line to the start and end points instead. 

## Consonants

The mapping of left and right hand consonants is identical. There is no reflective symmetry. Basic consonants represent only one key. Blends represent a combination of keys.

All basic consonants are based on an ellipse and drawn left to right. Top row keys are drawn upwards, and bottom row keys are drawn downwards. From left to right, the first two keys in a row are drawn vertically and then horizontally; the next two keys are drawn horizontally and then vertically. Short lines are 1/2U tall and 1U wide; long lines are 1U tall and 2U wide. The outer keys, SHR-FRTS, are short lines and the inner keys, TKPW-PBLG, are long lines. -DZ are an exception and are drawn the same as -TS, but with the addition of a short hook towards their origin. 

The blends combining two horizontally adjacent keys are, from left to right, a straight diagonal line half a U tall and wide, another 1U tall and wide, and a U-shape with almost straight lines and rounded corners. The three horizontally adjacent keys to the right of the first one are blended with a similar stroke 1U tall and 2U wide. All four keys (not including -DZ) are blended with a teardrop shape drawn away from the asterisk 1/2U tall and 1U wide. This is an exception to the lack of reflective symmetry.

The blends combining two vertically  adjacent keys are curves 1/2U wide with their start and end points vertically aligned, which are drawn downwards by default but may be drawn upwards if another shape blocks it. From left to right, the first and the second curve left and are respectively 1.5U and 2.5U tall, and the third and fourth curve right and are respectively 2.5U and 1.5U tall. -TS and -DZ are exceptions that are drawn upwards by default and are 1.5U tall and wide. -DZ is distinguished from -TS with the addition of a short hook towards their origin.

The final type of consonant blend combines four keys that are horizontally and vertically adjacent. They are teardrop shapes drawn downward. From left to right, the first is 1U tall and wide, the second is 2U tall and 1U wide, and the third is 1.5U tall and 0.5U wide. The shape for -TSDZ is 0.5U tall and 1.5U wide.

## Vowels

The vowels are drawn left to right and, with the exception of three blends, are all based on a looping circle shape; all such circles are of equal height and width. The horizontal or vertical lines leading into and out of them, the leaders, only matter in their orientation. Their default lengths of 0.5U are not critical; they may be made shorter or longer as spacing requires. Small vowels are 0.5U in diameter and large vowels are 1U in diameter.

The basic vowels have horizontal leaders. Of them, the  outer vowels, those farthest from the asterisk, are small, and the inner vowels are large. The left vowels are drawn above the leaders and the right vowels below.

Blends of three vowels take the same shape as the vowel on the opposite side from the other two, but lead out with a vertical line.

Blends of two vowels on the same side are made with a sharp V-shape without leaders by default, 1U tall and half a U wide, with the left vowels pointing up and the right vowels pointing down.

The blend of all four vowels is a combination of these is a characteristic EKG shape, with the lead-in line sharply curving straight up, then down the same amount past the leader, and then sharply curving up again into the lead-out line. The vertical line made this way is 1U tall and of negligible width. 

Blends of two vowels of opposite sides are similar to the basic vowels, but instead of looping above or below the leaders, it intersects them, appearing to bisect the circle. The left vowel determines the diameter of the circle, which is the same size as its corresponding basic vowel. The right vowel determines the orientation of the leaders; if the corresponding basic vowel is the same size as the left vowel, the blend is horizontal, and if a different size, vertical. These vertical vowel blends may be drawn upwards or downwards as spacing may require.
