# React + Vite and Docker
### Version 0.0.1


Clone the project
```sh
git clone git@github.com:chrisrjrs/react-vite-docker-demo.git
```
From the /app diretory run 
```sh 
docker compose build 
```

Once the image is built run the container.
```sh
docker comopose up
```

The page should be visible via the Vite server
```sh
http://localhost:5173/
```

The react app was scafolded with the command:
```sh
npm create vite@latest my-app -- --template react
```
See the README.md in the app directory for more details about it.