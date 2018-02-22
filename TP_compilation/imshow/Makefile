CXXFLAGS = -std=c++11 -Wall -Wextra

all : imshow.out

imshow.o : imshow.cpp
	g++ $(CXXFLAGS) -c imshow.cpp

imshow.out : imshow.o
	g++ $(CXXFLAGS) -o imshow.out imshow.o `pkg-config --cflags --libs opencv`

clean :
	rm -rf *.o *.out  
