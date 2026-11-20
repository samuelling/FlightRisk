# FlightRisk

**Search Committee Flight Simulator.** A single-page web toy for faculty search committees: turn a knob (method of adjustment) until the plane looks the way the search *feels*.

- Turn it down: the plane sheds its wing, tail, propeller and banner, catches fire, and dives toward the Dean's office while the committee parachutes out. The Chair goes down with the plane.
- Turn it up: the fuselage gets skinned, the tail and wing bolt on, CVs fly *in*, and the banner reads OFFER ACCEPTED! under sunshine and confetti.

## Method of adjustment

- Each trial starts the knob at a random setting to avoid anchoring on the previous person.
- Optional blind mode hides the number while adjusting.
- Settings are logged with their start points and shown as a dot plot with mean ± SEM.
- **Fly the consensus** sets the plane to the committee mean.
- **Copy CSV** exports the log.

Settings are stored in the browser's localStorage, so it works best on one shared screen with the knob passed around.

## Run

Open `index.html` in a browser, or use GitHub Pages. There's no build step and no dependencies.

Controls: drag around the knob, use the scroll wheel, or press the arrow keys (hold Shift for big steps; Home and End jump to the extremes).
