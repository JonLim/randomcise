## Welcome to Randomcise

A proof-of-concept website, displaying a random exercise video from a vetted YouTuber who makes great exercise videos.

<a id="random" href="">Random Exercise</a>

<script>
    num = Math.floor((Math.random() * 3) + 1)
    document.getElementById("random").href = `./${num}.md`;
</script>