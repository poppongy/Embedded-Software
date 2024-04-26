# Embedded-Software

# Summarize the project and what problem it was solving. 
This was the final project of the class, and it was a prototype of a thermostat designed to send data to SysTec’s server software over Wi-Fi. This prototype of low-level thermostat used the TMP006 temperature sensor to read room temperature using I2C, an LED to indicate the output to the thermostat where LED on means heat is on (using GPIO). The project also included two buttons to increase and decrease the set temperature (via GPIO interrupt), and the UART to simulate the data being sent to the server.

# What did you do particularly well?
I believe what I excelled at in this project is transforming the older uart driver code implementation to the latest uart2 driver.

# Where could you improve? 
One area I could improve is getting more familiar with the C language. Through out my research, I found myself looking up syntax after syntax trying to understand C programming construct in embedded systems. Spending more time to understand the fundamentals would be of tremendous help.

# What tools and/or resources are you adding to your support network? 
Particularly, the notes from the manufacturers are resources that would be crucial to my success as an embedded systems engineer. In this class, the TI notes on the CC3220SF launch board were what got me over the hump. Whenever I got stuck, I would read the notes for more information.
# What skills from this project will be particularly transferable to other projects and/or course work?
In this project, I learned to debug code more accurately. This skill would transfer to other course work. 
# How did you make this project maintainable, readable, and adaptable?  
I used comments and spacing to make my code more readable. As mentioned earlier, the resources I researched were coded in uart. To stay up to date and make the project maintainable and adaptable, we had to transform this peripheral to uart2 which is the latest version. Additionally, the code review done by my professor proved the code works. With code review, I know my code works delivering in its functionality.

