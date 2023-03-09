## introduce
This is a project that makes the open source project [tweb](https://github.com/morethanwords/tweb) on github into a docker image, which is used to set up on your own slag machine. I checked dockerhub and couldn’t find it. used it, so I made one myself
## Usage
Clone this project locally, then
```sh
docker build -t <image name:label> -f ./tweb_build .
#Modify the content in tweb.yml according to your own ideas
docker-compose -f tweb.yml up -d
```
If you have not made any changes, you should be able to use it through 127.0.0.1:8080

Enjoy!!