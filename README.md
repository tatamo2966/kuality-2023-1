# kuality-2023-1
scanf함수는 버퍼오버플로우 해킹기법에 취약하다. 버퍼오버플로우 기법은 어떤 프로그램에 비정상적인 데이터를 많이 주입하여, 오류를 발생시키거나,
임의이 악성 코드를 실행하게 만드는 기법이다. scanf 함수는 입력받은 데이터의 크기를 고려하지않고 전부 복사하기때문에 bof기법에 취약하다.
