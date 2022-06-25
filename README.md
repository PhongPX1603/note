```bash
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
```
# note


## 1. Setup working space
### 1.1 Install Operation System (OS)
* Windows 10 and Ubuntu

#### 1.1.1 Windows
#### 1.1.2 Ubuntu
* Install Ubuntu 22.04

### 1.2 Install packages
* SSH: Private key SSH, Public key SSH, remote SSH, remote server (237, 238)
```
Create SSH Key (Private/Public)
ssh-keygen -t rsa

To take Private Key
cat ~/.ssh/id_rsa

To take Public Key
cat ~/.ssh/id_rsa.pub

Logging in server:
ssh ocr@10.240.142.237

copy file from local to server
scp -r (folder_dir) ocr@10.240.142.237:/folder_dir_server_computer
scp (file_path) ocr@10.240.142.237:/folder_dir_server_computer
```
* GPU: v100 tesla 32GB (server), local
* Install basic packages
* [Conda environment](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

     [How to install anaconda](https://docs.anaconda.com/anaconda/install/linux/)
* [Tmux](https://tmuxcheatsheet.com/)
- install
```
conda install -c conda-forge tmux
```
- create tmux session
```
tmux new -s <mysession>
```
- enter tmux session
```
tmux a -t <mysession>
```
* Htop
```
conda install -c conda-forge htop
```

* watch nvidia-smi

* [Github](https://education.github.com/git-cheat-sheet-education.pdf) 
```
```

* remote tool: teamviewer, anydesk
```

### 1.3 Common Libraries
* Shapely
* Cv2

### 1.4 [Flow](https://docs.google.com/document/d/1zAiTrEINrVP7vnkV3pH_mM4A7NrD1N0zi-KAq0fXL0c/edit#heading=h.hzm7uijj1sgr)

### 1.5 Expand
* API
* Docker
* Microservices
