1.Go to AWS Console,Navigate to lex

2.Click on create to create a new bot

3.choose the custom bot option and provide a name and discription for your bot

4.Configure bot’s language,voice  

5.Once its done click on done

6.Now lets create an INTENT (Greetings) which is used for initial response from the bot



7.In the intent greeting type the sample utterances (user input)

8.Scroll down to closing Response and type what response should bot give to the user 

Input.



9.Click on save Intent

10.Then create another Intent







11.Name that intent as BookHotel























12.Then type the sample utterances

13.Then click on slots to add the NIGHTS,CHECKINNDATE,LOCATION & ROOMTYPE





14.for creating RoomType slot we need to create a slot type where we can 

Specify what type of room user needs such as:single,duplex etc




15.Once you specified the slot type create slot and in slottype select the  slot which we have

Created before











16.Once its done click on ADD

-- save the intent 

-- built the bot 



17.Scroll down & in confirmation type the promt if user accepts and what if user declines The request according to that type the prompt.

18.In the fulfilment type the prompt for successful fulfilment & for in case of failure



19.And in the closing response type the promt for closing 





Creating lambda function 

1.Navigate to lambda in AWS console

2.create a function named HotelBookingLambda



3.And there will be several language available and I have selected python



4.Once its done click on deploy



INTEGRATING LAMBDA FUCTION WITH OUR BOT

1.Under deployment click on aliases –> test bot-aliases select the lambda

Fuction which we have created.





2.click on save 

3.Then navigate to the BookHotel intent and under code hooks enable 

The lambda function



4.Now click on save intent and build 

5.now test the bot

6.output



