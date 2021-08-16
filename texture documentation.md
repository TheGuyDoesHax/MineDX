# __*Texture Map Documentation*__

### The textures are simple:

  grab your image off the "net" or just use a pixel editor and scale it to size. From there place your image in a white area, make sure that if the block you are placing has **_MORE THAN ONE TEXTURE_**, for example the acacia log, you have to place the side sprite FIRST, then add the top sprite after it unless if it has more than 2 textures. (In that case, see me about it.)
___

### In the code, your code has to look like this for a single texture item:

```js
nodeType.diamondblock = {
  // x = any number
  id: x,
  texture: function(face)
  {
    return [z, z];
  },
  /* the z's can be any number, and there has to be a SPACE
  after the comma or else it will throw an error! Also, do 
  NOT put these line comments inside the code, as they are for
  documentation purposes ONLY!
  */
  transparent: false,
  solid: true
  }
}
```
___
### If it is a double texture block like an acacia log, consult the code below:

```js
  nodeType.acacialog = {
    id: x,
    texture: function(face)
    {
      return [z, z];
    }
    else
    {
      return [y, y];
    },
    // again y can be any number.
    transparent: false,
    solid: true
  },
}
```
___
That is all there is to know about adding render textures to the texture map! Again, if you are having trouble adding textures, shoot me a comment through replit.com or reach out to me via my current school Email: 13458@tusge.org, and my personal Email: 49minecraftlord@gmail.com.