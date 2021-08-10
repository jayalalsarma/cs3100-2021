# CS3100: Paradigms of Programming - 2021

## Running the Jupyter notebooks

Install [docker](https://docs.docker.com/install/#supported-platforms) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for your platform.
Then run the following commands:

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
## Windows

In some windows machines you may have to install wsl 2. Follow only step 4 from this [link](https://docs.microsoft.com/en-us/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package).

For running the docker step, on Windows, you need to run the docker command as follows:

```bash
$ docker run -it -p 8888:8888 -v PATH:/cs3100-2021 jayalalsarma/cs3100-2021:latest
```
where PATH in the command should be replaced with the location you cloned the git repo into in the above steps


