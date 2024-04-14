# CN_multiFTP

## Commands

### Server
Run command to start the server.
```
python ftpserver.py
```

### Client
Run the command to start a client.
The port must be specified, such as 8000 in this command line.
Can start multiple clients at the same time.
```
python ftpclient.py 8000
```

### Requests
* Download file from the server
  
  Use get command in the request for downloading file from the server. The downloaded file will be saved as "new{filename}".
```
get [filename]
```

* Upload file to the server
  
  Use upload command in the request for uploading file to the server. The uploaded file will be saved as "new{filename}".
```
upload [filename]
```

* Quit
  
  Use quit command to disconnect from the server.
```
quit
```
