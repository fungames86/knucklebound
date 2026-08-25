# Knucklebound phone viewer

A 3D-printable headset that holds an iPhone on your face. Two cheap lenses, two eye holes, phone drops in from the top. The **back of the phone stays open** so the camera can watch your hands.

## What to buy

- Two **25 mm biconvex** VR lenses, about **45 mm** focal length. Search “cardboard VR lenses 25mm 45mm”.
- A 25 mm elastic strap (or a leftover from a cheap headset).
- Optional: thin foam for the face (craft foam or mousepad).

## Print

On the GameStudio Mac:

```
env -u PYTHONHOME -u PYTHONPATH /Users/elirodgers/Applications/Blender.app/Contents/MacOS/Blender --background --python ~/GameStudio/projects/knucklebound/print/build_holder.py
```

STL lands in `print/stl/knucklebound_viewer.stl`.

Bambu P1S: 0.20 mm layer, 15% gyroid, no supports if you print **face-plate down** (the lens wall on the bed). If the phone rails look messy, add supports on that side only.

PLA is fine. PETG is a bit tougher for strap slots.

## Fit

The tray is landscape: about **168 mm wide × 82 mm tall × 12 mm thick**. That covers a 16 Pro Max in a thin case. Smaller phones: fold a scrap of paper or foam on the short edges so the screen sits in the middle. The whole viewer is about **175 × 56 × 88 mm**, so it fits a Bambu P1S.

USB-C / Lightning should sit on the **right** when the headset is on your face. The cameras then sit on the **left**, looking out the open back.

## Lenses

Push each lens into a socket from the **phone side** until it hits the lip. If a lens is loose, a drop of glue around the rim. If it is tight, sand the socket.

## Strap

Thread elastic through the side slots. Tie a knot. Pad the face with foam if the plastic bites.
