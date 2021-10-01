###################### MANDATORY #######################
NAME		=	libgnl_bonus.a
SRCS		=	get_next_line_bonus.c \
			get_next_line_utils_bonus.c
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