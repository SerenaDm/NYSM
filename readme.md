# Readme

The main folder of the dataset contains two sub-folders, one for each gender named “Female” and “Male”, a “Mesh” folder, an `Avatar_Parameters.txt` file, and a `readme.txt` file.

## Avatar_Parameters.txt

This txt file contains the list of the avatar parameters used to build the different avatars. The parameters are expressed in integer numbers and refer to the values in HumanGen3D used to build a given trait. It also contains the HEX value of eye color, hair color, and clothes used for building the avatar meshes in Unity, and the values of the hair, brows, and eyelashes thickness for particle conversion.

## Readme.txt

This file contains the organization of the dataset and specifies the type of format the avatars are created in.

## Female Subfolder

Contains all the avatars labeled as female. Each different avatar is indicated by a short code in the following format: `FD5S`. 
- The first letter indicates the gender.
- The second letter refers to the facial shape.
- The third letter refers to the height value.
- The last letter refers to the body volume.

For specific parameter values, please refer to the `Avatar_Parameter.txt`. All the avatars are in `.fbx` format, directly importable into Unity. For each avatar, a `.xlsx` file is present, which contains the ratings for the given avatar.

## Male Subfolder

Contains all the avatars labeled as male. Each different avatar is indicated by a short code in the following format: `MD6S`.
- The first letter indicates the gender.
- The second letter refers to the facial shape.
- The third letter refers to the height value.
- The last letter refers to the body volume.

For specific parameter values, please refer to the `Avatar_Parameter.txt`. All the avatars are in `.fbx` format, directly importable into Unity. For each avatar, a `.xlsx` file is present, which contains the ratings for the given avatar.

## Mesh Folder

This folder contains Unity-compatible meshes of the `.fbx` avatar files. Available meshes include trousers, shoes, sweaters, skin, eyes, hair, lashes, and brows. Each mesh can be directly dragged and dropped onto the corresponding part of the avatar.
