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

![sampleregistration03](https://cloud.githubusercontent.com/assets/1276717/16519096/0c38612e-3f87-11e6-9308-5a969ae5f9d9.png)

![sampleregistration01](https://cloud.githubusercontent.com/assets/1276717/16519100/124e72b0-3f87-11e6-9eb5-94bfc3baec3b.png)

![sampleregistration02](https://cloud.githubusercontent.com/assets/1276717/16519105/15ccc266-3f87-11e6-94b8-d828742e5b30.png)