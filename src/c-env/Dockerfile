FROM gcc:latest

WORKDIR /usr/src/myapp

COPY . .

RUN gcc -o myprogram main.c

CMD ["./myprogram"]
