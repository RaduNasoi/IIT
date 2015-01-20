# IIT
#!/bin/bash
a=$(find /home/andadrn/Desktop/1211 -type f -name '*.jpg' | wc -l)
echo "$a"
b=$(du -h /home/andadrn/Desktop/1211 | tail -n1)
echo "$b"
c=$(find /home/andadrn/Desktop/1211/elev1 -type f -name '*.jpg' | wc -l)
echo "$c"
d=$(du -h /home/andadrn/Desktop/1211/elev1 | tail -n1)
echo "$d"
e=$(find /home/andadrn/Desktop/1211/elev2 -type f -name '*.jpg' | wc -l)
echo "$e"
f=$(du -h /home/andadrn/Desktop/1211/elev2 | tail -n1)
echo "$f"
g=$(find /home/andadrn/Desktop/1211/elev3 -type f -name '*.jpg' | wc -l)
echo "$g"
h=$(du -h /home/andadrn/Desktop/1211/elev3 | tail -n1)
echo "$h"
