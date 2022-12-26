# Create custom nginx image instead of installing apt package

## Roadmap for creating custom image

1. Get a good base image for building the application, like ubuntu
1. Install necessary build dependencies on the base image
1. Copy the `nginx-1.19.2.tar.gz` file inside the image
1. Extract the contents of the archive and get rid of it.
1. Configure the build, compile and install the program using the make tool.
1. Get rid of the extracted source code.
1. Run nginx executable.