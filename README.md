# Klipper configs

1. install KAMP - https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging
2. Clone this directory
   ```
   cd ~/printer_data/config
   git clone git@github.com:brabijan/klipper-configs.git
   cp klipper-configs/example-printer.cfg printer.cfg
   mkdir nozzles
   cp klipper-configs/example-nozzle.cfg nozzles/e3dv6-0.4.cfg
   ```
3. use macros PRINT_START and PRINT_END in your slicer
4. enable labeling objects in slicer
5. enable object processing in moonraker.conf
   ```   
   [file_manager]
   enable_object_processing: True
   ```
6. enjoy!
