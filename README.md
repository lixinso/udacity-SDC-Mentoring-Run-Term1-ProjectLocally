References: https://github.com/udacity/CarND-Term1-Starter-Kit

git clone https://github.com/udacity/CarND-Behavioral-Cloning-P3.git

Copy https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/run.sh to your project folder.


If you're using Windows PowerShell:

docker run -it --rm --entrypoint "/run.sh" -p 8888:8888 -v ${pwd}:/src udacity/carnd-term1-starter-kit

If you're using bash or Docker Quickstart Terminal:

docker run -it --rm --entrypoint "/run.sh" -p 8888:8888 -v `pwd`:/src udacity/carnd-term1-starter-kit
