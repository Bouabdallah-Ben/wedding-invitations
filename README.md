# 💍 Wedding Invitation — Mohamed & Abir

A modern, elegant, and mobile-first digital wedding invitation built with **Next.js** and **React**.

The website was designed as a personalized online invitation for the wedding of **Mohamed & Abir**, providing guests with the essential wedding information through an interactive and responsive experience.

---

## ✨ Features

* 💍 Elegant wedding invitation landing page
* 📱 Mobile-first and responsive design
* ❤️ Personalized bride and groom information
* 📅 Wedding date and event information
* ⏳ Wedding countdown
* 🎵 Background music with interactive music controls
* 📍 Wedding venue and location information
* 🗺️ Integrated directions/map links
* 🖼️ Optimized images using Next.js `next/image`
* ✨ Smooth animations and transitions
* 📱 Optimized experience for sharing through messaging and social media
* 🔗 Open Graph metadata for link previews

---

## 🛠️ Tech Stack

| Technology     | Purpose              |
| -------------- | -------------------- |
| **Next.js 16** | React framework      |
| **React 19**   | User interface       |
| **JavaScript** | Application language |
| **CSS**        | Styling              |
| **Next/Image** | Image optimization   |
| **Next/Font**  | Font optimization    |
| **Vercel**     | Deployment           |

---

## 📂 Project Structure

```text
wedding-invites/
│
├── app/
│   ├── layout.js          # Root layout and metadata
│   ├── page.js            # Main invitation page
│   └── ...
│
├── components/            # Reusable UI components
│   └── ...
│
├── public/
│   ├── images/            # Wedding images
│   ├── audio/             # Background music
│   └── ...
│
├── package.json            # Dependencies and scripts
├── next.config.js          # Next.js configuration
├── jsconfig.json           # JavaScript configuration
├── README.md               # Project documentation
└── ...
```

> The exact contents of the `app` and `components` directories may evolve as the project is developed.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js** — LTS version recommended
* **npm**

You can verify your installation with:

```bash
node -v
npm -v
```

---

### 1. Clone the repository

```bash
git clone https://github.com/brahimbbr312/wedding-invites.git
```

Navigate into the Next.js application:

```bash
cd wedding-invites/wedding-invites
```

---

### 2. Install dependencies

```bash
npm install
```

---

### 3. Start the development server

```bash
npm run dev
```

Open the application in your browser:

```text
http://localhost:3000
```

The page will automatically update when you modify the source files.

---

## 📦 Production Build

Before deploying, you can verify that the project builds successfully:

```bash
npm run build
```

To run the production build locally:

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

---

## 🖼️ Images & Assets

Static assets are stored inside the `public` directory.

For example:

```text
public/
├── images/
│   ├── ...
│   └── og-wedding.webp
└── ...
```

Images can be referenced from the application using paths relative to `/public`:

```jsx
<Image
  src="/images/example.webp"
  alt="Wedding"
  width={1200}
  height={800}
/>
```

The project uses Next.js `Image` for optimized image delivery.

---

## 🎵 Music

The invitation includes an interactive background music experience.

Audio files should be placed inside the appropriate directory under `public`, allowing them to be referenced directly by the application.

Example:

```text
public/audio/wedding-music.mp3
```

---

## 📍 Wedding Location

The invitation includes the wedding venue and navigation information so guests can easily find the location.

The route information can be updated directly within the relevant invitation component.

---

## 📱 Responsive Design

The website is designed primarily for mobile visitors while remaining usable on larger screens.

Recommended testing:

* 📱 Mobile phones
* 📲 Tablets
* 💻 Desktop browsers

---

## 🌐 Deployment

The application can be deployed directly to **Vercel**, the platform created by the team behind Next.js.

### Deploy with Vercel

1. Connect the GitHub repository to Vercel.
2. Select the repository:

   ```text
   brahimbbr312/wedding-invites
   ```
3. Set the **Root Directory** to:

   ```text
   wedding-invites
   ```
4. Make sure the framework is detected as:

   ```text
   Next.js
   ```
5. Deploy.

Vercel will automatically build and deploy the Next.js application.

### Production Build

The project uses:

```bash
npm run build
```

as its production build command.

---

## 🔄 Development Workflow

After making changes:

```bash
git status
git add .
git commit -m "Update wedding invitation"
git push
```

When connected to Vercel, pushes to the configured Git branch can automatically trigger a new deployment.

---

## 🎨 Customization

Wedding information, images, colors, text, animations, and other visual elements can be modified directly within the project source.

When customizing the invitation, pay particular attention to:

* Couple names
* Wedding date
* Event information
* Venue
* Map/directions
* Images
* Background music
* Social sharing metadata
* Mobile layout

---

## 🔗 Social Sharing

The project includes Open Graph metadata and a dedicated wedding preview image:

```text
/public/images/og-wedding.webp
```

This allows the invitation to generate a customized preview when its URL is shared on supported platforms.

---

## 📋 Available Scripts

| Command         | Description                  |
| --------------- | ---------------------------- |
| `npm run dev`   | Start the development server |
| `npm run build` | Create a production build    |
| `npm start`     | Start the production server  |

---

## 📄 License

This project is a private/personal wedding invitation website.

Unless a separate license is added to this repository, the project should not be assumed to be licensed for redistribution or commercial use.

---

## 💙 Wedding

### Mohamed & Abir

**Notre mariage — 23 Novembre 2026**

Made with love for a special day. 💍
