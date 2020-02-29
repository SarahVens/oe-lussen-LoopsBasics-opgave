# oe-lussen-LoopsBasics-opgave
Basisoefening die alle soorten lussen behandelt.

## Opdracht
Deze applicatie bevat een aantal listboxes. In elke listbox komen een aantal items terecht, maar dat aan de hand van verschillende soorten lussen.
Bekijk hieronder per soort lus wat er moet gebeuren. **De eventhandlers zijn al gekoppeld.**

### while
#### Count to 10
Schrijf in `void BtnWhile_Click` een while-lus die de getallen 1 t.e.m. 10 in `lstWhile` toevoegt.

```
1
2
3
4
...
10
```

#### Even/oneven
Schrijf in `void BtnEven_Click` een while-lus die de getallen 1 t.e.m. 10 in `lstWhile` toevoegt.
Wanneer het getal even is dan voeg je tekst toe aan het getal met de vermelding "(even)".
Bij oneven getallen noteer je "oneven".
```
1 (oneven)
2 (even)
3 (oneven)
4 (even)
...
10 (even)
```

### do ... while
Schrijf in `void BtnDoWhile_Click` een do ... while-lus die de getallen 1 t.e.m. 10 in `lstDoWhile` toevoegt.

```
1
2
3
4
...
10
```

*EXTRA: pas de startwaarde in de while én de do ... while lus aan naar 12. Wat is het verschil?*

### for
#### Villains array
Schrijf in `void BtnForArray_Click` een for-lus die aan `lstFor` de namen van slechterikken toevoegt.
Maak hiervoor eerst een array met als inhoud de top 10 bad guys:
1. Darth Vader
2. The Joker
3. Two-Face
4. Warden Norton
5. Hannibal Lecter
6. Sauron
7. Bane
8. Tyler Durden
9. Agent Smith
10. Gollum

```
Darth Vader
The Joker
Two-Face
Warden Norton
Hannibal Lecter
Sauron
Bane
Tyler Durden
Agent Smith
Gollum
```

#### Villains list
Hergebruik de bovenstaande top 10. Voeg de slechterikken deze keer eerst toe aan een `List` i.p.v. een array.
Schrijf vervolgens een for-lus die de slechterikken in omgekeerde volgorde weergeeft. De lijst mag niet in omgekeerde
volgorde genoteerd worden en je mag enkel een for-lus gebruiken.
Schrijf je code in `void BtnForList_Click` en voeg toe aan `lstFor`.

```
Gollum
Agent Smith
Tyler Durden
Bane
Sauron
Hannibal Lecter
Warden Norton
Two-Face
The Joker
Darth Vader
```

### foreach
Maak een ´List´ met de meest overrated acteurs. Deze zijn:
1. Angelina Jolie
2. Jennifer Lopez
3. Brad Pitt
4. Nathalie Portman
5. Jennifer Aniston
6. Scarlett Johansson
7. Kristen Stewart
8. Adam Sandler
9. Robert Pattinson
10. Ben Affleck

Voeg aan `BtnForEach_Click` een foreach-lus toe die aan `lstForEach` hun namen toevoegt in oplopende volgorde.
Je vermeldt er echter ook hun 'rank' (nummer) bij:

```
1. Angelina Jolie
2. Jennifer Lopez
3. Brad Pitt
4. Nathalie Portman
5. Jennifer Aniston
6. Scarlett Johansson
7. Kristen Stewart
8. Adam Sandler
9. Robert Pattinson
10. Ben Affleck
```

### break
Maak een array in `BtnBreak_Click` met daarin de woorden "I", "want", "to", "break" en "free".
Lus met een for-lus door je array, maar onderbreek het lussen zodra je het woord "break" tegenkomt.
Voeg toe aan `lstBreak`.

```
I
want
to
```

### continue
Voeg aan `BtnContinue_Click` de onderstaande `List` toe (copy paste deze code!). Lus vervolgens door de zinnen van het nummer Hey girls, Hey Boys van de Chemical Brothers
en filter alle "Here we go"'s eruit. Gebruik hiervoor een `continue`.
```
List<string> chemicalBrothersLyrics = new List<string>();
            chemicalBrothersLyrics.Add("Hey girls");
            chemicalBrothersLyrics.Add("Hey boys");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Hey girls");
            chemicalBrothersLyrics.Add("Hey boys");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Hey girls");
            chemicalBrothersLyrics.Add("Hey boys");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Hey girl");
            chemicalBrothersLyrics.Add("Hey boys");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Hey girl");
            chemicalBrothersLyrics.Add("Hey boy");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Hey girl");
            chemicalBrothersLyrics.Add("Hey boy");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Hey girl");
            chemicalBrothersLyrics.Add("Hey boy");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Hey girls");
            chemicalBrothersLyrics.Add("Hey boys");
            chemicalBrothersLyrics.Add("Superstar DJ's");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Here we go");
            chemicalBrothersLyrics.Add("Here we go");
```

output:
```
Hey girls
Hey boys
Superstar DJ's
Hey girls
Hey boys
Superstar DJ's
Hey girls
Hey boys
Superstar DJ's
Hey girl
Hey boys
Superstar DJ's
Hey girl
Hey boy
Superstar DJ's
Hey girl
Hey boy
Superstar DJ's
Hey girl
Hey boy
Superstar DJ's
Hey girls
Hey boys
Superstar DJ's
```
