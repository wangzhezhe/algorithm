CC = /usr/local/cuda/bin/nvcc

sssp: *.cu *.c
	$(CC) -std=c++11 parse_graph.cu utils.c entry_point.cu -O3 -arch=sm_30 -o sssp
#parse_graph.cpp impl1.cu impl2.cu opt.cu 

clean:
	rm -f *.o sssp
