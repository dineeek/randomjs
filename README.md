# Animated Greeting Page

An animated, customizable greeting page built with GSAP (GreenSock Animation Platform). Features a multi-step animated sequence with text reveals, floating balloons, and a personalized message — perfect for birthdays, Valentine's Day, or any special occasion.

## Live Demo

https://dineeek.github.io/dearjs/

## Features

- Multi-step GSAP timeline animation with smooth transitions
- Fully customizable content via `customize.json` (no code changes needed)
- Floating balloons, text animations, and profile image reveal
- Replay button to re-watch the animation
- Mobile-friendly responsive design

## Customization

Edit `animation-script-page/customize.json` to personalize the greeting:

```json
{
  "greeting": "Hello",
  "recipientName": "Name!",
  "occasionTitle": "Happy Birthday!",
  "chatMessage": "Your message here",
  "profileImage": "img/her.jpeg",
  "mainWish": "Happy Birthday Name!",
  "personalMessage": "Your personal note here"
}
```

## Local Development

```bash
cd animation-script-page
npm install
npm start
```

Opens at `http://localhost:7777`.

## Tech Stack

- HTML/CSS/JavaScript
- [GSAP (TweenMax)](https://greensock.com/gsap/) for animations
- [Babel](https://babeljs.io/) for ES6+ support
- GitHub Pages for hosting
