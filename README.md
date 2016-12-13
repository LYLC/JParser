● Introduction

JParser was developed in C++ programming language to parse USN Journal files ($J) on Linux. This is an initial release. Use it as is. Testings have been done before this release. However, please feel free to reach out to me if any bugs are found.

● Usage

Usage: jparser [-h] [-w OUTPUT_FILE] [JOURNAL_FILE]

Options:

-h,–help Show this help message

-w,–write OUTPUT_FILE Write the journal data in a file

● Example

jparser -w output.csv J

● Supported Output Format

L2TCSV

● Supported Operating Systems

Ubuntu 14.04 x64 (tested)

Ubuntu 16.04 x64 (tested)

It may work on other Linux distributions. However, testings are required to confirm it.

● Dependency

libc++1

● Notes
- Currently, this tool only supports UTC.
- The date format is yyyy-mm-dd. 
