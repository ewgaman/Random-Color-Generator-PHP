Random-Color-Generator-PHP
==========================

Generate random hex values with PHP

<?php
$c1 = "#ffcc00";
$c2 = "#ffff99";
$c3 = "#cfeef6";
$c4 = "#b2ebc5";
$c5 = "#ffffff";
$c6 = "#d7ebff";
$c7 = "#dfceb9";
$c8 = "#b3ccc5";
 
$number = rand(1,8);
$bgcolour = ${"c$number"};
echo ("<BODY BGCOLOR=\"$bgcolour\">");
?>