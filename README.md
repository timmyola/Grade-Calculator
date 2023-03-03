Calculate grades for students

This is a shell script that accepts a .csv file as input and calculates the grade for each student based on their score. The calculated grade will be added as the 5th column in the same input file.

Usage

To use this script, follow the steps below:

1. Download the shell script named calculate_grades.sh from this repository.
2. Make sure the file has executable permission using the following command:

  chmod +x calculate_grades.sh

3. Prepare your input .csv file with the following format:

  First Name,Last Name,Student ID,Score
  John,Doe,1001,85
  Jane,Smith,1002,92

Note: The header must be the same as the one shown above.

4. Execute the script with the following command: 

./calculate_grades.sh <input_file_name>.csv

Note: Replace <input_file_name> with the name of your input .csv file.

5. The script will update the input file with the calculated grade for each student. The output file will have the following format:

First Name,Last Name,Student ID,Score,Grade
John,Doe,1001,85,B+
Jane,Smith,1002,92,A+

Note: The grade obtained will be stored as the 5th column in the file.

6. Borderline cases will be highlighted in the output file.


