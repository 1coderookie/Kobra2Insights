<link rel=”manifest” href=”docs/manifest.webmanifest”>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

---  


# Printer Profiles & Slicers

---

## Printer Profiles

The USB drive shipped with your printer should contain Cura and PrusaSlicer profiles. If you don't have them, you can download them at [Anycubic's support page](https://www.anycubic.com/pages/firmware-software) but I'll list and link to them further below also.  

However, these profiles most likely need individual tweaking. The settings like print speed, retraction settings, extruder and bed temperature etc. also depend on the type of material you want to use (e.g. PLA/ABS/PETG/TPU). But also for the same type of filament material like PLA the settings often need to be adjusted again if you're using filament of a different manufacturer or even just another spool or colour of the same brand.  
There are countless guides about this topic in general, so I'd recommend to dig into it deeper using your preferred sites or specific videos.   

You can always set up your own custom profile in your slicer. Just pay attention to the general machine settings, like the bed size and so on.  
  
??? tip "Set Up Filament Specific Profiles"

    When you're using more than one filament, it's a good idea to set up a profile for each spool of filament you have. So not only for the type of filament (like PLA, PETG etc.), but also for the different manufacturer, the colour and so on. It happens that you have to use slightly different settings even with the same type of filament from the same brand but just when using a different colour of it.   

??? tip "Try PrusaSlicer"  

    Many users seem to get better results when using PrusaSlicer instead of Cura (I personally switched to PrusaSlicer a long time ago and don't use Cura anymore, so I can't really judge it), so maybe give PrusaSlicer a try if you're using Cura.  

  
---

### Official Profiles

The following list links to the specific profiles from [Anycubic's firmware page](https://www.anycubic.com/pages/firmware-software): 
 
 - [PrusaSlicer Profiles](https://drive.google.com/file/d/1xRKTQGgymFw3FAtVjINtNMWzweHxCR1M/view?usp=drive_link)
 - [PrusaSlicer PLA Profiles for V3.0.6](https://drive.google.com/file/d/1ZNOGmGPSo8SZ9BioIqVIY0JSXSWmNQUE/view?usp=drive_link)  
 - [cura Filament Profiles](https://drive.google.com/file/d/170L5J1IZMJ6ZVOkNt4dI0MkcvKeBq_f2/view?usp=drive_link)  

    
---

### Custom Profiles  

Here you'll find links to profiles made by users - if I'm getting aware of them.  

---

## Slicers  
<!--
In the following you'll find some short notes on the most common Slicers, which (imho) are PrusaSlicer, SuperSlicer, OrcaSlicer and Cura.   
I won't go over [Ancubic's slicer](https://www.anycubic.com/pages/anycubic-slicer) at this point though as it's based on PrusaSlicer.  
-->

A slicer is a program you open your STL file with and which needs to be set up with a profile which contain the specific settings for your printer.  
When you open the STL file of the model you want to print, you then adjust some settings for how the printer should print the model (like speed, temperature etc.) and then you "slice" the model for getting the `.gcode` file generated, which then will be taken and processed by the printer.   

The most common Slicers are (imho) PrusaSlicer, SuperSlicer, OrcaSlicer and Cura.  
You'll find many resources online though where you'll find more information about them. There are many comprehensive YouTube videos out there about this topic as well.  

<!--
---
 
### PrusaSlicer, SuperSlicer, OrcaSlicer 
PrusaSlicer (initially based on "Slic3r") and it derivates like SuperSlicer and OrcaSlicer are my personal favourites after using Cura for some time.  

If you need it, you can find [Anycubic's PrusaSlicer Usage Instructions V1.1 here](https://cdn.shopify.com/s/files/1/0245/5519/2380/files/PrusaSlicer_Usage_Instructions_V1.1_EN.pdf?v=1685695259).

Of course all slicers have many functionalities to finetune and control the output - you can even choose between different patterns for the top layer finish. They're all pretty identical overall, yet they differ in certain functions. One of them being worth mentioned is a *handy set of calibration tools that comes with SuperSlicer and OrcaSlicer*. This function actually guides you step by step through the calibration process and allows you to generate calibration models like temperature or retraction towers with individual settings by just a few clicks.  

Make sure to enable the optional "Arachne Engine" (Print Settings -> Perimeters) as it improves the quality of the printed parts. 

---

### Cura  
Cura is probably the most commonly known slicer.  
If you check support page of Anycubic or if you have a look at the content of the microSD card that was shipped with the printer, you'll probably find an *outdated* version of Cura and some printer profiles for it. 
-->

---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

