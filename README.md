# -
음성인식기반 텍스트변환
섹션	내용 및 포함할 근거									
제목 및 배지	프로젝트 이름(예: 실시간 화자 분리 음성 인식 앱)과 기술 스택 배지(Kotlin, Android, Google Cloud)를 추가합니다.									
개요 (Introduction)	프로젝트의 목표를 명확히 설명합니다. "사용자의 음성을 놓치지 않고 실시간으로 텍스트 변환하며, 화자 분리(A, B) 기능을 제공하는 안드로이드 앱"과 같이 기술합니다.									
핵심 기술 및 아키텍처	"사용된 핵심 기술을 강조합니다. 
1. Kotlin Native: 고성능 및 안정적인 실시간 오디오 처리. 
2. Google Cloud STT Streaming API: setInterimResults(true)를 활용한 실시간성 확보. 
3. Speaker Diarization: 화자를 A, B로 ""담백하게"" 분리하는 커스텀 로직. 
아키텍처 다이어그램()을 포함하면 이해도를 높일 수 있습니다."									
설치 및 실행 방법	"1. Android Studio에서 프로젝트를 클론하는 방법. 
2. Google Cloud 자격 증명 설정 (API Key 또는 서비스 계정 파일 경로) 방법을 자세히 설명합니다."									
주요 코드 스니펫	SpeechRecognitionManager.kt의 setEnableSpeakerDiarization(true) 설정 부분과 MainActivity.kt의 getSpeakerName 함수(A, B 변환 로직)를 보여주어 핵심 기능을 부각합니다.									
데모 (Demo)	앱이 실행되는 짧은 GIF 또는 스크린샷을 첨부하여 '놓치지 않고' 실시간으로 텍스트가 변환되는 모습을 시각적으로 보여줍니다.									
