# Snow Walk: Script and Animation Guide

29 Sept 2026 · Kyle Ross

## Reality check

Claude alone can make this as a motion comic, not as Ghibli-style animation. Claude can't draw new frames in this art style. It can cut your existing images into layers, move them, swap faces and mouths, pan, zoom, parallax, dissolve, add snow and light, and play it all as an HTML page with sound. Everything on screen has to come from the nine images you uploaded.

What that means in practice:

- **Walking is the weak point.** You have one walking pose per character. A believable walk cycle needs 6 to 8 drawn frames per step. Claude can fake it with bob, sway and a two-pose swap, or hide it behind camera moves and the pre-drawn approach shots in image 9. Expect it to read as puppetry.
- **Faces are the strong point.** Both characters have enough expressions and mouth shapes for real lip sync and reaction beats. Build the film around close-ups and two-shots of talking, not around action.
- **Every pose change is a cut, not a move.** She can't go from standing to sitting in one continuous shot. Cut on the change and it reads as editing, not a missing frame.
- The two characters came from separate generations, so line weight, scale and paper texture differ slightly. A shared grain overlay and colour grade on every shot hides most of it.
- Image 9's nine frames redraw the background each time, so crossfading them will make the trees and buildings shimmer. Lean into it as "boiling line" or use only three of the frames.

Two content problems to fix before you build. She wears a crop top in a snowstorm, which any viewer will notice; the script turns that into a story beat. Image 4's apartment has a *Where the Wild Things Are* poster, a Wild Thing statue and a "MAURICE" book spine baked into it. Don't use that image in anything you publish.

Target length: 3 min 24 s, 29 shots (the shot table below sums to 204 s). Longer than that and the limited poses start to wear thin.

## Asset inventory

You have five usable park locations, two full character kits and one pre-drawn approach sequence. Codes below are used in the shot guide.

| Code | Source | What it gives you | Use for |
|---|---|---|---|
| BG-PATH | Image 2 | Empty path, bench, lamps, bridge in distance | Opening, meeting, walk start |
| BG-BRIDGE | Image 1, top right | Stone bridge over water | Bridge scene |
| BG-LAWN | Image 1, middle right | Open snowy lawn, fence | Establishing shot, snow beat |
| BG-ARBOR | Image 1, bottom left | Arbor tunnel, two benches | Sitting and talking scene |
| BG-FOUNTAIN | Image 1, bottom right | Fenced fountain | Ending |
| M-SHEET | Image 3 | Him: front/back, 12 expressions, 7 poses, 5 head angles, 7 mouth shapes | Face swaps, lip sync, poses |
| W-SHEET-A | Image 5 | Her: turnaround, 8 poses, 5 expressions, 7 head angles | Poses, head turns |
| W-SHEET-B | Image 6 | Her: cleaner turnaround, 5 poses, 5 expressions | Body sprites (better line quality than A) |
| W-FACE | Image 7 | Her: 4 speaking mouths, smile, 3 laughs, 4 crying | Lip sync, laugh beat |
| DUO | Image 8 | Both walking hand in hand, full res | Key two-shot, final walk |
| APPROACH | Image 9 | 9 frames of the couple walking toward camera | Push-in walking shot |
| M-ROOM | Image 4 | Him in apartment | Don't publish (Sendak artwork in frame) |

Frames to leave out: her "spinning" pose in image 5 puts her in a skirt, which breaks continuity. Her "jumping" and "running" poses don't fit a date. His "angry" face has no place in this story. Her mouth set has no closed M/B/P shape, so use her "neutral" mouth for those sounds.

## The script

A first date built on one running joke: she came out without a coat and refuses his jacket, and it pays off when she takes his hand instead. That payoff is image 8, so the story ends on your best frame. Names are placeholders: THEO (him) and JUNE (her). Dialogue runs about 90 seconds; the rest is walking, looking and snow.

### Scene 1. Park path, late afternoon, snow falling

Empty path. Lamps flicker on one by one. THEO stands by the bench, hands in pockets. He glances down the path. Nothing. He looks at the bench, thinks about sitting, doesn't.

> **JUNE (O.S.):** You're early.

He turns. JUNE walks up the path. No coat. Long sleeves, a crop top, bare midriff in the snow.

> **THEO:** You're... not dressed for this.
> **JUNE:** It was sunny when I left.
> **THEO:** It's been snowing since lunch.
> **JUNE:** It was sunny in my heart.

He laughs. He starts to take off his jacket.

