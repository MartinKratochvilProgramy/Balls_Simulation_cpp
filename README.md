
# How it works?
Program was written in c++ using Microsoft Visual Studio, you can load it the VS using the .sln file.

  First Ball class is created, balls are initialized with random positions and velocities. In run loop, program iterates through pairs of balls (because thanks to Newton's third law F12 = -F21, wit is not necessary to loop through all the balls), then gravity is calculated and if collision happens deflection. On collision there is some loss of momentum specified c_rest = 0.25 so that the balls have a tendency to "stick" together.

![image](https://user-images.githubusercontent.com/94861828/149720357-87ec17af-d88c-40d1-bf49-7aa9eb7e5227.png)

![image](https://user-images.githubusercontent.com/94861828/149720570-3dc7c18b-7120-4dcf-9a03-ef187b7becd4.png)

