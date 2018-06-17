# Profit
This will trade everything that's digital and will give me profit!!! Of course the algorithms that I put in here should be really well researched and back tested.


This application will have a wrapper that does all the interpreting between the exchange's APIs. Then it'll have the right strategies to execute at that time when the machine is going to actually trade. After the trade, we will need a notification system and need to save the data in a serial way. 
Since this is just a trader, we additionally need a data analysis platform for tradeable asset data. More of a back testing platform. 

## Development Stack
* Python or Go
    * Don't know which one would be nice for this application.
    * Thinking of mostly Python but I have to choose.
    * Mostly I'm thinking of parallel computing stuff so it could be Go, but could code parallel in Python. 
    * In this project, I'm going to study the language internals too, and then get on with this project.
* Kubernetes
    * Not thinking of just creating a dumb server that just installs everything locally. 
    * The environment needs to be reproduceable and should get up right after the computer reboots.
    * Since it's a trading platform I need to make it really secure and nice.
* Monitoring & Logging
    * I need to learn a hell of this kind of stuff. 
    * Thinking of reading a few books like `The Art of Monitoring`.
* Infrastructure
    * Try to think of consistency, concurrency.
    * You should study some database stuff and model data properly.
