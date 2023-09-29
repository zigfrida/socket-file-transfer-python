# socket-file-transfer-python

## Running Instructions

In one terminal start the server by running the following command, where './directory_storate' is the path to where the files sent by the client will be stored.

### `python3 server.py ./directory_storage`

In another terminal run the client by typing the following command, where in this case, the client sends all the files with an extension .txt present in the current directory to the server.

### `python3 client.py *.txt`
