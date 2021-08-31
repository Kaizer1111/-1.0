## <이 프로그램은 국립 국어원 API를 이용한 끝말잇기 코드입니다. 소스를 가져가실때는 반드시 원작자 표시를 해주시기 바랍니다.>

---
### <사용법>
1. **apikey 변수에 자신의 국립국어원 API를 넣습니다.** <u>(매우 중요)</u>(국립국어원 api를 받는 방법은 https://waddlecorp.github.io/2019/10/31/%EA%B0%9C%EB%B0%9C%EC%9D%B4%EC%95%BC%EA%B8%B0-%ED%91%9C%EC%A4%80%EA%B5%AD%EC%96%B4%EB%8C%80%EC%82%AC%EC%A0%84-api-%EC%82%AC%EC%9A%A9%ED%95%B4%EC%84%9C-%ED%81%AC%EB%A1%A4%EB%A7%81%ED%95%98%EA%B8%B0/ 참고)
2. 실행한다.
3. 끝!

### <코드설명>
1. 먼저 국립국어원 api를 사용, 파싱합니다.
2. xml파일(데이터)에 맞게 xml을 파싱할 수 있게 해주는 xml.etree.ElementTree를 임포트, 데이터를 가공합니다.
3. 단어를 받고, 여러가지 검사(명사인지, 한방단어인지, 이미 쓴 단어인지, 앞 단어의 끝과 현재 단어의 앞이 맞는지 등)
4. 만약 사용자가 '그만', '멈춰', 'end', 'stop'을 입력했다면 프로그램을 종료합니다.

<u>**참고 사항 : version 1.0은 혼자서만 플레이할 수 있습니다^^**</u>


```
git clone https://github.com/Kaizer1111/end_to_end_version-1.0.git
```
