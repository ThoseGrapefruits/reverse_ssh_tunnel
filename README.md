# Reverse SSH Tunnel
> Using autossh and reverse ssh tunneling to enable accessing your machines even if they are NAT'd or behind firewalls - automatically.

## Usage
> Note: this script assumes you are using OS X and have homebrew installed

```$
wget http://github.com/mikeymckay/reverse_ssh_tunnel/raw/master/setup_reverse_tunnel.sh
chmod +x ./setup_reverse_tunnel.sh
sudo ./setup_reverse_tunnel.sh
```

## Why to use this
I want all of my machines to be setup with an ssh tunnel whenever one of them finds an internet connection. That way I can always access all of my machines no matter where I, or they are the world. I want this even if they are in some high security firewalled corporate prison or if they are sharing the same IP address as the other million NAT'd users tethering internet through their phones. This should happen automatically and without fuss.

## More information can be found here
- http://www.vdomck.org/2005/11/reversing-ssh-connection.html
- http://www.vdomck.org/2009/11/ssh-all-time.html
