# PlotInsectTrajectory
Script to Plot the X, Y and Z values over time from the H5.kalmanized file generated by Flydra. The values ploted are the x,y,z and frame values from the kalman_estimates dataset.

It requires the PyTables package. Please read the following document to install it: https://www.pytables.org/usersguide/installation.html 
To run the script: 
    python plotXYZ_from_h5_files.py -f kalmanized_file.h5
