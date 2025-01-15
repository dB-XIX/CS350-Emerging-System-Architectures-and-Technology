# Emerging Systems Architectures and Technologies Project: SysTec Smart Thermostat

## Project Summary
This project involved the development of a smart thermostat prototype using the **TI CC3220x LaunchPad**. The thermostat was designed to:
- Read room temperature via the **TMP006 sensor**.
- Control heating using an **LED indicator**.
- Adjust the set temperature with buttons.
- Simulate server communication via **UART**.

The objective was to create a foundational system for a smart thermostat that could integrate into SysTec’s analytics software, addressing the global market demand for connected, energy-efficient devices.

---

## Artifacts

### Thermostat Source Code
- Demonstrates proficiency in writing interface software to control hardware components:
  - **I2C**: Used for temperature sensor readings.
  - **GPIO**: Configured for LED indicators and button functionality.
  - **UART**: Implemented for simulated server communication.

### Hardware Architecture Report
- Analyzed hardware designs and compared architectures, including:
  - **TI CC3220**
  - **Microchip ATWINC1510**
  - **Freescale NXP Kinetis**
- Recommended the optimal solution based on SysTec’s business requirements.

---

## Reflection

### What Did I Do Particularly Well?
- **Task Scheduler Implementation**: Successfully implemented a task scheduler to manage periodic functions such as:
  - Temperature readings
  - Button handling
  - Data logging
  - Ensured synchronization and system reliability.
- **Documentation**: Effectively documented the hardware architecture analysis, providing a clear and concise recommendation that aligned with the project’s business goals.

### Where Could I Improve?
- **Debugging Process**: Enhance the initial debugging phase to identify and resolve issues more efficiently.
- **Peripheral Optimization**: Spend additional time optimizing peripheral configurations and testing edge cases to streamline development.

### Tools and Resources Added to My Support Network
- **TI Code Composer Studio**: Used for development and debugging.
- **GitHub**: Managed version control and collaboration.
- **draw.io**: Created task scheduling diagrams.
- **Online Resources**:
  - Datasheets
  - Technical documentation
  - TI’s SimpleLink SDK
- Gained deeper knowledge of **I2C**, **UART**, and embedded systems.

### Transferable Skills
- **Low-Level Code Development**: Writing and debugging code for hardware peripherals, applicable to any embedded systems project.
- **Task Scheduling**: Designing and managing task schedulers for system synchronization.
- **Hardware Architecture Analysis**: Evaluating and comparing hardware solutions based on technical and business needs.

### Ensuring Maintainability, Readability, and Adaptability
- **Clean Code Practices**:
  - Consistent formatting
  - Meaningful variable names
  - Detailed inline comments
- **Modular Design**:
  - Components like I2C, UART, and GPIO are designed independently, allowing for easy modifications or replacements without affecting the entire system.
- **Comprehensive Documentation**:
  - Includes pseudocode and detailed reports, providing a clear roadmap for future development and adaptation.

---

This project has not only enhanced my technical skills but also demonstrated the importance of balancing technical and business needs when designing embedded systems. The knowledge and practices gained will be invaluable in future academic and professional endeavors.

