# Rawdata HTML + JS Converter

#### Instructions

Create a sample of 0.3sec or less in Audacity or any other audio editor and output the RAW data. After that, you can easily spit out the binary data by drag and dropping the RAW data onto the page, It will then spit out the binary data and you can use these in your projects.

#### Description

When handling large data, if the system can operate files, it can be handled by reading and writing files, but Arduino alone has no choice but to have data in the program area.
Data is placed in a few to several tens of kB of Flash memory and read from there.
If it is text data, it is quite likely to put it on the program, but in the case of binary data, I think about how to bring the data.

Usually, large data is stored in a file, so I think it is realistic to convert it to an array as it is.
That's why I made a conversion script with HTML5 + JavaScript.
A collection of sample programs + style sheets are messy, but I think it's easy to use because it's just Drag & Drop.

If your system is capable of file operations, you can read and write files to handle large data, but when using Arduino alone, it is easiest to hold data in the program area.
However, the Arduino can only hold and read data in the program area, which is a just a few to 10 kB of Flash memory.

If it's text data, you can probably get away with putting it in the program, but if it's binary data, you'll have to think about how to get the data.
Usually, large data is stored in a file, so I think it is more practical to convert it directly into an array.

So, I made a conversion script in HTML5 + JavaScript.
It's a mishmash of sample programs and stylesheets, but I think it's easy to use because you just drag and drop.

