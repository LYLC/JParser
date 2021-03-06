

## Introduction

JParser was originally developed in C++ to parse USN Journal files ($J) on Linux. It was re-developed in Swift 4. Use it as is. It supports Linux(Ubuntu) and macOS. Testings have been done before this release. However, please feel free to reach out to me if any bugs are found.

## Version
0.3.0

## Usage
Usage: jparser [-h] [-w OUTPUT_FILE] [JOURNAL_FILE]

Options:  
-h,–help Show this help message  
-w,–write OUTPUT_FILE Write the journal data in a file

## Example
jparser -w output.csv J

## Supported Output Format
L2TCSV

## Supported Operating Systems
* Ubuntu 16.04 x64 (tested)
* macOS High Sierra (tested)

It may work on other Ubuntu version. However, testings are required to confirm it.

## Dependency
Ubuntu: Latest Swift 4.2 libraries (https://swift.org/download/).

1. Download the Swift 4.2 package according to your Ubuntu version
2. Unpack the package.
3. In the unpacked package, the library files (\*.so) can be found in "/usr/lib/swift/linux"
4. Copy them to /usr/lib or other shared library folders. Alternatively, define your own shared library folder for those files.

## SHA256
61506b4823bf35dde1f10fdf377038f5a55cc0ebf1dc767d6463e6a1759f9787  jparser-0.3.0-macOS.zip
e5e4f694cb4f8450d53fea496ca86ac5a7573b22c781e70a75cb110dd92c4a26  jparser-0.3.0-Ubuntu-x64.zip

## Notes
* Currently, this tool only supports UTC.  
* The date format is yyyy-mm-dd.

## License
Apache License 2.0
