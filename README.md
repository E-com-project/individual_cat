# individual_cat
<img name="slide" width="100" height="100">
<script>
  var i=0;
var images = [];
var time = 3000;
images[0]='../candidate.png.png'
images[1]='../download (1).png'
images[2]='../download.png'
images[3]='../image.png'
images[4]='../rosario-fernandes-2H_hBOgwWKM-unsplash.jpg'
images[5]='../diego-ph-fIq0tET6llw-unsplash.jpg'
function changeImag(){
    document.slide.src = images[i];
    if (i < images.length - 1) {
        i++;
    }
    else {
        i = 0;
    }
    setTimeout("changeImag()", time);
}
window.onload = changeImag;
  </script>
