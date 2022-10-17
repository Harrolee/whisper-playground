<p align="center">
  <img width="60px" src="https://user-images.githubusercontent.com/6180201/124313197-cc93f200-db70-11eb-864a-fc65765fc038.png" alt="giant microphone"/>   <br/>
  <h2 align="center">Whisper Playground</h2>
  <h6 align="center">Instantly build speech2text apps in 99 languages using OpenAI's Whisper</h6>
</div>


https://user-images.githubusercontent.com/6180201/194214280-3a4106d5-53cf-4463-ba0e-201d8e1b0c0e.mp4



# Setup
1. Whisper requires the command-line tool [`ffmpeg`](https://ffmpeg.org/) to be installed on your system, which is available from most package managers:
```bash
# on Ubuntu or Debian
sudo apt update && sudo apt install ffmpeg

# on Arch Linux
sudo pacman -S ffmpeg

# on MacOS using Homebrew (https://brew.sh/)
brew install ffmpeg

# on Windows using Chocolatey (https://chocolatey.org/)
choco install ffmpeg

# on Windows using Scoop (https://scoop.sh/)
scoop install ffmpeg
```

2. Clone or fork this repository
3. Install the backend and frontend environmet `sh install_playground.sh`
4. Run the backend `cd backend && source venv/bin/activate && flask run --port 8000`
5. In a different terminal, run the React frontend `cd interface && yarn start`

# License
This repository and the code and model weights of Whisper are released under the MIT License.
