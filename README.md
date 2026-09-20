# Gateway-Galaxy



Demo video. Click to open in YouTube

[![Gateway Demo](https://img.youtube.com/vi/haEn1a1Hde8/0.jpg)](https://www.youtube.com/watch?v=haEn1a1Hde8)





## Water Shader
<img width="2559" height="1439" alt="Screenshot 2026-09-19 173954" src="https://github.com/user-attachments/assets/81a13ddc-1941-4d65-8b7d-3de29a3579c0" />


The water effect was recreated using two transparent scrolling noise textures added together.

<img width="1380" height="693" alt="Screenshot 2026-09-19 175819" src="https://github.com/user-attachments/assets/6c569023-bac0-4ceb-a07c-9722aba8620b" />


Alpha clipping is then used to remove parts of the combined noise texture with moderate levels of transparency. 
<img width="1092" height="693" alt="Screenshot 2026-09-19 180251" src="https://github.com/user-attachments/assets/2151dea9-0b28-4393-83fd-ee0747c0f854" />


This leaves only the lowest and highest areas of transparency to be visible, creating the illusion of sunlight reflecting off the water.
Vertex colours are placed at the perimeter of the mesh to add the effect of water foaming/splashing up against the edges.
<img width="2559" height="1439" alt="Screenshot 2026-09-19 174005" src="https://github.com/user-attachments/assets/16e0036c-a5d0-4f3e-b8d9-11c3ae81cc09" />

Lastly, an opaque dirt/rock texture is placed beneath the water shader and distorted using another noise texture. This makes the dirt texture exhibit a wavy distortion, emulating light refracting through the water.

<img width="1370" height="619" alt="Screenshot 2026-09-19 181320" src="https://github.com/user-attachments/assets/a41879e3-9726-455a-91aa-ac04950dd7fb" />








### Disclaimer
This is an unofficial project created solely for educational purposes. All 3D assets, textures, and sounds belong to Nintendo.
