Example to run Behavioral Cloning project locally with Docker.

If you don't have Docker installed on your local machine, you need install it first.

Then,

- git clone https://github.com/udacity/CarND-Behavioral-Cloning-P3.git
- $ cd CarND-Behavioral-Cloning-P3/
- $ wget https://raw.githubusercontent.com/udacity/CarND-Term1-Starter-Kit/master/run.sh

Then, run one of the command below in  CarND-Behavioral-Cloning-P3/ folder,

If you're using Windows PowerShell:

docker run -it --rm --entrypoint "/run.sh" -p 8888:8888 -v ${pwd}:/src udacity/carnd-term1-starter-kit

If you're using bash or Docker Quickstart Terminal:

docker run -it --rm --entrypoint "/run.sh" -p 8888:8888 -v `pwd`:/src udacity/carnd-term1-starter-kit


## References
- https://github.com/udacity/CarND-Term1-Starter-Kit
