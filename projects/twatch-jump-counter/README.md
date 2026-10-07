# Fault-tolerant jump counter on T-Watch

[View the project page](https://jadhavshubham560.github.io/#project/twatch-jump-counter)

Team: Shubham Jadhav and Shanal Orin Dsouza. Coursework at Technische Hochschule Brandenburg; presentation dated 14 January 2026.

The application counts jumps from Z-axis IMU acceleration, tracks workout time and provides start, pause, resume and reset controls. A 15-second inactivity timeout automatically pauses the workout. The presentation discusses Hanmer’s Minimize Human Intervention and Correcting Audits patterns.

## Project material

- [Demo 1: interface and controls](demo-1.mp4)
- [Demo 2: jump-counting demonstration](demo-2.mp4)
- [Presentation PDF](presentation.pdf)
- [PowerPoint with both embedded videos](presentation.pptx)
- [Arduino source archive](arduino-source.zip)
- [Watch interface photo](watch-interface.png)

Student numbers and private author metadata have been removed from the public presentation copies. The original project files are preserved locally.

## Source and limitations

The ZIP contains the supplied Arduino sketch and supporting headers. It requires the T-Watch libraries and hardware; it has not been compiled or tested on hardware as part of this upload.

Single-axis sensing can miss jumps or count arm movements when the watch tilts or is worn loosely. The design has one IMU and no sensor redundancy or orientation compensation. Individual team responsibilities are not assigned here.
