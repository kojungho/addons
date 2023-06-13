## RELEASE NOTES
```txt
0.8.7.0 설치 시 오류 수정
0.8.7 hyundai 월패드 js 파일 업데이트
0.8.6 알파인 리눅스에서 python을 python3로 변경해서 설치해야 함
0.8.3 hyundai 월패드 수정
0.8.2 타 월패드도 소켓 연결 추가. config 설명 json에서 yaml로 수정
0.8.1 삼성 월패드 소켓 연결 추가 
0.8 코맥스 월패드 테스트 완료
```


  DEVICE_CONFIG: {
    'switch/homenet/breaker3-1': { name: '엘베호출', unique_id: 'switch-homenet-breaker3-1', state_topic: '~/elv/state', command_topic: '~/elv/command' },

  //          엘베       34


    // breaker2(away): f7 0e 01 2a 04 40 10   00 19 02 1b 04 82


    { base_topic: 'switch/homenet/breaker3-1', commandHex: 'f7 0b 01 34 02 41 10 06 00 9c ee'.toBuffer(), ackHex: 'f7 0b 01 34 04 41 10 00 06 9a ee'.toBuffer(), stateName: 'elevator', state: 'CALL' }
