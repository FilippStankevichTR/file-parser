# Book parser

You need to design and code application that read files of different format into domain objects
Bear in mind that design should be object oriented and needs to support adding new file formats in furture

## Input file samples

*books.json*
```json
{
    "books" : [
        {
            "title": "Java",
            "author": "Eckel",
            "year": 2004
            "pages": 500
        },
         {
            "title": "C#",
            "author": "Schildt",
            "year": 2003
            "pages": 800
        }
    ]
}
```

*books.txt*

```csv
Java,Eckel,2004,500
C#,Schildt,2003,800
```
