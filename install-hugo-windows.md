# Run as admin on Windows
>> choco install hugo -confirm

# Windows “extended” Sass/SCSS version
>> choco install hugo-extended -confirm


----------------------------------------------------
# Create a New Site

# hugo version
Hugo Static Site Generator v0.59.1/extended windows/amd64 BuildDate: unknown

mhatr@LAPTOP-0AIQ4IVM C:\Users\mhatr
# cd c:\

mhatr@LAPTOP c:\
# mkdir hugo

mhatr@LAPTOP c:\
# cd hugo

mhatr@LAPTOP c:\hugo
# hugo new site PrashantMhatre
Congratulations! Your new Hugo site is created in c:\hugo\PrashantMhatre.

Just a few more steps and you're ready to go:

1. Download a theme into the same-named folder.
   Choose a theme from https://themes.gohugo.io/ or
   create your own with the "hugo new theme <THEMENAME>" command.
2. Perhaps you want to add some content. You can add single files
   with "hugo new <SECTIONNAME>\<FILENAME>.<FORMAT>".
3. Start the built-in live server via "hugo server".

Visit https://gohugo.io/ for quickstart guide and full documentation.

----------------------------------------------------

mhatr@LAPTOP c:\hugo
# cd PrashantMhatre

mhatr@LAPTOP c:\hugo\PrashantMhatre
# hugo new posts/my-homepage.md
c:\hugo\PrashantMhatre\content\posts\my-homepage.md created

# cd PrashantMhatre

mhatr@LAPTOP c:\hugo\PrashantMhatre
# hugo new posts/my-homepage.md
 (c:\hugo\PrashantMhatre\content\posts\my-homepage.md created

----------------------------------------------------
## Content of my-homepage.md (c:\hugo\PrashantMhatre\content\posts\my-homepage.md 
<pre>
| ---
| title: "My Homepage"
| date: 2019-11-21T20:58:18-05:00
| draft: true
| ---
----------------------------------------------------
</pre>


----------------------------------------------------
# Generate Static SIte

mhatr@LAPTOP c:\hugo\PrashantMhatre
# hugo -D
<pre>
Building sites … WARN 2019/11/21 21:05:22 found no layout file for "HTML" for "page": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2019/11/21 21:05:22 found no layout file for "HTML" for "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2019/11/21 21:05:22 found no layout file for "HTML" for "section": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2019/11/21 21:05:22 found no layout file for "HTML" for "home": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
WARN 2019/11/21 21:05:22 found no layout file for "HTML" for "taxonomyTerm": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.

                   | EN
+------------------+----+
  Pages            |  4
  Paginator pages  |  0
  Non-page files   |  0
  Static files     |  0
  Processed images |  0
  Aliases          |  0
  Sitemaps         |  1
  Cleaned          |  0

Total in 39 ms
</pre>


NOTE: Without theme, Hugo will create xml output only.
