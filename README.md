# 2016-FRS-CANBUS-STEERING-
 This is a simple arduino code to send can messages to activate the eps syestem on a 2016 scion frs. 
 Upload to arduino with a canbus shield, power up and output to can lines at obd2 port ( pins 6 can hi and pin 14 can lo ) 
 check that you have MCP_CAN CAN set to the propper SPI pin for you board,
 you might be able to get another board to work or edit code, just transfer the id and data of te message, the messages need to be sent at 100 times per second, 
