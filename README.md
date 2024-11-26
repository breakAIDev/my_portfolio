# My Development History Portfolio
## You can see the my portfolio site that is designed and created to be very user-friendly here and it is easily customizable so it is for both you and freelancers to use comfortable.

---

# View live preview [here]()

---

# Table of Contents :scroll

- [Sections](##sections-bookmark)
- [Demo](#demo-video-and-image)
- [Installation](##installation-arrow_down)
- [Getting Started](#getting-started)
- [Usage](#usage-joystick)
- [Packages Used](#packages-used-package)

---

## Sections bookmark

- Hero Section
- About Me
- Experience
- Skills
- Projects
- Education
- Blog
- Contacts

--- 

## Demo: video and image
![](./public/image/screen.png)

---

## Installation arrow_down

### You will need to download Git and Node to run this project.

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

---

## Getting Started

## Fork and Clone the repo

```
git clone https://github.com/<YOUR GITHUB USERNAME>/portfolio.git

cd portfolio
```

## Install packages from the root directory

```bash
npm install
# or
yarn install
```

## Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

---

# Usage :joystick:

Goto [emailjs.com](https://www.emailjs.com/) and create a new account for the mail sending. In free trial you will get 200 mail per month. After setup `emailjs` account, Please create a new `.env` file from `.env.example` file.

Eg:

```env
NEXT_PUBLIC_EMAILJS_SERVICE_ID =
NEXT_PUBLIC_EMAILJS_TEMPLATE_ID =
NEXT_PUBLIC_EMAILJS_PUBLIC_KEY =
```

### Then, Customize data in the `utils/data` [folder](https://github.com/athenea0118/portfolio/tree/main/utils/data).

Eg:

```javascript
export const personalData = {
  name: "Kadueng Xaysongkham",
  profile: "/profile.png",
  designation: "Full-Stack Software Developer",
  description: "My name is Kadueng Xaysongkham....",
  email: "tonywilson930727@gmail.com",
  phone: "+8562099487362",
  address: "Vientiane, Laos",
  github: "https://github.com/IanOliver0318",
  facebook: "https://www.facebook.com/profile.php?id=61567158248931",
  linkedIn: "https://www.linkedin.com/in/kadueng-xaysongkham-3b53a5335//",
  twitter: "https://x.com/IanOliver0318",
  stackOverflow: "https://stackoverflow.com/users/27899849/kadueng",
  devUsername: "IanOliver0318",
  resume: "...",
};
```

`devUsername` Used for fetching blog from `dev.to`.

---

---

# Packages Used :package:

| Used Package List  |
| :----------------: |
|        next        |
|  @emailjs/browser  |
|    lottie-react    |
| react-fast-marquee |
|    react-icons     |
|   react-toastify   |
|        sass        |
|    tailwindcss     |

---
