---
layout: default
---
<!-- Slick CSS -->
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel/slick/slick.css"/>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel/slick/slick-theme.css"/>

<!-- Carousel Container -->
<div class="slider">
    <div><img src="/assets/images/puerto-rico-1.jpg" alt="Image 1"></div>
    <div><img src="/assets/images/niagara.jpg" alt="Image 2"></div>
    <div><img src="/assets/images/brownie.jpg" alt="Image 3"></div>
</div>

<!-- jQuery & Slick JS -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/slick-carousel/slick/slick.min.js"></script>

<!-- Initialize Slick -->
<script>
    $(document).ready(function(){
        $('.slider').slick({
            autoplay: true,
            autoplaySpeed: 3000,
            dots: true,
            arrows: true,
            infinite: true,
            slidesToShow: 1,
        });
    });
</script>
