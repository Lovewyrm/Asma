#ASMA
simple arma 3 launcher for linux

#Compile
gcc asma.h asma.c addons.h addons.c $(pkg-config --cflags --libs gtk+-3.0) -o asma
