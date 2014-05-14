<section class="comment">

<!-- Disqus Comment BEGIN -->
	<div id="disqus_container" style="padding: 20px 20px 20px 0px;border-top: 1px dashed #CCC;">		 
	<a href="#" class="comment" onclick="return false;" style="color:#4A75B5;">点击查看评论</a>
	<div id="disqus_thread"></div>
    <script type="text/javascript">
        /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
        var disqus_shortname = 'matrixq'; // required: replace example with your forum shortname
 
		$('#disqus_container .comment').on('click',function(){
		        $(this).html('加载中...');
		        var that = this;
		        $.getScript('http://' + disqus_shortname + '.disqus.com/embed.js',function(){$(that).remove()});
		    });
    </script>
   </div>
    
<!-- Disqus Comment END -->
</section>

