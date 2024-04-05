<?php
 
  header('Content-type: image/jpeg');


 
  $source="mk.jpg";
  $jpg_image = imagecreatefromjpeg($source);

  
  $white = imagecolorallocate($jpg_image, 255, 255, 255);

  
  $font_path = 'ASMAN.ttf';

  
  $text = "This is a sunset!";

  
  imagettftext($jpg_image, 25, 0, 75, 300, $white, $font_path, $text);

  
  imagejpeg($jpg_image,'newimage.jpeg');

  
  imagedestroy($jpg_image);
?>
