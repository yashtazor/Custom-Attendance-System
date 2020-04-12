# Custom Attendance System

An attendance system which was made according to my teacher's need.

##### My Teacher's Needs

1. He will set a max number of students present in the class that day and each student will have a serial number within that range.
2. Then, students will fill their roll numbers along with their serial numbers.
3. These should directly get registered on an Google Sheet stored in his Google Drive.

##### Our Solution

1. Take the input from the teacher from an interface locked by a password known only to him.
2. Register this value in firebase.
3. At the student's end if the student enter an invalid serial number like a -ve number, text or a serial greater than the 
number set by the teacher, no input in taken.
4. Send this data to firebase if details are valid.
5. Use AJAX to send this data to the google spreadsheet created in any drive.

##### How to use?
1. Replace the Google Drive Link in the Student.html file with your Google Drive link.
2. Replace the names as per your Google Drive names (Can be found by inspecting the page source).
3. Run the index.html file.
