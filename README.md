Unicode Rewriter is a Java tool which converts ID3 tags of MP3 files into Unicode. The reconverted MP3 files can be processed by iTunes and Rhythmbox.

WARNING: The mp3 files get overwritten when they are converted, so make sure to create a backup first!

Make sure you have at least a Java 17 Java Runtime Environment (JRE) installed in your environment.

To start the application, run the equivalent of the following command (adjust the 0.0.1 version number, for future releases, as needed)

    java -jar mp3-tag-unicode-rewriter-0.0.1.jar

Use the following VM argument to have the window scale well on a 4K monitor
-Dsun.java2d.uiScale=2.5

    java -Dsun.java2d.uiScale=2.5 -jar mp3-tag-unicode-rewriter-0.0.1.jar