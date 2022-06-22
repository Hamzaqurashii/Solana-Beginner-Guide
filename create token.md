# Creating Token

# create the token by adding this command

spl-token create-token --url devnet

# save the token address

# create the account to save the token by this command

spl-token create-account >>You token address<< --url devnet

# save the account address. 

# check the balance with this command.

spl-token balance >>token address<< --url devnet

# Now you can create as much token as you want by this command. 

spl-token mint >>your token address<< 1000 --url devnet

# now check the balance with following command. 

spl-token balance >>token address<< --url devnet

# The best practice is always to limit the token so that you can not create more tokens, in that way the value of the token will be intact
# and for this you need to run this command. 

spl-token authorize >>your token address<< mint --disable --url devnet

# now try to mint more tokens and you are going to get the error. 

# you can burn some or all of your token by running following command.

spl-token burn >>Your account address<< >>number of tokens<< --url devnet

# burning the tokens are the good way to increase the value of token but it'll only burn the tokens which owns by you 
# so if you have transferred some of the tokens to any other user then it won't delete those tokens because you don't have any ownership on that tokens. 


