<h3 id="게임-모드란">게임 모드란?</h3>
<p>텍스트게임 모드(GameMode)는 게임의 규칙 세트를 정의한다. 그 규칙에는 플레이어의 게임 참가, 게임 일시정지, 레벨 전환 방식은 물론, 승리 조건과 같은 게임 전용 작동방식이 포함된다. 게임 모드는 각 레벨별로 설정되며, 다수의 레벨에서 재사용 가능하다. <a href="https://dev.epicgames.com/documentation/ko-kr/unreal-engine/setting-up-a-game-mode-in-unreal-engine">[dev.epicgames.com/documentation]</a></p>
<h3 id="게임-모드-블루프린트-생성">게임 모드 블루프린트 생성</h3>
<ol>
<li>콘텐츠 브라우저에서 생성
콘텐츠 브라우저 &gt; +추가 &gt; 블루프린트 클래스 &gt; 게임 모드 베이스<img alt="" src="https://velog.velcdn.com/images/ldsldy/post/70ff70ee-e972-4a9a-8543-68a0dde877bc/image.png" /></li>
<li>에디터 툴바의 블루프린트 메뉴에서 생성
<img alt="" src="https://velog.velcdn.com/images/ldsldy/post/9f1704cb-a4b2-4c10-9f55-a8d14619bdc4/image.png" /></li>
</ol>
<h3 id="gamemode-vs-gamemodebase">GameMode VS GameModeBase</h3>
<blockquote>
<p>GameModeBase
<em>GameMode</em> 보다 가벼운 클래스</p>
</blockquote>
<blockquote>
<p>GameMode 
<em>'딜레이 시작', '비활성 플레이어 스테이트 수명'</em>  같은 설정이 추가된 더 복잡한 클래스<img alt="" src="https://velog.velcdn.com/images/ldsldy/post/738fa1ab-725a-4e2d-b461-7822a54c20eb/image.png" /></p>
</blockquote>