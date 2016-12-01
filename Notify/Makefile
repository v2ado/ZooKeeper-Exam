CC=gcc
HOME=/usr/local
CFLAGS=-g 
ZOOKEEPER_INC=-I${HOME}/include/zookeeper
ZOOKEEPER_LIB= -L${HOME}/lib -lzookeeper_mt

APP=notify
all:
	${CC} notify.c -DTHREAD ${CFLAGS} ${ZOOKEEPER_INC} ${ZOOKEEPER_LIB} -o ${APP} 
clean:
	rm -f ${APP}
