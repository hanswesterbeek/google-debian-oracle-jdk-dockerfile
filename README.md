Oracle's JDK installed on top of Google's debian/wheezy image. The footprint seems to be a good 350 MB smaller than images made off Ubuntu base-images.

To check if it works:

`docker run hanswesterbeek/google-debian-oracle-jdk:VERSION java -version`

Replace version with '7' or '8'.