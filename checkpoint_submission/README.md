# Checkpoint submission materials

**Status: NOT READY. The team slide is still a placeholder: add your team to `video/team.json` and rebuild.**

Upload one MP4 to Gradescope by Thursday 11/05, 11:59 PM. Current length: 1:47 (limit 2:00).

| # | The submission asks for | File | In the video at |
|---|---|---|---|
| 1 | Team name and members | `1_team.png` | 0:00 |
| 2 | Dataset and the aspects you plan to use | `2_dataset.png` | 0:02 |
| 3 | 5-6 exploratory graphs that led to the question | `3a` to `3f` | 0:16 |
| 4 | Title of the graph, or the question | `4_question.png` | 1:02 |
| 5 | Current progress on the final dynamic graph | `5_progress_demo.mp4` (no audio) | 1:06 |
| | Voiceover | `voiceover_script.md` | whole video |

## The videos

- `checkpoint_draft.mp4`: the whole video with a text-to-speech voice.
- `checkpoint_silent.mp4`: the same video with no audio, to record over. One person can do the recording.
- `checkpoint_final.mp4`: appears after you add your own recording, as below.

## Finish it

1. Put your team in `video/team.json`.
2. Rebuild. This refreshes everything in this folder:

       cd video && ../.venv/bin/python build_video.py

3. Optional, to use a real voice: read `voiceover_script.md` over `checkpoint_silent.mp4`, then:

       cd video && ./add_voice.sh your_recording.m4a

The individual files are here in case you would rather assemble the video yourself.