> **JUNE:** No. Absolutely not. I'm not the girl who gets cold on a first date.
> **THEO:** You're already the girl who gets cold on a first date.
> **JUNE:** Then I'll be the girl who doesn't admit it. Walk.

### Scene 2. Park path, continuous

They walk toward us, side by side, not touching.

> **THEO:** So what made you say yes?
> **JUNE:** Your message said "walk in the park." Everyone else said "drinks."
> **THEO:** I don't really drink.
> **JUNE:** I know. That's why I said yes.

### Scene 3. Stone bridge, dusk

They stop on the bridge. Dark water below. JUNE leans on the rail and goes quiet.

> **JUNE:** My nan used to bring me here. Every winter. She'd make me count the lamps.
> **THEO:** How many are there?
> **JUNE:** I never got to the end. She always started talking.

Her eyes well up. She looks away. THEO doesn't fill the silence.

> **JUNE:** Sorry. First date. Very sexy.
> **THEO:** No, I... I like knowing that.

She wipes her eye and smiles.

### Scene 4. The arbor, evening

A bench under the snow-covered arbor. They sit, a gap between them.

> **JUNE:** Tell me something embarrassing. It's only fair.
> **THEO:** I practised this. The walk. I did the route on Tuesday. Twice.
> **JUNE:** You rehearsed a walk?
> **THEO:** I timed it. It's forty minutes if you don't stop at the bridge.

She laughs. Then laughs harder. He puts a hand to the back of his neck, red.

> **JUNE:** That's the nicest thing anyone's done for me.
> **THEO:** It's a walk.
> **JUNE:** It's a rehearsed walk.

### Scene 5. The lawn, night

Open snow. JUNE steps out, arms up, stretching into the falling snow. THEO watches from the path.

> **JUNE:** Come on.
> **THEO:** You'll freeze.
> **JUNE:** I'm already frozen. It stopped mattering ten minutes ago.

### Scene 6. The fountain, night

The fountain, iced over. All the lamps lit now. They stand by the railing.

> **THEO:** That's the end of the route.
> **JUNE:** Already?
> **THEO:** We stopped at the bridge.

A pause.

> **THEO:** Last chance. Jacket?

She looks at the jacket. Then at him. She takes his hand instead.

> **JUNE:** Hand's warmer.

### Scene 7. Park path, night

They walk toward us, holding hands. Then from behind, the two of them walk away down the path until they're small.

> **JUNE (O.S.):** How many lamps, do you reckon?
> **THEO (O.S.):** I counted on Tuesday.
> **JUNE (O.S.):** Of course you did.

Fade out.

## Scene-by-scene animation guide

29 shots, 204 seconds. Rule of thumb: any line of dialogue is delivered in a close-up so the lip sync shows; wide shots carry silence, walking and voice-over.

Continuity catch: every frame in image 9 has them holding hands. That makes it useless for Scene 2, where they haven't touched yet. Scene 2 is built from separate walking sprites; image 9 is saved for the ending, where the hand-hold is earned. The same rule applies to the back-view sprites in shot 29: they come from the turnarounds, arms at their sides, so the shot has to hide the hands (see shot 29).

