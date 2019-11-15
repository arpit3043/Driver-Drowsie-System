# Driver-Drowsie-System
Driver drowsiness detection is a car safety technology which helps prevent accidents caused by the driver getting drowsy. Various studies have suggested that around 20% of all road accidents are fatigue-related, up to 50% on certain roads

# working through

Drowsiness detection with OpenCV
Two weeks ago I discussed how to detect eye blinks in video streams using facial landmarks.
Today, we are going to extend this method and use it to determine how long a given person’s eyes have been closed for. If there eyes have been closed for a certain amount of time, we’ll assume that they are starting to doze off and play an alarm to wake them up and grab their attention.
To accomplish this task, I’ve broken down today’s tutorial into three parts.
In the first part, I’ll show you how I setup my camera in my car so I could easily detect my face and apply facial landmark localization to monitor my eyes.
I’ll then demonstrate how we can implement our own drowsiness detector using OpenCV, dlib, and Python.
Finally, I’ll hop in my car and go for a drive (and pretend to be falling asleep as I do).
As we’ll see, the drowsiness detector works well and reliably alerts me each time I start to “snooze”.
Rigging my car with a drowsiness detector
