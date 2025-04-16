# Frost Link

**Frost Link** is a beautiful and responsive personal link-in-bio page built with **HTML**, **Tailwind CSS**, and **Font Awesome**.  

## Live Demo

**[Frost Link](https://cx48.github.io/FrostLink/)** can be deployed using **GitHub Pages** or **Vercel**

All deployment steps are included at the bottom of this README

## Preview

### Mobile View

<img src="screenshots/frost-link-mobile.png" alt="Frost Link Mobile View" style="max-width: 600px; height: 600px;">

### Desktop View

![Frost Link Desktop View](screenshots/frost-link.png)

## What's Inside

```
📁 FrostLink/
├── index.html       ← Main HTML file
├── style.css        ← (Optional) Custom styles
└── img.png          ← Your profile picture
```

## How to Use FrostLink (Step-by-Step)

#### 1. **Fork the Repository**

1. Click the **Fork** button at the top right of the GitHub repo.
2. This creates a copy of the project under your own GitHub account.

#### 2. **Clone Your Fork**

Open your terminal and run:

```bash
git clone https://github.com/YOUR-USERNAME/FrostLink.git
```

> Replace `YOUR-USERNAME` with your actual GitHub username.

#### 3. **Navigate into the Project Folder**

```bash
cd FrostLink
```

#### 4. **Open in VS Code (or any code editor)**

If you're using **VS Code**, just type:

```bash
code .
```

## Customize Your Page

### Change the Profile Picture

- Replace the `img.png` with your own image (same file name works best).
- Recommended size: 300x300 pixels.

### Update Name & Bio

Inside `index.html`, find:

```html
<h1 class="...">@cx48</h1>
<p class="...">Digital creator | Web developer | Tech enthusiast</p>
```

Change to your name/handle and short description.

### Edit or Add Links

There are 3 sections:

- **Connect With Me** — for social media
- **My Content** — blogs, newsletters, podcasts
- **Quick Links** — donations, bookings, support

### To edit a link:
Find this:

```html
<a href="https://twitter.com" ...>
  <i class="fab fa-twitter"></i>
  <span>Twitter</span>
</a>
```

Replace the URL, icon class, and name

### To add a new link:
Copy this template and paste it into the section you want:

```html
<a href="YOUR_LINK_HERE" target="_blank" class="link-item frost-card flex items-center p-4 rounded-xl">
  <div class="w-8 h-8 rounded-full bg-gradient-to-br from-COLOR1 to-COLOR2 flex items-center justify-center mr-3">
    <i class="fab fa-PLATFORM text-white text-sm"></i>
  </div>
  <span>PLATFORM NAME</span>
  <i class="fas fa-arrow-right ml-auto text-white/50"></i>
</a>
```

💡 Find icon names here: https://fontawesome.com/icons  
Use `fab` for brands (e.g. `fab fa-twitter`) and `fas` for standard icons (e.g. `fas fa-link`)

## Deploy with GitHub Pages

#### 1. **Fork the Repository**

Click the **Fork** button on the top-right of the repo to create a copy under your GitHub account.

#### 2. **Enable GitHub Pages**

1. Go to **Settings** of your forked repository.
2. Scroll down to **Pages** (in the left sidebar or under Code & automation > Pages).
3. Under **Source**, choose:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **Save**.

#### 3. **Wait for Deployment**

After a few seconds, GitHub will provide a link to your live site.

It will look like:
```
https://your-username.github.io/frostlink/
```

#### 4. **Done!**

You can now share that link or customize your site by editing `index.html`.

## Deploy with Vercel

#### 1. **Go to Vercel**  

[https://vercel.com](https://vercel.com)

#### 2. **Import GitHub Repo**

- Click **"Add New Project"**
- Choose your **frostlink** repo from GitHub

#### 3. **Configure (Optional)**

- No special settings are needed—Vercel auto-detects static sites
- Just click **Deploy**

#### 4. **Done!**

You’ll get a public URL like `https://yourname.vercel.app`

You can always update your code, push to GitHub, and Vercel will auto-update the live site

## Customization Tips

- Edit `style.css` to add extra styles or override Tailwind
- Use gradients creatively to group link types
- Add/remove sections as needed

## Credits

- Font Awesome for icons: [fontawesome.com](https://fontawesome.com/)
- Tailwind CSS for utility-first styling: [tailwindcss.com](https://tailwindcss.com/)
- Created with ❤️ 

## Need Help?

Email at [hello@cx48.dev](mailto:hello@cx48.dev) — happy to help!
