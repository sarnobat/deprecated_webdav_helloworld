# Server
(Ubuntu)
```
	easy_install pip
	pip install wsgidav cheroot
	wsgidav --host=192.168.1.3 --port=4498 --root=/tmp --verbose 
```
# Client
Make sure you are on the same network
```
curl 'http://192.168.1.3:4498/'
```
