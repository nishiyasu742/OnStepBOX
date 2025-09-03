# OnStepBOX

For the past few years, I have been enjoying astronomical observations by connecting OnStep with the SHC (Smart Hand Controller) online. However, I found it inconvenient to use two separate devices during observing sessions. To address this, I set out to combine both functions into a single unit.  

About two years ago, I succeeded in merging them, and since then I have been using the combined device—what I call **OnStepBOX**—for my personal observations. In practical use, I have not experienced any problems, so I decided to make the design public.  

I am not an electronics expert, so if you notice any issues or improper parts of the circuit, I would greatly appreciate your feedback.  

## Hardware Notes

- The case is made by milling an off-the-shelf plastic enclosure  
  (Manufacturer: **TAKACHI Electric Enclosure Co., Ltd.**, Product No.: **LC135-H-N-W**,  
  [Product Page](https://www.takachi-enclosure.com/products/detail/LC135-H-N-W)).  
- The circuit design was created using the free version of Eagle (limited to 10 cm × 10 cm).  
- The LCD is mounted separately on another PCB.  
- This circuit currently uses an **ESP-32 development board**. A prototype using the **ESP-WROOM-32** module is under testing, and once it operates successfully, it will also be released.  

## Connections

- **OnStep and motors** are wired through RJ45.  
- **Autoguiders (e.g., M-GEN)** are connected using RJ11 modular cables.  

Although I was initially concerned about driving the motors with modular cables, using larger jacks would not fit within a single enclosure, so I adopted this approach. In operation:  

- Motor current during sidereal tracking: ~0.3 A  
- Motor current during GoTo slewing: ~0.9 A  

So far, no overheating or other issues have occurred.  

## Included Files in This Repository

This repository contains all the resources needed to reproduce or modify the **OnStepBOX**:

- 📷 **Images**: Exterior and interior photos of the assembled device  
- 🛠️ **G-code**: CNC milling data required for case processing  
- 📐 **Eagle Files**: Circuit schematic and board layout created with Eagle (free version, 10 × 10 cm limit)  
- 🗂️ **Gerber Files**: Ready-to-fabricate PCB production data  

## Conclusion

The **OnStepBOX**, which combines OnStep and SHC in one case, has proven to be very convenient.  

## Acknowledgment

Finally, I would like to express my deepest respect and gratitude to Mr. Howard Dutton for providing the magnificent OnStep system.  

## Contact

If you have questions or find any issues, please feel free to contact me via Groups.io or other channels.  

— NEWEVI  
