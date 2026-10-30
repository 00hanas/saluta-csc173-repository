# Lecture 03 Activity: Notes
Name: **Juhanara M. Saluta** · Student ID: **2023-0167**

## My photos (Parts 0 to 6)
I used 3 photos that I took myself:
- **1.jpg**: a cream-colored wall with three tall dark windows and a white office chair at the lower right. This is my strong-edges photo (used in Parts 1 to 3, 5b and 6).
- **2.jpg**: a tablet seen at an angle, with a colorful grid of apps on its screen.
- **3.jpg**: a plain wall with three thin items hanging on it and a white folding table at the lower right, with a hallway on the left.

## My dataset (Part 7)
Categories: Pen vs. Makeup brush
Photos per category: 20 and 20 (40 in total; 30 for training and 10 for validation)
How I took them (places, backgrounds, lighting, angles): I took the photos indoors and changed the background between shots: a wooden table, a white folding table, a white slotted chair, a metal mesh, patterned tile, and held in my hand in front of windows and walls. Angles go from top-down shots of the object lying flat to close-ups of it held in my hand. The lighting is normal indoor light, with some brighter and some dimmer photos.
Final validation accuracy: transfer **0.70** · from scratch **0.30**

## My kernel (Part 2c)
The numbers:

```
[[-1, -1,  2],
 [-1,  2, -1],
 [ 2, -1, -1]]
```

What it detects: thin diagonal lines running in the "/" direction (from bottom-left to top-right), because the +2 weights lie on that diagonal and all other weights are -1. The weights sum to 0, so it gives about 0 on flat areas like a plain wall. On my wall photo the response is weak because that photo has mostly vertical and horizontal edges.

## AI and outside help
- Claude (Anthropic): helped me write this notes.md from my completed notebook.
