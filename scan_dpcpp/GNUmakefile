
main.ex: main.cpp
	dpcpp -O3 -std=c++17 -fsycl -fsycl-device-code-split=per_kernel -fno-sycl-early-optimizations -o $@ $<

clean:
	${RM} *.ex *.o
