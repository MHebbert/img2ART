# img2ART
A flexible image processing tool using OpenCV for selective blurring, gamma correction, and custom cross-hatching patterns. Features interactive region selection, dynamic threshold adjustment with trackbars, and saving/loading settings. Ideal for generating artistic sketches and stylized visual effects with reproducible results.

Features

Interactive Region Selection:
Use the mouse to select a specific region of the image for focused processing.

Customizable Image Processing:
Apply grayscale conversion, gamma correction, and Gaussian blur selectively based on the chosen region.

Dynamic Threshold Adjustment:
Modify various thresholds in real-time with trackbars, affecting shading, edge detection, and cross-hatching levels.

Cross-Hatching Patterns:
Generate detailed cross-hatching patterns on the processed image with configurable line directions, spacing, and threshold-based exclusions.

Save and Load Settings:
Store your customized settings in a JSON file for easy reuse and consistent results across different images.

Installation
Clone this repository:
git clone 

Install the required dependencies:
pip install 

Usage
Run the Script:
Use the main(image_path) function with your desired image.

Select a Region:
A window will open allowing you to select a region on the image using your mouse.

Adjust Parameters:
Use the interactive trackbars to adjust processing thresholds and observe changes in real-time.

Save Settings:
Press 'h' to save your current settings to a JSON file and close the interface.

Recreate Results:
Use saved settings to apply the same processing to other images or recreate results with the recreate_image_with_saved_thresholds(image_path, settings_path) function.

Example
1. Original Image
   
![image](https://github.com/user-attachments/assets/02dfa442-ec42-46a4-8e93-19ee3ceb4dcc)

2. Selected Region

![image](https://github.com/user-attachments/assets/8b1662fb-bbb9-43f4-8ac4-bbc4cec7541b)


 3.a Parameter Control

![image](https://github.com/user-attachments/assets/5f8b5fe7-f1b9-4e67-ad75-de20093ba366)

 3.b Current Settings

![image](https://github.com/user-attachments/assets/33130184-df43-4170-8a26-003af7d9bba8)


4. Cross-Hatching Result
   
![image](https://github.com/user-attachments/assets/832abf86-4514-4fba-8c58-b0f9c74ecac7)

5. Save Processed Image



Contributions are welcome! Please submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.
