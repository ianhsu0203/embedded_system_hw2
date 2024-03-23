This is README file for embedded system hw2
Author: b10502139 許禎勻
Date: 2024/3/21
=====
SYNOPSIS:

NTU_sort -[IS|MS|QS|RQS|HS] <input_file_name> <output_file_name>

This program supports three different sorting methods: insertion sort, merge sort and heap sort.
=====
DIRECTORY:

bin/	  executable binary
doc/	  reports
inputs/   input data (unsorted)
outputs/  output result (sorted)
lib/	  library
src/ 	  source C++ codes
utility/  checker
======
HOW TO COMPILE:

directly build
======
HOW TO RUN:

	cd bin/
	./bin/NTU_sort -[IS|MS|QS|HS] <input_file_name> <output_file_name>
	For example,
	under <student_id>_pa1
	./bin/NTU_sort -MS inputs/1000.case1.in outputs/1000.case1.out
======
HOW TO VERIFY RESULT

    cd utility/
    ./PA1_Result_Checker <result_file_name>
	For example,
	under <student_id>_pa1
	./utility/PA1_Result_Checker ./output/5.case1.out

OTHER NOTICE:
