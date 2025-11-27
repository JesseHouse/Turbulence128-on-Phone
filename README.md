# Turbulence128-on-Phone

**World-first real-time 128³ 3D pseudospectral turbulence simulation running natively on an Android phone**  
- Pure Python + NumPy + PyTorch  
- Zero external libraries, no CUDA, no GPU  
- ~1.17 FPS on Snapdragon 8 Gen 2 (stock cooling)

### Full notebook (complete code + live outputs + interactive plots)
[T128-on-Phone.ipynb](T128-on-Phone.ipynb)  
Click the green **Open in Colab** button at the top of the notebook to run it instantly in your browser – no install required.

### Real phone run – 400 steps @ 1.17 FPS
![400 steps @ 1.17 FPS on phone](https://github.com/JesseHouse/Turbulence128-on-Phone/raw/main/phone_run_400_steps_1.17fps.jpg)  
*(upload your screenshot and name it exactly `phone_run_400_steps_1.17fps.jpg` or change the filename above)*

### Run it yourself on Android (Termux)
```bash
pkg update
pkg install python python-numpy pytorch ffmpeg libjpeg-turbo -y
git clone https://github.com/JesseHouse/Turbulence128-on-Phone
cd Turbulence128-on-Phone
python turbulence_128_phone.py

320³ already in progress…   If this broke your brain, drop a star or fuel the chaos:   https://paypal.me/jessehouse  Chaos on a phone. 2025.
