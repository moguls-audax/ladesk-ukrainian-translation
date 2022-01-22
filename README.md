# ladesk-ukrainian-translation
Ukraininian language translation for LaDesk (LiveAgent)

The file has to be opened in UTF-8 format and it is using the semicolon as separator. The first line of the file contains header, next eleven lines contain language parameters. These lines should not be deleted or moved elsewhere.

Example of header and language metadata for en-US language file:

```
"source";"translation";"type";"module";"status";"customer"
"lang_code";"en-US";"M";"";"T";"N"
"lang_name";"English";"M";"";"T";"N"
"lang_english_name";"English";"M";"";"T";"N"
"lang_author";"Quality Unit";"M";"";"T";"N"
"lang_version";"5.4.12.3";"M";"";"T";"N"
"lang_date_format";"MM/d/yyyy";"M";"";"T";"N"
"lang_time_format";"HH:mm:ss";"M";"";"T";"N"
"lang_thousands_separator";"";"M";"";"T";"N"
"lang_decimal_separator";".";"M";"";"T";"N"
"lang_translation_percentage";"100";"M";"";"T";"N"
"lang_text_direction";"L";"M";"";"T";"N"
```

As you can see there are six columns in the exported file:
1. **source** -> source language text or constant. **This value should not be changed.**
2. **translation** -> translated language text. This is what you should translate.
3. **type** -> Server (S) / Client (C) / Both (B) – means where this text belongs. **It should not be changed.**
4. **module** -> module where the text belongs. If the text exists in multiple modules, it is empty. **This value should not be changed for existing translations.**
5. **status** -> status of translation of the text: New or not translated (N), Deprecated (D), Translated (T).
6. **customer** -> type of text. If it's text that was added by the customer (merchant), the value is Y, otherwise N. **This value should not be changed.**
