all:
	gcc -Iinclude/ src/app.c src/main.c src/scene.c src/utils.c src/texture.c src/camera.c -lmingw32 -lSDL2main -lSDL2 -lSDL2_image -lobj -lopengl32 -lm -o mario.exe -Wall -Wextra -Wpedantic

linux:
	gcc -Iinclude/ src/app.c src/main.c src/scene.c src/utils.c src/texture.c src/camera.c -lSDL2 -lSDL2_image -lobj -lGL -lm -o mario -Wall -Wextra -Wpedantic
