<script lang="ts">
    import Hee from '$lib/components/hee.svelte';
</script>

<Hee />

<div class="flex    justify-center">
    <div class="carousel" style="max-width: 560px;">
        <div id="slide1" class="carousel-item relative w-full">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/wLxJF91MPzU?si=Qr71sU1D6TYZoXgc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
            <a href="#slide4" class="btn btn-circle">❮</a>
            <a href="#slide2" class="btn btn-circle">❯</a>
        </div>
        </div>
        <div id="slide2" class="carousel-item relative w-full">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/508EjhsN8yU?si=fAsx9vCauWF6Hwfc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
            <a href="#slide1" class="btn btn-circle">❮</a>
            <a href="#slide3" class="btn btn-circle">❯</a>
        </div>
        </div>
        <div id="slide3" class="carousel-item relative w-full">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/4vaRMaZ5x2g?si=FXVGaQWcbIdx49AS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
            <a href="#slide2" class="btn btn-circle">❮</a>
            <a href="#slide4" class="btn btn-circle">❯</a>
        </div>
        </div>
        <div id="slide4" class="carousel-item relative w-full">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/3h8fla8LnAg?si=fIJio50PeEsQ8p8E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
            <a href="#slide3" class="btn btn-circle">❮</a>
            <a href="#slide1" class="btn btn-circle">❯</a>
        </div>
        </div>
    </div>
</div>