
# jupyter-lab-docker
A simple docker project that build **Jupyter Lab** docker image.

## Prerequisites
Make sure you've installed the docker in your machine/PC

## How to use?
1. Clone the repository<br>
`git clone https://github.com/jerinpetergeorge/jupyter-lab-docker.git`
2. move into repository directory<br>
`cd jupyter-lab-docker`
3. Build the image<br>
`docker build . -t jupyter-lab-docker`
4. Run docker image<br>
`docker run -p 8888:8888 jupyter-lab-docker --NotebookApp.token='' --NotebookApp.password=''`
5. Open your browser and head into [http://0.0.0.0:8888/](http://0.0.0.0:8888/)

