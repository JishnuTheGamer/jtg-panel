
<h2> jtg-Panel is a panel for managing your game servers, applications, and more built with modern technologies such as Node.js, Docker, and Express - made to work with our jtg-Daemon software.</h2>

## Installation
### Picking a Server OS

jtg-Panel runs on various operating systems, so pick whichever you are most comfortable using.

| Operating System | Version |     Supported      | Notes                                                       |
|------------------|---------|:------------------:|-------------------------------------------------------------|
| **Ubuntu**       | 24.04   | ✅ | Documentation written assuming Ubuntu 24.04 as the OS. |
|                  | 22.04   | ✅ |                                                             |
| **CentOS**       | 7       | ✅ | Extra repos are required.                                   |
|                  | 8       | ✅ | Note that CentOS 8 is EOL. Use Rocky or Alma Linux.         |
| **Debian**       | 11      | ✅ |                                                             |
|                  | 12      | ✅ |                                                             |
| **Windows**      | 11      | ⚠️ | May have issues due to Windows firewall.                   |
|                  | 10      | ⚠️ |                                                             |
| **macOS**        | 10.15+  | ⚠️ |                                                             |

## Dependencies

* Node.js `v20` and higher (Nodejs `v20` recommended).
* ### Installation Nodejs 20

```bash
curl -sL https://deb.nodesource.com/setup_20.x | sudo bash -
```
```bash
apt-get install nodejs -y
```

### Installation Panel

To install and start the jtg Panel , run the following commands:

```bash
git clone https://github.com/JishnuTheGamer/jtg-panel.git && cd jtg-panel && npm install && npm run seed && npm run createUser && node .
```

- Skyport (EOL)
- Edited by **hopingboyz**
- re-launch by **Jishnu**
