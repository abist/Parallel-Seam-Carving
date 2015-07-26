# Parallel Seam Carving

With the aid of certain approximations, we designed a new algorithm for content aware retargeting which ran ~25x faster than the conventional seam carving on a x86 Haswell platform. We adopted this approach because owing to the inherent sequential nature seam carving mapped directly on to a GPU (NVIDIA GTX 780) yielded only an approximate speed up of 7x when compared to a single threaded CPU baseline implementation and was largely due to parallelization of the energy computation stage of the algorithm (which is quite trivial) 

Project Link - http://www.contrib.andrew.cmu.edu/~abist/seamcarving.html
