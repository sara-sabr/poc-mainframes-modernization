# Configuration of development environment

## Requirements

1. Docker installed on Windows
    a. If you have Windows 10 Pro or above, use [Docker for Desktop](https://hub.docker.com/editions/community/docker-ce-desktop-windows)
    b. If you have Windows 7 or Windows 10 Home, use [Docker Toolbox](https://download.docker.com/win/stable/DockerToolbox.exe)
2. Install a X server software on Windows, Example [VCXSRV](https://sourceforge.net/projects/vcxsrv/)
3. Start docker and set the environment variable ```DISPLAY``` for the X11 window. Example in Linux: ```DISPLAY=192.168.0.2:0.0``` where you would change the IP to the IP address of X11. 
4. Run ```docker-compose up -d```.

## Account details

Taken from [docker-ubuntu-hercules-mvs:latest](https://hub.docker.com/r/rattydave/docker-ubuntu-hercules-mvs)

- **Username**: HERC01  
  **Password**: CUL8TR  
  **Description**: A fully authorized user with full access to the RAKF users and Profiles tables.
- **Username**: HERC02  
  **Password**: CUL8TR  
  **Description**: A fully authorized user without access to the RAKF users and profiles tables.
- **Username**: HERC03  
  **Password**: PASS4U  
  **Description**: A regular user.
- **Username**: HERC04  
  **Password**: PASS4U  
  **Description**: A regular user.
- **Username**: IBMUSER  
  **Password**: IBMPASS  
  **Description**: A fully authorized user without access to the RAKF users and profiles tables. This account is meant to be used for recovery purposes only.
