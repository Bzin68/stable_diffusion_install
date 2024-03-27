# stable_diffusion_install: 
   <!--this is a guide for beginners to realize the fundamental functionalities of Automatic1111 and Comfyui-->
   - *Author: Bernard Bai*
   - *Date: 19.03.2024*

## Software you need to install:
1. Install **Python 3.10.6**
   + URL: https://www.python.org/downloads/release/python-3106/
   + Note: the newest version of Python may result in problems, so installing Python 3.10.6 is enough.
2. Instal **Git**
   + URL: https://git-scm.com/downloads 
   + Note: Use the *Standalone Installer*
3. Downloading **checkpoints** from Huggingface
   + URL: https://huggingface.co/
   + Recommended checkpoints:
      * [stabilityai/stable-diffusion-xl-base-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
        ![First_step_ckpt](https://github.com/Bzin68/stable_diffusion_install/raw/main/huggingface_1.png)
        ![Second_step_ckpt](https://github.com/Bzin68/stable_diffusion_install/raw/main/huggingface_2.png)
      * [runwayml/stable-diffusion-v1-5](https://huggingface.co/runwayml/stable-diffusion-v1-5)
        ![First_step_ckpt](https://github.com/Bzin68/stable_diffusion_install/raw/main/huggingface_3.png)
        ![Second_step_ckpt](https://github.com/Bzin68/stable_diffusion_install/raw/main/huggingface_4.png)

## Install Automatic1111
1. Windows
   + Automatic1111 can be downloaded by entering the following command line into the **Windows Powershell**
   `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`
   + Click `webui-user.bat` to run Automatic1111
   + Move the checkpoints into the `stable-diffusion-webui>models>stable-diffusion` folder
2. MAC

## Install Comfyui
   + Download Comfyui using this [link](https://github.com/comfyanonymous/ComfyUI/releases/download/latest/ComfyUI_windows_portable_nvidia_cu121_or_cpu.7z), extract the file (7-zip is recommanded).
   + Comfyui can be run with the PC's CPU by clicking `run_cpu.bat`, if the PC has a Nvidia GPU, clicking `run_nvidia_gpu.bat` is recommended.
   + Move the checkpoints into the `ComfyUI>models>checkpoints` folder


### Credits
   - Stable Diffusion web UI - https://github.com/AUTOMATIC1111/stable-diffusion-webui
   - Comfyui - https://github.com/comfyanonymous/ComfyUI
