# Audio_cleaning_pipeline
This repository contains a pipeline to clean audio files. The pipeline can reduce background noises, detect and remove silence, change the pitch, and make the sound louder.

Summary: 
1. This repository contains a pipeline to clean audio files.
2. The pipeline can reduce background noises, detect and remove silence from the beginning and end of videos, change the pitch of audio, and make the sound more louder.
3. The pipeline is implemented in Python and uses the following libraries:
    * librosa
    * numpy
    * scipy
    * soundfile
4. To use the pipeline, you can follow these steps:
    1. Clone the repository to your local machine.
    2. Install the dependencies.
    3. Run the following command to clean an audio file:
        `python clean_audio.py <audio_file>`
5. The pipeline will output a cleaned audio file with the same name as the input file, but with the extension `.cleaned`.
6. The pipeline is still under development, but it has been tested on a variety of audio files and has been shown to be effective in cleaning audio files.
7. If you have any feedback or suggestions, please feel free to open an issue in the repository.
8. Thank you for using this pipeline!

Here are some additional details about each of the tasks that the pipeline can perform:

* **Reduce background noises:** The pipeline uses a variety of techniques to reduce background noises, including:
    * Spectral subtraction
    * Wiener filtering
    * Notch filtering
* **Detect and remove silence from the beginning and end of videos:** The pipeline uses a simple threshold to detect silence. Silence is defined as any section of audio that has a mean amplitude below a certain threshold. The pipeline then removes any sections of audio that are detected as silence.
* **Change the pitch of audio:** The pipeline can change the pitch of audio by adjusting the sample rate of the audio file. A higher sample rate will result in a higher pitch, while a lower sample rate will result in a lower pitch.
* **Make the sound more louder:** The pipeline can make the sound more louder by adjusting the volume of the audio file. A higher volume will result in a louder sound, while a lower volume will result in a quieter sound.
