CXX = g++
CFLAGS = -std=c++14 -O2 -Wall -g 

TARGET = server
OBJS = ../code/log/*.cpp ../code/pool/*.cpp ../code/timer/*.cpp \
       ../code/http/*.cpp ../code/server/*.cpp ../code/config/*.cpp\
       ../code/buffer/*.cpp ../code/cache/*.cpp ../code/main.cpp

all: $(OBJS)
	$(CXX) $(CFLAGS) $(OBJS) -o ../bin/$(TARGET) -pthread -L/usr/lib64/mysql -lmysqlclient

clean:
	rm -rf ../bin/$(OBJS) $(TARGET)




