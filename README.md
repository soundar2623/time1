Single File Programming Question
Problem Statement



Janu recently joined as a parking attendant at Prozone Mall. 



She needs to write a program to calculate the parking charges as follows:

It is free if out-time is not more than 10 minutes from in-time.
It is Rs. 40 for a 4-wheeler for up to 2 hours and Rs. 20 for a 2-wheeler for up to 2 hours.
For every additional hour, add Rs. 20 for a 4-wheeler and Rs. 10 for a 2-wheeler.


Get the in-time and out-time in hrs: min (in 24-hour format) and then calculate the parking charges. Assume all vehicles parked are moving out of the mall on the same day. Use T for 2-wheeler and F for 4-wheeler identification.

Input format :
The first line of input consists of the vehicle type code (T or F).

The second line consists of the in-time in 24-hour time format (HH:MM)

The third line consists of the out-time in 24-hour time format (HH:MM)

Output format :
The first line of output prints the parking duration.

The second line prints the parking charge.



Refer to the sample output for the exact text and format.

Sample test cases :
Input 1 :
T
13:30
14:45
Output 1 :
Parking Duration : 1:15
Parking Charge : 20
Input 2 :
T
7:45
11:55
Output 2 :
Parking Duration : 4:10
Parking Charge : 50
Input 3 :
F
6:10
11:55
Output 3 :
Parking Duration : 5:45
Parking Charge : 120
Input 4 :
F
1:30
1:35
Output 4 :
Parking Duration : 0:5
Parking Charge : 0# time1
