# Ray Tracing In One Weekend
It's my implementation of [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html) project.

# Usage
On Ubuntu, run the following command to compile, render, convert to png, and open the image:
```bash
g++ -o code code.cpp && ./code > image.ppm && convert image.ppm image.png && eog image.png
```
or simply `bash run.sh`.

# Final scene
![Final render scene](https://github.com/mahdavifar2002/ray-tracing-in-one-weekend/blob/main/image.png)
