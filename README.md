# Echo rotation reading: expert pilot

A browser-based reading task for echocardiography. Each trial shows two apical recordings from one patient. The reader
says which way the probe rotated between them, or that they can't tell, and gives a confidence rating. The reader also
says whether both recordings are four-chamber views, and which recording is more suitable for assessing LV function.

**Open the pilot:** https://elahej.github.io/echo-rotation-reading-test/

- Use a laptop or desktop browser (Chrome, Edge or Safari). 34 trials, 30 to 40 minutes.
- Answers are saved in your browser after every trial, so you can stop and resume on the same computer and browser.
- Enter the access code from the study team's email. Answers are sent to the study team automatically at the break
  and at the end. If sending fails, click **Download answers** and email the CSV file to the study team.
- To work offline instead, download this repository as a ZIP and open `index.html`.

## Status

12 November 2026: this page serves a short expert pilot. The full 130-trial reading test is paused until the pilot has
been read. It is kept at the tag `full-test-build_5`. The `clips/` folder holds the recordings of both.

## Data and licence

The clips are derived from the EchoXFlow dataset (Ahus-AIM), https://huggingface.co/datasets/Ahus-AIM/EchoXFlow,
pinned commit `7a36922880061791519a8f01553c15cad5df564f`. EchoXFlow is licensed under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Changes: selected 2D recordings were scan-converted from beamspace to display images and encoded as MP4 video.

This repository is shared under the same licence, CC BY-NC-SA 4.0. Non-commercial research use only.
