# Fonts 

These are a couple of fonts we use on our developer systems.

  * Inconsolata: a good developer font
  * Inconsolata_No_Hints: a modification to remove font hinting, to help display in Java Swing


## Fonts in Java, NetBeans, RubyMine, etc.

To enable custom fonts to be available in Java:

  * Ensure it is Unicode font
  * Copy font file into $JDK_HOME$/jre/lib/fonts
  * Restart the app, e.g. NetBeans or RubyMine


## Fonts with anti-aliasing in RubyMine

To enable anti-aliasing in RubyMine:

  * Go to Settings > Editor
  * Set Editor > Appearance > 'Use antialiased font' to enabled
  * Refer to http://forums.debian.net/viewtopic.php?f=10&t=39790 if these instruction do not work for you


## Font cache reloading on Linux

To build font information cache files:

    fc-cache -v
