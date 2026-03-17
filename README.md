# AI Sports Video Commentary Generator

![Built with Llama](https://img.shields.io/badge/Built%20with-Llama%203.2-044DFE?style=for-the-badge&logo=meta&logoColor=white)

This project generates creative sports-style commentary for any type of video using a combination of computer vision techniques and large language models. The system detects objects in the video, tracks their movements, and generates audio commentary using either Llama-3.2-1B-Instruct or GPT-Neo-125M. It then combines the generated audio and the annotated video for the final result.

---

## Features

- Object detection using YOLOv5
- Movement tracking and interaction detection
- Text commentary generation using Llama-3.2-1B-Instruct or GPT-Neo-125M
- Audio generation using gTTS
- Video output with synchronized commentary
- Works in Google Colab for easy setup

---

## Requirements

- **LLaMa model:** To use Llama-3.2-1B-Instruct, you need a Hugging Face account and token.  
  - If access is denied, request permission here: [Meta-LLaMA](https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct).  
  - Instructions are also included inside the notebook.
- **RAM:** For smooth execution, ensure your system or Colab session has at least 12 GB of RAM.
- **FFmpeg:** Needed to combine the final audio and video.  
  - For local installations, download it here: [FFmpeg Downloads](https://www.ffmpeg.org/download.html)
- **Python packages:** Install all required packages locally with:

```bash
pip install -r requirements.txt
```

---

## License & Terms of Use
This project is dual-governed by the author's terms and the licenses of its underlying dependencies (specifically Meta's Llama 3.2).

Software Code: All original code in this repository is © bigfoot-888 2026. All Rights Reserved. Use is permitted for personal, research, or educational purposes only. Redistribution or commercial use is prohibited without explicit written permission.

Model Weights & LLM Logic: Use of the Llama 3.2 components is subject to the Llama 3.2 Community License Agreement (see LICENSE).

Third-Party Dependencies: This project utilizes several open-source libraries (e.g., PyTorch, OpenCV, gTTS). Users are responsible for complying with their respective licenses (MIT, BSD, etc.).

For the full legal text, including the Llama 3.2 Community License and the breakdown of third-party attributions, please refer to the LICENSE file.

## Author

David Xu Hu  
BSc Software Engineering — Universidad Complutense de Madrid

GitHub: https://github.com/bigfoot-888
LinkedIn: www.linkedin.com/in/david-xu-hu-bb8abb350
