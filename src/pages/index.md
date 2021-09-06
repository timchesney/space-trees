---
layout: "../layouts/Page.astro"
metaTitle: Design, code & smack talk
title: Space trees. It's trees, but in space!

---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Rutrum quisque non tellus orci ac auctor augue mauris augue. Fermentum odio eu feugiat pretium nibh ipsum consequat. Lectus nulla at volutpat diam ut venenatis tellus in metus. Lectus magna fringilla urna porttitor rhoncus dolor purus non. In pellentesque massa placerat duis ultricies. Facilisis magna etiam tempor orci eu lobortis elementum nibh tellus. Gravida neque convallis a cras semper auctor neque vitae tempus. Rutrum tellus pellentesque eu tincidunt tortor. Enim facilisis gravida neque convallis. Nisi vitae suscipit tellus mauris a diam. Aliquam purus sit amet luctus venenatis lectus magna fringilla. Felis imperdiet proin fermentum leo vel orci porta. Eu sem integer vitae justo eget magna fermentum. Diam volutpat commodo sed egestas egestas fringilla phasellus faucibus scelerisque. Amet nisl suscipit adipiscing bibendum est ultricies integer quis. Tempus quam pellentesque nec nam aliquam sem. Risus feugiat in ante metus dictum at tempor. Laoreet sit amet cursus sit. Sapien pellentesque habitant morbi tristique senectus.

Volutpat maecenas volutpat blandit aliquam etiam erat velit. Blandit turpis cursus in hac habitasse. Lectus urna duis convallis convallis tellus. Nullam non nisi est sit amet facilisis magna. Quis hendrerit dolor magna eget est lorem ipsum. Risus nec feugiat in fermentum posuere. Pharetra pharetra massa massa ultricies mi quis hendrerit. Viverra tellus in hac habitasse platea. Diam quam nulla porttitor massa id neque. Orci eu lobortis elementum nibh tellus molestie nunc. Aliquet eget sit amet tellus cras adipiscing. Sagittis vitae et leo duis ut diam quam nulla porttitor. Morbi leo urna molestie at. Purus in massa tempor nec feugiat nisl.

```js
function findMatches(stringToMatch, data) {
    return data.filter(place => {
      const regex = new RegExp(stringToMatch, 'gi' )
      return place.city.match(regex) || place.state.match(regex)
    })
  }

  function updateResults() {
    const results = findMatches(this.value, cities)
    const html = results.map(result => {
      const reg = new RegExp(this.value, 'gi')
      const city = result.city.replace(reg, `<span class="hl">${this.value}</span>`)
      const state = result.state.replace(reg, `<span class="hl">${this.value}</span>`)
      return `
        <li>
          <span>${city}, ${state}</span>
          <span>${result.population}</span>  
        </li>
      `
    }).join()
    suggestions.innerHTML = html
  }

```
Iaculis at erat pellentesque adipiscing commodo elit. Etiam non quam lacus suspendisse faucibus interdum. Interdum velit laoreet id donec. Aliquet enim tortor at auctor urna. Ridiculus mus mauris vitae ultricies leo integer malesuada nunc. Neque laoreet suspendisse interdum consectetur libero id faucibus nisl. Lorem ipsum dolor sit amet consectetur adipiscing elit duis tristique. Dolor sit amet consectetur adipiscing. Rutrum quisque non tellus orci ac auctor augue mauris augue. Pharetra et ultrices neque ornare aenean euismod elementum nisi. Sed cras ornare arcu dui vivamus arcu felis. Id donec ultrices tincidunt arcu non sodales neque sodales. Pulvinar mattis nunc sed blandit libero volutpat sed cras ornare. Accumsan lacus vel facilisis volutpat est. Consectetur a erat nam at. Elementum nisi quis eleifend quam adipiscing vitae proin sagittis nisl. Viverra nibh cras pulvinar mattis nunc. Pulvinar pellentesque habitant morbi tristique senectus et netus.