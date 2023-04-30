# My test repo  
I am currently experimenting with docker and docker compose. These are my test docker compose files. If you use them use at your own risk.

## About me
I am an accountant who early on in his career was tasked with looking after the it and network of the business I worked for as I had an interest in computers. I had enough experience to get myself into trouble. But over the years and through different business I worked in I was tased with managing different IT position.  
So, I know enough to get into trouble and sometime enough to get out of it.

I have a love of technology and like learning new things. My trouble is it is hard to stay focused on one thing for to long.
At the moment I have an interest in docker, and have been playing with;
### Frigate 
Came across this and did not think I could use it as I was not willing to forkout the money for a Coral tpu but I have been testing it with just the cpu detection on my proxmox server and it works pretty great. The UI could do with a little work, but this project is fantastic. I am running Frigate in a HP 360P G8 server, I have allocated 8 CPU cores and 16 GB RAM and it works better than iSpy running Deepstack and does not use that much more resources. I also run 3 other docker containers on this Docker VM and the CPU usage averages around 25% and memory at 4 GB.  I am thinking about investing in a Coral tpu to see what difference would make.

Before frigate I had tried Xeoma, which is paid software on a per camera basis, it was great but there were too many false positives with the motion detection that came with the licenses I had purchased. And it had not option to add external object detection like Deepstack, to add good object detection (human detection) to it was expensive, it was like $299 (USD) per camera, I had already forked out  a $192 (USD) + on 2 standard and 2 pro licenses. If I was using video surveillance commercially, I would definitely look at using this software.

I also tried iSpy Agent, which was very good. I like this, it worked well running in a Docker container and integrated reasonably well with Home Assistant. But having to run a separate container for object detection, Deepstack or CodeProject.AI was annoying. The UI was great but the camera feeds at times were not great, recording was good but viewing them the UI was not as clear as Frigate, play back was pretty bad it would play back really slow at times, and scrubbing through playback was slow and not very precise. 

### Traefik – this has some very interesting use cases.  

### Pi-hole

### Bind9


