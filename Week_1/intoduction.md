# Intro

## storing data

1. memory
 -  memory will be cleared on every boot/program start
2. disk
 -  for persistance 
 
 ## Disk storage
  -  plain text files
  -  structured text file
     - json
     - csv/tsv (Comma Separated Value/ Tab Separated Value)
     - xml
     - ini
     - svg (for images, xml file)
 - binary file
     - data in binary format
     - images 
     - audio
     - video

## Examples

 -  unicode.org
 -  https://en.wikipedia.org/wiki/List_of_file_signatures

## plain text

```
Mary River
2024

Report

This year 2024 will be the beginning of new project. Designers of the new project Mary River and Matt Jones attended the launch.......
```

## structured text
```
Writer: Mary River
Year: 2024

Type: Report

This year 2024 will be the beginning of new project. Designers of the new project Mary River and Matt Jones attended the launch.......
```

## json documentation

## better solutions

```json
{
    "writer":{
        "first name":"Mary",
        "last name":"River"
    },
    "year":2024,
    "type":"Report",
    "text":[
        "This year 2024 will be the beginning of a",
        "new project. Designers of the new project",
        "Mary River and Matt Jones attended the launch......."
    ]
}
```

### XML documentation

```xml
<document>
    <writer>
        <firstname>Mary</firstname>
        <lastname>River</lastname>
    </writer>
    <year>2024</year>
    <type>Report</type>
    <text>
        This year 2024 will be the beginning of new project. Designers of the new project Mary River and Matt Jones attended the launch.......
    </text>
</document>
```