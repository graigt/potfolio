# potfolio
<?php

@$user_name = ($_POST['user_name']);

if(isset ($_POST['SUBMIT']) ) {
    if(!empty($_POST['Wish_list']) || ($_POST['user_name'])) {   
	    //Count number of checks
		$checked_count = count($_POST['wish_list']);
		echo "Your name is".@$user_name."and you have selected these".$checked_wishes. " wishes: <br/>';
		
		//display values for checked boxes
		
" . "		   foreach(_$_POST)['wish list'] as $selected) {
			   echo "<p>".$selected ."</p>";
		       }
		   echo "<br><br/>Note :";
              }
			  else{
			  echo"<b">Please select least option."</b>\";
			      }
			}
	?>
	
	<!DOCTYPE html>
	<html>
	    <head>
		    <title>New Year Wish</title>
			<link rel=\"stylesheet\" type=\"text/css\" href=\"main.css\"/>
		</head>
		
		<body>
		    <?php
			include"menu.inc';
			?>
		<main>
		    <h1>New Year wish List</h1>
			
			<form action="" method="post">
			    <label>Name:</label>
				<input type="text" name="name" value="" class="textbox">
				
				<br>
				<p>Select new year wish list:</p>
				<input type="checkbox" name="wish_list[]" value="Quit smoking">
                <label>Quit smoking</label><br>
				<div>
                <input type="checkbox" name="wish_list[]" value="lose weight">
                 <label>lose weight</label><br>
                </div>
                <div>
                <input type="checkbox" name="wish_list[]" value="go on a beach holiday">
                 <label>go on a beach holiday</label><br>
                 </div>
				 <div>
                <input type="checkbox" name="wish_list[]" value="Start a business">
                 <label>start a business</label><br>
                 </div>
                <input type="checkbox" name="wish_list[]" value="invest in propeties">
                 <label>invest in propeties</label><br>
                 </div>
                 <div>
                 <input type="checkbox" name="wish_list[]" value="Buy a house">
                 <label>Buy a house</label><br>
                 </div>
                 <div>
                 <input type="checkbox" name="wish_list[]" value="buy a new car">
                 <label>buy a new car</label><br>
                 </div>
                 <div>
                 <input type="checkbox" name="wish_list[]" value="Start training">
                 <label>start training</label><br>
                 </div>
                 <div>
                 <input type="checkbox" name="wish_list[]" value="strat eating healthy">
                 <label>start eating healthy</label><br>
                 </div>
                 <div>
                 input type="checkbox" name="wish_list[]" value="get married">
                 <label>get married</label><br>
                 </div>
                
                ,<label>&nbsp;</label></br>
                 <input type="submit" name="submit" value="submit"/>
	<?php
			include'menu.inc';
			
			?>

                </form>

            </main>
        </body>
         <iframe src="task2.txt">
                       Your browser does not support iframes.
                   </iframe>
    </html>				   
                 				
   
