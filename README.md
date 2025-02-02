# 📄 Overview

This project focuses on Image Forgery Detection, exploring methods to identify and analyze manipulated digital images. It covers various types of forgeries, detection techniques, and applications relevant to forensics, media verification, and security systems.



ARCHITECTURE
![image](https://github.com/user-attachments/assets/d1b531da-2cfb-4ef0-9891-f6c244aa7b39)


# 🚀 Features

   - Detects common types of image forgery:
    
-    Copy-Move Forgery
    
   - Splicing
    
  -  Retouching
 -   Implements both active and passive detection methods
    
   - Analyzes inconsistencies in:
    
  -  Pixel data
    
  -  Image format metadata
    
 -   Camera source data
    
 -   Physical properties (lighting, shadows)

# 🧪 Techniques Used

-    Pixel-based Analysis
    
 -   Format-based Detection
    
  -  Camera-based Forensics
    
 -   Lighting and Shadow Analysis

# 📊 Applications

-    Digital Forensics
    
 -   Media and News Verification
    
  -  Identity Fraud Detection
    
  -  Legal Evidence Authentication

📂 Project Structure    

![image](https://github.com/user-attachments/assets/c9d416d4-86b1-4cb5-b8ae-6c386228a570)

# 📈 Sample Results

Detection highlights forged regions in red.

Metadata inconsistencies flagged in logs.


  ![image](https://github.com/user-attachments/assets/c9037034-df82-48a4-94dd-d0ef7d287a53)


The image above illustrates the process of detecting forgery in digital images using image processing techniques. Here’s an explanation of the workflow depicted:

1. Original Image (Left)
This is the input image which appears to be an aerial view of a parking lot with several cars parked in designated spaces.
At first glance, the image looks normal without any obvious signs of tampering.
2. Forgery Detection Process (Middle Arrow)
The arrow represents the application of image forgery detection algorithms.
Techniques like copy-move detection, pixel-based analysis, and pattern recognition are used to analyze the image for inconsistencies.
The algorithm scans for duplicated regions, unusual pixel structures, and metadata discrepancies.
3. Detected Forgery (Right Image)
In the processed image, forged regions are highlighted:
The green-shaded car indicates a copy-move forgery, where a car has been duplicated from another part of the image and pasted here.
The red-shaded car with an orange spot indicates another tampered region, possibly identifying an area where the object was inserted or altered.
The detection algorithm marks these regions based on inconsistencies found in texture, color distribution, or structural alignment.
Key Points in Forgery Detection:
Copy-Move Forgery Detection: Identifies identical regions copied and pasted within the same image.
Color and Lighting Inconsistencies: Algorithms check if shadows, lighting direction, and object placement are consistent.
Metadata Analysis: Examines image file data for signs of manipulation.
