# PartyAI: Your Dance Party AI 🕺 🎶

PartyAI is a multimodal user interface called PartyAI that tracks crowd engagement and facilitates music selection at dance parties using a webcam and pre-trained YOLOv5 head and hand detection model. Watch PartyAI_demo.mp4 for a demo.

## Table of Contents 🗂

├── models/ - pytorch helper functions for inference with YOLOv5 model
├── utils/ - helper functions for loading data from webcam with opencv, checking file types, and annotating frames with opencv
├── export.py - exports a YOLOv5 PyTorch model to other formats
├── input.mp4 - example party video setup used in development
├── PartyAI_demo.mp4 - system demo video
├── partyai_dev.ipynb - development notebook
└── partyai_main.ipynb - RUN THIS jupyter notebook
└── partyai_model.pt - weights for YOLOv5 head and hand detection model
└── requirements.txt - python3 packages to install

## Prerequisites 🛠️

The system runs in a Python >=3.10 Environment and VSCode.

A Spotify Developer Account is needed to control music. Create a Client ID and Client Secret. [Guide](https://medium.com/@maxtingle/getting-started-with-spotifys-api-spotipy-197c3dc6353b)

PartyAI has been tested on a MacBook Pro with Apple M1 and 12.1 MacOS (Monterey).

## Run 🏃‍♂️

Open partyai_main.ipynb in local jupyter notebook IDE (VSCode is preferred, [guide here](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)).

Run first block of code to pip install all necessary python packages.

Replace Spotify Client ID and Client Secrent in second block of code, then run.

Run third block of code and have fun with PartyAI!

## Questions ❓

Have any questions or concerns? Feel free to reach out to rik01@mit.edu.
