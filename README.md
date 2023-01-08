# Csv2Json
An Elm web application that converts CSV files to JSON files that does not require you to upload your (potentially confidential) files.

You can web application using this link: https://yokurang.github.io/Csv2Json/

## Inspiration 
Sometimes people need to convert CSV files to JSON files for whatever reason. Usually, people turn to online converters to do this. However, there are two problems with online CSV to JSON converters.

1) They can not handle CSV files that are too large
2) Most online conveters will have you upload your files to their network 

This can be problematic if you need to convert very large files or if your files contain confidential information. Out of this concern, I decided to build a CSV to JSON converter that can handle (very) large CSV files and does not require the files to be uploaded to the network. This way, users can enjoy a reliable CSV to JSON converter that protects their privacy. 

## Installation 
1) Clone my repository or download as a Zip file. 
2) Make sure that Elm is installed. 
3) Enter the following command and then open the index.html file.

```
elm make src/Main.elm
```

Success!
