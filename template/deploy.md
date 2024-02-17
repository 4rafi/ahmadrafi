C:\Users\Windows10\Documents\Personal Blog\ahmadrafi>npx quartz sync

https://quartz.jzhao.xyz/hosting#github-pages
https://github.com/jackyzha0/quartz/
https://notes.nicolevanderhoeven.com/How+to+publish+Obsidian+notes+with+Quartz+on+GitHub+Pages
https://nicolevanderhoeven.com/blog/20240126-how-to-publish-your-notes-for-free-with-quartz/
### Build your site locally

Before you publish your site online, you should verify that it all works on your computer. This requires "building" the site by running a Quartz server that will convert the Markdown to HTML so that you can see it on your web browser.

Then, in your terminal, run this command:

```
npx quartz build --serve
```

You should see a block of text that includes this line:

```
Started a Quartz server listening at http://localhost:8080
```

Open up your web browser and type in `http://localhost:8080`