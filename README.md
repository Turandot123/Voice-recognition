# Voice-recognition

## TODO's
- Record an audio file of the following sentence "Hello, my name is <your_name_here>"
- Open the file using pydub
- Apply a low-pass `Butterworth` digital filter (the order of the filter doesn't matter). Choose different `Wn` also known as cuttoff frequency and plot the signal `filtered` and `unfiltered`. Use `filtfilt`.
- Do the same with a high-pass filter (read the docs 😼)
- Explain the visual differences of the high-pass and low-pass filter on the filtered signal.
- Choose `butter` filter parameters to save an `mp3` audio file of your recording that resembles to be recorded from a phone call
## How to deliver the project
- Deliver your code in following folder as a PR: `module2/lab-pydub-filter`
## Links & Resources
- https://github.com/jiaaro/pydub
- https://docs.scipy.org/doc/scipy-0.14.0/reference/generated/scipy.signal.butter.html
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.filtfilt.html
