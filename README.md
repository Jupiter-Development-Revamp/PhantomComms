# 👻 PhantomComms – Immersive Proximity Chat System for Roblox Horror Games

PhantomComms isn't much of a chat system; it's a new meaning for chat, bringing it to a new standard.

Built from the ground up, we want communication to replicate eerie, real, and atmospheric. PhantomComms creates a new meaning for text chats, distance-driven dialogue, glitching whispers, and lingering ghost messages.

> 🎮 Perfect for: Horror games, roleplay experiences, or any game where immersion is the goal.

## ✨ Key Features

- 📏 **Proximity-Based Visibility**  
  Text becomes visible the closer you get, just like real voices.

- ⚡ **Distortion & Delay FX**  
  Characters flicker, jitter, or scramble when players are far away (or near cursed objects 👁️).

- 🔊 **Emotion Commands**  
  Use `!shout`, `!whisper`, or `!scream` to adjust message radius and style dynamically.

- 👻 **Ghost Messaging**  
  Messages can linger after a player leaves—or even appear from nowhere in haunted zones.

- 💬 **No GUI Needed**  
  World-space chat hovers above characters or appears ambiently, with optional GUI support for devs.

- ⚙️ **Customizable API**  
  Lightweight module-based structure. Easy to wrap over Roblox’s default chat system.

## 📖 Developer Docs

Ready to implement PhantomComms into your game?

> 🔗 **[Click here to view the Developer Documentation »](https://github.com/Jupiter-Development-Revamp/PhantomComms/blob/main/Developers/Docs.md)**

Inside you'll find:
- 


## 🧠 Why PhantomComms?

Roblox games often do very little to create a real experience, grounding realistic proximity chat and other ideas, which work until you need and want more. 

PhantomComms lets players who use the chat system and don't want to use microphones, or any versions of voice chat. I dislike using voice chat, so I decided this would be an amazing product for me to create and help others with the same issues. 

> You're not just giving players a way to chat—  
> You're giving them a *reason* to walk toward the voice.

## 🔧 Credits & Attribution

Developed by [Jupiter Development](https://github.com/Jupiter-Development-Revamp)  
Contributions are a welcome addition, a small credit in your game description would be appreciated:
> `Chat System – Jupiter Development`

## 📌 Coming Soon
- 

## 💬 Example Use

```lua
PhantomComms:Speak(player, "I saw something move...", {
    Volume = "whisper",
    Range = 10,
    Distort = true,
    Delay = 0.05
})

From a distance, players see:

I . . . . .

Closer:

I saw . .

Even closer:

I saw something move...

Stay close. Listen carefully. You never know who’s talking.
