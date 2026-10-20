# Office Pulse

An isometric pixel-art office where every hire adds an office noise to the band:

| Teammate | Noise | Part | Second hire adds |
|---|---|---|---|
| Teleconsult Caller | Phone rings | Lead melody | Digital desk-phone beeps |
| Flu-Season Survivor | Coughing | Snare on the backbeat | Small coughs and an "ah-ah-CHOO" fill |
| Espresso Addict | Coffee machine buzz | Bass, plus knock-box kick | Steam wand, grinder, drips |
| Deadline Typist | Typing | Hi-hats, spacebar | Fast burst into an Enter-key slam |
| Spreadsheet Clicker | Clicking | Off-beat mouse clicks and double-clicks | Pen clicks and scroll-wheel ticks |
| Claims Approver | Rubber stamp: APPROVED | Accent hits | Stapler ka-chunks |
| Hydration Hero | Pen on a glass of water | Bell melody | A higher answering line |
| Policy Photocopier | Photocopier sweep | Whoosh and sub bass each bar | Buzzy paper-feed stabs |

Each teammate covers one benefit on a group health policy. Cover all eight to hear the full band.

Everything is in one static `index.html`: Web Audio synthesis (no samples) and a hand-rasterised canvas.

Run it by opening `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Controls: click a role card to hire, drag a card onto a desk, click an empty desk to fill the biggest
coverage gap, click a person to send them home, and press Space to play or pause.
