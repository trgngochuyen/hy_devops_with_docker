# Start from the alpine:3.13 image
FROM alpine:3.13

# Use /usr/src/app as the workdir. The following instructions will be executed in this location
WORKDIR /usr/src/app

# Copy the hello.sh file from this location to /usr/src/app creating /usr/src/app/hello.sh
COPY hello.sh .

# Execute the command with `/bin/sh -c` prefix
RUN touch additional.txt 

# If the file does not have yet execution permissions, we run this during the build
# RUN chmod +x hello.sh

# The command will be ./hello.sh
CMD ./hello.sh

