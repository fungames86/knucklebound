# Knucklebound

Phone VR ape parkour. Slap the ground to run the way you look. Tag friends online, or hunt AI in the grove. Talk with voice chat.

**Play in a browser:** https://fungames86.github.io/knucklebound/

This is **not** Gorilla Tag. Names, maps, and looks are original.

## How you move

You do **not** walk with WASD.

1. Look around by turning your head (phone VR) or moving the mouse (computer). The grove turns with you.
2. Swing a hand down into the ground. You go the **opposite** way the hand pushed — slap back to go forward, slap left to go right.
3. Slap **down** hard to jump.
4. Joy-Con sticks swing that hand. Stick down slaps the ground.

## Voice chat

In **Online with friends**, pause and tap **Mic**. Talk into the phone. Friends hear you nearby, and ape mouths open while you talk. Name tags glow green when someone is speaking.

## Joy-Cons on a phone (Switch OLED)

iPhone **iOS 16+** can pair Switch Joy-Cons. Pair **both**.

1. Charge the Joy-Cons on the Switch, then slide them off.
2. Hold the tiny black **sync** button on the Joy-Con rail (between SL and SR) until the lights run back and forth.
3. iPhone: **Settings → Bluetooth**. Tap **Joy-Con (L)**.
4. Do the same for **Joy-Con (R)**.
5. Open Knucklebound in **Safari**. Keep the Switch **asleep** so it does not steal them.
6. Stick down slaps the ground the way you are looking. Push down to jump. **+** pauses.

The phone cannot feel where the Joy-Cons are in the air. Use the sticks to swing each arm.

## Play on iPhone

Apple will not let us text you a real App Store app as a file. Play it in **Safari**:

1. Print the headset in `print/` (or use any cheap phone VR viewer).
2. Open the game on the phone (Safari).
3. Allow **mic** if you want voice chat.
4. Drop the phone in the holder, landscape, USB-C on the **right**.
5. Look around — the world looks that way. Slap the ground to move.
6. Safari → Share → Add to Home Screen if you want an icon.

The screen is split into **two eyes**. Cheap cardboard lenses bend each half so it looks 3D.

Voice chat needs **https**. GitHub Pages is fine.

Tall cliff walls close off each grove so you cannot fall off the edge of the map.

## Play on a computer (to try it)

```
~/GameStudio/tools/bin/godot --path ~/GameStudio/projects/knucklebound/godot
```

| Control | What it does |
|---|---|
| Mouse | Look (the world looks the way you look) |
| Hold **left mouse** + drag | Right hand |
| Hold **right mouse** + drag | Left hand |
| Scroll | Hands closer / farther |
| **C** | Recenter |
| **V** | Two-eye VR split |
| **Esc** | Pause / free mouse |
| **Space** or both mouse buttons | Make fists |
| Clap (open hands together) | Pause on phone |

## Modes

- **Practice** — empty grove, learn slaps.
- **Singleplayer tag** — you plus three AI apes. Infection tag: seekers glow red.
- **Online** — same grove across the internet. First phone to open it hosts. Pause → Mic to talk.

## Maps

Start in **Mossgrove Hollow**. Walk **east** into the cave and step through a glowing ring:

- **Frostveil** — ice and snow.
- **Brickmarket** — rooftops and alleys.
- **Sparrow Spire** — thin planks and parkour.
- **Emberkiln** — dark rock and warm ledges.
- **Sunledge Quarry** — stone terraces and a pit.

Each land has a return ring back to Mossgrove.

## Outfitter

West of spawn is a wooden stall. Walk in. Slap a colored ball to change fur, slap a hat / shirt / stick to wear it. There is no shop button.

## Print the headset

See `print/README.md`. You need two 25 mm VR lenses (~45 mm focal length) and a strip of elastic. The holder leaves the phone **back open** so the camera can see your hands.

## Why two screens

A phone on your face is a tiny cinema. We draw the world twice, once for each eye, with a little gap (IPD). Lenses in the holder make each half fill that eye. That is the same trick Google Cardboard uses.
