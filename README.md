# Sample Registration
Android application for sample registration in the field

The application creates a folder called "sampleregistration" under the DOCUMENTS system folder.
The sampleregistration folder contains two new folders, "projects" and "config".

The projects folder contains the log files for each project.

The format of the log file is as follows:

The first line in the file is a unique ID for the file.
The remaining lines are | separated fields with the following format:
Phone ID | Project name | Sample ID | Date/Time (ISO) | Latitude | Longitude | Altitude | Station | Sample type | Measurement value | Measurement unit | Satellite count | Accuracy (meters) | Sample comment

If there is a file called sample-types.txt under the config folder, this file will be used as a suggestion database for the sample type field.
The sample-types.txt file should have one sample type per line.

If there is a file called units.txt under the config folder, this file will be used as a suggestion database for the unit field.
The units.txt file should have one unit per line.

## Screenshots

![sampleregistration003](https://cloud.githubusercontent.com/assets/1276717/16519246/da2a85da-3f87-11e6-9e5d-6a318ec7e31f.png)

![sampleregistration001](https://cloud.githubusercontent.com/assets/1276717/16519252/df8df994-3f87-11e6-9bdf-5e0d38295050.png)

![sampleregistration002](https://cloud.githubusercontent.com/assets/1276717/16519255/e2c64bb6-3f87-11e6-9899-a680993c5d87.png)