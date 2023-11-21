# Ping

Ping is a cutting-edge chat application designed to bring people closer through seamless and intuitive communication. With a focus on real-time chat and group collaboration, Ping offers a dynamic platform for individuals and teams to interact effortlessly.

#### The Website is Deployed at - https://ping-nine-bay.vercel.app/ ####

## Key Features:

- Real-time messaging using Pusher
- Group chats and one-on-one messaging
- Credential authentication with NextAuth
- Google authentication integration
- Github authentication integration
- Tailwind design for sleek UI
- Full responsiveness for all devices
- Message read receipts
- Online/offline user status
- User profile customization and settings


## Run

### Cloning the repository

```shell
git clone https://github.com/Aryan-tiwari/Ping-2.0.git
```

### Install packages

```shell
npm i
```

### Setup .env file

Add a .env file in parent directory(i.e. the directory that also have our readme.md)

```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## System Design
 [System Design](https://github.com/Aryan-tiwari/Ping-2.0/blob/master/.github/systemDesign.md)

## Dependencies Details
[Dependencies](https://github.com/Aryan-tiwari/Ping-2.0/blob/master/.github/dependencies.md)

 ## Creator
 - [Aryan Tiwari](https://github.com/Aryan-tiwari)
 - Computer Science Engineering
 - IIT Bhilai