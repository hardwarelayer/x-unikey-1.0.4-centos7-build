Unikey Input Method for X-Window
================================
Copyright (C) 2004 Pham Kim Long

This package contains following components:
- ukxim: Unikey XIM (X Input Method) server
- unikey: GUI for ukxim and unikey-gtk
- unikey-gtk: GTK vietnamese input method module

To install: see INSTALL
Manual: see doc/manual

TienTN comment:
  This is my build and fixes for CentOS Linux release 7.2.1511 (Core)
  This version can type vietnamese language on XWindows, but not well.
  I did fix some code inside the repo in order to make it work on XWindows (KDE Plasma)
  
  to build
  ./configure
  make
  make install

  to run:
  /usr/local/bin/unikey -xim /usr/local/bin/ukxim
