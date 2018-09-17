# docker-galaxy-glycobiology-gap
Galaxy for Glycobiology and Glycobioinformatics :)

## run 
```
 sudo docker run -d -p 8080:80 cbarnett/docker-galaxy-glycobiology-gap
```
Pulls image from DockerHub. Try port 8081, or 8090, if 8080 is in use. 

## build with Docker
- clone this repository - `git clone git@github.com:galaxyglycobiology/docker-galaxy-glycobiology-gap.git`
- `pushd docker-galaxy-glycobiology-gap`
- `docker build -t gap .`
- `docker run -d -p 8080:80 gap`
- `browse to http://localhost:8080`

