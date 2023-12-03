# AI Powerpoint to Video

Takes a `.pptx` file as input, then uses GPT-4 vision + any embedded speaker notes to write a transcript for the whole presentation. Finally it uses OpenAI's TTS to create a believable audio track, and compile the whole slide show as a video.

## Usage

* To get started, clone this repo
```
git clone https://github.com/chaonan99/ppt_presenter.git
cd ppt_presenter
```
* Install required packages
```
pip install -r requirements.txt
```

* Install other dependencies

- [`ffmpeg`](https://github.com/adaptlearning/adapt_authoring/wiki/Installing-FFmpeg)
- libreoffice
- poppler

* Watch the video `example/test.mp4`

