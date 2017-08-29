# pchat
 
pchat is a simple chat room script in python. pchat uses AES encryption for secured data transfer over public network. It consist of two scripts a server and a client. Run the server.py in a system so that the client pchat.py can connect from remote systems with the correct password. You can connect multiple pchat.py to one single server from remote systems for a group chat. You can edit pchat.conf and change password, host, port and view mode.



SERVER.PY USAGE

 $ python server.py

pchat.PY USAGE

 $ python pchat.py "host_ip" "port" "password" "nick_name"
