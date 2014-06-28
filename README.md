Worked through the http://www.nodebeginner.org/ book. 

A few small things from the ebook that may fail when you go through the book:

- The directory that contains the image needs to exist. Also, it might be eaiser to create the image folder in your working directory and reference as such, so: './tmp/test.png' instead of '/tmp/test.png'

- In the final step, Chrome kept on displaying the plain text of the response, not the image with a src of '/show '. I think Chrome had cached the text-only response? 