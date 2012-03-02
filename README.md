Taipei Torrent
==============

This is a simple command-line-interface BitTorrent client coded in the go
programming language.

FAQ:
----

Q: Why call it Taipei Torrent?
A: I started writing it while visiting Taipei, Taiwan

Q: What is the license?

A: The code in the bencode subdirectory is controlled by the LICENSE file in
that directory.

The code in the rest of Taipei Torrent is controlled by the LICENSE file in the
top level.

Current Status
--------------

Works, at least for some torrents.

Development Roadmap
-------------------

+  Implement choke/unchoke logic
+  Full UPnP support (need to be able to search for an unused listener port,
   detect we have already acquired the port,
   release the listener port when we quit.)
+  Clean up source code
+  Deal with TODOs
+  Add a way of quitting other than typing control-C

Build Instructions
------------------

    go build

Usage Instructions
------------------

    ./Taipei-Torrent -torrent mydownload.torrent

Related Projects
----------------

https://github.com/nictuku/Taipei-Torrent nictuku has an actively developed
fork that includes support for Distributed Hash Tables.
