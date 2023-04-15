## Requirements

- Clone the repository:

```
git clone
cd
```

- FFmpeg is required to combine the audio and the silent generated videos. Please check [FFmpeg](http://ffmpeg.org/download.html) for installation. For Linux users,  you can also:

```
sudo apt-get install ffmpeg
```

- Install the dependences:

```
pip install -r requirements.txt
```



## Demo

- Download the pre-trained models and data from [Google Drive](https://drive.google.com/drive/folders/1sHc2xEEGwnb0h2rkUhG9sPmOxvRvPVpJ?usp=sharing) to the `data` folder.  Five subjects data are released (May, Obama1, Obama2, Nadella and McStay).

- Run the demo:

  ```
  python demo.py --id Nadella --driving_audio ./data/Input/welcome.mp3 --device cuda
  ```

  Results can be found under the `results` folder.


  
- **For the refernce of the project please check issue (https://github.com/YuanxunLu/LiveSpeechPortraits).**

  
