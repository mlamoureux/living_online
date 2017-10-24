# EBook - Hugo

Notes on using Hugo are here: https://gohugo.io/



Hugo is used to make books. Somehow, I did this for the book intro.syzygy.ca, but I really don't remember how. This will take some re-contruction.



We have a PIMS repo of the syzygy book here:



https://github.com/pimsmath/syzygy-intro



You can see that there are all sorts of folders and files in there, and there is some kind of organizational structure to it. I'm not sure I understand it all -- a lot of it came from Ian, or Jim, who worked hard to make the book look nice and function well. 



Inside the folder "content" is most of the stuff I wrote. But somehow my content got compressed into single files, with lots of text in them. Maybe this is part of Ian's work to optimize things. 



To install Hugo, read the online notes above. I had to update my version of Ruby to get this to work. 



Here are some commands to get a new hugo site started. From terminal, of course:



- hugo new site LivingOnline

- cd LivingOnline

- git init

- git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke

- echo 'theme = "ananke"' &gt;&gt; config.toml

- hugo new posts/my-first-post.md

- hugo server -D



This is the draft mode. 

Point your web browser at http://localhost:1313 to see the details. If you edit the content files, the local host will update your webpage automatically. However, some of the config files will not necessarily update automatically. 



