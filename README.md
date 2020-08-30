# Amateur-Running
# This file contains a dataset of my running between 07/08/2016 and 07/05/2020
# please note file structure as follows:
Number Id	Name	                 Type Description 	Explaination 	                                                                         Format
1	     Progression               int 64	            Progressive number of activity	Ordinal ranking	                                       Number
2	     Activity Type             Object	            Type of exercise	Running by default	                                                 String
3	     Date                      Object	            Date of the running	Date and time	                                                     dd/mm/yy/hh/mm
4	     Title                     Object	            Name of the activity	Title field	                                                     String
5	     Distance                  float	            Length of the running	Metric (Km)	                                                     k.mm
6	     Calories                  Object	            Calories burnt in the session	-	                                                       Number
7	     Time                      Object	            Duration of Exercise	Time	                                                           hh:mm:ss
8	     Avg HR                    Object	            Heart Rate avarage 	Beats per mintute	                                                 Number
9	     Max HR                    Object	            Highest pulse reached	Beats per mintute	                                               Number
10	   Aerobic TE                Object	            Training Effect Indicator	from 1 to 5	                                                 Number
11	   Avg Run Cadence           Object	            Avg. number of steps in a minute	frequency rate at which your feet land on the ground	Number
12	   Max Run Cadence           Object	            Max. number of steps in a minute	frequency rate at which your feet land on the ground	Number
13	   Avg Speed                 Object	            Speed avarage in the workout	Minutes per K.	                                         mm:ss
14	   Max Speed                 Object	            Fastest Speed  in the workout	Minutes per K.	                                         mm:ss
15	   Elev Gain                 Object	            Meters climbed during activity	meters	                                               Number
16	   Elev Loss                 Object	            Meters descended during activity	meters	                                             mts,cm
17	   Avg Stride Length         float	            avg. length  of steps 	meters	                                                       mts,cm
18	   Avg Vertical Ratio        float	            cost-to-benefit ratio where the cost is the vertical oscillation (ground clearance or lift)
                                                    and the benefit is the distance travelled (stride length)	-	                           Percentage
19	   Avg Vertical Oscillation  float	            is the amount that the torso moves vertically with each step, while running, 
                                                    measured in centimeters (cm)	Centimeters	                                             cm, Number
20	   Avg Ground Contact Time   Object	            Avarage percentage time of how much the foot spend on the ground	Milliseconds	       mms, Number
21	   Avg GCT Balance           Object	            Avarage percentage time of how much each foot spend on the ground	%L-%R	               Percentage
22	   Number of Laps            Object	            Number od given laps	If not otherwise stated is 1 k by default	                       Number
