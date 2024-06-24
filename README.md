# CS-350

Summarize the project and what problem it was solving.

The project was to create a prototype thermostat that read temperature from the temperature sensor on the board,
and based on a set temperature that was adjusted by the button inputs, would either enable or disable the heating function
indicated by the red led. Then it was to simulate outputing the data to the cloud system via Wi-Fi simulated by the terminal output.

What did you do particularly well?

I feel I did a good job on adjusting the feedback rate with the GPIO and the buttons to get a realistic form of feedback.
The default value was so slow it was annoying to wait for updates.

Where could you improve?

I really struggled getting the UART system to function, mainly that I didn't have it configured right. Learning more
about all of the various requirements for each component would help me in the future.

What tools and/or resources are you adding to your support network?

I feel the use of I2C an GPIO will be really invaluable for utilizing embedded system hardware to software functionality
when working on providing proper hardware/software response.

What skills from this project will be particularly transferable to other projects and/or course work?

My goal is to work with either AI and/or embedded systems when I'm done with school. If I stay with the company I'm at now
working with manufacturing technology I will need to understand embedded systems clearly as most of the production line is
basically a giant network of embedded systems.

How did you make this project maintainable, readable, and adaptable?

I compartmentialized the code into functions instead of leaving the code all in the open. It keeps the code clean, adaptable, and readible.
I have inline comments explaining each section and function on what they are and what they do. Keeping the main function clear from clutter
helps maintain the code functionality and readability.
