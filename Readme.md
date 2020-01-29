#### vue.js youtube search app 

Run command to start project locally
```bash
docker run -it --rm -p 8080:8080 -u $(id -u ${USER}):$(id -g ${USER}) -v ${PWD}:/app node:12 /bin/bash
```
Inside container run 
```bash
cd app/youtube-search/
yarn serve
```