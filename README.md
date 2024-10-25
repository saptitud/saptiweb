# 🚀 SAPtiweb

## ⚗️ Local environment setup

Follow these steps to preview the Jekyll site locally on Fedora.

1. **Install Ruby and Jekyll**

    First, install Ruby and necessary development tools using the following command:

    ```bash
    sudo dnf install ruby ruby-devel @development-tools
    ```

2. **Next, install Bundler and Jekyll**

    ```bash
    sudo gem install bundler jekyll
    ```

3. **Build and Serve the Jekyll Site**

    To build and serve your Jekyll site locally, use the following command:

    ```bash
    jekyll serve
    ```

4. **Preview the Site Locally**

    Once the server starts, open your browser and go to:

    ```bash
    http://localhost:4000
    ```

## ✍️ Create a New Post

To create a new post for your Jekyll site, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/saptitud/saptiweb.git
    ```

2. **Navigate to the `_posts` directory:**

   Navigate to the `_posts` directory within your Jekyll site.

   ```bash
   cd _posts
   ```

3. **Create a New Markdown File:**

   Use the following naming convention for your new post: `YEAR-MONTH-DAY-title.md`. Replace `YEAR`, `MONTH`, `DAY`, and `title` with the appropriate values.

   ```bash
   touch 2024-01-01-new-post-title.md
   ```

4. **Add Front Matter and Content:**

   Open your newly created file and add the front matter at the top. The front matter should include details such as layout, title, date, categories, tags, and an image if desired.

   ```yaml
   ---
   layout: post
   title: "New Post Title"
   subtitle: "New Post Subtitle"
   date: 2024-01-01
   categories: blog
   tags: [tag1, tag2]
   image: /assets/images/new-post-image.jpg
   ---
   ```

    Below the front matter, add the content of your post. You can use Markdown syntax to format your text, add images, links, etc.

    If there is an image in your post, include the path to the image in the `image` field in the front matter and save the image to the `assets/images` directory.

5. **Save and Preview:**

    Save your changes and preview your site using the `jekyll serve` command as described above to ensure your new post appears as expected.

6. **Make a PR with the changes:**

   Once you have made the necessary changes, push your changes using the following command:

   ```bash
   git add .
   git commit -m "Add new post"
   git push origin main
   ```

   Finally, open a pull request on GitHub to submit your changes.
