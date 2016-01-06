```
cd node-pm2/
docker build -t="rakam/node-pm2" .
docker run -e "APP=server.js" -p 3000:80 5858:5858 -v **/path/to/app/folder/**:/app -ti rakam/node-pm2 /bin/bash /launch
```
