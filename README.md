# DOF Calculator  
*Final project for the Building AI course*  

## Summary  
A fast, privacy-first Depth of Field (DOF) calculator for photographers and filmmakers.  
Runs entirely in your browser, works offline, and helps visualize how aperture, focal length, focus distance, and sensor size affect depth of field and framing — no data ever leaves your device.

---

## Background  
Depth of field control is one of the key elements in visual storytelling, yet most existing calculators require an internet connection or display ads.  
When shooting in remote locations or studios without connectivity, this can be a real issue.

**This project solves the problem by providing:**
- A fast, accurate DOF calculator that works fully offline  
- Total privacy — no tracking, no cloud storage, no analytics  
- A simple interface optimized for both mobile and desktop browsers  

**Motivation:**  
The need came from my own production work — I often needed to check DOF quickly on set without third-party services.  
This project helps creators plan and shoot independently, with privacy and reliability.

---

## Data and AI techniques  
The current version is purely physics-based and does not rely on external datasets.  
All calculations are performed locally in JavaScript using standard optical formulas involving:  
- Aperture (f-stop)  
- Focal length  
- Focus distance  
- Sensor size  

**Possible future AI extensions:**
- EXIF-based AI suggestions for ideal DOF settings  
- Machine learning analysis of lens sharpness and focus zones  
- Depth-map estimation from sample photos  

---

## How it’s used  
**Intended users:**
- Photographers and filmmakers  
- Students and teachers of optical theory  
- Pre-production and storyboard planners  

**Benefits:**
- Works anywhere — offline and privacy-first  
- Simple and accessible interface  
- No installation or data collection required  

<img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Depth_of_field_diagram.svg" width="400" alt="Depth of field illustration">

---

## Challenges  
**Limitations:**
- Does not simulate lens character, bokeh, or sensor noise  
- Cannot replace creative judgment or real test shots  
- AI features are conceptual at this stage  

**Ethical aspects:**  
No user data is collected, transmitted, or stored.  
The project is fully privacy-safe and open for educational use.

---

## What next  
**Potential future development:**
- AI-assisted DOF simulation with visual focus previews  
- Automatic EXIF analysis and recommendations  
- Integration with photo metadata tools (Lightroom, Capture One, etc.)

Further development would benefit from collaboration with optical engineers, photographers, and the open-source AI community.

---

## Acknowledgments  
Created by **Veijo “Wexi” Ruotanen / Moodfilms**  
[ruotanen.com](https://ruotanen.com)
