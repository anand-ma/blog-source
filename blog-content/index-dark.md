-----------------------------------------------------------------------------
github     : https://github.com/casualwriter/casual-markdown-blog
title      : Sample Blog (Dark Theme)
subtitle   : Simple is the best
nav-group  : featured, new-3, tags, months
nav-width  : 320px
theme      : dark
menu       : 
   Home    : ?
   github  : https://github.com/casualwriter/casual-markdown-blog
   About   : ?page=about.md
-----------------------------------------------------------------------------
<style comment="additional style">
#header { {{css-header}}  }
#left-panel  { width:{{nav-width}} }
#right-panel { left: calc({{nav-width}} + 20px) }
h1 { border-bottom:1px dotted grey }
.nav-post a  { color: teal }
.nav-tag  a  { color: green }
.nav-month a { color: grey }
.post-date   { font-size:10px; color:#aaa }
.post-title  { font-size:16px; }
.post-tags   { left-margin:20px; padding:4px; font-size:10px; color:green }
#md-post a { border-bottom:1px dotted grey }
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