Stuti Chugh Lob Letter Project
======


##### Instructions

* I used python to create this letter. You can run the program by opening the file `lobletter.py` via command prompt or by using IDLE. It will ask you to input your name, address, and message to the legislator. If you enterred everything correctly it will create a pdf of the letter in the test environment that can be accessed from the lob dashboard of my account. I have included a pdf of a sample letter under the file name `StutiChughLobLetter.pdf`

* I decided to set `'levels':'country','roles':'legislatorUpperBody'` in my python get request to google civic API so you will be able to contact a legislator according to that. This often returns a list of government officials who could possibly be contacted. I set the parameter such that the user is able to contact the first person in list returned by this request.

* If the user forgets to input their zipcode or input an incorrect address or any other type of bad input there is an invalid request error by lob 
