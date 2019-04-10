# VoicePrint

## 1. Program Description

VoicePrint ([Algorithm of Algorithms] (http://blog.csdn.net/c395565746c/article/details/6210920)) is a text-independent voiceprint recognition algorithm verification program based on Gaussian mixture model.



The features of VoicePrint are:
 
- Speech feature vector: using MFCC coefficient (Meir cepstrum coefficient)
- Pattern matching model: using the GMM model (Gaussian hybrid model)

## 2. Last updated

**VoicePrint V1.1 official version**

- Repairing the modeling and recognition process The intermediate voice dump temporary files may not be deleted.
- Change the number of voice segments from 3 to 4, and change each voice to 50 frames of fixed length.
- The GMM model data dump file structure is fine-tuned and is no longer compatible with versions prior to V1.1.

**VoicePrint V1.0**

- Added the ability to export GMM model data to a file and import files into the program.
- Modified the recognition range value.
- Modified the voiceprint recognition algorithm to allocate memory to a dynamic array.

## 3. Warm reminder

This program is developed for the course experiment verification, and the voiceprint recognition algorithm realized is inevitably wrong and inappropriate!
   
Reminder: Because this program is a simple verification program, it is recommended not to use the voiceprint recognition code in this program directly in the official project.

### TODO:

- Volume normalization (no time, improve recognition rate)
- Remove background noise (nothing, improve recognition rate)
- iOS Demo (2016)
- English notes and README (2016)

## 4. Contributors

- [Dake](https://github.com/dake/)


**If you find this project useful, support my other projects:**

- [Support my project Thor] (https://github.com/PixelCyber/Thor)
