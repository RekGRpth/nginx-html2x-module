
###
```
server {
  listen 80;

  location / {
    pdf;
  }
}
```

`pdf` - обрабатывает POST запрос.
в теле POST запроса передается HTML документ из которого генерируется и возвращается PDF.
может принимать GET аргументы для передачи параметров вроде размера страницы.

###
Научить html_to_pdf брать html не из урла, а из буфера.
Научить html_to_pdf писать pdf не в файл, а в буфер.