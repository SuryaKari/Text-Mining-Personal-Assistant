# Trika : The Text Mining Personal Assistant
### <b>[Always On Feature] The chatbot is always on. So it is always waiting for input.</b>
   * The emphasis of this chatbot is on natural language input and relevant output. It is still a work in progress and I am implementing      new features all the time. 

### FORK AND CUSTOMIZE
* Please feel free to fork and customize this to your needs. 
* There are tons of cool API's on the internet that can make this a lot of fun

### IMPLEMENTATION

* Download this python notebook and run it using the following options:
   * if you want always on feature, run the asktrika() function and it should always keep a text box waiting for input
   * If you dont want the always on feature, run the trika('what is...') function with your question as an input to the function. 


<b>=============================================================</b>

### What can this do this so far? (Examples)

<b>Questions about You</b>
* I have moved or any variation there of
  * Cool, A New Place ....
  * Allright I'll remember

<b>Time based Questions</b>
* what time is it?
* what time is it now?
* what time is it in Sydney?
* what time is it in Sydney,NS?

<b>Knowledge based Questions</b>
   * For now, this scrapes wikipedia and gets you the first paragraph. Doesnt always work
   * This will be replaced with a DuckDuckGo api
* what is a pigeon?
* Pull information from Wikipedia
* Who is Mahatma Gandhi?
* What is a computer?
* Who is Stephen Colbert?

<b>To do List based Questions</b>
* Can you please add groceries to my to do list
* add groceries to my to do list
* what is on my to do list
* show me what is on my to do list
* what is on my task list?
* is groceries on my to do list?
   * Yes
   * No, do you want me to add it?
* Remove groceries from my to do list
* delete groceries from my to do list

<b>Joke based Questions</b>
* Trika, tell me a joke
* Trika, tell me something funny
* Move based Questions
* Hey did you know I moved?
   * Cool, whats your new address?
* Do you know where I live?
   * Here is your home address ....

<b>Distance based Questions</b>
   * Uses Google Maps API
* What is the distance between Rogers center and Oshawa Go?
* Distance between New york and Toronto
* Tell me the distance between 100 King St, Toronto to New York Mets Stadium
      * Do you want the directions as well? YES/NO
            * YES : Directions given
            * NO : Allright, no directions then
* Get me directions from rogers center, toronto to miami beach

<b>News based Questions</b>
* What is happening in the news?
* What is the news?
* What is happening?

<b>=============================================================</b>
### Work in Progress

<b>Directions based Questions</b>
* What is the phone number of the nearest mcdonalds?
* How far is the ROM from home?

<b>Weather based Questions</b>
* What is the weather like today?
* What is the weather like in
* will it be sunny today?
* will i need an umbrella today?

<b> Knowledge Based Questions </b>
* Who is the ceo of apple? (Code in different sources)
* Trika, what can you do?

<b>Other Features to add</b>

* Login
* Reminder event
* Trika, I am bored
   * Pull up a random fact
   * At a later time, pull up the highest trending video from youtube
* Trika, I am sad
   * I am sorry, what will cheer you up? I can pull up some options around you ( Send query to gmaps and display)


<b>Store a favorites dataframe and if no response for 30 mins</b>
   * Pull up a random store about food favorite and suggest
   * Pull up a good movie and suggest going to it
   * Pull stock value information based on Text
   * Trika, what is the value of ETH?
   * Trika, how much is ETH in CAD?


