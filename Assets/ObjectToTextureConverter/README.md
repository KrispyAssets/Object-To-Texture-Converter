# Object to Texture Converter for Unity

## Description

The Object to Texture Converter is an advanced Unity Editor tool designed for game developers and digital artists. It simplifies converting 3D models into 2D textures, offering a range of customizable settings. Whether for game assets, UI elements, or any creative project, this tool provides an efficient solution for capturing the visual essence of 3D objects in 2D form.

## Features

- **Automated Setup**: Automatically configures cameras and a capture target upon tool initialization.
- **Format Support**: Converts objects into PNG or JPG textures.
- **Resolution Customization**: Offers a wide range of texture resolutions from 1x1 to 8192x8192 pixels.
- **Enhanced Clarity**: Features anti-aliasing and anisotropic filtering settings for superior texture quality.
- **Precise Capturing**: Includes auto-centering and orientation adjustments for accurate captures.
- **Visual Guidance**: Utilizes gizmos for real-time alignment and area visualization.

## Getting Started

### Using the Included Scene

For immediate use, open the provided "ObjectToTextureConverterScene". This scene comes pre-configured with all necessary components.

### Setting Up in Your Scene

1. **Create the Converter**: Navigate to `Window > Custom Tools > Create Object To Texture Converter`. A new converter GameObject, along with required components, will be created in your scene.

2. **Prepare the Object**:
   - Make the 3D object you wish to convert a child of the automatically created Capture Target GameObject.
   - Adjust the position of the object as needed within the Capture Target's bounds.

3. **Adjust Settings**:
   - Configure the conversion settings (e.g., resolution, format) in the converter's Inspector.

4. **Convert and Save**:
   - Specify a Save Path and Texture Name.
   - Click "Convert" to generate your texture, which will be saved to the designated location.

## Conversion Requirements

- Ensure a save path is selected within the `Assets` directory.
- Provide a unique name for the texture to avoid overwriting existing files.

## Tips for Effective Use

- **Inspector Locking**: Click the lock icon in the Inspector to keep the converter's settings accessible while working on other parts of your scene.
- **Dual Inspectors**: Open a second Inspector window for easier management of settings (Right-click on the Inspector tab > Add Tab > Inspector).

## Contributing

We welcome contributions to make the Object to Texture Converter even better. Feel free to suggest improvements.

## Contact

For questions, support, or feedback, please contact us at KrispyAssets@gmail.com.