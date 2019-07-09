### Running the server
* Makes ure that no other servers (like Apache or Nginx) are using port **80**
* Make sure to run server.py as a sudoer since [port 80 needs sudo privilages](https://www.w3.org/Daemon/User/Installation/PrivilegedPorts.html):
```sh
sudo python3 server.py
```
