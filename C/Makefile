CC=gcc
CFLAGS=-g -Wall -std=c11
BINS=simple_shell

all: $(BINS)

%: %.c
	$(CC) $(CFLAGS) $^ -o $@

clean:
	$(RM) $(BINS)
