SRCS = main.c \
	  math.c \

OBJS = ${SRCS:%.c=%.o}

NAME = problem_c

#Linking step:
${NAME}: ${OBJS}
	gcc ${OBJS} -o ${NAME}

#Compilation step:

%.o: %.c math.h
	gcc -c $< -o $@

clean:
	rm -f math.o main.o

fclean: clean
	rm -f problem_c

re: fclean ${NAME}



