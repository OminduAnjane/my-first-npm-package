# telegram-img-url-convert-Api

## Installation 

```sh

npm i @omindubro/telegram-img-url-convert-Api

```

***

## Example

```ts

let { img2url } = require('@omindubro/telegram-img-url-convert-Api')

const path = './omi.jpg'

img2url(path).then(url => {

    console.log(url); //=> https://telegra.ph/file/a45e08f53773b1a6a16af.jpg

})


```

***
