# stable_diffusion_install: 
   <! this is a guide for beginners to realize fundamental functionalities of Automatic1111 and Comfyui >
   - *Author: Bernard Bai*
   - *Date: 19.03.2024*

## Softwares you need to install:
1. Install **Python 3.10.6**
   + URL: https://www.python.org/downloads/release/python-3106/
   + Note: the newest version of Python may result in problems, so installing Python 3.10.6 is enough.
2. Instal **Git**
   + URL: https://git-scm.com/downloads 
   + Note: Use the *Standalone Installer*
3. Downloading **checkpoints** from Huggingface
   + URL: https://huggingface.co/
   + Recommanded checkpoints:
      * [stabilityai/stable-diffusion-xl-base-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
      * [runwayml/stable-diffusion-v1-5](https://huggingface.co/runwayml/stable-diffusion-v1-5)  

## Install Automatic1111
1. Windows
   + Automatic1111 can be downloaded by entering the following command line into the **Windows Powershell**
   `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`
   + Click `webui-user.bat` to run Automatic1111
   + Move the checkpoints into the `stable-diffusion-webui>models>stable-diffusion` folder
2. MAC

## Install Comfyui
   + Download Comfyui using this [link](https://github.com/comfyanonymous/ComfyUI/releases/download/latest/ComfyUI_windows_portable_nvidia_cu121_or_cpu.7z), extract the file (7-zip is recommanded).
   + Comfyui can be run with the pc's cpu by clicking `run_cpu.bat`, if the pc has a nvidia gpu, clicking `run_nvidia_gpu.bat` is recommanded.
   + Move the checkpoints into the `ComfyUI>models>checkpoints` folder


### Credits
   - Stable Diffusion web UI - https://github.com/AUTOMATIC1111/stable-diffusion-webui
   - Comfyui - https://github.com/comfyanonymous/ComfyUI
