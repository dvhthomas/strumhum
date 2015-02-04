+++
date = "2015-01-24T13:07:15-08:00"
draft = true
title = "Basic Jazz Chords"

+++

## Five chords with two positions each

<div id="gdim7"></div>

Pulled shamelessly from [Justin][1] these are the first ones I need to memorize. They are Major 7th (Maj 7 or &#x25B3;), Minor 7th (Min7 or &ndash;), Dominant 7th (Dom7 or just 7), Minor 7b5 (Minor 7th flat 5, min7b5, -7b5), and Diminished 7 (dim or as &#x25CB;).

### Major 7th

![Gmaj7](/Gmaj7-root6.png)
![Cmaj7](/Cmaj7-root5.png)


### Minor 7th

<div id="gmin7"></div>
![Gmin7](/Gmin7-root6.png)
![Cmin7](/Cmin7-root5.png)

### Dominant 7th

![G7](/G7-root6.png)
![C7](/C7-root5.png)

### Minor 7th flat 5

![min7b5](/Gmin7b5.png)
![Cmin7b5](/Cmin7b5-root5)

[1]: http://www.justinguitar.com/en/JA-001-JazzGuitarChords.php (Justin Guitar)

## Diminished 7


<script type="text/javascript">
    var paper = Raphael(document.getElementById("gdim7"), 200, 200);
    var chord = new ChordBox(paper, 40, 40, 130, 140);
    chord.setChord(
        [[6, "x"], [5,4,2], [4,5,3], [3,3,1], [2,5,4], [1,"x"]],
        1,
        []);
    chord.draw();

    paper = Raphael(document.getElementById("gmin7"), 200, 200);
    chord = new ChordBox(paper, 40, 40, 130, 140);
    chord.setChord(
        [[6, 3, 2], [5, "x"], [4,3,3], [3,3,3], [2,3,3], [1,"x"]],
        1,
        [{from_string: 4, to_string: 2, fret: 3}]);
    chord.draw();
</script>