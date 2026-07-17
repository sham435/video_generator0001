# Demo Video Guide for TikTok App Review

This guide explains how to record a demo video that satisfies TikTok's app review requirements.

## Requirements

- **Format:** MP4 or MOV, max 50MB
- **Environment:** Must use TikTok's sandbox environment (not production)
- **Content:** Must show the complete end-to-end flow of TikTok integration
- **Domain:** Website shown in the video must match `sham435.github.io/video_generator0001/`
- **Scopes:** All selected scopes must be clearly demonstrated

## Scopes to Demonstrate

| Scope | How to Show |
|-------|-------------|
| `user.info.profile` | Show the app displaying the user's TikTok username and avatar after login |
| `user.info.stats` | Show the app displaying follower count, likes count, video count |
| `video.list` | Show the app reading and displaying the user's existing TikTok videos |
| `video.upload` | Show the app uploading a rendered video to TikTok |
| `video.publish` | Show the user confirming and the video appearing on their TikTok feed |

## Recording Script (Step-by-Step)

### Scene 1: Website Overview (10 seconds)
1. Open browser to `https://sham435.github.io/video_generator0001/`
2. Show the homepage with features and TikTok Integration section
3. Scroll down to show Privacy Policy and Terms of Service links in the footer

### Scene 2: Login with TikTok (15 seconds)
1. Click "Login with TikTok" button
2. Show the TikTok authorization screen (sandbox environment)
3. Show the scopes being requested: profile, stats, video list, video upload, video publish
4. Click "Authorize" to grant access
5. Show the app displaying the user's TikTok username, avatar, and follower stats

### Scene 3: Generate Content (20 seconds)
1. Enter a subject description (e.g., "fitness coach from ref photo")
2. Enter outfit list (e.g., "Look A|gym wear|gym; Look B|track suit|outdoor track")
3. Click "Generate"
4. Show the generated video prompt and social media post text
5. Show the app rendering the video (NVIDIA NIM cloud)

### Scene 4: View TikTok Videos (10 seconds)
1. Show the app displaying the user's existing TikTok video list
2. Demonstrate that `video.list` scope is working

### Scene 5: Publish to TikTok (15 seconds)
1. Click "Publish to TikTok"
2. Show the video being uploaded (Content Posting API)
3. Show the user confirmation screen
4. Show the video appearing on the user's TikTok feed in the sandbox

### Scene 6: End (5 seconds)
1. Return to the website homepage
2. Show the Privacy Policy and Terms of Service links again

**Total: ~75 seconds**

## Recording Tools

- **macOS:** QuickTime Player (File → New Screen Recording)
- **Browser:** Use Chrome or Safari in sandbox mode
- **TikTok Sandbox:** Access via TikTok Developer Portal → your app → Sandbox tab

## Tips

- Use TikTok's **sandbox environment** (not production) for the demo
- Keep the video under 50MB
- Show clear cursor movements and clicks
- Narrate each step if possible (optional but helpful)
- Make sure the website URL in the video matches `sham435.github.io/video_generator0001/`
