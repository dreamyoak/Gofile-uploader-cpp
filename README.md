# GoFile Uploader c++

This is a simple command-line tool to upload files to [GoFile.io](https://gofile.io/) using their API. It supports uploading any type of file, and displays the response from the API including the download page, guest token, and other useful information.

## Dependencies

- libcurl
- nlohmann/json

## Installation

Clone the repository and compile the source code:

```bash
git clone https://github.com/dynastyoak/Gofile-uploader-cpp.git
cd Gofile-uploader-cpp
g++ -o Gofile-uploader-cpp main.cpp -lcurl
```

## Usage
Run the compiled binary and specify the path to the file you want to upload:

```bash
./gofile-uploader
file path >: /path/to/your/file.txt
```

If the file exists, it will be uploaded to GoFile and the response from the API will be displayed in the terminal.
