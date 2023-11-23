tcp:
	@-rm tcpserver tcpclient
	@gcc tcpclient.c -o tcpclient
	@gcc tcpserver.c -o tcpserver

udp:
	@-rm udpserver udpclient
	@gcc udpclient.c -o udpclient
	@gcc udpserver.c -o udpserver

clean:
	@-rm udpserver udpclient tcpserver tcpclient