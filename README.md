# pythonocc-docker
Example docker image for pythonocc.
1. Clone the repository
```
git clone https://github.com/OkanPinar/pythonocc-docker.git
```
2. Go the repository directory
```
cd pythonocc-docker
```
3. Build docker image
```
docker build -t pythonocc_docker .
```
4. Run docker image
```
docker run -d -t -p 8000:8000 pythonocc_docker
```
5. Open following url: http://127.0.0.1:8000/