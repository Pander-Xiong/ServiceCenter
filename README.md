ServiceCenter
=============

//this is a little test code
<?php
$a = '5646';
$brr = array();
foreach($array as $k => $v)
{
	for($i = 0; $i < count($v); $i++)
	{
		$brr[] = $v[$i];	
	}	
}
if(in_array($a,$brr))
{
	echo 'OK';
}
else
{
	echo 'NO';	
}
?>
