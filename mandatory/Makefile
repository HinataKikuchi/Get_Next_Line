###################### MANDATORY #######################
NAME		=	libgnl.a
SRCS		=	get_next_line.c \
			get_next_line_utils.c
OBJS		=	${SRCS:.c=.o}

###################### GCC RULES #######################
CC		=	gcc
CFLAGS		=	-Wall -Wextra -Werror
INCLUDE		=	-I./

###################### COMPILE RULES #######################
.c.o:
			@${CC} ${CFLAGS} ${INCLUDE} -o $@ -c $<
			@printf "»»"
all:			$(NAME)
$(NAME): $(OBJS)
			@ar rcs $(NAME) $(OBJS)

clean:;			$(RM) *.o
fclean:clean;		$(RM) $(NAME)
re:			fclean $(NAME)
.PHONY:			re clean fclean all