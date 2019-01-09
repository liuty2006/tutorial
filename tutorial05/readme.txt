gcc -o tutorial05 tutorial05.c -lavutil -lavformat -lavcodec -lswscale -lz -lm \
`sdl-config --cflags --libs`