# Assignment 5: Interview a dataset
"Interview" a dataset with three specific, interesting questions.

## 1) A link to the dataset (which you can include in your repository), your questions, as well as the answers to those questions.
https://explorer.usaid.gov/prepared/us_foreign_aid_complete.csv

<br> a) Which Northern Triangle country did the U.S. provide the most aid to? </br>

_Honduras_

<br> b) What sector (government or non-government organizations) did the U.S. provide the most aid to?  </br>

_Government_

<br> c) What organization recieved the most money? </br>

_U.S. Agency for International Development_

## 2) Additionally, write down all steps used to clean and analyze the data, including any Excel formulas.
 <br> a) The first thing I did was filter the data to get the three countries in the Northern Triangle (El Salvador, Guatemala, and Honduras) </br>

 <br> b) The second thing I did was complete a pivot table, selecting those three countries and using the country code to get a count of how many times the U.S. gave money.  
(El Salvador-8240, Guatemala-13391, Honduras-9831)  </br>

 <br> c) The third thing I did was complete a pivot table, selecting those three countries and using the country code to get a count of how many times the U.S. gave money to government organizations v. NGOs. 
Country name and Channel category name are my rows, with count of country code as my value. See Below.   </br>

### El Salvador	8240
 <br> Church and Faith Based	178  </br>
 <br> Enterprises	3018  </br>
 <br> Government	3410  </br>
 <br> Multilateral	252  </br>
 <br> NGO	1234  </br>
 <br> Public and Private Partnerships	2  </br>
 <br> Universities and Research Institutes	146   </br>
### Guatemala	13391
 <br> Church and Faith Based	725 </br>
 <br> Enterprises	4093 </br>
 <br> Government	3654 </br>
 <br> Multilateral	646 </br>
 <br> Networks	3 </br>
 <br> NGO	3746 </br>
 <br> Universities and Research Institutes	524 </br>
### Honduras	9831
<br> Church and Faith Based	311 </br>
<br> Enterprises	3383 </br> 
<br> Government	3628 </br>
<br> Multilateral	359 </br>
<br> Networks	9 </br>
<br> NGO	1964 </br>
<br> Universities and Research Institutes	177 </br>

<br> d) The fourth thing I did was add the current amount and constant amount to the values column. This gets me an understanding of where the money is going and how much. </br>

### Row Labels	Count of country_code	Sum of current_amount	Sum of constant_amount
### El Salvador	8240	8817386878	14212674200
<br> Church and Faith Based	178	72567568	86700994 </br>
<br> Enterprises	3018	931514086	1042286183 </br>
<br> Government	3410	7071790468	12218194758 </br>
<br> Multilateral	252	77701532	88294718 </br>
<br> NGO	1234	551380119	654510555 </br>
<br> Public and Private Partnerships	2	200000	255304 </br>
<br> Universities and Research Institutes	146	112233105	122431688 </br>
### Guatemala	13391	6680593617	10336445667
<br> Church and Faith Based	725	385310380	417935558 </br>
<br> Enterprises	4093	1107810026	1206860557 </br>
<br> Government	3654	3332680948	6636215123 </br>
<br> Multilateral	646	196732760	226355483 </br>
<br> Networks	3	440194	439151 </br>
<br> NGO	3746	1394908612	1556906730 </br>
<br> Universities and Research Institutes	524	262710697	291733065 </br>
### Honduras	9831	6083687545	9497176110 </br>
<br> Church and Faith Based	311	102941530	113443263 </br>
<br> Enterprises	3383	1043019562	1142016263 </br>
<br> Government	3628	3995789174	7172821143 </br>
<br> Multilateral	359	114138375	125750222 </br>
<br> Networks	9	718976	717228 </br>
<br> NGO	1964	778946027	885996467 </br>
<br> Universities and Research Institutes	177	48133901	56431524 </br>
<br> Grand Total	31462	21581668040	34046295977 </br>

e) The final thing I did was pull out the implementing agency name by putting that in my rows. This enabled me to see which agency was getting the money and how it was classified. 

## 3) Lastly, write a sample headline and nut graf based on the most interesting of the three questions. 

### In El Salvador, the U.S. spends more money on the Peace Corps than the Department of Defense
 
<br> In an age where spending on defense is exorbitant, the latest data from U.S. AID shows an interesting fact. The U.S. spends more on the Peace Corps than the Department of Defense in El Salvador. In 2018, the U.S. spent nearly 94 million on the Peace Corps, three million more than on Defense in that country. In fact, this is the only country in the Northern Triangle where this is the case. </br>



