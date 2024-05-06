# Object to Icon Converter for Unity

## Description

The Object to Icon Converter is an advanced Unity Editor tool designed for game developers and digital artists. It simplifies converting 3D models into 2D icons, offering a range of customizable settings. Whether for game assets, UI elements, or any creative project, this tool provides an efficient solution for capturing the visual essence of 3D objects in 2D form.

## Features

- **Automated Setup**: Automatically configures cameras and a capture target upon tool initialization.
- **Automated Cleanup** Automatically clean up your scene once you have finished capturing your icons.
- **Format Support**: Converts objects into PNG or JPG textures.
- **Resolution Customization**: Offers a wide range of texture resolutions from 1x1 to 8192x8192 pixels.
- **Enhanced Clarity**: Features anti-aliasing and anisotropic filtering settings for superior texture quality.
- **Precise Capturing**: Includes auto-centering and orientation adjustments for accurate captures.
- **Unlimited Capture Bounds** Capture objects of any size with ease.
- **Visual Guidance**: Utilizes gizmos for real-time alignment and area visualization.

## Getting Started

- **Video showcase can be found here**
	- https://www.youtube.com/watch?v=wFBMWRX286A

- **Navigate to `Tools > Icon Converter` for Editor Tools.**
	- `Tools > Icon Converter > Load Converter Scene` brings you to the provided converter scene.
	- `Tools > Icon Converter > Create Converter` will automatically set up the converter in your scene.
	- `Tools > Icon Converter > Destroy Converter` will destroy the converter and all components created alongside it.

### Using the Included Scene

For immediate use, open the provided "Object Converter" scene. This scene comes pre-configured with all necessary components.
Navigate to `Tools > Icon Converter > Load Converter Scene` for quick access.

### Setting Up in Your Scene

1. **Create the Converter**: 
	- Navigate to `Tools > Icon Converter > Create Converter`. A new converter GameObject, along with required components, will be created in your scene.

2. **Disable any Cameras in your scene.**:
	- Ensure you have no other Cameras displaying in your scene as this may cause issues.

3. **Adjust the lighting.**:
	- Configure the lighting in your scene to optimally achieve your desired outcome.

4. **Prepare the Object**:
   - Make the 3D object you wish to convert a child of the automatically created Capture Target GameObject.
   - Adjust the position of the object as needed within the Capture Target's bounds.

5. **Adjust Settings**:
   - Configure the conversion settings (e.g., resolution, format) in the converter's Inspector.

6. **Convert and Save**:
   - Specify a Save Path and Icon Name.
   - Click "Convert" to generate your texture, which will be saved to the designated location.

7. **Destroy the Converter**:
	- After you are finished converting all of your assets, navigate to `Tools > Icon Converter > Destroy Converter` to clean up your scene.
	- NOTE: This will destroy all child objects under any of the converter’s components.

## Conversion Requirements

- Ensure a save path is selected within the `Assets` directory.
- Provide a unique name for the texture to avoid overwriting existing files.

## Tips for Effective Use

- **Inspector Locking**: Click the lock icon in the Inspector to keep the converter's settings accessible while working on other parts of your scene.
- **Dual Inspectors**: Open a second Inspector window for easier management of settings (Right-click on the Inspector tab > Add Tab > Inspector).

## Contributing

We welcome contributions to make the Object to Icon Converter even better. Feel free to suggest improvements.

## Contact

For questions, support, or feedback, please contact us at KrispyAssets@gmail.com.
