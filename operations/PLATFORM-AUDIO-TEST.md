# Online Platform and Music-Audio Verification

**Status:** Not yet tested. Comparison must include representative facilitator and participant networks, especially connections used from Iran. Do not assume any platform is reachable or works equally for everyone.

## Candidate platforms

| Candidate | Documented capabilities to investigate | Unknowns to test locally |
|---|---|---|
| Zoom | Original sound for musicians; computer audio sharing; local MP4/MOV built-in video file player | Actual accessibility, stability and intelligibility on participants' connections; host license, phone behavior |
| Skyroom | Persian-oriented online classroom with media playback, chat, whiteboard and roles reported in published guides | Actual sound fidelity for musical details, cue/pause behavior, browser/device coverage, access for facilitator and attendees |
| Backup option | Choose only after testing | Join procedure, audio quality, ownership and fallback |

Useful technical references:
- Zoom original sound and live performance caveats: https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0059985
- Zoom direct video file playback: https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0064733
- Skyroom overview (education technology journal): https://www.roshdmag.ir/fa/article/28168/اسکای-روم

## Test participants and equipment

- Facilitator on production computer with headphones and live instrument/mic input.
- Dedicated technical cohost using a separate account/device.
- At least one person connecting from a typical participant network inside Iran.
- At least one mobile participant and, where possible, a weaker internet connection.
- A second listening device to verify the **received** audio rather than relying on the facilitator's local playback.

## A/B test script (15–25 minutes per candidate)

| Step | Test action | Pass criterion / evidence |
|---|---|---|
| 1 | Open join link as guest/mobile participant | Joins and understands instructions without special technical support |
| 2 | Talk at ordinary volume, then silence | Persian speech intelligible; no persistent echo |
| 3 | Play 20 seconds of licensed/test musical audio | Listener hears attacks, pauses, soft/loud contrast and timbral differences |
| 4 | Share a subtitled video excerpt, pause at cue, resume | Words readable on a phone; video/audio remain sufficiently synchronized |
| 5 | Demonstrate the **same phrase** live twice with a controlled change | Listener can identify intended musical distinction |
| 6 | Run participant A → silence → participant B response | No overlapping talk; cohost can manage microphones |
| 7 | Switch briefly to limited bandwidth/mobile | At least speech + core audible examples remain usable, or fallback works |
| 8 | Simulate broken video share or facilitator disconnect | Cohost gives next instruction; facilitator resumes using prepared backup |

Record platform, app/browser and version, test region/network type, device type, speakers/headphones, issues and the participant's perceived sound quality. **Do not record IP addresses, credentials or private details in this public repo.**

## Zoom-specific trial configuration

- For recorded music, try **Share → Advanced → Video file** with compatible H.264 MP4/MOV. Compare against screen share + computer sound.
- For live playing, test **Original sound for musicians** instead of speech-oriented noise filtering. Use headphones and check echo suppression behavior.
- High-fidelity music and live-performance modes increase resource/network requirements; do not force them on a heterogeneous beginner group.
- Avoid claiming perfect low-latency synchronized ensemble audio.

## Operational fallback ladder

1. Retry playing the **same audio locally via a different supported sharing method**.
2. Use the facilitator's original live melody example (one element changed).
3. Share a short written prompt; ask chat answers and demonstrate one participant suggestion live.
4. If the facilitator disconnects, cohost preserves the session, tells participants what to do, and shares the approved reconnection path.
5. If core listening is impossible for a substantial portion of the group, stop the affected activity; arrange an accessible alternative or reschedule rather than falsely claiming learning occurred.

## Decision matrix (fill only after tests)

Score each candidate from 0–2 on: (a) joining/availability; (b) music audio intelligibility; (c) stable video subtitle delivery; (d) host control and participant turn-taking; (e) mobile/weak-network use; (f) support/backup. Document actual observations; totals guide discussion but **any failure of intelligible musical audio or access is disqualifying until fixed**.

| Candidate | Join | Music | Video | Interaction | Mobile/weak | Backup | Decision |
|---|---|---|---|---|---|---|---|
| Zoom | OPEN | OPEN | OPEN | OPEN | OPEN | OPEN | UNTESTED |
| Skyroom | OPEN | OPEN | OPEN | OPEN | OPEN | OPEN | UNTESTED |
