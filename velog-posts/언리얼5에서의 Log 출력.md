<h3 id="log">Log</h3>
<p>로그는 개발을 하면서 디버깅, 상태 확인, 성능 분석, 에러 추적을 빠르게 하기 위한 중요한 도구이다.</p>
<h3 id="ue_log">UE_LOG</h3>
<p>UE_LOG는 로그 파일에 포맷이 지정된 메시지를 로깅하는 메크로이다.</p>
<pre><code>UE_LOG(LogTemp, Warning, TEXT(&quot;Warning&quot;));</code></pre><h3 id="log-수준">Log 수준</h3>
<blockquote>
<table>
<thead>
<tr>
<th>수준</th>
<th>설명</th>
</tr>
</thead>
<tbody><tr>
<td>Fatal</td>
<td>로깅이 비활성화된 경우에도 항상 치명적인 오류를 콘솔 및 로그 파일에 출력한 후 크래시를 발생시킨다.</td>
</tr>
<tr>
<td>Error</td>
<td>오류를 콘솔 및 로그 파일에 출력한다. 오류 메시지의 결과로 커맨드릿 실패가 발생한다.</td>
</tr>
<tr>
<td>Warning</td>
<td>경고를 콘솔 및 로그 파일에 출력한다. 커맨드릿과 에디터가 경고를 수집하고 보고한다.</td>
</tr>
<tr>
<td>Display</td>
<td>메시지를 콘솔 및 로그 파일에 출력한다.</td>
</tr>
<tr>
<td>Log</td>
<td>메시지를 로그 파일에는 출력하지만 콘솔에는 출력하지 않는다.</td>
</tr>
<tr>
<td>Verbose</td>
<td>해당 카테고리에 대해 상세 로깅이 활성화된 경우 상세 메시지를 로그 파일에 출력한다.</td>
</tr>
<tr>
<td>VeryVerbose</td>
<td>상세 메시지를 로그 파일에 출력한다. 다른 경우에 스팸으로 출력될 상세 로깅에 사용된다.</td>
</tr>
</tbody></table>
</blockquote>
<h3 id="로그-예시">로그 예시</h3>
<pre><code>UE_LOG(LogTemp, Display, TEXT(&quot;Configured Moved Distance: %f&quot;), MoveDistance);
UE_LOG(LogTemp, Warning, TEXT(&quot;Warning&quot;));
UE_LOG(LogTemp, Error, TEXT(&quot;Error&quot;));
</code></pre><p><img alt="" src="https://velog.velcdn.com/images/ldsldy/post/bc2c6c52-5f54-4160-8534-06321f9b24f5/image.png" /></p>