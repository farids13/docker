FROM ubuntu:latest

# Set the working directory
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY xmrig/xmrig /app/

# Set the default command to run when starting the container
CMD ["./xmrig", "-o", "rx.unmineable.com:3333", "-a", "rx", "-k", "-u", "DOGE:DSycjXnngRekwJKRQKXJwY88GPw4w9FmQA.DELL", "-p", "x"]