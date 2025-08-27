connect your grocery list with google keep/notion or just the simple text message to automatically add the cart
input the image (handwritten list) to automatically add to the cart
multi agent -> refund, exchange, return, normal query about discounts/recommendation/recipe  ( use VQA from the image)
voice agent -> adding to the cart
smart search (missing in some apps) 
recommendation of products (other users, previous history)

#1. connect with google keep/ notion /simple text message

use the google keep mcp or notion mcp to get the latest message
simple text message too
start from normal text message 


#2. ocr basic on both handwritten and normal list
use basic vlm 

#3. support agent - refund, exchange, return, normal query about discounts/recommendation/recipe
main agent will see what to go for

#4. voice agent - adding to the cart / normal conversation / query
tool calling such that adding the product to the cart, update quantity, delete

#5. smart search (missing in some apps)
vector search but binary quantisation

#6. recommendation of products (other users, previous history, location)


Database

POSTGRES 

1. users – who is shopping.  
2. stores – where the groceries come from.  
3. categories – aisles in the digital catalog.  
4. products – every product you can buy.  
5. lists – a user’s reusable grocery lists.  
6. list_items – each line on a list (product + quantity).  
7. orders – finalized checkout carts.  
8. order_items – each line inside an order.  
9. refunds – money-back requests against orders.  
10. conversations – multi-turn support chat sessions.  
11. messages – every user/bot/support utterance inside a conversation.  
12. events – raw user actions for recommendations & analytics.


