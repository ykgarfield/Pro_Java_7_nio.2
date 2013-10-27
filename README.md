Pro_Java_7_nio.2
================

Pro_Java_7_nio.2译文


<h2>勘误列表</h2>

■ Chapter 7, P139, 在ByteBuffer Properties的Limit中,When writing from a buffer, the limit specifies how much data remains to get. When you are reading into a buffer, the limit specifies how much room  remains to put data into.    </br>
这里的表述弄反了write和read,应该是reading from a buffer和writing int a buffer.
 </br> 下面的图解中也有同样的问题.
 
■ Chapter 8, P175, SO_REUSEADDR: This option’s value is an integer ...
SO_REUSEADDR的应是一个boolean.

TCP_NODELAY: This option’s value is an integer ... 也是同样的问题.

■ Chapter 8, P182, "Creating a New Socket Channel "小节中You can check if a server socket is...,这里讲的是套接字,而不是服务器套接字.所以英文的话应该要把server去掉.

"Setting Socket Channel Options "小节You can find the supported options for a server socket...也是同样的问题.

■ Chapter 8, P199, "Binding the Datagram-Oriented Socket Channel "小结中 calling the ServerSocketChannel.getLocalAddress() method, 这里将的是DatagramChannel,应该是DatagramChannel. getLocalAddress().
