# compression_project
This code can generate, compress and decompress files using run length encoding.

The encoding works by reading each character with getc and counting how many times that character repeats. If there isn't a repition the code prints 01 representing one occurance but for example if there was a repeating "e7e7e7" it would compress to 03e7.

Available Modes:
  -c     Compress: Performs RLE compression on "filename"
                   and writes result to "filename.rle"

  -x     Expand: Performs RLE expansion on "filename". The
                 supplied "filename" must have the extension
                 ".rle" The result is written to "filename"
                 with the extension ".rle" removed.

  -d     Debug: Prints a hexdump of "filename" to the screen.

  -g     Generate: Writes the test file described in the Project 2
                   assignment document to disk as "filename". Use
                   this file to test and debug your program.
                   
             
