# Digital Post Map

You can use the jQuery click function to tap into the existing location function.

$(".dploc").on("click", function(){

  alert($(this).attr("data-loc"));

});

Demo: https://sergiocutone.github.io/digitalpost-map
