# Pandas Homework - Pandas, Pandas, Pandas by Meriane Franco

## Option 1: Heroes of Pymoli

For this assignment, I imported the data in two different dataframes. One with all the data and the other one I used to drop the duplicated user names.
THis was necessary because some of the calculation was related to all data, and some specific ones was related only to the single users.

The results are listed below:

### Player Count- represented by totalplayers_df

* Total Number of Players 
Total Players
576
### Purchasing Analysis (Total) - represented by panalysis_df

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

Number of Unique Items           179
Average Price                  $3.05
Number of Purchases              780
Total Revenue               $2379.77

### Gender Demographics - represented by gender_group

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

                    Gender               
Total Count            Male                        484
                       Female                       81
                       Other / Non-Disclosed        11
Percentage of Players  Male                     84.03%
                       Female                   14.06%
                       Other / Non-Disclosed     1.91%

### Purchasing Analysis (Gender) - represented by p_analysis_df 

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

      Purchase Count	Average Purchase Price	Total Purchase Value	Avg Total Purchase Per Person
Gender				
Female	113	            $3.20	                        $361.94	                $4.47
Male	  652	            $3.02                       	$1,967.64             	$4.07
Other / Non-Disclosed	15	$3.35	                      $50.19	                $4.56

### Age Demographics - represented by newgrouped_age_df and pa_final_df



* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group
### newgrouped_age_df
	      Total Count   	Percentage of Players
Age Ranges		
<10        	17    	2.95%
10-14	      22    	3.82%
15-19	      107   	18.58%
20-24	      258   	44.79%
25-29     	77	    13.37%
30-34     	52	    9.03%
35-39     	31	    5.38%
40+	        12	    2.08%
### pa_final_df

	Purchase Count	Average PPrice	Total P Value	Avg      Total Purchase per Person
Age Ranges				
<10	        23	      $3.35     	$77.13	              $4.54
10-14	      28	      $2.96     	$82.78	              $3.76
15-19	      136	      $3.04     	$412.89	              $3.86
20-24	      365	      $3.05     	$1,114.06	            $4.32
25-29	      101	      $2.90 	    $293.00	              $3.81
30-34	      73	      $2.93	      $214.00             	$4.12
35-39	      41	      $3.60	      $147.67             	$4.76
40+	        13	      $2.94	      $38.24              	$3.19


### Top Spenders - represented by sorted_spenders_df.head() 

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

	Purchase Count	Average Purchase Price	Total Purchase Value
SN			
Lisosia93 	5    	$3.79                 	$18.96
Idastidru52	4	    $3.86                 	$15.45
Chamjask73	3	    $4.61                 	$13.83
Iral74    	4	    $3.40                 	$13.62
Iskadarya95	3	    $4.37                  	$13.10

### Most Popular Items - represented by sorted_pop_f_df.head()

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value


  	                                	Purchase Count	Item Price	Total Purchase Value
Item ID	Item Name			
92	Final Critic	                                13	$4.61	       $59.99
178	Oathbreaker, Last Hope of the Breaking Storm	12	$4.23	       $50.76
145	Fiery Glass Crusader	                         9	$4.58      	 $41.22
132	Persuasion                                     9	$3.22        $28.99
108	Extraction, Quickblade Of Trembling Hands      9 	$3.53        $31.77

### Most Profitable Items - represented by sorted_prof_f_df.head()

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

                                      Purchase Count  Item Price	Total Purchase Value
Item ID	Item Name			
92	Final Critic	                                13	$4.61	        $59.99
178	Oathbreaker, Last Hope of the Breaking Storm	12	$4.23       	$50.76
82	Nirvana	                                       9	$4.90       	$44.10
145	Fiery Glass Crusader                           9	$4.58       	$41.22
103	Singed Scalpel                                 8	$4.35       	$34.80





### three observable trends based on the data.
The great majority of the users are male and have between 20 to 24 years old
The items"Final Citric" and "Oathbreaker, Last Hope of the Breaking Storm" are the preferred and the most profitable ones.
The user "Lisosia93" is the top buyer, with 5 orders and a total purchase value of $18.96.
