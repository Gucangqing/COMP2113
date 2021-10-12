gcd.o:  gcd.cpp gcd.h
  g++ -c gcd.cpp
lcm.o:  lcm.cpp lcm.h
  g++ -c lcm.cpp
calc.o: calc.cpp gcd.h lcm.h
  g++ -c calc.cpp
calc: gcd.o lcm.o calc.o
  g++ gcd.o lcm.o calc.o -o calc
clean:
  rm -f gcd.o lcm.o calc.o calc
.PHONY: clean
