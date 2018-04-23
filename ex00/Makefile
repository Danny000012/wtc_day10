# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: dseabela <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/01/22 18:08:22 by dseabela          #+#    #+#              #
#    Updated: 2018/01/22 18:17:21 by dseabela         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC_PATH = ./srcs/

SRC = $(SRC_PATH)ft_putchar.c $(SRC_PATH)ft_putstr.c $(SRC_PATH)ft_strcmp.c \
	  $(SRC_PATH)ft_strlen.c $(SRC_PATH)ft_swap.c

HDR = ./includes/

OBJ = ft_putchar.o ft_putstr.o ft_strcmp.o ft_strlen.o ft_swap.o

all: $(NAME)

$(NAME):
		gcc -Wall -Wextra -Werror -c -I $(HDR) $(SRC)
		ar rc $(NAME) $(OBJ)

clean:
		/bin/rm -rf *.o

fclean: clean
		/bin/rm -rf $(NAME)

re: fclean all
