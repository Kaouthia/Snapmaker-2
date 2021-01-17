# Snapmaker 2.0 A350 Files

This is my archive of files for the Snapmaker 2.0 A350. At the moment, that primarily means my Cura 3D printing profiles. In the future, I may add profiles for other slicers, and possibly CNC and laser-related files, as well as potential upgrades you might want to print to improve the features of your Snapmaker 2.0.

All my final releases will go into this repository, so be sure to keep checking back for updates - and I will be updating the Cura files as I keep printing, testing and tweaking.

## Snapmaker 2 Cura Settings & Profiles

Currently, there are screenshots of machine settings for the Snapmaker 2.0 A350 for Cura 3.6 and Cura 4.8 as well as downloadable cura settings profiles for both versions. There is a video (coming soon!) to go along with these profiles as well.

- [Download the profiles for Cura 3.6 and 4.8](https://github.com/Kaouthia/Snapmaker-2/archive/main.zip)
- [Watch the SM2.0 A350 Cura video on YouTube](https://youtube.com/johnaldred) *(Coming soon)*

Here are the machine settings for Cura 4.8 for the Snapmaker 2.0 A350. For the A350, the X, Y and Z dimensiuons are 320mm, 350mm and 330mm respectively. For the A250, those dimensions are 230mm, 250mm and 235mm. For the A150 they are 160mm, 160mm and 145mm.

![Snapmaker 2.0 A350 Settings](https://github.com/Kaouthia/Snapmaker-2/blob/main/Cura%20Profiles/Cura%204.8.x%20Profiles/machine-settings.jpg?raw=true)

So that you don't have to risk making typos by manually typing out the start and end G-code, here are a pair of text files that you can just copy+paste straight into Cura. These are for the Snapmaker 2 (***don't*** try to use these with the original Snapmaker).

- [Snapmaker 2.0 Start G-code](https://github.com/Kaouthia/Snapmaker-2/blob/main/Cura%20Profiles/start-g-code.txt)
- [Snapmaker 2.0 End G-code](https://github.com/Kaouthia/Snapmaker-2/blob/main/Cura%20Profiles/end-g-code.txt)

You'll also need to dial in the extruder settings to change the filament diamenter from the Cura default of 2.85mm to 1.75mm.

![Snapmaker 2.0 A350 Extruder Settings](https://github.com/Kaouthia/Snapmaker-2/blob/main/Cura%20Profiles/Cura%204.8.x%20Profiles/extruder-settings.jpg?raw=true)

The only thing I haven't finalised yet are the "Printhead Settings" section (my printer's just been too busy printing and I keep forgetting to measure it when it's not). But, these are only important if you're printing multiple models with the "Print Sequence" set to "One at a time". If you're printing multiple models with it set to "All at once" then they are irrelevant. I will fill them in at some point, though. :)

***Disclaimer** : The [official position from Snapmaker](https://support.snapmaker.com/hc/en-us/articles/360044341034-What-is-the-recommended-3D-printing-settings-in-Cura-or-Simplify3D-for-Snapmaker-2-0-) is that if 3rd party software (which includes slicing software like Cura) kills your printer, then your warranty is void. So, while I don't expect any of these files to have negative issues on your printer (they don't with mine) you still use them at your own risk.*
