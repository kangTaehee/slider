# slider
팝업존 슬라이드 접근성 보장
<code>
<div class="area">
		<ul>
			<li class='on'>
				<a href="#news-list_1" class="num"><span class="r"><span class="t">1번 최근소식 보기</span></span></a>
				<a href="" class="view" id="news-list_1">
				1번 최근소식 내용
				</a>
			</li>
			<li>
				<a href="#news-list_1" class="num"><span class="r"><span class="t">2번 최근소식 보기</span></span></a>
				<a href="" class="view" id="news-list_1">
				2번 최근소식 내용
				</a>
			</li>
		</ul>
	</div>
</code>
	<script type="text/javascript">
	//<![CDATA[
		jQuery(".news").slideCtrl({
			photo_list		: jQuery('.news>.area li'),
			photo_list_left	: jQuery('.news_pre'),
			photo_list_right: jQuery('.news_next'),
			photo_list_play	: jQuery(".news_play"),
			photo_list_stop	: jQuery(".news_stop"),
			FXconfig		: true,
			d_time			: 6000
		});
	//]]>
	</script> 
