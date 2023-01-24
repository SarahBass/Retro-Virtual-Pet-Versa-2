# Retro-Virtual-Pet-Versa-2
Versa 2 Model of a Pixel Pet

To publish to Versa 2, Versa, and Versa Light some settings must be changed to work with SDK 4.3

Here is an example of Retro Pixel Pet from Versa 3 and Sense SDK 6.0 changed to work with older models with a 300X300 resolution screen. You can just change the x% and y% in Styles.css to adjust about 89.2%. 

Important Tidbit: I have noticed that Versa 2, Versa, and Versa Lite have less memory jerryscript issues running graphics than the newer Sense and Versa 3 models. This is because .gui is better suited to run graphics, meanwhile .defs is better for running large amounts of data in the form of numbers and text. The older 4.3 SDK uses .gui insteas of .view and .defs. You can find an old copy of the Fitbit 2019 4.3 SDK on the [Internet Archive](https://web.archive.org/web/20191102093406/https://dev.fitbit.com/build/guides/user-interface/svg-components/buttons/#button-with-icon). 
