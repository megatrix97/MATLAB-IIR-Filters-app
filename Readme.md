A simple MATLAB app aimed at students to visualize the effect of IIR Filters on digital signals.

A butter-worth filter is used in the entire app. A sample signal which is a combination of sinusoidal signals with 
different amplitudes at frequencies 25Hz, 50Hz, 100Hz is used (no option is given to change this signal, to change it look into section 1.2)

To use it as an app, package it first.
Section 1.1:
  How to package the app?
    Requisites: Make sure you have 'appdesigner' for MATLAB installed.
    1. Download the repository to your local disk.
    2. Open MATLAB
    3. Click 'Open -> Open..' in the 'HOME' tab, which pops a dialog box.
    4. Locate the Filters.mlapp present on your local disk
    5. Click 'Open'
    6. You should see a 'Package' icon in the 'DESIGNER' tab
    7. Enter required details and click on 'Package', which generates an installable package.
    8. Install it using the MATLAB package manager.
Section 1.2:
  How to change the sample signal?
    1. Open the 'Filters.mlapp' in MATLAB App Designer.
    2. Switch to 'Code view' tab.
    3. Look for these functions:
      i.   plotSignal
      ii.  plotSignalFFT
      iii. plotFilterResponse
            In all these three functions you will find the variables, 'Fs', 'x'
            Fs - Sampling Frequency
            x - Signal
            Change these variables to your required data.
            **Make sure you have signal of length 2000**
   Once the above steps are done, you can package the app(Section 1.1).
