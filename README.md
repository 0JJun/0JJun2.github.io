# Cheating detection model

###         """
###         Input : 시험 도중 부정행위로 간주할 수 있는 음성의 MFCC 값.

###         Argument:
###         .txt -- MFCC가 저장 되어있는 텍스트 파일

###         X -- 수집한 음성 Data의 mfcc
###         Y -- X와 매핑된 Label
###         """

# Data Manufacturing

### TimeStep = 10으로 설정 후, Data 버림 작업
### One-hot Encoding

# Shuffle

### X, Y의 Mapping을 유지한 채, Random Shuffle

# Model
![image](https://user-images.githubusercontent.com/105787074/169682306-ed545718-64b8-434f-b364-eff9e772f44d.png)
