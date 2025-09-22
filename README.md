# Emotion-Aware UI Prototype

A simple Tkinter-based interface that adapts its appearance
based on the user’s detected emotions (via webcam).

## 🚀 How to Run

1. Clone this repo
<code>
git clone https://github.com/yourusername/emotion-ui.git
cd emotion-ui
</code>

# Structure
<code>
emotion-ui/
│
├── README.md                 # Project overview, how to run
├── requirements.txt          # Python dependencies
├── .gitignore                # Ignore unnecessary files
│
├── src/                      # Source code
│   ├── main.py               # Main app (Tkinter + DeepFace)
│   ├── detector.py           # Functions for emotion detection
│   ├── ui.py                 # UI logic (Tkinter windows, colors, etc.)
│   └── utils.py              # Helper functions (logging, config loading)
│
├── data/                     # Store any sample images, test videos
│   └── sample.jpg
│
├── logs/                     # Logs of detected emotions
│   └── emotions.csv
│
├── docs/                     # Documentation, research notes, diagrams
│   └── design.md
│
└── tests/                    # Unit tests
</code>
    └── test_detector.py
