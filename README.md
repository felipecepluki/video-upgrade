# Video Upgrade

## About
This project is base in [video-to-reels](https://github.com/diego3g/video-to-reels) repo and Youtube Video of Rocketset Channel at the title [WE AUTOMATE INSTAGRAM REELS EDITION [feat. Mayk Brito]](https://www.youtube.com/watch?v=i6EcAV0yhqg&t=833s)

## Dependencies
To run this script you need to install locally on your machine the following dependencies:

- [Node.js](https://nodejs.org/en)
- [FFmpeg](https://ffmpeg.org/)
- [Imagemagick](https://imagemagick.org/index.php)
- [ZX](https://github.com/google/zx)

## Running
1. Open `detect-face` folder and rum `npm install`;
2. Save a video inside the `origins` folder;
3. Change the value of `videoFile` variable inside `convert.mjs`;
4. Run `zx convert.mjs` in the root folder to start the conversion;
5. Done! The output file will be stored at `/videos` folder;

# Features
- [ ] Resize
- [ ] Color filter
- [ ] Audio normalization
- [ ] Remove background noises
- [ ] Position video by face
- [ ] Cut video when not talking
- [ ] Subtitles
- [ ] Post video in social media 
