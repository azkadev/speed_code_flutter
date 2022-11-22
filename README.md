# Speed Code Flutter

Speed Code Flutter, experiment make video with flutter
 

https://user-images.githubusercontent.com/82513502/203358935-e8501a5a-d458-400d-a8ca-bb396d9773e3.mp4


---
<p align="center">
    <a href="https://github.com/azkadev">
        <img src="https://telegra.ph/file/e90bdeab8390b8c0d9df2.png" alt="Specta"
            width="312"
            height="312">
    </a>
    <br>
    <a href="https://youtube.com/c/galaxeus">
        <img
            src="https://raw.githubusercontent.com/azkadev/azkadev/main/assets/images/powered_galaxeus.png"
            alt="galaxeus"
            width="350"
            height="80"
        >
    </a>
    <br>
    <b>Author Azkadev 🔥</b>
    <br>
</p>
 
### About this

Repo ini hanya project biasa, dan hanya sebuah testing kalau flutter gak cuma bikin app tapi bikin video apapun tergantung pilot

### Support
> Tolong beri saya dukungan dengan cara follow up semua social media saya / donate di github ya

### Social Media Me

1. [Youtube](https://youtube.com/@azkadev)
2. [Telegram](https://t.me/azkadev)

---

### Development

1. Clone source code 

    ```bash
    git clone https://github.com/azkadev/speed_code_flutter.git
    cd speed_code_flutter
    ```

2. Download package

    ```bash
    flutter pub get
    ```

3. Running

    ```bash
    flutter run
    ``` 

### Render

```bash
ffmpeg -i ./result/%d.png -c:v libx264 -r 60 ./screenshot/result.mp4
```

```bash
ffmpeg -i ./result/%d.png -pix_fmt yuva420p -filter:v fps=60 ./screenshot/result.webm
```
