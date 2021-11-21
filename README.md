simply send file or directory to Remote Servers
how to use it ?

ansible-playbook copyfile.yaml --extra-vars "myfile=/path/to/file-or-directory  destination_file=/path/to/file-or-directory myhost=my-server-name" 
