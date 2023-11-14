all:
	riscv64-unknown-linux-gnu-gcc -O3 -march=rv64gcv -S  test.c -o test.gcv.s
	riscv64-unknown-linux-gnu-gcc -O3 -march=rv64gc -S  test.c -o test.gc.s
clean:
	rm *.s
