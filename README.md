# Office Pulse

An isometric pixel-art office where every hire adds a sound. Each employee has a healthy habit
(heartbeat kick, step-counter hats, water-drop plucks, breathing pads, bass, bells, a heart-monitor
melody, claps, a pill-bottle shaker) and each habit maps to a benefit on a group health policy.
Cover all nine benefits to hear the full band. Hire a second person in the same role to add a harmony part.

Everything is in one static `index.html`: Web Audio synthesis (no samples) and a hand-rasterised canvas.

Run it by opening `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Controls: click a role card to hire, drag a card onto a desk, click an empty desk to fill the biggest
coverage gap, click a person to send them home, and press Space to play or pause.
