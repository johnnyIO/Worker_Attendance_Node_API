# Worker_Attendance_Node_API
This is a node API that was written to take workers roaster in a give organization, it uses the qr code as a means of taking record. 
The API exposes an end point that allows the user to be registered into the system. On successful registration, the user is given a qr, which is used for signing in and out of the organization
A sign process captures the users fullname, date and time of arrival and a signout process updates the early signed in record for that given date, to provide the departure time
