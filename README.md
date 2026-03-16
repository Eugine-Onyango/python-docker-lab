The Indestructible Moving Box: A Docker PBL Mission.

My main mission:
I am building a containerized Python backend from scratch to master Docker and Project-Based Learning (PBL). Instead of just writing code that "works on my machine," I'm learning to pack my entire environment into Docker (an indestructible moving box) so it runs flawlessly anywhere—from my laptop to the cloud.

Tech Stack:

Host OS: Windows 11(via WSL 2)
Docker Desktop: Where I am carrying out my operations.
Language: Python


Current Progress: Sprint 0 (The Prep)
[x] Sub-Sprint 0.1: Understood why "It worked on my machine" is a lie and how Docker fixes it.
[x] Sub-Sprint 0.2: Installed the hardware! Docker Daemon is officially clocked in.Verified Version: Docker version 29.2.1 (Screenshot below!)
[ ] Sub-Sprint 0.3: Setting up this showroom and repository.


Sprint 1 Progress

'''
Microsoft Windows [Version 10.0.26200.8037]
(c) Microsoft Corporation. All rights reserved.

C:\Users\EUGENE>docker --version
Docker version 29.2.1, build a5c7197

C:\Users\EUGENE>docker pull ubuntu
Using default tag: latest
latest: Pulling from library/ubuntu
01d7766a2e4a: Pull complete
fd8cda969ed2: Download complete
Digest: sha256:d1e2e92c075e5ca139d51a140fff46f84315c0fdce203eab2807c7e495eff4f9
Status: Downloaded newer image for ubuntu:latest
docker.io/library/ubuntu:latest

C:\Users\EUGENE>docker run -it ubuntu bash
root@c63f39624590:/# echo "Hello world from Lower Kabete!"
Hello world from Lower Kabete!
root@c63f39624590:/# exit
exit

C:\Users\EUGENE>
