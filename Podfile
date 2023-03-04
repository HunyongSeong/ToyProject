platform :ios, '13.0'

target 'Flash Chat iOS13' do
  use_frameworks!

  # Pods for Flash Chat iOS13
  
  pod 'CLTypingLabel', '~> 0.4.0'
  # pod 파일을 제거할때는 바로 위 코드를 지운다. 그리고 스토리보드에서 애니메이션을 주기위해서 글자를 UIkit -> CLTypingLabel 로 변경해준 것을 다시 원상복구한다. 그리고 저장.
  # 그리고 터미널로 가서 다시 pod install 해주면 이번에는 삭제된다.(초기화 설치)
  
  # 참고
  # pod update 는 말그대로 업데이트 시키는 것이다
  
  
  
  # 데이터 베이스 만들기
  # https://firebase.google.com/docs/storage/ios/start?hl=ko
  # 단계별로 진행하면 아래에 코드가 생성된다
  
  pod 'FirebaseAuth'
  pod 'FirebaseFirestore'

end
