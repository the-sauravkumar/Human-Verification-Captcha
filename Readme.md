# Image Verification Captcha

This project is an implementation of a human verification system using images. It presents users with a series of image-based challenges to verify that they are human users and not bots.

## Features

- **Bridge Module**: Users are presented with images of bridges and roads. They need to select all the images of bridges while avoiding the roads.
- **Animal Module**: Users are presented with images of various animals. They need to select all the images of cats while avoiding other animals like dogs and calves.
- **Verification**: Once users select the correct images based on the instructions, they can click the "Submit" button to verify their selections.
- **Refresh**: Users can refresh the images if they are unsure or want to try again.

## Components

### Bridge Module

- Users need to select all images of bridges.
- They should avoid selecting images of roads.
- Images are displayed in a grid layout for selection.

### Animal Module

- Users need to select all images of cats.
- They should avoid selecting images of other animals like dogs and calves.
- Images are presented in a grid layout for selection.

### Submit Button

- Users click this button to submit their selections for verification.
- It triggers the verification process to check if the correct images are selected.

### Refresh Button

- Users can click this button to refresh the images and start over if needed.
- It resets the selections made by the user.

## Usage

1. Run the program.
2. Check the "I am not a robot" checkbox to activate the verification process.
3. Select the correct images based on the instructions provided for each module.
4. Click the "Submit" button to verify your selections.
5. If successful, a verification message will be displayed. Otherwise, try again.
6. Use the "Refresh" button to start over if needed.

## Requirements

- Python 3.x
- tkinter library
- PIL library (Python Imaging Library)

## Installation

1. Clone this repository to your local machine.
2. Ensure you have Python installed on your system.
3. Install the required libraries using pip:
4. Run the Python script:

## Contributing

Contributions are welcome! If you have any ideas for improvements or encounter any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
