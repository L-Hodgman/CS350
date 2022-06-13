# CS350
SNHU CS-350: Emerging Systems Architectures &amp; Technologies

Summarize the project and what problem it was solving.

The final project was to develop a smart thermostat protype using the TI board for SysTec. The prototype used the TMP006 temperature sensor to read the room temperature (via I2C), the LEDs had to indicate the output to the thermostat where LED on = heat on (via GPIO), two buttons had to increase and decrease the set temperature (via GPIO interrupt), and the UART had to simulate the data being sent to the server.

What did you do particularly well?

I felt like I figured out the Task Schedular pretty quickly. After looking at ZyBooks, it made alot more sense. Then, after piecing our past milestones together, everything fit into place.

Where could you improve?

My biggest issue through out this course was understanding how everything functioned, such as the timers, GPIO, and UARTs. I just knew what functions to call for what from previous milestones, but I trouble understanding exactly how they worked. 

What tools and/or resources are you adding to your support network?

This was my first time ever working with an embedded system. I really enjoyed working with the Code Composer IDE, as someone who has experience with Eclipse, it was super easy to learn. Then, the biggest resource that helped me was our ZyBooks book and TI pdfs.

What skills from this project will be particularly transferable to other projects and/or course work?

Just doing proper research on how to correctly build certain models, such as the state machines and task schedulars. Also, looking at example codes and figuring out how I can implement them into my program.

How did you make this project maintainable, readable, and adaptable?

For the Thermostat program, I had already utalized a lot of recycled code from the past milestones. So, this program is very adaptable. Also, I made sure to comment a lot of key lines to tell readers what they are used for. Lastly, I tried to keep the code as simple as possible, so it could be easily read and maintained.
