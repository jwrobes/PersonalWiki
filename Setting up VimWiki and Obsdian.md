:vim:obsidian:vimwiki:notes:

# VimWiki and Obsidian together

1. First get VimWiki and follow the steps on this [blog](https://mkaz.blog/working-with-vim/vimwiki/)
1. Then download Obsidian from [[https://obsidian.md/|here]] and install it on your mac
1. When installing Obsidian pick a folder on your laptop to be where you store you obsidian files
1. Then you have to configure VimWiki to create all its file in that Obsidian folder like it says 
   [here](https://forum.obsidian.md/t/integrate-with-vim-wiki/11626)
   ```
   let g:vimwiki_list = [{'path': '~/repos/obsidian/',
                      \ 'syntax': 'markdown', 'ext': '.md'}]
   ```
   I put it in my personal folder on my work laptop so it looked like this
   ```
   let g:vimwiki_list = [{'path': '~/personal/obsidian/Jwrobes',
                      \ 'syntax': 'markdown', 'ext': '.md'}]
   ```
1. Now let's play with some of the formats available for Vim Wiki and see how they look in Obsidian  
   1. Tables
   
| First | Last   | Number       | zip   | religion |
|-------|--------|--------------|-------|----------|
| Jon   | Wrobel | 555-555-5555 | 94606 | pagan    |
| Jane  | Doe    | 555-555-5555 | 94947 | droos    |
1. What about code blocks with code syntax as they have in github
```rb
 def test
   puts 'test'
 end
```
1. What about backing up things and publishing them to github.  Not yet I'll save this for later
1. What about images that I want to have, can I drop in screen shots and have them stored and saved in markdown?
![[EverythingFine 1.png]]
![[EverythingFine 1.png]]
   1. I have found one way just using the Obsidian app, I can copy and paste an image and drop it directly into the editor when it is in edit mode
   1. But this is not that easy when I'm taking notes from vim and I want to grab a screen shot that I take, and I have questions around if I need to do it quickly.
   1. I have a question, what if I actually create a script or look for a script where I can grab a file name and add it into my wiki doc quickly.  And what will this look like in github?
1. Back to seeing if I sync things in Github
