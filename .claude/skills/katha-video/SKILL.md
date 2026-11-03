---
name: katha-video
description: Create a vertical Hindi animated katha video from a pravachan audio file.
---

# Katha Video Skill

When the user runs `/katha-video <audio-file>`, follow these steps.

## Goal
Create a 9:16 Hindi devotional cartoon video using the supplied audio.

## Step 1: Analyze Audio
- Check the audio duration using FFmpeg.
- Transcribe Hindi speech into Devanagari.
- Show the transcript to the user for correction.
- Do not proceed until the user approves it.

## Step 2: Storyboard
- Divide the narration into short scenes.
- Identify characters, locations, and actions.
- Create a scene-by-scene animation plan.
- Keep all scenes consistent in Indian 2D cartoon style.

## Step 3: Characters
- Show a respectful cartoon depiction of Premanand Maharaj Ji when requested.
- Use consistent character designs.
- Include facial expressions, gestures, and body movements.
- Do not use static posters as a substitute for animation.

## Step 4: Animation
- Animate characters according to the narration.
- Add walking, hand movements, blinking, and scene transitions.
- Synchronize mouth movements with speech when suitable tools are available.
- If accurate lip-sync cannot be produced, clearly tell the user.

## Step 5: Subtitles
- Add Hindi subtitles.
- Display short phrases.
- Highlight the currently spoken words when alignment is available.

## Step 6: Final Video
- Use 1080x1920 resolution when possible.
- Preserve the original audio.
- Export an MP4 using H.264 and AAC.
- Save the output as output/katha_final.mp4.

## Important
Before rendering, check which tools are actually installed.
Never claim that animation, transcription, or lip-sync succeeded without verifying the output.
If a required tool is unavailable, explain what is missing.
