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

#4. voice agent - adding to the cart
tool calling such that adding the product to the cart, update quantity, delete

#5. smart search (missing in some apps)
vector search but binary quantisation

#6. recommendation of products (other users, previous history, location)
