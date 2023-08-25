# creat_makefile_generate_automatically_files_in_c

1. Make sure you have the necessary permissions to execute the script.

2. Run the script using the following command:

   ```bash
   ./create_makefile_generate_automatically_files_in_c.sh

The script will start monitoring the directory for new .c files and will automatically generate or update the Makefile as needed.

    The script will keep running indefinitely. To stop the script, press Ctrl + C.

Important Notes

    The script uses a simple polling mechanism to detect changes in the directory. While this approach doesn't require any external dependencies, it may not be the most efficient solution for all scenarios.

    Ensure that the script and the Makefile generated are located in the same directory where you want to compile the C source files.

    The script includes a sleep time of 5 seconds between checks for new files. You can adjust this value according to your preferences and system resources.
