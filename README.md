# No Output Buffer Sort (replacement selection)

No output buffer sort is an optimization of external merge sort for memory-constrained embedded devices. It uses less memory than external merge sort and is significantly faster when the memory is limited. The algorithm was published in the ACM Transactions on Embedded Computing Systems in 2021 ([paper](https://dl.acm.org/doi/10.1145/3446976)). It uses replacement selection that improves performance especially if the data is partially sorted.

No output buffer sort  has the following benefits:

1. Reduces the minimum memory usage to 1 KB which is 33% less than external merge sort.
2. Uses replacement selection to build sorted runs. This improves performance especially for partially sorted data.
3. No use of dynamic memory (i.e. malloc()). 
4. Easy to use and include in existing projects. 
5. Open source license. Free to use for commerical and open source projects.

## License
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Code Files

* no_output_buffer_sort_replace.c, no_output_buffer_sort_replace.h - implementation of no output buffer sort
* test_no_output_buffer_sort_replace.c - test file


#### Ramon Lawrence<br>University of British Columbia Okanagan

