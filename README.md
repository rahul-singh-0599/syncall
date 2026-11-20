# syncall
Cross-Browser and Cross-Device sync service

Name for each new bookmark - **Save Bookmark**
URL for each new bookmark

```js
javascript:(()=>{const u='rahul-singh-0599',r='syncall',t=document.title,l=location.href,s=window.getSelection().toString().trim();window.open(`https://github.com/${u}/${r}/issues/new?template=add-bookmark.yml&title=${encodeURIComponent('Bookmark: '+t)}&name=${encodeURIComponent(t)}&url=${encodeURIComponent(l)}&description=${encodeURIComponent(s)}`,'_blank');})();
```