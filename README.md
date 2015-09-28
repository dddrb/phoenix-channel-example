# Phoenix Channel Example

## Installation

```
$ git clone https://github.com/ogom/phoenix-channel-example.git
$ cd phoenix-channel-example
$ npm install
$ mix deps.get
$ mix ecto.create
$ mix ecto.migrate
$ mix phoenix.server
```

## Usage

Enter the message content, and then type the Enter key.

```
$ open http://localhost:4000/messages/new
```

## License

* MIT
