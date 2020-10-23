# Defines the Compiler
# For C use gcc
# For C++ use g++
CC = g++

# Creating a list of source files found in the specified folder
# Replace "your_src_folder" with your relative folder name
src = $(wildcard your_src_folder/*.cpp)

# Sets the name of your compiled application
name = your_application_name

# Standard building rule to compile the application from the sourcefiles
build: $(src)
	$(CC) -o $(name) $^

# Clean rule to remove the binary file
clean:
	rm -f $(name)
