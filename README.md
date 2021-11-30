# link-checker
A simple package to check for bad links
## List Of Functions Available
```
   is_cam
  is_dating
  is_gambling
  is_pirated
  is_ip_grabber
  is_nsfw
  is_scam
```
### Downloading
```
npm i https://github.com/Bumblebee-3/link-checker-malacious
```

#### Approximately around 9000+ links (total) of "bad sites".
## Usage
  ```js
const r = require("link-checker");

const link = "your link here";
const cam = r.is_cam(link);
const dating = r.is_dating(link);
const gambling = r.is_gambling(link);
const pirated = r.is_pirated(link);
const ip = r.is_ip_grabber(link);
const nsfw = r.is_nsfw(link);
const scam = r.is_scam(link);

console.log("Link: "+link)
console.log("is it a cam site: "+cam)
console.log("is it a dating site: "+dating)
console.log("is it a gambling site: "+gambling)
console.log("is it a pirated site: "+pirated)
console.log("is it a ip grabber: "+ip)
console.log("is it a nsfw site: "+nsfw)
console.log("is it a scam site: "+scam)

```
## Credits: 
[Bumblebee#1447](https://discord.com/users/818377414367379487) (on discord) creating the package
[DevSpen](https://github.com/DevSpen) for [this repo](https://github.com/DevSpen/links) & [ELBKR](https://github.com/elbkr) for [this repo](https://github.com/elbkr/bad-websites).
All "illegal" websites have been taken from here.
