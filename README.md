<h1 align="center">Mirage Master - An AI SaaS Platform</h1>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🚨 [Credits](#credits)

## <a name="introduction">🤖 Introduction</a>

Mirage Master is an AI image SaaS platform that excels in image processing
capabilities, integrates a secure payment infrastructure, offers advanced image
search functionalities, and supports multiple AI features, including image
restoration, recoloring, object removal, generative filling, and background
removal. This project can be a guide for your next AI image tool and a boost to
your portfolio.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- MongoDB
- Clerk
- Cloudinary
- Stripe
- Shadcn
- TailwindCSS

## <a name="features">🔋 Features</a>

👉 **Authentication and Authorization**: Secure user access with registration,
login, and route protection.

👉 **Community Image Showcase**: Explore user transformations with easy
navigation using pagination

👉 **Advanced Image Search**: Find images by content or objects present inside
the image quickly and accurately

👉 **Image Restoration**: Revive old or damaged images effortlessly

👉 **Image Recoloring**: Customize images by replacing objects with desired
colors easily

👉 **Image Generative Fill**: Fill in missing areas of images seamlessly

👉 **Object Removal**: Clean up images by removing unwanted objects with
precision

👉 **Background Removal**: Extract objects from backgrounds with ease

👉 **Download Transformed Images**: Save and share AI-transformed images
conveniently

👉 **Transformed Image Details**: View details of transformations for each image

👉 **Transformation Management**: Control over deletion and updates of
transformations

👉 **Credits System**: Earn or purchase credits for image transformations

👉 **Profile Page**: Access transformed images and credit information personally

👉 **Credits Purchase**: Securely buy credits via Stripe for uninterrupted use

👉 **Responsive UI/UX**: A seamless experience across devices with a
user-friendly interface

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git https://github.com/YousifAbozid/mirage-master.git
cd mirage-master
```

**Installation**

Install the project dependencies using npm:

```bash
npm run dev
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the
following content:

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# Clerk Webhook Secret
CLERK_WEBHOOK_SECRET=

# MongoDB
MONGODB_URI=

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

# Next
NEXT_PUBLIC_SERVER_URL=
```

Replace the placeholder values with your actual respective account credentials.
You can obtain these credentials by signing up on the
[Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/),
[Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the
project.

## <a name="credits">🚨 Credits</a>

This SaaS project was inspired by
<a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript
Mastery</b></a>.

If you prefer visual learning, this is the perfect resource for you. Follow his
tutorial to learn how to build projects like these step-by-step in a
beginner-friendly manner!

<a href="https://youtu.be/Ahwoks_dawU?feature=shared" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>
