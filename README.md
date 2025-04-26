# Setup

```bash
sudo docker build -t coral:pi5 .
sudo docker run -d --name coral --device /dev/bus/usb:/dev/bus/usb --restart unless-stopped coral:pi5
```