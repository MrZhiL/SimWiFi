CXXFLAGS =	-O9 -w -g -fmessage-length=0

OBJS =		SimMain.o SimNode.o 

LIBS =

TARGET =	.\CA.exe

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
