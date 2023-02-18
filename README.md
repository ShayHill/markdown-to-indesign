# markdown with svg to InDesign

* Starting with `document.md`, a simple markdown file with

~~~
![image caption](image.svg)
~~~

* Convert to `document.docx` with pandoc

~~~
pandoc -s -f markdown -t docx -0 document.docx document.md
~~~

`image.svg` *is* in `document.docx`

* Open InDesign `18.1 x64`

* Create a default document

* File > Place > select `document.docx`

* place `document.indd`

The image is missing.

I can place the *same* image manually into the `document.indd` and everything is fine.

