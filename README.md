# Geometry-Dash-ALL-VERSIONS-sprite-sheets-converter

A little program that converts Geometry Dash sprite sheets from any version format to the version you pick. It works in reverse too, so you can go up or down. Every version from 1.9 up to the newest one is supported.

Handy if you're making texture packs and don't feel like redoing the same sheets for every version by hand.

## Preparation
- Go to the [releases page](https://github.com/SzczupakUser/Geometry-Dash-ALL-VERSIONS-sprite-sheets-converter/releases)
- Pick a version of the program and download the .zip file
- Open the folder where you downloaded it and unzip it

(It's an .exe, so you'll need Windows.)

## Usage
- Open the converter folder and run the .exe file
- A window should pop up on your screen
  <details><summary>Screenshot</summary><img width="825" height="768" alt="A" src="https://github.com/user-attachments/assets/12effa7f-bc62-4df0-8ebc-6ef87edc9e46" /></details>
- On the Conversion mode tab you can choose whether you want to convert one file or a bunch of them at once
  <details><summary>Screenshot</summary><img width="825" height="768" alt="B" src="https://github.com/user-attachments/assets/9b9758ff-225e-4940-ae5e-e4262ff62d6a" /></details>
- Pick the files you want to convert in the biggest tab, Selected PNG files. Click the "Select PNG file" button, find the file on your disk, and its name should show up in the list
  <details><summary>Screenshot</summary><img width="825" height="768" alt="C" src="https://github.com/user-attachments/assets/6a625016-d718-43c4-a984-013b1f7319a2" /></details>
- Now choose the versions. Set "Source version" to the version your file is currently in, then set your target version to whatever you want it converted to
  <details><summary>Screenshot</summary><img width="825" height="768" alt="D" src="https://github.com/user-attachments/assets/c36ca37b-a1ab-42be-82a2-023c6fe206d1" /></details>
- Finally, hit the "Convert selected files" button. Your converted sheets will land in the "Converted" folder
  <details><summary>Screenshot</summary><img width="825" height="768" alt="F" src="https://github.com/user-attachments/assets/8093ff8a-16c7-4416-9687-b40e9138c90b" /></details>

## Troubleshooting

**Got "None of the selected sheets can be converted"?**
Your file name probably doesn't match the name of the .plist file, so the program can't figure out which sheet it is. No worries, you can fix it manually:
- Use manual plist selection
- In "Manual source plist", select a plist that references your sheet
- Then pick a manual target plist, which is the same sheet but in the version you want to convert to
  <details><summary>Screenshot</summary><img width="825" height="768" alt="E" src="https://github.com/user-attachments/assets/5ea475c3-db3f-410a-a0f9-2644a93f8def" /></details>

**Still stuck or found a bug?**
Open an issue on the [Issues tab](https://github.com/SzczupakUser/Geometry-Dash-ALL-VERSIONS-sprite-sheets-converter/issues) and tell me what happened (a screenshot helps a lot).

### Credits
- Program made by SzczupakUser (Szczupak)
- Credits to RobTop for plist from Geometry Dash
- I made this all by myself, so there's no one else to credit here :)
