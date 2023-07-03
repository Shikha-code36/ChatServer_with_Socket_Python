# Chat Server and Client - Socket Programming in Python

This is a simple chat server and client project implemented using Python and socket programming. The server can handle multiple client connections concurrently, allowing them to exchange messages with each other.

## Features

- Basic chat functionality: Clients can send messages to the server, and the server will broadcast the received messages to all connected clients.
- Concurrent connections: The server uses threading to handle multiple client connections concurrently.
- Local testing: The chat server and client are designed to be tested locally on your machine.

## Requirements

- Python 3.x

## How to Use

1. First, clone this repository to your local machine using the following command:
```
git clone https://github.com/Shikha-code36/Socket_Programming_Python.git
```


2. Open a terminal window and navigate to the project directory.

3. Run the server script:
```
python server.py
```

4. Open another terminal window and navigate to the project directory.

5. Run the client script:
```
python client.py
```

6. The client will prompt you to enter your message. Type your message and press Enter to send it to the server. The server will respond with a confirmation message.

7. You can run multiple instances of the client script in separate terminal windows to simulate multiple clients connecting to the server.

## License

This project is licensed under the [MIT License](LICENSE).

## Disclaimer

This project is a basic implementation of a chat server and client for educational purposes. It may not be suitable for production use. Use it at your own risk.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.


