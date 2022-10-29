# Computer Vison Based Basketball Referee

Sports are evolving day by day and the technology that supports these sports are evolving at an exponential rate. Many sports have implemented computer vision in order to improve the referee calls and overall fairness of the game. Tennis using cameras to detect if a ball is out, Track and Field using cameras to detect who won a race, and many more. One sport however that has failed to do so on a signiicant scale is basketball. On top of that, basketball is one of the sports that is notorious for championship-changing, egregious referee calls. Implementing computer vision to watch over basketball games can not only make the game a much more fair experience for players and fans, but also a way of collecting data to use for greater machine learning models.

This project is a first step towards that goal. I developed a computer vision based basketball referee to detect if a player travels in a game of basketball. Using OpenCV libraries, I was able to track a ball using color masking, pixel arrays, and post-processing kernels to create a realtime ball tracker. Utilizing the X/Y coordinates, I was able to figure out the radius and center point of the ball. Then using an android app as a pedometer, I was able to detect realtime steps of a player. Comparing the realtime dribbles
