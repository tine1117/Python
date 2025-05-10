# Python
My python code

### Audio Program
**[Audio Joiner] ([AudioProgram/AudioJoiner.py](https://github.com/tine1117/Python/blob/main/AudioProgram/AudioJoiner.py))**
- This program concatenates multiple .wav audio files, adding silence between each file if needed, and saves the combined audio as a new .wav file.
- 여러개의 음성 파일을 합쳐서 하나의 파일로 만드는 프로그램입니다. 무음을 넣어서 음성 파일간 간격을 조절할 수 있습니다.
- python AudioJoiner.py <audio_directory_path> <audio_save_name> <audio_empty_time>
- <audio_empty_time> 1000ms

**[Audio Split] ([AudioProgram/AudioSplit.py](https://github.com/tine1117/Python/blob/main/AudioProgram/AudioSplit.py))**
- This is a program that splits a single Korean audio file into sentence‐level segments and then generates a dataset.
- 하나의 음성파일을 문장단위로 자른 후 데이터셋을 생성하는 프로그램입니다.
- Usage : python AudioSplit.py <input_audio_path> <output_audio_path> <dataset_name>
