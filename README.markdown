# Potty Time Countdown Clock
This is a simple webpage to remind me if I should take my dog for a potty time

# Feature backlog
1. Make the background color dynamic from green to red depends on how long time since last potty time. 4 hours should be very warning for Poggi!
1. Convert the application into a web app so that the data can be access with any clients
1.1. create a dynamoDB to record the event history
1.1. Create a front end that consume such event history
1.1. Racing issue, if the reset should happened on the remote server so that all client can reset their timer
1. Adding the capablity of editing event history
1. When reset the timer,  add a line to record the time. So you always know when was the last time Poggie went for potty!
1. When reset the timer, there should be a animation to celebrate Poggi's potty
