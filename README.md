# FollowBeat
It is an e-commerce website developed with Next.js, ContextAPI, Sanity, and Stripe for headphones.

Demo: https://followbeat.vercel.app

## Prerequisites

You will need [Node.js](https://nodejs.org) version 8.0 or greater installed on your system.

## Setup

Get the code by either cloning this repository using git

```bash
git clone https://github.com/hilmicantaskiran/followbeat.git
```

... or [downloading source code](https://github.com/hilmicantaskiran/followbeat/archive/refs/heads/main.zip) code as a zip archive.

Once downloaded, open the terminal in the project directory, and install dependencies with:

```bash
npm install
# or
yarn install
```

If you're running your own Sanity project with the example movie dataset, go to `lib/sanity.js` and change the following lines:

```
  projectId: 'YOUR_PROJECT_ID',
  dataset: 'NAME_OF_YOUR_DATASET',
```

You can locate the ID of your project in the header of the [management page for your project](https://manage.sanity.io/).

Then run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
