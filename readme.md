https://zuma-lab.com/posts/docker-python-settings


# Setting Up a Python Remote Interpreter Using Docker
https://dev.to/alvarocavalcanti/setting-up-a-python-remote-interpreter-using-docker-1i24
## Visual Studio Code
1. Install the Python extension
2. Install the Remote - Containers extension
3. Open the Command Pallette and type Remote-Containers, then select the Attach to Running Container... and selecet the running docker container
4. VS Code will restart and reload
5. On the Explorer sidebar, click the open a folder button and then enter /code (this will be loaded from the remote container)
6. On the Extensions sidebar, select the Python extension and install it on the container
7. When prompet on which interppreter to use, select /usr/local/bin/python
8. Open the Command Pallette and type Python: Configure Tests, then select the unittest framework