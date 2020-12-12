all: openmp pthread

openmp:
	gcc openmp.c -std=gnu99 -fopenmp -lm -o openmp

openmp2:
	gcc openmp2.c -std=gnu99 -fopenmp -lm -o openmp2
pthread:
	gcc pthread.c -std=gnu99 -lpthread -lm -o pthread

clean:
	rm openmp pthread
