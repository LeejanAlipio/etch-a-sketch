# Etch-A-Sketch
Second last project of Odin's Foundation Path. When you hover a grid, it changes to a random color and it's opacity keeps increasing until it hits 1.

## Preview
![Project image](/image.png)

## Live 
[Live Page](https://markleejanalipio.github.io/etch-a-sketch/)

## Pseudocode

- REFERENCE the container and btn
- DECLARE the normal size (16)
- CREATE the squares inside a container when CHANGE SIZE is clicked
    - REMOVE the normal size
    - LOOP throught the size given
    - CREATE a square that is proportional to the container size
    - SET backgroundColor to random
    - ADDEVENTLISTENER when mouse enters the square and change the color while the opacity is getting darker each time the mouse enters a square
- CHANGES SIZE when change btn is clicked
    - PROMPT the user for the size and limit it to a 100
- RESET progress when reset btn is clicked while the size stays the same
