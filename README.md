gun-ui-lcd
==========
> a member of the gun-ui library.
> A collection of widgets created to work brilliantly with GUN, or without

Disclamer:
_All canvas elements in the gun-ui-lib are created by Gerrit Grunwald (@hansolo)_**

## What is it ?
Let me show you 
'gun-ui-lcd'
https://cloud.githubusercontent.com/assets/890650/19285672/2d0dbfb0-8ffb-11e6-8b56-ef9025ce5045.jpg

## Okay what about gunDb ?
Every item in the gun-ui-lib needs 2 attributes, 'parent'  and 'prop'. They represent the key(soul) and the property you want to subscribe to.
like `gun.get(<parent>).path(<prop>)` 
> (If you have no idea what i'm talking about...take a look at 
> https://github.com/amark/gun)

So in your html it would look like 
```
<gun-ui-lcd parent="livingroom" prop="temperature"></gun-ui-lib>
```
That's it!  The element will monitor and update it's own state now !

## Styling/Theming
https://cloud.githubusercontent.com/assets/890650/19287504/3ffbd312-9002-11e6-826d-aa547f37bef6.png

## values
https://cloud.githubusercontent.com/assets/890650/19287458/192c4726-9002-11e6-84b7-a58985a2688e.png


_All canvas elements in the gun-ui-lib are created by Gerrit Grunwald (@hansolo)_**