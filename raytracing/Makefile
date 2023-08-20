NAME = raycasting

CC = gcc

FLAGS = -Wall -Wextra -Werror

SOURCES = raycasting.c


MLXLIBRARY = -Lmlx -lmlx -Imlx -framework OpenGL -framework AppKit
MINILIBX = mlx

all:
	make -s -C $(MINILIBX)
	$(CC) $(FLAGS) $(SRCS)  $(MLXLIBRARY) -o $(NAME)

clean:

fclean: clean

	make clean -C $(MINILIBX)
	rm -rf $(NAME)

re: fclean all
