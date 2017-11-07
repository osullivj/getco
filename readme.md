#### Getco coding challenge
This is the code I submitted as a first step in the Getco hiring process back in 2009. During the
phone interview I was told I would need to spend three months in Chicago, so I dropped out at that
point. The challenge was to write some code that figured out CPU cache sizes; you can see that in
main.cpp which is, of course, win32 code.

#### Some research links
Here's some stuff I found handy in figuring out the problem.

[Always good to start with wikipedia](http://en.wikipedia.org/wiki/CPU_cache)

[No need to use push/pop, chance of scheduler interruption during measurement](http://www.strchr.com/performance_measurements_with_rdtsc)

[Agner Fog on model specific register for performance monitoring events](http://www.agner.org/optimize/)

[Intel paper on RDTSC](http://www.ccsl.carleton.ca/~jamuir/rdtscpm1.pdf)

[CPUID for processor info. But Intel only gives us the L2 cache size directly.](http://www.sandpile.org/ia32/cpuid.htm)

[Cache experiments](http://dsrg.mff.cuni.cz/publications/BabkaTuma-spec09.pdf)

[Cache measuring](http://ecommons.library.cornell.edu/handle/1813/5670)
