# ESP32-Telegram-Bot-Based-Power-Switch
A Telegram-controlled IoT power switch built using an ESP32, allowing secure remote ON/OFF control of a device via chatbot commands. The system authenticates messages through a fixed chat ID and provides real-time status feedback
This project implements a chatbot-controlled power switch using an ESP32 microcontroller and the Telegram Bot API. The system enables users to remotely control an output device (such as an LED, relay, or appliance) through simple text commands sent via Telegram.

The ESP32 connects to Wi-Fi and continuously monitors incoming Telegram messages. When a user sends predefined commands like /led_on, /led_off, or /state, the bot processes the instruction and toggles the output pin accordingly. Only authorized users—identified by a specific chat ID—are allowed to control the system, ensuring secure operation.

Key features include:

Remote control from anywhere using Telegram

Secure access control via predefined user chat ID

Real-time GPIO control (ON/OFF)

Status monitoring with feedback messages

Non-blocking message handling for smooth performance

This setup can be extended to control relays, home appliances, or IoT devices, making it a practical and cost-effective home automation solution.
