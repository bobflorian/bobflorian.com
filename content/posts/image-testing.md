---
title: "My First Post - Image Testing"
date: 2019-12-13T12:39:17-06:00
draft: false
---

<div class="demo-gallery">
<div id="mypicts" class="list-styled" >
    <a href="/img/day1/1.jpg">
        <img class="img-responsive" src="/img/day1/thumbnail_1.jpg">
        <div class="demo-gallery-poster">
            <img src="/img/zoom.png">
        </div>
    </a>
        
     <a href="/img/day1/2.jpg">
        <img class="img-responsive" src="/img/day1/thumbnail_2.jpg">
        <div class="demo-gallery-poster">
            <img src="/img/zoom.png">
        </div>
    </a>

        <a href="/img/day1/3.jpg">
        <img class="img-responsive" src="/img/day1/thumbnail_3.jpg">
        <div class="demo-gallery-poster">
            <img src="/img/zoom.png">
        </div>
    </a>

        <a href="/img/day1/4.jpg">
        <img class="img-responsive" src="/img/day1/thumbnail_4.jpg">
        <div class="demo-gallery-poster">
            <img src="/img/zoom.png">
        </div>
    </a>

        <a href="/img/day1/5.jpg">
        <img class="img-responsive" src="/img/day1/thumbnail_5.jpg">
        <div class="demo-gallery-poster">
            <img src="/img/zoom.png">
        </div>
    </a>

        <a href="/img/day1/6.jpg">
        <img class="img-responsive" src="/img/day1/thumbnail_6.jpg">
        <div class="demo-gallery-poster">
            <img src="/img/zoom.png">
        </div>
    </a>

    </a>       
</div>
</div>

<script type="text/javascript">
$('#mypicts').lightGallery(
    {
}
);

$('#mypicts').justifiedGallery({
    rowHeight : 100,
    lastRow : 'nojustify',
    margins : 20
});

</script>