# Pensheen Steno Technical Specification v0.4.5

## Overview 

A *stroke* is a figure consisting of multiple *key lines* connected to each other in steno order, each representing a steno key or combination of keys, with defined dimensions. Each stroke may have one or more *consonants* and exactly one *vowel* or *null line*, although a trailing null may be omitted, as may null between consonants in certain situations. Multiple strokes defined as one translation make an *outline*.

(The concept of center lines and outer lines from earlier versions are no longer used.)

All lines must be drawn as to not be confused with similar lines, except when that other line would be impossible in that context.

Each key line is defined in terms of *units*, or U for short. 1U is arbitrarily defined as the vertical length between ruled lines. If your paper's ruled lines are too close together, you may define it as the distance between two ruled lines, or any other length, but you *must* be consistent.

When determining the height and width of a line, compare their start and end points relative to each other. If those points are aligned and would result in a height or width of 0, compare the outermost part of that line to the start and end points instead. 

## Vowels

The vowels are drawn left to right and, with the exception of three blends, are all based on a looping circle shape; all such circles are of equal height and width. The horizontal or vertical lines leading into and out of them, the leaders, only matter in their orientation. Their default lengths of 0.5U are not critical; they may be made shorter or longer as spacing requires. Small vowels are 0.5U in diameter and large vowels are 1U in diameter.

The basic vowels have horizontal leaders. Of them, the outer vowels, those farthest from the asterisk, are small, and the inner vowels are large. The left vowels are drawn above the leaders and the right vowels below.

Blends of two vowels on the same side are made with a sharp V-shape without leaders by default, 1U tall and 0.5U wide, with the left vowels pointing up and the right vowels pointing down.

Blends of two vowels of opposite sides are similar to the basic vowels, but instead of looping above or below the leaders, it intersects them, appearing to bisect the circle. The left vowel determines the diameter of the circle, which is the same size as its corresponding basic vowel. The right vowel determines the orientation of the leaders; if the corresponding basic vowel is the same size as the left vowel, the blend is horizontal, and if a different size, vertical. These vertical vowel blends may be drawn upwards or downwards as spacing may require.

Blends of three vowels take the same shape as the basic vowel on the opposite side from the other two, but lead out with a vertical line.

The blend of all four vowels is a combination of the same-side two-vowel blends in a characteristic EKG shape, with the lead-in line sharply curving straight up, then down the same amount past the leader, and then sharply curving up again into the lead-out line. The vertical line made this way is 1U tall and of negligible width. 

## Null

The null line, or simply null, represents the absence of a vowel. It serves a similar purpose in distinguishing left and right consonants.

The null is a horizonal line 1.5U long, but can be extended as spacing may require.

A stroke cannot have both a vowel and a null.

A trailing null may be omitted. It may also be omitted between consonants if steno order provides only one reading of the stroke, for example TPH-T. If in doubt, null it out.

## Consonants

The mappings of left and right hand consonants are identical. There is no reflective symmetry. Left and right hand consonants may not touch, as they are distinguished by their position before or after the stroke's vowel or null. If neither is present, all are left consonants.

Basic consonants represent only one key. Blends represent a combination of keys.

All basic consonants are based on an ellipse and drawn left to right. Top row keys are drawn upwards, and bottom row keys are drawn downwards. From left to right, the first two keys in a row are drawn vertically and then horizontally ("outwards"); the next two keys are drawn horizontally and then vertically ("inwards"). Short lines are 0.5U tall and 1U wide; long lines are 1U tall and 2U wide. The outer keys, SHR-FRTS, are short lines and the inner keys, TKPW-PBLG, are long lines. -DZ are an exception and are drawn the same as -TS, but with the addition of a short hook towards their origin. 

The blends combining two horizontally adjacent keys are, from left to right, a straight diagonal line 1U tall and wide, another 2U tall and wide, and a U-shape with almost straight lines and rounded corners. The three horizontally adjacent keys to the right of the first one are blended with a similar stroke 1U tall and 2U wide. All four keys (not including -DZ) are blended with a teardrop shape drawn away from the asterisk 0.5U tall and 1U wide. This is an exception to the lack of reflective symmetry.

The blends combining two vertically adjacent keys are curves 0.5U wide with their start and end points vertically aligned, which are drawn downwards by default but may be drawn upwards if another shape blocks it. From left to right, the first and the second curve left and are respectively 1U and 2U tall, and the third and fourth curve right and are respectively 2U and 1U tall. -TS and -DZ are exceptions that are drawn upwards by default and are 1U tall and 1U wide. -DZ is distinguished from -TS with the addition of a short hook towards their origin.

The final type of consonant blend combines four keys that are horizontally and vertically adjacent. They are teardrop shapes drawn downward. From left to right, the first is 1U tall and 0.5U wide, the second is 2U tall and 1U wide, and the third is 1.5U tall and less than 0.5U wide. The shape for -TSDZ is 0.5U tall and 1.5U wide.

## Asterisk

The asterisk may be added to a stroke by drawing a short perpendicular mark through the consonant whose sound it would change, or if there's no such part, next to the vowel or through the center of the null. The asterisk mark cannot be made through a vowel except for its leaders.

## Other marks

The number bar may be added to a stroke with a horizonal line of the same length above it.

The + key used in some theories may be added to a stroke with a horizontal line of the same length below it.

Strike through mistakes, or if that would be awkward, circle them.

Numbers may be written out in Arabic numerals such that they cannot be mistaken for strokes.

Gregg punctuation and capitalization may be used when it cannot be mistaken for a stroke.

