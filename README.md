# KCAICoop-Getting-Started
Steps to get started

## Reading Material (will be dynamically updated)
- [ISLR](http://www-bcf.usc.edu/~gareth/ISL/) - free book

## Docker
We will be using docker for our compute environment. This makes it easy for people to colloborate on different os platforms

[Our Docker Container](https://github.com/KCMachineLearning-AI-Group/KCAICoop_workbench)

[Getting started with docker for newbies](https://docs.docker.com/get-started/)

We will be using jupyter notebook to run excercises (most of the time) [Getting started](http://jupyter.org/index.html)

#### Instructions how to run the docker image
##### Using Docker Pull
1. `git clone https://github.com/KCMachineLearning-AI-Group/KCAICoop_workbench.git`
2. `cd KCAICoop_workbench`
3. `docker pull kcaicoop/kcaicoop_workbench` 
4. `./run.sh` (works on linux and mac windows 10 with the linux subsystem)
5. You should see a url returned in your terminal. copy the (http://localhost:8888/{randomstringhere}) and paste url in browser

##### Using build script
1. `git clone https://github.com/KCMachineLearning-AI-Group/KCAICoop_workbench.git`
2. `cd KCAICoop_workbench`
3. `./build.sh` (works on linux and mac and maybe windows 10 with the linux subsystem)
4. `./run.sh` (works on linux and mac windows 10 with the linux subsystem)
5. You should see a url returned in your terminal. copy the (http://localhost:8888/{randomstringhere}) and paste url in browser

you should now be in the jupyter notebook environment