| # | Scene | Secs | Background | Sprites | Motion and camera | Audio and lip sync |
|---|---|---|---|---|---|---|
| 1 | 1 | 6 | BG-PATH | none | Push-in 100% to 106%. Lamps fade on one at a time, 0.6 s apart, via radial glow layers | Wind, soft piano in |
| 2 | 1 | 6 | BG-PATH | Theo neutral pose, small, by bench | Breathing idle: scaleY 1.00 to 1.01, 3 s loop. Head swaps front to 3/4 at 3 s | Ambience |
| 3 | 1 | 3 | BG-PATH, blurred | Theo head, side view | Hold, tiny drift. Eyes toward bench | none |
| 4 | 1 | 3 | BG-PATH, blurred | Theo head: 3/4 back, then surprised | Snap swap on "early" | June O.S. "You're early" |
| 5 | 1 | 5 | BG-PATH | June walking pose (image 6) | Enters far right, scales 40% to 70% as she nears. Bob 3 px at 2 steps/s, rotate ±1°. Cut before she stops | Footsteps in snow |
| 6 | 1 | 12 | BG-PATH, 2 px blur | Theo neutral, June standing relaxed | Two-shot, slow push. Both breathing idles offset so they don't sync | Theo and June lines, 4 swaps between CU-style head overlays |
| 7 | 1 | 4 | Blur | June head, W-FACE | Lip sync, end on smile | "Sunny in my heart" |
| 8 | 1 | 3 | Blur | Theo head: laughing | Shoulder bounce, 3 hops of 4 px | Laugh |
| 9 | 1 | 10 | BG-PATH | Theo gesturing pose (the jacket offer), June leaning, arms crossed (the refusal) | Cut from shot 8 straight into the arms-crossed pose; that cut is the joke | Jacket exchange, both CU inserts for lip sync |
| 10 | 2 | 14 | BG-PATH, panning | Theo walking (3/4), June walking, gap between them | Background slides left at 30% speed, sprites bob out of phase. Keep feet cropped by a low frame line to hide the sliding | "So what made you say yes" as V.O. |
| 11 | 2 | 6 | Blur | June 3/4 head smiling; Theo embarrassed | Alternating CUs | "That's why I said yes" |
| 12 | 3 | 5 | BG-BRIDGE | Both back-view sprites, 10% scale, at the rail | Water shimmer: brightness flicker on a masked water region. Snow | River ambience |
| 13 | 3 | 10 | Blur | June front talking, then June looking down | Lines on front head; cut to looking-down on the pause | Nan lines |
| 14 | 3 | 3 | Blur | Theo concerned | Hold | "How many are there?" |
| 15 | 3 | 8 | Blur | June: welling up, tears, quiet cry (side) | Slow push 100% to 110%. Swap every 2 s. No music | Silence, wind only |
| 16 | 3 | 8 | Blur | June speaking, Theo concerned to smiling | Alternating CUs, end on June's smile | "Very sexy" / "I like knowing that" |
| 17 | 4 | 6 | BG-ARBOR | Both, waist-up only | Bench arm cut from BG as a foreground layer to hide missing seat | Music back in, quieter |
| 18 | 4 | 8 | Blur | Theo embarrassed, talking | Lip sync, eyes down | "I practised this" |
| 19 | 4 | 6 | Blur | June: smile, soft laugh, laugh, hard laugh | 0.6 s per face, head bob 5 px, hard laugh tilts back 4°, settle to smile | Laugh track, recorded |
| 20 | 4 | 3 | Blur | Theo embarrassed (hand on neck) | Hold. Warm tint on cheeks | none |
| 21 | 4 | 8 | Blur | Alternating CUs | Standard | Last three lines |
| 22 | 5 | 8 | BG-LAWN | June stretching, Theo neutral small at left | Heavier snow, slow push | "Come on" |
| 23 | 5 | 6 | Blur | Theo CU; June looking up | Snowflakes pass in front of lens (large blurred particles) | "You'll freeze" / "already frozen" |
| 24 | 6 | 5 | BG-FOUNTAIN | Both standing, small, at railing | All lamps on, push-in | Quiet |
| 25 | 6 | 8 | Blur | Theo, June CUs | Standard | "End of the route" lines |
| 26 | 6 | 5 | Blur | Theo gesturing (offer); June thoughtful | Hold on June's face 2 s before the cut | "Jacket?" |
| 27 | 6 | 4 | DUO, cropped to hands | none extra | Slow zoom into the joined hands, then June CU smiling. Crop tight enough that DUO's park background doesn't show; it isn't the fountain | "Hand's warmer" |
| 28 | 7 | 16 | APPROACH | none extra | Crossfade frames 1 to 9, 1.2 s each (10.8 s). Frame 9 holds 0.2 s, then cut to DUO full frame for 5 s | Music swells |
| 29 | 7 | 15 | BG-PATH | Both back-view sprites side by side | Start small (35%) and shrink to 12% toward the vanishing point, with bob. Overlap their inner arms by about 10 px so the gap between the hands doesn't read. Fade to black over last 3 s | Final three V.O. lines |

### Lip sync mapping

Swap at 12 frames per second, not 24; limited animation reads as a style at 12 and as a glitch at 24.

Rhubarb Lip Sync outputs nine shapes: six basic (A to F) and three extended (G, H, X). Map them like this:

| Rhubarb | Sound | Him (image 3) | Her (image 7) |
|---|---|---|---|
| A | Closed: M, B, P | M/B/P | neutral |
| B | Slightly open, teeth: K, S, T, EE | A/E/I | E |
| C | Open: EH, AE | A/E/I | E |
| D | Wide open: AA | A/E/I | A |
| E | Slightly rounded: AO, ER | O | O |
| F | Puckered: UW, OW, W | U | O |
| G | Teeth on lip: F, V | F/V | E |
| H | Tongue up: L | TH | D |
| X | Idle / rest | rest | neutral |

Head swaps on a static body only work if the neck join lines up. Cut every head at the collar line, and keep a 10 px overlap under the jacket collar (him) and neckline (her).

