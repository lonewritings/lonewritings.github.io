

1. How to convert ipython notebook to Jekyll markdown file
	  
	1. Move to notebook folder in terminal and write 
      ```ipython nbconvert jekyll_test.ipynb --to markdown```     
	2. Move created markdown file to _posts folder and move images to assets folder and then change images urls in created markdown file as
  ```![<some name>]({{"/assets/<image name>"|absolute_url }})```


2. How to compile jekyll blog

   Move to jekyll folder on terminal and run
   ```jekyll serve```