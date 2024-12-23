# Command to initialize your react project
$ npm init -y

# Next command to run and install the project
$ npm install express --save

command to run the code
node . 

# process to push docker images to dockerhub
1 may sure you are at right project directory
2 may sure you have dockerfile and docker desktop
# 3 check images avaliable.
 docker images
# 4 to build the image 
docker build -t easyfex39/sudayimg .
# 5 to check the image again
docker images
# 6 docker login
# 7 push your docker image 
 docker push easyfex39/reactimg:latest
 # 8 go to dockerhub to check image push