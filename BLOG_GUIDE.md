# Blog Post Template & Guide

## How to Add Blog Posts to Your Website

### Quick Start

1. Create a new HTML file in the `/blog` folder
2. Use the template below
3. Update the main `index.html` to link to your new post
4. Commit and push to GitHub

---

## Blog Post Template

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="[Your post description]">
    <title>[Post Title] | Sagbo Mitchozounou</title>
    <link rel="stylesheet" href="../css/styles.css">
    <style>
        .blog-post {
            max-width: 800px;
            margin: 0 auto;
            padding: 60px 20px;
        }
        /* Include the styles from pinn-tutorial.html */
    </style>
</head>
<body>
    <!-- Navigation (copy from pinn-tutorial.html) -->
    
    <div class="blog-post">
        <a href="../#blog" class="back-link">← Back to Blog</a>
        
        <div class="post-header">
            <span class="post-category">[Category: Tutorial/Research/Reflection]</span>
            <h1 class="post-title">Your Post Title</h1>
            <div class="post-meta">
                <p><strong>By Sagbo Jean-Claude Mitchozounou</strong></p>
                <p>Published: [Date]</p>
                <p>Reading time: ~X minutes</p>
            </div>
        </div>

        <div class="post-content">
            <!-- Your content here -->
        </div>
    </div>

    <!-- Footer (copy from pinn-tutorial.html) -->
</body>
</html>
```

---

## Step-by-Step: Creating a New Blog Post

### Step 1: Create the HTML File

Save a new file in `/blog/` with a descriptive name:
- `mpi-tutorial.html`
- `domain-decomposition.html`
- `math-career.html`

### Step 2: Structure Your Post

Use the following sections:

```html
<h2>Introduction</h2>
<p>Hook the reader and explain what they'll learn</p>

<h2>Main Topic</h2>
<p>Core content here</p>

<h2>Key Points</h2>
<ul>
    <li>Point 1</li>
    <li>Point 2</li>
</ul>

<h2>Code Examples</h2>
<pre><code>
// Use pre/code tags for code
console.log("example");
</code></pre>

<h2>Conclusion</h2>
<p>Summary and next steps</p>
```

### Step 3: Update Main Index

In `index.html`, find the blog section and add:

```html
<article class="blog-card">
    <div class="blog-category">Tutorial</div>
    <h3>Your Post Title</h3>
    <p class="blog-date">May 2026</p>
    <p class="blog-excerpt">
        Brief description of your post (1-2 sentences)
    </p>
    <a href="blog/your-filename.html" class="blog-link">Read Article →</a>
</article>
```

### Step 4: Commit and Push

```bash
cd /home/jc1er/PersonalSite

git add .
git commit -m "Add blog post: Your Post Title"
git push
```

Your new post will be live in 1-2 minutes!

---

## Blog Categories

Use one of these categories for consistency:

| Category | Best For |
|----------|----------|
| **Tutorial** | Step-by-step guides, how-tos, implementation examples |
| **Research** | Research findings, academic insights, deep dives |
| **Reflection** | Personal experiences, lessons learned, career advice |
| **News** | Research updates, conference announcements |

---

## Formatting Tips

### Headings
```html
<h2>Main Section</h2>
<h3>Subsection</h3>
```

### Lists
```html
<ul>
    <li>Unordered item</li>
</ul>

<ol>
    <li>Ordered item</li>
</ol>
```

### Code Blocks
```html
<pre><code>
your code here
</code></pre>
```

### Inline Code
```html
Use <code>inline code</code> for variables/commands
```

### Emphasis
```html
<strong>Important text</strong>
<em>Emphasized text</em>
```

---

## Example Blog Post Files

Available examples:
- `blog/pinn-tutorial.html` - Complete tutorial post
- Use as reference for structure and styling

---

## Connecting to External Blog Platforms

If you prefer to write on Medium, Hashnode, or dev.to:

1. Write your post on the external platform
2. Update the blog card link to point to your post:
   ```html
   <a href="https://medium.com/@yourname/post-slug" class="blog-link">Read Article →</a>
   ```
3. External links automatically open in a new tab (target="_blank")

---

## SEO Best Practices

1. **Meta Description:** Write compelling meta descriptions (see head section)
2. **Keywords:** Use relevant terms in your title and first paragraph
3. **Headings:** Use h2 and h3 tags for proper hierarchy
4. **Links:** Link to related posts where appropriate
5. **Images:** Consider adding images to blog posts (create an `assets/blog/` folder)

---

## Adding Blog Post Images

1. Create folder: `assets/blog/`
2. Add your images (JPG, PNG, WebP)
3. Reference in your post:
   ```html
   <img src="../assets/blog/your-image.jpg" alt="Description">
   ```

---

## Sample Blog Post Structure

```html
<div class="blog-post">
    <a href="../#blog" class="back-link">← Back to Blog</a>
    
    <div class="post-header">
        <span class="post-category">Tutorial</span>
        <h1 class="post-title">How to Implement Algorithm X</h1>
        <div class="post-meta">
            <p><strong>By Sagbo Jean-Claude Mitchozounou</strong></p>
            <p>Published: May 15, 2026</p>
            <p>Reading time: ~8 minutes</p>
        </div>
    </div>

    <div class="post-content">
        <h2>Introduction</h2>
        <p>What is Algorithm X and why should you care?</p>
        
        <h2>Background</h2>
        <p>Historical context and motivation...</p>
        
        <h2>Implementation</h2>
        <p>Step-by-step guide with code examples</p>
        <pre><code>
# Your implementation code
        </code></pre>
        
        <h2>Performance Analysis</h2>
        <p>Time and space complexity analysis</p>
        
        <h2>Conclusion</h2>
        <p>Summary and next steps</p>

        <div class="post-footer">
            <h3>Questions?</h3>
            <p>Email: <a href="mailto:sagbo.mitchozounou@um6p.ma">sagbo.mitchozounou@um6p.ma</a></p>
            <p><a href="../#blog" class="back-link">← Back to Blog</a></p>
        </div>
    </div>
</div>
```

---

## Publishing Schedule Tips

- Aim for consistency (monthly, bi-weekly, etc.)
- Write drafts in advance
- Announce new posts on LinkedIn and ResearchGate
- Engage with comments and questions

---

## Questions?

For technical issues or suggestions, contact: **sagbo.mitchozounou@um6p.ma**

Happy writing! 📝
