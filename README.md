# BRACHINSKI // MANUAL

The manual for BRACHINSKI, a browser-based drum synth and sequencer by Snad Industries.

**Read it:** https://snadbreugen.github.io/brachinski-manual/
**Use the machine:** https://snadbreugen.github.io/Brachinski/

## What is in here

One file, `index.html`. The screenshots are embedded in it, so there is nothing to place beside it and nothing to break when the file is moved.

Six pages:

| Page | Shows |
|---|---|
| Map | Where a sound comes from and where it ends up |
| A kit and a beat | The state you land in |
| Adding a master effect | The master chain, open |
| The rack, filled | Your own kit with groups and the slot menu |
| Editing a voice | A slot opened up |
| Live mode | The performance screen |

Every page reads two ways. Wide enough, and it is a plate: picture in the middle, a marker on the part, a line out to the description. Narrower, the markers turn into numbers and the descriptions become a numbered key under the picture.

## Keeping it current

The screenshots are from a numbered revision of the machine, printed in the footer of every page. When the machine changes in a way you can see, the shots are replaced and that number moves with them.

Annotations live in the `VIEWS` list near the top of the script. Each one is a point on the picture in percent, a heading and a line of text:

```js
{x:36.0, y:15.7, s:"R", k:"Copy", t:"Drops the set you are on into the rack."}
```

`x` and `y` are percentages, so they survive any window size. `s` forces the description onto the left or right margin; leave it out and it follows the point.

To find a point, open the page and press **s**. The pointer turns into a crosshair, and every click on a picture writes a ready-made line into the box at the bottom. Escape closes it again.

## Licence

Snad Industries. Ask before reusing.
