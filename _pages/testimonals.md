---
title: Testimonials
permalink: testimonials/
layout: single
author_profile: true
author: Leaf and Seed
---
### Customer Reviews from [Google Business](https://goo.gl/maps/hw6SuVUt8462)
<script src='https://maps.googleapis.com/maps/api/js?v=3.exp&key=AIzaSyB1bSt36-cxlJLxltTNqvxHZ-VqxuZaxlI&signed_in=true&libraries=places'></script>
<div id="google-reviews"></div>

<script>
jQuery(document).ready(function( $ ) {
   $("#google-reviews").googlePlaces({
        placeId: 'ChIJl2wRr6fAdUgRLoohbSFmiJw' //Find placeID @: https://developers.google.com/places/place-id
      , render: ['reviews']
      , min_rating: 4
      , max_rows: 5
   });
});
</script>