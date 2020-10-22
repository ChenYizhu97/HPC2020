all: mandel_seq mandel_omp

mandel_seq: mandel_seq.c pngwriter.c
	gcc -o $@ -I. -O3 $^ -lpng

mandel_omp: mandel_omp.c pngwriter.c
	gcc -o $@ -I. -O3 $^ -lpng

clean:
	rm -rf mandel_seq
	rm -rf mandel_omp

