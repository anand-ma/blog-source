-----------------------------------------------------------------------------
github     : https://github.com/casualwriter/casual-markdown-blog
title      : Casual-Markdown's Blog 
subtitle   : Simple is the best
nav-group  : featured, new-3, tags, months
nav-width  : 320px
css-header : background:linear-gradient(to bottom right, #06c, #fc0); color:white
menu       : 
   Home    : ?
   github  : https://github.com/casualwriter/casual-markdown-blog
   Dark    : javascript:darkmode()
   About   : ?page=../blog-content/about.md
-----------------------------------------------------------------------------
<style comment="additional style">
#header { {{css-header}}  }
#left-panel  { width:{{nav-width}} }
#right-panel { left: calc({{nav-width}} + 20px) }
h1 { border-bottom:1px dotted grey }
.nav-post a  { color: teal }
.nav-tag  a  { color: #06c }
.nav-month a { color: grey }
.post-date   { font-size:12px; font-weight:400; }
.post-title  { font-size:16px; color:#333 }
.post-tags   { left-margin:20px; padding:4px; font-size:10px; color:green; font-weight:400 }
</style>

<div id="md-post">
# Featured

## [Markdown as blog](../blog-content/20220820-markdown-as-blog.md)
> ![build blog site by markdown files](../blog-content/campo01.jpg)
> date:2022/08/20, tags: `#markdown, #blog`
> 
> build blog site by markdown files in minutes.
> host on github, or other static web hosting  

# Archives
   
### Aug 2022
                    
* 2022/08/20: [Markdown as blog](../blog-content/20220820-markdown-as-blog.md) { #markdown, #blog, #featured }

### July 2022
                    
* 2022/07/31: [release of casual-markdown v0.90](../blog-content/20220731-casual-markdown-v0.90.md) { #markdown, #regexp }
</div>