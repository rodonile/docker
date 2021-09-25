## Use case
Docker stack I have deployed in my homelab server (with Ubuntu 18.04) which runs various applications.

### Applications
- Heimdall Dashboard (https://github.com/linuxserver/Heimdall)
- Scipy Jupyter Notebook Server (https://github.com/jupyter/docker-stacks)
- Tensorflow Jupyter Notebook Server with Nvidia GPU (https://www.tensorflow.org/install/docker)
- Psitransfer (https://github.com/psi-4ward/psitransfer)
- Librespeed speedtest server (https://github.com/librespeed/speedtest)
- HomeAssistant (https://www.home-assistant.io/)
- Jellyfin server with GPU passed through for ffmpeg transcoding (https://jellyfin.org/)
- Youtube DL video downloader (https://github.com/Tzahi12345/YoutubeDL-Material)

### Instructions
- adapt paths, users, PIDs, etc...
- docker-compose up -d