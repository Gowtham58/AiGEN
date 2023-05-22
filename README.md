# AiGEN
 This project aims to develop an application that generates images and music based on user input using pre-trained deep learning models through an Application Programming Interface (API). The application will allow users to input text and the pre-trained deep learning models will generate a corresponding image and music track. 
## To Run on Locally
1. Download the repository or clone it locally
2. Create a python virtual environment using ```python -m venv```
3. Once Created Activate the virtual environment
4. Install the packages from the requierments.txt
5. Run the application using ```flask --app aigen run```

## PROPOSED SYTEM FOR THE WEB APPLICATION
The system is divided into two parts: Getting the input from the user, Display the generated output to the user. 

The music and image is generated using publicly available __pre-trained models__ through Inference API from __HuggingFace__.

Image Generating Model: __Stable Diffusion__ is a latent text-to-image diffusion model capable of generating photo-realistic images given any text input

Music Generating Model: __Riffusion__ is a latent text-to-image diffusion model capable of generating spectrogram images given any text input. These spectrograms can be converted into audio clips.


