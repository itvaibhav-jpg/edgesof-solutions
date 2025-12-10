# EdgesOf Solutions - Setup Guide

## 🎉 Your Website is LIVE!

**URL:** https://itvaibhav-jpg.github.io/edgesof-solutions/

---

## 📸 Add Your Professional Photo

### Option 1: Upload via GitHub Web Interface (Easiest)

1. Go to: https://github.com/itvaibhav-jpg/edgesof-solutions
2. Click on `images` folder
3. Click "Add file" → "Upload files"
4. Upload your professional photo (name it: `kumar-vaibhav.jpg`)
5. Commit changes
6. Edit `index.html` and replace the placeholder sections with:

```html
<!-- In hero section, replace the placeholder div with: -->
<img src="images/kumar-vaibhav.jpg" alt="Kumar Vaibhav" class="hero__img">

<!-- In about section, replace the placeholder div with: -->
<img src="images/kumar-vaibhav.jpg" alt="Kumar Vaibhav" class="about__img">
```

### Option 2: Use External URL (Fastest)

If your photo is already hosted online:

1. Edit `index.html`
2. Replace placeholder divs with:

```html
<img src="YOUR_PHOTO_URL" alt="Kumar Vaibhav" class="hero__img">
```

---

## 🎨 Add Project Screenshots

1. Upload project images to `images/projects/` folder
2. Name them: `aims2health.jpg`, `mediscript.jpg`, `recore-ams.jpg`
3. Update the project cards in `index.html` to include images

---

## 📧 Set Up Contact Form

### Using EmailJS (Free, Easy):

1. Sign up at https://www.emailjs.com
2. Create email service
3. Get your Public Key, Service ID, Template ID
4. Add this before `</body>` in `index.html`:

```html
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
<script>
    emailjs.init('YOUR_PUBLIC_KEY');
</script>
```

5. Update the form submission in `js/main.js`

---

## 🔗 Update Social Media Links

In `index.html`, find the footer section and update:

```html
<a href="https://linkedin.com/in/YOUR_PROFILE" target="_blank">
<a href="https://github.com/itvaibhav-jpg" target="_blank">
<a href="https://twitter.com/YOUR_PROFILE" target="_blank">
```

---

## 📊 Add Google Analytics

1. Create account at https://analytics.google.com
2. Get Measurement ID (G-XXXXXXXXXX)
3. Add to `<head>` in `index.html`:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

## 🚀 Quick Edits

All content is in `index.html` - you can edit directly on GitHub:

1. Go to the file
2. Click the pencil icon (Edit)
3. Make changes
4. Commit changes
5. Wait 1-2 minutes for site to update

---

## ✅ Current Status

- ✅ Website deployed and live
- ✅ Responsive design working
- ✅ Navigation functional
- ✅ Contact form ready (needs email integration)
- ⏳ Add your professional photo
- ⏳ Add project screenshots
- ⏳ Set up email service
- ⏳ Add Google Analytics

---

## 📞 Need Help?

Email: vaibhav.iimcal@gmail.com
Phone: +91-9999456126

---

**Your website is live and ready to customize!** 🎉