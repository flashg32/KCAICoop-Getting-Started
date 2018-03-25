# KCAICoop-Getting-Started
Steps to get started

## Reading Material (will be dynamically updated)
- [ISLR](http://www-bcf.usc.edu/~gareth/ISL/) - free book

## Docker
We will be using docker for our compute environment. This makes it easy for people to colloborate on different os platforms

*Update*: If you are having trouble installing Docker on a Windows computer, try the following:
  1. Ensure you are on Professional Version, and
  2. Enable Hyper-V: [instructions for Windows 10](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v), and   
  3. Change your BIOS to allow virtualization:  [instructions for Windows 10](https://blogs.technet.microsoft.com/canitpro/2015/09/08/step-by-step-enabling-hyper-v-for-use-on-windows-10/), and
  4. After you've downloaded docker and git and run the build.sh file, if you get an error when you run ".\run.sh", try changing the          file in one place.  
    a. In Windows Explorer, navigate to the file, it should be in the folder named "C:\Users\*user*\KCAICoop_workbench"       
    b. Open it in notepad and change the line "docker run -it --rm \" to "docker run -i --rm \"
    
*End Update*

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
