<h1>
  Thermal Camera
</h1>
A compact, low-cost thermal imaging solution built for diagnostic, repair, and monitoring applications in electronics, industrial safety, and embedded systems. Unlike commercial thermal cameras that are often expensive, this DIY thermal imager is designed using readily available and affordable components, making it accessible for students, hobbyists, and engineers.

Thermal cameras play a critical role in detecting temperature anomalies, benchmarking heat performance, and assisting in electronic hardware debugging. Commonly used in defense, predictive maintenance, and the repair industry, thermal imaging enables faster and safer identification of faults such as short circuits or overheating components. Our project aims to replicate these capabilities at a fraction of the market cost.

<h2>Project Workflow </h2>

We began by understanding the working principles of thermal cameras and the core requirements of a low-cost system. The MLX90640 thermal sensor was selected for its high sensitivity and compact resolution, while the 2.4” TFT display offered a visually rich and user-friendly interface.

We wrote firmware from scratch to handle thermal data acquisition, color mapping, and display control using an ESP32 microcontroller. All SPI and I2C communication protocols were manually configured and tested for stability. We then implemented SD card image storage and added support for selectable color palettes and refresh rates.

The enclosure and power management were developed in parallel. A custom battery management system was integrated to allow portability, and the housing was designed to be compact yet thermally stable. The complete schematic and PCB were designed in KiCad.

<h2>
Features:
</h2>

- Image Sensor Resolution: 32×24 pixels
- Field of View (FoV): 55° × 35°
- Temperature Measurement Range: -40°C to 300°C
- Operating Temperature Range: -40°C to 85°C
- Adjustable Refresh Rate: 4 Hz to 32 Hz
- Color Palettes: 10 selectable thermal color schemes
- Display: 2.4" TFT screen with 320×240 resolution
- Storage: Supports saving thermal images to SD card
- Power: Built-in rechargeable battery with charging circuit



<h2>Schematic</h2>

![WhatsApp Image 2025-06-22 at 16 25 18](https://github.com/user-attachments/assets/65ad85ee-184b-42cb-ac40-4695d1b9c40d)

<h2>PCB Layout </h2>

![pcb1](https://github.com/user-attachments/assets/de7cf788-f19d-4a72-8f52-c36841873612)
![pcb2](https://github.com/user-attachments/assets/67eb05c0-93dc-49ad-bdf6-afdffa7c7f62)
![pcb3](https://github.com/user-attachments/assets/4c519ef6-7281-4e9a-af50-b7df18d0dccb)

<h2>Setup</h2>

![WhatsApp Image 2025-06-22 at 16 26 38](https://github.com/user-attachments/assets/1e8768ed-6d3a-4f66-9dd8-91ff530ea7c5)

<h2> Working Video </h2>

https://github.com/user-attachments/assets/c0b89b00-765c-46c9-96d5-a79226db0dfd

https://github.com/user-attachments/assets/fa7a4603-ffcd-4ff7-a3ee-2d5423cac2e8




<h2>Applications</h2>

- Electronics repair and thermal diagnostics
- Industrial safety monitoring
- DIY electronics and embedded systems projects
- Educational use for temperature visualization

<h2>Challenges Faced</h2>
 
- Occasional screen lag during rapid refresh.
- Difficulty in storing data reliably on the SD card due to SPI timing issues.
- Display showed only half-screen output initially, resolved through pin remapping and timing adjustments.

<h2>Team Members</h2>

- Abhey Garg (EE23BTECH11202)
- Chirag Garg (EE23BTECH11206)
- Prashant Maurya (EE23BTECH11218)
- Preetam (EE23BTECH11221)
- Sasa Mardi (EE23BTECH11222)

