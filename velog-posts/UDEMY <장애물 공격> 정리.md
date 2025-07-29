<h3 id="장애물-공격">장애물 공격</h3>
<p>[Udemy] Unreal Engine 5 C++개발자: C++학습하고 비디오 게임 제작하기의 장애물 공격 파트를 공부하고 필요한 내용을 정리한 노트이다.</p>
<h4 id="46-uproperty-변수">46. UPROPERTY 변수</h4>
<p>프로퍼티는 표준 C++변수 문법이다. 변수 선언을 통하여 에디터에서 변수를 확인할 수 있다.</p>
<blockquote>
</blockquote>
<pre><code>UPROPERTY([specifier, specifier, ...], [meta(key=value, key=value, ...)])
Type VariableName;</code></pre><p>UPROPERTY에 대한 더 자세한 내용과 프로퍼티 지정자에 대한 내용. <a href="https://dev.epicgames.com/documentation/ko-kr/unreal-engine/unreal-engine-uproperties">[언리얼엔진 문서]</a></p>
<p><img alt="" src="https://velog.velcdn.com/images/ldsldy/post/ae7d28dd-185e-405d-8390-00c21d4974a3/image.png" /></p>
<p><img alt="" src="https://velog.velcdn.com/images/ldsldy/post/d4f5388b-2fae-4c08-9644-da2023f1098f/image.png" /></p>
<h3 id="59블루프린트-하위-클래스">59.블루프린트 하위 클래스</h3>
<p>같은 기능을 하는 오브젝트가 여러개 필요할 때, 이에 일일이 C++파일을 연결 시키는 것은 힘든 일이다. 따라서 C++클래스를 기반으로 하는 블루프린트 클래스를 만들어 활용할 수 있다.
<img alt="" src="https://velog.velcdn.com/images/ldsldy/post/39ba1c05-5d02-4ad4-9f98-45f8325d22a3/image.png" /></p>
<h3 id="60캐릭터-충돌-강제-적용">60.캐릭터 충돌 강제 적용</h3>
<p>캐릭터 코드는 움직이지 않는 한 콜리전(물리적 충돌이나 레이 캐스팅을 실시간 처리)을 확인하지 않는다. 따라서 이를 해결하기 위한 장치를 해야하는데 여기서는 틱마다 캐릭터를 움직이게하여 인식하게 하였다.
<img alt="" src="https://velog.velcdn.com/images/ldsldy/post/93162017-90a3-4521-a170-b9554ede4c5d/image.png" /></p>
<h3 id="61게임모드">61.게임모드</h3>
<p><a href="https://velog.io/@ldsldy/UE5-%EA%B2%8C%EC%9E%84%EB%AA%A8%EB%93%9C">게임모드에 관한 포스팅</a></p>
<h3 id="62-출력-로그에-기록하기">62. 출력 로그에 기록하기</h3>
<p><a href="https://velog.io/@ldsldy/%EC%96%B8%EB%A6%AC%EC%96%BC5%EC%97%90%EC%84%9C%EC%9D%98-Log-%EC%B6%9C%EB%A0%A5">로그에 관한 포스팅</a></p>