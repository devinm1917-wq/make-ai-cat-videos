---
name: make-ai-cat-videos
description: Plan and produce reusable AI cat story videos from story beats through shot breakdown, anchor images, concise Kling prompts, individual shot acceptance, failure recovery, and editing handoff. Use for new themes, revising a failing shot, or reviewing a cat video workflow. Do not assume the convenience-store story or begin production unless requested.
---

# AI cat video workflow

Apply the user's current story, character references, tools, format, and acceptance decisions. Treat earlier approved story beats as fixed unless the user asks to change them. Ask only for details that block an actual decision. Do not produce a new video merely because this skill is installed or requested for planning.

## Gates

1. **Story gate:** Write the visible cause-and-effect chain, emotional turn, and ending. Check that a first-time viewer can understand the action without explanatory copy. Break it into shots with one main narrative job each. Default to roughly five seconds and two to four sequential actions per generated clip; split a complex task into more shots. Record the exact action, starting state, endpoint, main prop, character identity, continuity link, and acceptance criterion for each shot. Obtain the user's story approval before producing anchors when the story is being developed collaboratively.
2. **Anchor gate:** For each shot, make a still frame from which the action can naturally start in the next second. Lock character appearance, clothing, location and light. Place people, cat and props at plausible distances and orientations; show the relevant contact point and direction of travel. Put main subjects close enough to read, keep important limbs and props complete with safe margins, and leave room for running, turning or standing. Prefer an approved prior shot's end frame when continuity benefits. Inspect and correct the still before sending it to Kling; do not try to repair a wrong spatial relationship through motion instructions.
3. **Motion gate:** Write a short, concrete Kling image-to-video prompt in time order: starting state → two to four continuous actions → final stop or reaction → fixed camera or at most one simple camera move. Preserve natural cat anatomy while allowing expressive running, braking, looking back, waiting and observing. Keep bystanders and props stable. State only two or three essential prohibitions when necessary; do not pile on constraints. For each prompt give generated duration, intended usable duration, and its observable acceptance points. Generate clean picture first; add dialogue, meows, music, and sound effects during editing when relevant.
4. **Shot acceptance:** Inspect the first 0–1 seconds, before and after the key action, contact with props, middle, and ending. Check identity and clothing, number and position of subjects, prop identity and stability, motion direction, physical contact, readable causality, and suitability of the last frame for the next shot. Give one explicit verdict: **通过**, **裁切后通过**, or **重做**. For a trim, record exact usable in/out times and the continuity frame. Do not approve a shot with a missing core action or structural error just to move on. Advance after acceptance.

## Diagnose and converge after failure

- If the intended action is complete in an earlier segment and later frames degrade, trim the good segment and check the resulting story continuity.
- If subjects, props, directions, contact points or motion space are wrong from the start, fix the anchor and rerun; do not lengthen the prompt.
- If one clip must perform several incompatible actions, split the shot and simplify each action chain. If only an incidental motion is wrong, change that instruction and retain the validated anchor.
- If successive generations fail, isolate the one failing condition, remove nonessential prohibitions, and change one layer at a time: edit/trim → motion wording → anchor → shot design. Compare versions by the same acceptance criteria. Consider a still, cut, or sound cue for a beat that does not require generated motion.

## Working record and handoff

Keep a per-shot record: ID, anchor version, Kling prompt version, generated and usable duration, acceptance verdict, observed failure, in/out times, continuity frame, next adjustment layer, and final approved prompt. Preserve approved versions. Once shots pass, hand off their approved ranges, order, sound and dialogue cues, and continuity notes for editing. Check the assembled cut for comprehensible cause and effect, character/prop consistency, pacing and sound sync; revise only the affected shot if the final cut exposes a problem.

Adapt shot count and duration to the new theme and available media. Never carry over specific convenience-store actions, props, character outfits, or story beats by default.
