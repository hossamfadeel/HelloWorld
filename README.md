# Hello World Application

This is a simple "Hello World" application written in C++ that is built with CMake.

## Requirements

- C++ Compiler
- CMake (version 3.0 or higher)

## Building the Application

To build the application, follow these steps:

1. Clone the repository to your local machine.

    ```
    git clone https://github.com/hossamfadeel/hello-world.git
    ```

2. Navigate to the directory where you cloned the repository.

    ```
    cd hello-world
    ```

3. Create a new directory for the build and navigate to it.

    ```
    mkdir build && cd build
    ```

4. Run CMake to configure the project and generate a build system.

    ```
    cmake ..
    ```

5. Build the project.

    ```
    cmake --build .
    ```

    On Windows, you might need to specify the build configuration (e.g., `--config Release` or `--config Debug`).

6. After building, you will find the executable in the `build` directory.

To run the application, simply execute the `HelloWorld` binary from the command line. The output should be:
