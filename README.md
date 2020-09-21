# Concurrent Cloud Classifier


## A few things to note when running the scripts:

1. After running the "make" command, all the necessary compilations of source files occurs.

2. Do not call "make run" because it does not allow you to pass command-line arguments in. Rather run the program by calling "java CloudDataThreaded \<input_file> \<output_file>" from the bin directory. You will then see the run times for all of the tests in the terminal.

	* \<input_file> - The data related to the cloud classifications and prevailing winds
	* \<output_file> - The true cloud classifications and prevailing winds

3. Ensure the input file is in the bin directory.

4. I have included a directory called "Other Java" which contains two classes:

	* CloudClassification.java - was used to compare the produced output to the given output.
	* SampleGenerator.java - used to generate input data files.