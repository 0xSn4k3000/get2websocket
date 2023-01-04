# get2websocket
Get2websocket is a middleware to automate stuffs like sql injection attacks over the websockets
get2websocket convert the get requests into your websocket target so you can easly use tools like sqlmap with websockets!

    Usage:
        -h , --help         : show this help.
        --ws , --web-socket : your target web socket (eq. http://example.com/ws , ws://redacted.com:9091 ...)
        --lp , --local-port : local port to listen to.
        -c , --contnet-type : content type to use with the server

    Example:
        if you have a websocket thats got some parameters like {"name":"joyboy" , "password":"test"}
        then you can attack this middle ware with the exact parameters in the get request
        http://localhost:{PORT}/?name=joyboy&password=test
    
    By @TheJoyBoy
    Thanks to @rayhan0x01


