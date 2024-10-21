NAME	= pokeapi
SRCS 	=	
OBJS 	=	$(SRCS:.cpp=.o)

all: $(NAME)

$(NAME): $(OBJS)
	gcc $(OBJS) -o $(NAME)

%.o: %.cpp
	gcc -c $< -o $@

clean:
	rm -f $(OBJS)
	
fclean: clean
	rm -f $(NAME)

re: fclean $(NAME)

.PHONY: all clean fclean re