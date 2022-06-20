# link-checker-malacious
A simple package to check for bad links

### Downloading
```
npm i link-checker-malacious
```

#### Approximately around 9000+ links (total) of "bad sites".

## Update: v1.5.0 has only one function, it will check for all types of links, and even return the detected link.
## Usage
  ```js
const mal = require("link-checker-malacious");
let data = mal.isMalLink("string of text here")//it will auto detect links in it and scan those links
if(data.isMal==true){
  console.log("Type: "+data.type+"\n Link: "+data.link)
}
else{
  console.log("Not a malacious string")
}
```
## Credits: 
[Bumblebee#1447](https://discord.com/users/818377414367379487) (on discord) creating the package
[DevSpen](https://github.com/DevSpen) for [this repo](https://github.com/DevSpen/links) & [ELBKR](https://github.com/elbkr) for [this repo](https://github.com/elbkr/bad-websites).

I also know that the name has a spelling error; but I can't rename on NPM :(
