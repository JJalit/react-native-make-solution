# react-native-make-solution
react-native-make-solution

react-native-make에서 splashscreen ios 적용시 블랙 스크린 현상 해결

1. npx react-native set-splash --path ./src/Assets/Images/app_splash.png --resize cover
2. SplashScreen.storyboard 파일 위치 상단으로 이동
3. info.plist와 이외 파일들 SplashScreen으로 설정 되어있는지 확인
4. npx react-native set-splash --path ./src/Assets/Images/app_splash.png --resize cover --background black
5. 2400 x 2400 규격의 스플래쉬 png 파일을 x3에 넣고 나머지 제거
6. 계속 리셋하고 계속 껐다 켰다 반복 
7. 게속 xcworkspace 껐다 켰다 반복
8. 어느 순간 뜸

### result
##### 그냥 설정 끝내고 다음꺼 하는게 좋다.. 캐싱되어있는 것이 바뀌는데 까지 좀 걸리나 보다.
