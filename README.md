### README ###



# COMMANDS
## Develop
```
sudo docker run -it --rm -v $(pwd)/site:/site -p 8000:8000 aripalo/gatsby-docker develop
```
## Build and Serve*
```
sudo docker run -it --rm -v $(pwd)/site:/site -p 8000:8000 aripalo/gatsby-docker stage
```
## Build
```
sudo docker run -it --rm -v $(pwd)/site:/site -p 8000:8000 aripalo/gatsby-docker build
```


# LINKS
- [Docker image fro GatsbyJS](https://github.com/aripalo/gatsby-docker/)
