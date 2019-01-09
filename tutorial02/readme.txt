gcc -o tutorial02 tutorial02.c -lavformat -lavcodec -lswscale -lz -lm \
`sdl-config --cflags --libs`