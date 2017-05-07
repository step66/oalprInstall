# oalprInstall

## test 

Test the library

wget http://plates.openalpr.com/ea7the.jpg

alpr -c us ea7the.jpg

wget http://plates.openalpr.com/h786poj.jpg

alpr -c eu h786poj.jpg


### sgTrain
Works on 1-line plates only. 

Todo: 2 line plates

put sg.conf to runtimedata/config

lsg.traineddata to runtimedata/ocr/tessdata

sg.patterns to runtimedata/patterns

sg.xml to runtimedata/regions

Reinstall openalpr 
