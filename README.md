This theme is modified based on the Hugo PaperMod theme: https://github.com/adityatelange/hugo-PaperMod

1. Cloning the Codebase
   ① Use git clone to fetch the code to your desktop. This will create a directory named sulv-hugo-papermod on your desktop.

② Navigate into the sulv-hugo-papermod directory and run git submodule update --init. This command fetches the submodule under themes/hugo-PaperMod/, which contains the official theme.

2. Starting the Interface
   ③ Navigate to the sulv-hugo-papermod directory. In the terminal, run hugo server -D and open localhost:1313 in your browser to view the ready-made blog template.

3. Modifying Information
   There are several personal information fields within the template that need to be configured manually. Please take your time to modify these. You can refer to the blogger's website creation tutorial for guidance: https://www.sulvblog.cn/posts/blog/

4. Usage of Shortcodes
   bilibili: {{< bilibili BV1Fh411e7ZH(fill in bvid) >}}

youtube: {{< youtube w7Ft2ymGmfc >}}

ppt: {{< ppt src="URL" >}}

douban: {{< douban src="URL" >}}
