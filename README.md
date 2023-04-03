# 📶 Minitalk
<p>
  <img src="Score_Minitalk.png" alt="Score Minitalk 125/100" align="left">

 <br><br>
The purpose of this project is to code a small data exchange program using UNIX signals.
It is an introductory project for the bigger UNIX projects that will appear later on in the cursus. 
<br><br>
<br><br>
</p>

## Installation

To install and run Minitalk, follow these steps:

1. Clone the repository: `git@github.com:raanki/Minitalk.git`
2. Change into the project directory: `cd minitalk`
3. Compile the server: `make server`
4. Compile the client: `make client`

## Usage

To use Minitalk, follow these steps:

1. Start the server by running the following command: `./server`
2. The server will display its process ID (PID). Keep this number handy.
3. Start the client by running the following command: `./client [server PID] [message]`
4. Replace `[server PID]` with the PID of the server that was displayed in step 2.
5. Replace `[message]` with the message you want to send to the server.
6. The client will send the message to the server using signals, and the server will display the message.

## Features

Minitalk has the following features:

- Small and efficient code.
- Uses signals for inter-process communication.

## Troubleshooting

If you encounter any issues while using Minitalk, try the following solutions:

- Make sure the server is running before starting the client.
- Make sure you have the correct server PID when starting the client.
- If the server is not receiving messages, make sure it is not blocked by a signal handler.

## Bonus

In addition to the mandatory part, Minitalk also includes some bonus features that were implemented by the developer. These include:

- Support for Unicode characters using the UTF-8 encoding.
- The server valid send for each bit receive a message to client.


