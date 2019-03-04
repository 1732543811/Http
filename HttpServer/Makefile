bin=HttpServer
cc=g++ -std=c++11
LDFLAGS=-lpthread 

.PHONY:all
all:$(bin) cal

$(bin):HttpServer.cc
	$(cc) -g -o $@ $^ $(LDFLAGS) #-D_DEBUG_
cal:cal.cc
	gcc -o $@ $^
.PHONY:clean
clean:
	rm -f $(bin) cal
