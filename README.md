# rpg2k-tween

```
yarn install
yarn build *****.json
```

```js
{
  "id": 1, // Picture ID
  "name": "red", // Picture Name
  "framerate": 0.1, // waitTime.repeat
  "size": {
    "w": 100, // Image Width
    "h": 100 // Image Height
  },
  "fixedPosition": true, // Centering Mode
  "offset": {
    "x": 0, // offset pixel X
    "y": 0, // offset pixel Y
    "mx": 100, // animation.X multiply by MX
    "my": 100 // animation.Y multiply by MY
  },
  "init": { // initial params
    "x": 0,
    "y": 0,
    "s": 100,
    "a": 100,
    "color": [100, 100, 100, 100],
    "effect": [0, 5]
  },
  "animation": [] // params per frame
}
```