## Build pipeline

Render the final film in Python and export an MP4. An HTML player is fine for previews, but a video file is what you'll post, and Python compositing gives you frame-exact lip sync.

If you work in claude.ai chat, plan on 5 to 7 sessions. The sandbox resets between chats, so every session starts by uploading a zip of the project and ends by downloading the updated zip. Skip this once and you lose the session's work. If you work in Claude Code against this repo instead, skip the zip routine: commit the images and outputs here and every session picks up where the last one stopped.

1. **Cut the backgrounds.** Crop image 1 into its five panels and image 2 as-is. Crop to 16:9 at 1280×720. The image 1 panels are about 950 px wide, so they need a 1.35× Lanczos upscale; the paper texture hides the softness.
2. **Cut the sprites.** Claude views each sheet, estimates a box per pose or head, and crops. Remove the parchment background with rembg first. If that fails to install (it downloads its model from GitHub on first run, which a locked-down sandbox may block), fall back to a colour-key on the parchment tone with a 2 px feathered edge. Check every sprite by eye; hair edges are where both methods break.
3. **Name everything consistently.** `m_head_happy.png`, `m_mouth_O.png`, `w_body_walking.png`, `bg_bridge.png`. The timeline refers to these names, so a sloppy name costs you a broken shot later.
4. **Write the timeline as JSON.** One entry per shot: duration, background, camera keyframes (x, y, zoom), a list of layers, each with keyframes for position, scale, rotation and opacity, plus swap schedules for heads and mouths. The shot table above maps one-to-one onto this file.
5. **Record the voices yourself.** Browser text-to-speech sounds like a GPS. Record each line on your phone as its own file, named by shot number, and upload them.
6. **Lip sync with Rhubarb.** Rhubarb Lip Sync is a free tool on GitHub that reads a voice file and outputs mouth shapes with timings. Download it from GitHub releases. Map its shapes with the table above. If Rhubarb won't run, use loudness-based sync with three mouths: closed, half, open.
7. **Add the shared finish.** Snow particles, lamp glow, a paper-grain overlay and one colour grade over every frame. This is what makes separate generations look like one film.
8. **Render and encode.** Render at 24 fps. Camera and snow move every frame; character swaps hold for two frames each (12 fps). PIL composites the frames, then ffmpeg joins frames and audio into an MP4.
9. **Music.** Bring your own royalty-free track, or have Claude write a simple piano piece with a Python synth. The synth version will sound thin; a real track is worth finding.

## Prompts, in order

One prompt per session. In chat, attach the project zip to every session after the first, and paste this doc's shot table when a prompt refers to it.

1. **Session 1, backgrounds.** Attach images 1 and 2. "Crop image 1 into its five panels. Save each panel and image 2 at 1280×720, upscaling with Lanczos where needed. Names: bg_path, bg_bridge, bg_lawn, bg_arbor, bg_fountain. Show me a contact sheet, then zip everything into snowwalk.zip."
2. **Session 2, his sprites.** Attach the zip and image 3. "Cut every body pose, head expression, head angle and mouth shape from this sheet into its own transparent PNG. Remove the parchment with rembg, colour-key fallback. Name them m_body_\*, m_head_\*, m_mouth_\*. Show a contact sheet on a grey background so I can see bad edges. Add to the zip."
3. **Session 3, her sprites.** Same as session 2 with images 5, 6 and 7, prefix w_. "Use image 6 for body poses where both sheets have one. Skip spinning, running and jumping." Add image 8 as duo.png and the nine frames of image 9 as approach_1 to approach_9.
4. **Session 4, rig test.** "Build a Python renderer that reads timeline.json and composites frames. Write the timeline for shots 1 to 9 only, using this table. Render shot 6 as a 12-second MP4 at 1280×720 with head swaps and a breathing idle. No audio yet." Watch it. Fix neck joins and scale before going further.
5. **Session 5, audio and lip sync.** Attach your recorded lines. "Download Rhubarb Lip Sync from GitHub releases, run it on each line, and write the mouth swaps into the timeline using the attached mapping table." Paste the lip sync mapping table.
6. **Session 6, remaining shots.** "Write shots 10 to 29 into the timeline from this table and render the full film with snow, lamp glow, paper grain and one colour grade."
7. **Session 7, fixes.** Watch the full render and give shot-numbered notes: "Shot 19, hard laugh holds too long. Shot 28, frame 5 flickers, drop it." Numbered notes get fixed in one pass; vague ones don't.

If any chat session runs out of room mid-task, ask Claude to zip what it has before it stops. That zip is your save file.
