punch_sctp
======

What is ``punch_sctp``?
-------------------

``punch_sctp`` is a library for p2p direct sctp data transfer between host on other networks which has NAT.

``punch_sctp`` ueses technologies of Web Real-Time Communication (WebRTC) partially.

So you need a STUN server (Google offers for testing now and you can use it) and a signaling server for establish sctp transport.

Acknowledgement
-------------------

This library is fork of aiortc (https://github.com/aiortc/aiortc) and most codes are wrote on aiortc project.

I am deeply grateful to contoributers of aiortc who maked very very nice product.

Requirement
-------------------
OS: Windows (tested only on win10 64bit), Linux (tested only Ubuntu Linux sid), MacOS (tested only Mojave)

Python: greater than 3.5 

Setup depend packages
-------------------

- ``Important``:

  - punch_sctp is under development. So package installation path isolation is recommended (ex: use virtualenv) 

There are two way

- use setup.py

  - $ python setup.py install

- use pip

  - $ pip install git+https://github.com/ryogrid/punch_sctp

Now, sample program refefences code tree directly.

So, when trying execution, you should do it on cloned local repository aside from Websocket signaling server(it only needs 'websockets' pip package).

License
-------

``punch_sctp`` is released under the `BSD license`_.

.. _BSD license: https://aiortc.readthedocs.io/en/latest/license.html
