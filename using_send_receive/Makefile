.PHONY: clean

CFLAGS  := -Wall -g
LDLIBS := ${LDFLAGS} -lrdmacm -libverbs -lpthread

APPS    := server client

all: ${APPS}


clean:
	rm -f ${APPS}
