# How to Add New Posts

Adding a new post to this blog is incredibly simple and requires no backend setup.

## Step 1: Write your Markdown
Create a new file in the `posts/` directory with a `.md` extension. For example, `my-awesome-post.md`.
Write your content using standard Markdown syntax. You can include code blocks, images, links, and headings.

## Step 2: Add it to the Blog List
Open the `blog.html` file in your editor. Locate the `<div id="blog-list">` section.

Copy an existing post card and paste it as a new entry. Update the `href` to point to your new file name (without the `.md` extension).

For example:
```html
<a href="post.html?id=my-awesome-post" class="block bg-white dark:bg-gray-800 p-8 rounded-2xl...">
    <!-- Update Title, Date, and summary here -->
</a>
```

## Step 3: Deploy
Since your site is hosted on GitHub Pages, just commit and push your changes. The site will automatically serve the new markdown file and render it perfectly!

Happy writing!
