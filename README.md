# REPZ Basketball Shot Analyzer

## Project Overview

REPZ Basketball Shot Analyzer is a computer vision project that uses pose detection to analyze basketball shooting form.

As a former college basketball coach, I wanted to create a tool that could help players during individual workouts and at-home training when a coach is not present.

The system detects body landmarks, measures shooting posture, and gives simple feedback based on the player’s form.

---

## Problem

Many basketball players train on their own at home, in the gym, or during individual workouts.

The problem is that players may take hundreds of shots without receiving feedback from a coach.

Without feedback, athletes can repeat poor shooting habits such as bad elbow position, poor balance, or limited knee bend.

---

## Solution

This project uses computer vision to detect a player’s body position during a basketball shot.

The system focuses on key body points such as:

- Shoulder
- Elbow
- Wrist
- Hip
- Knee
- Ankle

It then uses those landmarks to help evaluate shooting form.

---

## Tools Used

- Python
- Google Colab
- MediaPipe Pose
- OpenCV
- NumPy
- Matplotlib

---

## System Workflow

Input basketball image or video  
→ Detect body landmarks  
→ Measure body position  
→ Analyze shooting form  
→ Generate feedback  
→ Save output results  

---

## Project Files

- `README.md` - Project overview and instructions
- `requirements.txt` - Python dependencies
- `data/raw/` - Test basketball images or videos
- `notebooks/` - Google Colab notebook
- `src/` - Source code
- `results/images/` - Output images from the system
- `docs/AI_usage_log.md` - AI usage documentation
- `docs/inference_report.md` - Inference report
- `docs/presentation.pdf` - Final presentation slides

---

## Presentation Slides

The final presentation slides can be found here:

[View Presentation Slides] https://docs.google.com/presentation/d/1o7v9jWevLUIGF_eFtqI7n3dsPjzXvB1b_uh_JoQwoWo/edit?usp=sharing 

---

## Demo Video

Demo video link:

PASTE DEMO VIDEO LINK HERE

---

## Results

| Metric | Value |
|---|---|
| Total test cases | 5 |
| Successful detections | 4 |
| Failed detections | 1 |
| Detection success rate | 80% |
| Average inference time | 0.08 seconds per image |

---

## Challenges

The system worked best when the full body was visible and lighting was clear.

The system struggled when:

- Body parts were blocked
- The image was blurry
- The player was turned at a difficult angle
- Lighting was poor

---

## Future Improvements

Future improvements include:

- Live camera feedback
- Shot make/miss tracking
- Player profiles
- Rep history
- Full REPZ athlete development reports

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload a basketball shooting image or video.
3. Run each cell in order.
4. View the output in the `results/images/` folder.

---

## AI Usage

AI was used to help organize the project, create documentation, plan the presentation, and support code development.

Full documentation is located in:

`docs/AI_usage_log.md`

---

## License

Academic Use Only
