# IP-Sweep
This is a bash project to automatically detect and scan your local network for devices connected to it

## How it Works
The script will work as follows:
- Automatically discover the IP of the network you are connected to
- Discover the devices connected to it with a ping sweep
- Peform an Nmap scan on said devices to find open ports

### Pros
- Saves a lot of time compared to running Nmap alone
- There is no need to type several commands before starting

### Cons
- The script won't get any device that is not pingable

## Add it to your $PATH
