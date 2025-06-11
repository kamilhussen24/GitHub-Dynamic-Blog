
# 📰 GitHub Dynamic Blog using GitHub Pages

This project is a **dynamic blogging system** powered entirely by **GitHub Pages**. It allows you to write blog articles using plain `.html` files inside a `/post` directory, and the homepage (`index.html`) will automatically display them as individual blog posts — similar to Blogger, but without any CMS.

Ideal for developers, writers, and tech-savvy users who want a lightweight, fast, and free blogging platform.

---

## 🚀 Features

- ✅ **Dynamic Blog Posts**: All `.html` files inside the `/post` folder are treated as blog posts.
- ✅ **Automatic Post Listing**: The homepage (`index.html`) fetches the list of blog posts dynamically using the **GitHub Content API**.
- ✅ **No CMS Needed**: Write your articles directly in HTML — clean, fast, and flexible.
- ✅ **Static + Fast**: No backend or database needed. Entirely runs on GitHub Pages.
- ✅ **Free Hosting**: Uses GitHub’s free Pages hosting.
- ✅ **Open to Contributions**: Designed to be forkable and customizable.

---

## 🧠 How It Works

This system uses the **GitHub Content API** (`https://api.github.com/repos/{owner}/{repo}/contents/post`) to dynamically retrieve the list of `.html` files from the `/post` directory and renders them on the homepage.

So, whenever you add or remove `.html` files inside `/post/`, they are instantly reflected on the blog’s homepage — no manual updates required.

---

## 📁 Folder Structure

```
/
├── index.html               # Main homepage (lists all posts)
├── /post/                   # Folder containing all your blog posts
│   ├── article1.html
│   ├── article2.html
│   ├── ...
│   └── /image/              # Blog-specific images stored here
│       ├── post1-img.png
│       ├── post2-banner.jpg
│       └── ...
└── /assets/ (optional)      # CSS, JS, global images, etc.
```

---

## 🛠️ How to Use

1. **Fork this repository** or clone it to your local machine.
2. Inside the `/post` folder, create a new `.html` file for each blog post.
   - Example: `/post/my-first-post.html`
3. Place any images related to the post inside `/post/image/`.
   - Reference them in your post like: `<img src="image/my-image.png">`
4. Make sure `index.html` uses JavaScript to call the GitHub API and render post links (already configured).
5. Push your changes to GitHub.
6. Enable GitHub Pages from the repository settings.
7. Your blog is now live at `https://your-username.github.io/your-repo-name`.

---

## 🖼️ Blog UI Preview

This is how your homepage will look with live blog posts:

![Blog Screenshot](post/image/demo.jpg)

---

## 🌐 Live Demo

Check out a live demo of the blog system here:

🔗 [Live Demo](https://kamilhussen24.vercel.app/blog)

*(Replace the URL with your actual GitHub Pages link)*

---

## 👥 Contributing

Want to help improve this project? Contributions are warmly welcome!

1. Fork the repo
2. Make your changes
3. Submit a Pull Request with a brief description

Please follow proper formatting and naming conventions for consistency.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Credits

Maintained by [Kamil Husseen](https://github.com/kamilhussen24).  
Powered by GitHub Pages and the GitHub Content API.
