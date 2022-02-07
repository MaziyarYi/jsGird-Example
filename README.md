# jsGird-Example
This Is Example For Implement The JsGrid 


We Have A Customer Grid And A Customer Address Grid 

For Customer Grid We Have 4 Actions ( load-data , insertItem , updateItem , deleteItem )
I Used Ajax For This Actions To Load My Data , Insert My Data , Update My Data , Delete My Data

In Customer Address Grid , When You Chose A Customer , Then It Will Show You Data ( The Address That Belong To The Customer )
For Thet To Happend , When You Chose Customer , It Will Call The Load Data Action Of Address With Customer Id

When You Want To Insert A Address It Should Save It On A Customer 
For That To Happend , We Have Customer Id ( From The Customer That Chose ) Then We Ajax To Url With Data Of Items And Customer Id

For Delete Or Update The Address We Does Not Need The Customer ID , We Simply Sent The Items For Update Or Send The Address Id For Delete 

In Address Grid , We Have 2 Selection Box , For That Set The Items Of Selection Box We Should To Get The Items First Then We Show Load The Address Grid 

That Is all 
