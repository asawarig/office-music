# Office Pulse

An isometric pixel-art office where every hire adds an office object to the band. Knuckles on a
desk play the kick in a heartbeat rhythm, the claims stamp hits the backbeat, keyboards and pens are
the hi-hats, a spoon on a mug rings out the melody, the water cooler bubbles, the desk phone trills,
the printer buzzes the bassline and the microwave hums the chords and dings. Each role covers one
benefit on a group health policy. Cover all nine to hear the full band. A second hire in the same
role brings a related object (stapler, mouse, glass of water, photocopier, elevator ding) and plays a new part.

Everything is in one static `index.html`: Web Audio synthesis (no samples) and a hand-rasterised canvas.

Run it by opening `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Controls: click a role card to hire, drag a card onto a desk, click an empty desk to fill the biggest
coverage gap, click a person to send them home, and press Space to play or pause.
