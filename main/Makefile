# Usage:
# make          # compile all
# make clean    # remote ALL binaries and objects

# Defined compile to be used.  
CC=gcc

# Name of final binary.
TARGET=supragma.out

# Remove binary.
RM=rm
 
all:    main.o
	$(CC) main.c -o $(TARGET)
 
clean:
	$(RM) *.o $(TARGET)
