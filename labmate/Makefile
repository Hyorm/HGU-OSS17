labmate: labmate.o students
	gcc -o labmate labmate.o
	./labmate -f students.txt
labmate.o: labmate.c
	gcc -c labmate.c
students: students.txt
clean:
	rm *.o labmate
