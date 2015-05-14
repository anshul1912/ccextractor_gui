# CCExtractor GUI for linux
This is ccextractor gui for linux


#Ubuntu Install dependencies instruction:
$> sudo apt-get install libqt4-dev

#openSuse Install dependencies instruction:
$> sudo zypper install libqt4-dev

#To compile, navigate to the folder and type :
$> qmake -project
$> qmake
$> make

#FAQ
Possible causes for errors:
QApp... unable to find.Solution:
1) Just reinstall it
2) Update locate's database :    sudo updatedb
3) locate QApplication
4) Compile again
