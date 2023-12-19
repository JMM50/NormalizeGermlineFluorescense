# NormalizeGermlineFluorescense
Normalizes fluorescence intensity plot with variable lengths into columns of even length 

This program was developed to normalize fluorescence intensity plot profiles from ImageJ.
The output csv of plot profile in imageJ results in a fixed measurement of average fluoresence at a specific distances(measured in pixels).
When working with with biological samples of different sizes, these plot profiles cannot be easily directly compaired.
This program collects all seperate plot profiles and converts the axis to a fixed legnth as defined by % across the measurement.

to use this program you will be prompted to input the file location of the plot profiles you want to normalize. 
This program will normalize the legnth of each column and save the normalized data to a single csv file where each colomn is one of the plot profiles in th file.
