# 🎹 Generative Melody Composer Using Deep Learning in MATLAB

## 📌 Project Overview

The **Generative Melody Composer Using Deep Learning in MATLAB** is an AI-based music generation project that explores the use of deep learning to compose new melodies automatically.

The project uses a Long Short-Term Memory (LSTM) neural network to learn patterns from sequences of musical notes represented in MIDI format. The trained model predicts subsequent notes to generate new melodic sequences, which can be converted into MIDI files and synthesized for audio playback.

## 🎯 Objectives

* Understand MIDI-based musical representation.
* Preprocess MIDI files into sequences suitable for deep learning.
* Develop an LSTM-based model for next-note prediction.
* Generate new melodies from seed note sequences.
* Export generated melodies into MIDI and audio formats.
* Explore the potential of deep learning in creative music generation.

## 🛠️ Technologies Used

* **MATLAB**: Main development environment.
* **Deep Learning Toolbox**: For LSTM-based sequence learning and model training.
* **LSTM Neural Network**: For learning sequential patterns in musical notes.
* **MIDI Format**: For representing and exchanging musical note information.
* **Audio Synthesis and Playback**: For listening to generated melodies.

## ⚙️ Project Workflow

1. **MIDI Dataset Collection**
   Obtain MIDI files containing musical note sequences.

2. **Data Preprocessing**
   Extract note pitches and prepare sequences for model training.

3. **Sequence Preparation**
   Create input and target sequences for next-note prediction.

4. **Model Training**
   Train an LSTM neural network to learn patterns in the input sequences.

5. **Melody Generation**
   Use a seed sequence to predict subsequent notes and generate a new melody.

6. **MIDI and Audio Output**
   Convert generated notes into MIDI files and/or synthesized audio.

7. **Evaluation**
   Examine the generated output for note variety, repetition, and melodic coherence.

## 🧠 How LSTM Works in This Project

LSTM is a type of recurrent neural network designed to learn patterns in sequential data. It maintains information from earlier elements in a sequence, making it useful for tasks involving time-dependent patterns.

In this project, the LSTM model processes musical note sequences and predicts the next note based on patterns learned during training.

## 📂 Project Structure

```text
Melody-Generator-MATLAB/
├── run_melody_generator.m
├── src/
│   ├── readMidiPitches.m
│   ├── writeSimpleMidi.m
│   └── synthesizeMelody.m
├── data/
│   └── midi/
│       └── starter_melody_*.mid
├── outputs/
└── README.md
```

*Note: This is the expected structure of the starter project. Update it if your uploaded files differ.*

## 💻 Requirements

* MATLAB compatible with the project's code.
* Deep Learning Toolbox for LSTM model training.
* Audio output device for playback.
* Audio Toolbox if required by the selected audio-processing workflow.

The required MATLAB version and toolbox compatibility should be checked before execution.

## ▶️ How to Run

1. Download or clone this repository.
2. Extract the project files if downloaded as a ZIP archive.
3. Open MATLAB.
4. Navigate to the project root directory.
5. Ensure the required toolboxes are installed.
6. Open and run `run_melody_generator.m`.
7. Check the `outputs` folder for generated files, if execution completes successfully.

If an error occurs, review the MATLAB error message and check whether the code is compatible with your installed MATLAB version.

## 📊 Evaluation Criteria

The generated melodies can be evaluated based on:

* Successful generation of MIDI or audio output.
* Variety of predicted notes.
* Repetition within generated sequences.
* Melodic coherence.
* Rhythm consistency, if timing information is implemented.

Actual results should be recorded after running the project. No performance scores should be reported without testing.

## ⚠️ Limitations

* A small starter dataset is insufficient for robust music generation.
* Pitch-only sequences may not fully represent rhythm, duration, chords, or musical expression.
* Output quality depends on the training data and model configuration.
* Compatibility and successful execution must be verified in the target MATLAB environment.

## 🚀 Future Scope

* Train the model on a larger, appropriately licensed MIDI dataset.
* Include note duration, rhythm, velocity, and rests.
* Generate chords and polyphonic music.
* Support multiple musical instruments.
* Compare LSTM with other generative models.
* Improve evaluation through musical analysis and listening tests.

## 📝 Conclusion

This project explores how deep learning can be applied to automatic melody generation using MATLAB. By learning patterns from MIDI note sequences, an LSTM-based model can be used to predict subsequent notes and create new melodic sequences.

The project provides a foundation for further exploration of AI-driven music generation using richer datasets and more advanced musical representations.

## 📚 References

* MathWorks documentation for Deep Learning Toolbox and LSTM networks.
* MathWorks documentation for audio processing and playback.
* MIDI Association resources on the MIDI file format.

## 👨‍💻 Author

**Sahil Mahapure**
Department: Automation & Robotics Engineering
Institution: MES Wadia College of Engineering

## 📄 License

No license has been specified for this repository. Unless a license is added, the default copyright rules apply.
