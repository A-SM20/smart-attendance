# smart-attendance-website

A simple website integrated with the smart attendane AI chatbot build using vertex ai and dialogflow cx.
This chatbot is not an LLM and is only trained to answer the questions related to the attendance data given.
The data is taken from a rfid reader where accepts rfid stickers (to be placed in id card/anything else) (assumed) in the format "rfid-value,date-time-stamp,name-of-the-student(mapped from the rfid-value),class-attended,room-number"
