
IDA Pro plug-in and tools for displaying 3D graphs of procedures using UbiGraph.
based on modified MyNav-1.1 IDA plugin.

Video demo:
http://vimeo.com/26200637

UbiGraph project page:
http://ubietylab.net/ubigraph/index.html

MyNav plugin project page:
http://code.google.com/p/mynav/

Developed by:

Oleksiuk Dmitry, eSage Lab
mailto:dmitry@esagelab.com

http://d-olex.blogspot.com
http://twitter.com/d_olex


==========================
  Installation notes
==========================

1) Install patched MyNav (that located in mynav-1.1-ubigraph) as usual.
See ./mynav-1.1-ubigraph/README.TXT for more information.

1) Edit UbiGraph server address in ./mynav-1.1-ubigraph/ubiconfig.py

2) Copy ./ubicallback.pyd into the IDA root directory.

3) Run UbiGraph server. You can use it on a real Linux and OS X boxes, or in virtual machine for the Windows machines.

4) Use MyNav Functions Browser from IDA as usual.
