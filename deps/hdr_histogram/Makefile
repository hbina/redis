STD=
WARN= -Wall
OPT= -Os

R_CFLAGS= $(STD) $(WARN) $(OPT) $(DEBUG) $(CFLAGS)
R_LDFLAGS= $(LDFLAGS)
DEBUG= -gdwarf-4

R_CC=$(CC) $(R_CFLAGS)
R_LD=$(CC) $(R_LDFLAGS)

hdr_histogram.o: hdr_histogram.h hdr_histogram.c 

.c.o:
	$(R_CC) -c  $< 

clean:
	rm -f *.o


