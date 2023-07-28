## llama2.cpp

Forked from Karpathy repo [llama2.c](https://github.com/karpathy/llama2.c)

I implementled a modification over llama2.c to use Eigen for fast matrix multiplication. Eigen requires C++. Then to compile use:


```bash
g++ -I. -Ofast -fopenmp run.cpp  -lm  -o run
```

This version is not faster in my old computer but using Eigen you can use AVX2 (among others) set of instructions that could speedup the inference. 


## License

MIT
