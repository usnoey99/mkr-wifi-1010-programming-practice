# MKR WiFi 1010 Programming Practice

A hands-on programming practice repository using an **Arduino MKR WiFi 1010**.

The goal of this project is to move from basic C/C++ syntax to building complete embedded and networked applications through small, incremental projects.

## Goals

- Strengthen C/C++ programming fundamentals through practice
- Learn how to structure and complete small projects
- Become familiar with Arduino development
- Understand embedded programming concepts
- Learn basic networking and HTTP
- Build simple web-based interfaces using the MKR WiFi 1010
- Practice using Git and GitHub as part of the development process

## Hardware

- Arduino MKR WiFi 1010
- USB cable
- Laptop
- Smartphone

No additional electronic components are planned.

## Project Roadmap

### 1. LED Basics

- [ ] Blink the built-in LED
- [ ] Create a reusable `blink()` function
- [ ] Experiment with different timing patterns
- [ ] Practice variables, functions, loops, and conditionals

### 2. Morse Code

- [ ] Convert characters into Morse code
- [ ] Display Morse code using the built-in LED
- [ ] Support strings instead of single characters
- [ ] Practice arrays, strings, and character processing

### 3. Serial Calculator

- [ ] Read input from Serial Monitor
- [ ] Parse numbers and commands
- [ ] Implement basic arithmetic operations
- [ ] Practice input handling and functions

### 4. Reaction Time Game

- [ ] Generate a random delay
- [ ] Measure reaction time using `millis()`
- [ ] Display the result through Serial
- [ ] Track best and average reaction times
- [ ] Practice state management

### 5. Number Guessing Game

- [ ] Generate a random number
- [ ] Accept guesses through Serial
- [ ] Provide higher/lower hints
- [ ] Count attempts
- [ ] Add difficulty levels

### 6. Wi-Fi Connection

- [ ] Connect the MKR WiFi 1010 to a Wi-Fi network
- [ ] Display connection status
- [ ] Display the assigned IP address
- [ ] Experiment with basic network information

### 7. Basic Web Server

- [ ] Run a web server on the Arduino
- [ ] Serve a basic HTML page
- [ ] Access the page from a laptop
- [ ] Access the page from a smartphone
- [ ] Understand basic HTTP request/response behavior

### 8. Web-Based LED Controller

- [ ] Create ON/OFF buttons
- [ ] Control the built-in LED from a smartphone
- [ ] Add a blinking mode
- [ ] Display the current LED state

### 9. HTTP Command Interface

- [ ] Create simple HTTP commands
- [ ] Parse URL parameters
- [ ] Implement commands such as:
  - `on`
  - `off`
  - `blink`
  - `status`
- [ ] Return useful responses from the Arduino

### 10. Web Dashboard

- [ ] Combine previous projects
- [ ] Display Wi-Fi status
- [ ] Display uptime
- [ ] Display LED status
- [ ] Track command/request counts
- [ ] Create a simple dashboard for smartphone and laptop

## Repository Structure

```text
.
├── README.md
├── 01-led-basics/
├── 02-morse-code/
├── 03-serial-calculator/
├── 04-reaction-time/
├── 05-number-guessing/
├── 06-wifi-connection/
├── 07-web-server/
├── 08-web-led-controller/
├── 09-http-command-interface/
└── 10-web-dashboard/