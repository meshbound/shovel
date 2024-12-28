## Usage
Execute `src/main.py`.
- The first run generates **shovel.ini**.
- For help, use the **--help** flag.

https://github.com/meshbound/Shovel/assets/60497577/2bb3ae3d-49b9-45d5-8a1d-27f0d1547051

## Extras
- Place videos for the bottom in `stash/assets/bottoms`.  
- Add background music to `stash/assets/music`.  
- Customize overlays with your preferred software and place in `stash/assets/overlays`.

## Requirements
-   Python environment satisfying  `requirements.txt`.
-   `imagemagick` install.
-   `wkhtmltopdf` install.
-   `Arial.ttf`  font file.

## Generating Content

-   Set `use_placeholder`  instances in  **shovel.ini**  to  `False`  as needed.
-   Provide OpenAI API key and model for script generation in  **shovel.ini**.
-   Supply Stability API key for image generation in  **shovel.ini**.
-   System TTS engine is used by default.

While configuring, it's recommended to set  `use_placeholder`  to  `False`  one at a time.

## Leveraging Google TTS

1.  Select a project on Google Cloud Platform.
2.  Enable Cloud Text-to-Speech API.
3.  Create a serivce account.
4.  Download service account keys.
5.  Place keys in  `auth/google`.
6.  Set  `use_placeholder`  to  `False`  in  **shovel.ini**.

## Uploading Content to YouTube

1.  Select a project on Google Cloud Platform.
2.  Enable YouTube Data API v3.
3.  Download OAuth 2.0 client secrets.
4.  Place client secrets in  `auth/youtube`.
5.  Set  `do_not_upload`  to  `False`  in  **shovel.ini**.

Upload videos at your discretion; we do not condone abuse.
