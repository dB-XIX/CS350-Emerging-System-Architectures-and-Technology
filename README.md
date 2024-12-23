Emerging Systems Architectures and Technologies Project: SysTec Smart Thermostat
Project Summary
This project involved the development of a smart thermostat prototype using the TI CC3220x LaunchPad. The thermostat was designed to read room temperature via the TMP006 sensor, control heating with an LED indicator, adjust the set temperature using buttons, and simulate server communication via UART. The problem being solved was creating a foundational system for a smart thermostat to integrate into SysTec’s analytics software, addressing the global market need for connected, energy-efficient devices.

Artifacts
Thermostat Source Code: Demonstrates my ability to write interface software to control hardware components, including I2C for sensor reading, GPIO for LED and button functionality, and UART for simulated server communication.
Hardware Architecture Report: Showcases my ability to analyze hardware designs, compare architectures (TI CC3220, Microchip ATWINC1510, and Freescale NXP Kinetis), and recommend the best solution based on SysTec’s business requirements.
Reflection
What did you do particularly well?
I successfully implemented a task scheduler to manage periodic functions like temperature readings, button handling, and data logging, ensuring synchronization and reliability. Additionally, I effectively documented the hardware architecture analysis, providing a clear and concise recommendation that aligns with the project’s business goals.

Where could you improve?
While the project met its objectives, there’s room to improve the initial debugging process and optimization of peripheral configurations. Spending more time on testing and refining edge cases could have streamlined development.

What tools and/or resources are you adding to your support network?
I integrated several valuable tools into my workflow, including TI Code Composer Studio for development, GitHub for version control, and draw.io for task scheduling diagrams. Online resources like datasheets, technical documentation, and TI’s SimpleLink SDK were crucial. I also deepened my knowledge of I2C, UART, and embedded systems, which will continue to be part of my resource toolkit.

What skills from this project will be particularly transferable to other projects and/or coursework?
The skills gained in writing and debugging low-level code for hardware peripherals are transferable to any embedded systems project. The ability to design task schedulers, analyze hardware architectures, and make informed recommendations based on technical and business needs will be invaluable in both academic and professional settings.

How did you make this project maintainable, readable, and adaptable?
I followed best practices for clean code, including consistent formatting, meaningful variable names, and detailed inline comments. Additionally, the modular design ensures that components like I2C, UART, and GPIO can be modified or replaced without affecting the entire system. The documentation and pseudocode provide a clear roadmap for future development and adaptation.
