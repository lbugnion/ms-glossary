# Notes for the publisher

## Publishing a new video

> TODO Update

## Updating an existing video

- On [Github](https://github.com/lbugnion/wordsoftheday-md), create a new branch "TOPIC-update-nn" where
    - TOPIC is the current topic, for example `app-service`, `serverless`, `aad` etc.
    - nnn is an index to differentiate branches with similar names.

- Update the synopsis (in the [Synopsis folder](../synopsis))

- Edit the video and produce it.

- Update the captions file(s) (*.srt).
    - Caption files are saved in the [Captions folder](../captions).
    - Link to [Subtitle Edit for Windows](https://www.nikse.dk/SubtitleEdit/).

- Update the topic file (under [the Topics folder](../topics/)).

- Produce the video with embedded captions [with Handbrake](https://handbrake.fr/).
    - [See the Handbrake settings here](#handbrake)

- Upload the video with captions [in the Videos containers](http://gslb.ch/462).
    - If you don't have access to the Storage container, contact LBugnion@microsoft.com

- Publish the new video to YouTube.
    - [Instructions for YouTube](#youtube)

> Because of YouTube constraints, there is no way to update an existing video, you must publish it as a new video.

- Copy the new YouTube video code into the Topic file under `> YouTube: CODE`

> The YouTube code is what comes at the end of the YouTube URL. For example in `https://youtu.be/O3KuatPZjfs`, copy only the code `O3KuatPZjfs` to the Topic file.

- Double check everything, then commit the modified synopsis, captions and the topic file to the new branch.

- Push to GitHub

- Merge the new branch into Master and push to GitHub. This will trigger the website update.

- Once you verified that the site has been updated, delete the old YouTube video

<a id="handbrake"></a>

## Handbrake settings

> TODO Make screenshots

    - MP4
    - Web optimized: No
    - Align A/V Start: Yes
    - iPod 5G Support: No
    - 1080px x 1080px
    - H.264
    - 30PFS
    - **Quality: 30**
    - Audio AAC Bitrate 160
    - Import Subtitle
    - Forced Only: No
    - Burn In: No

<a id="youtube"></a>

## YouTube settings

### Title

Azure Words of the Day: TOPIC

### Description

Hello and welcome to Microsoft Azure Words of the Day, the show that teaches you the Azure vocabulary!

Today's words of the day are: TOPIC

More information, links etc:
LINK

> Use the friendly shortened link here, for example `http://gslb.ch/wod-serverless`.

### Other settings:

- Thumbnail: Upload a thumbnail looking like this:

![YouTube thumbnail](images/YouTubeThumb.png)

- Audience: No it's not made for kids
- Age restriction: None
- Visibility: Unlisted
- Playlists: Azure Words of the Day
- No end screen
- No cards

** More options**

- Recording date: Set
- Video location: None
- License: Creative Commons - Attribution
- Category: Science & Technology
- Original video language, subtitles and CC: Set
- Caption certification: None

- **Upload the captions file (SRT) here.**
    - With Timing

- Hold potentially inappropriate commens for review
- Users can view ratings for this video: Yes
- Allow embedding: yes
- Publish to the Subscriptions feed: Yes
- My video contains paid promotion: No
