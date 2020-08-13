# ExtractMelspectrogram

wav 파일을 spectrogram 형태로 변경

## librosa를 활용하여 MelSpectrogram을 추출하는 코드
- librosa를 활용하여 melspectrogram을 추출
- matplotlib를 통해서 spectrogram을 그리는 대신 해당 소스코드는 axis나 label을 다 제거한 순수한 melspectrogram만 추출

## use get_melspectrogram_features
- input_dir : 음원파일이 존재하는 디렉토리 경로를 설정
- output_dir : 추출된 melspectrogram을 png 파일로 저장할 디렉토리 이름
- sample_rate : sample_rate
