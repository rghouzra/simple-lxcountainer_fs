
NAME = simple-container

SRC = simple-lxcontainer_fs.c

OBJ = $(SRC:.c=.o)

all: $(NAME)

$(NAME): $(OBJ)
	gcc $(OBJ) -o $(NAME)

%.o: %.c
	gcc -c $< -o $@

run: $(NAME)
	sudo ./$(NAME)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)
