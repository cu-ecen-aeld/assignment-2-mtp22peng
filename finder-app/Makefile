
# Platform Overrides
 CROSS_COMPILE  = HOST


ifeq ($(CROSS_COMPILE),aarch64-none-linux-gnu-)
   CC = $(CROSS_COMPILE)"gcc"
else
   CC = gcc
endif







CFLAGS= -Wall -W -O2 -lrt -g

write: write.c
	$(CC) -o write write.c


clean:
	rm -f write.o write
