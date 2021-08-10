# CS3100: Paradigms of Programming - 2021

## Running the Jupyter notebooks

Install [docker](https://docs.docker.com/install/#supported-platforms) for your platform.

```bash
$ git clone https://github.com/jayalalsarma/cs3100-2021
$ docker run -it -p 8888:8888 -v "$(pwd)":/cs3100-2021 jayalalsarma/cs3100-2021:latest
$ jupyter notebook --ip=0.0.0.0
```

Copy and paste the diplayed URL that starts with `http://127.0.0.1:8888` into
your browser. If you save the changes to the notebook, they are saved locally.
As you go through the course, you will have to do `git pull` in the
`cs3100-2021` directory to get the latest updates from upstream.

## Linux

On Linux, you need to run the docker command with `sudo`:

```bash
$ sudo docker run -it -p 8888:8888 -v "$(pwd)":/cs3100-2021 jayalalsarma/cs3100-2021:latest
```
