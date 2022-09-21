SET answer TO '3'
SEND 'guess the number' TO DISPLAY
RECIEVE  number FROM KEYBOARD
If number > 10:
SEND 'it should be less that 10 stupid'
ELIF:number - answer
SENT CORRECT
ELSE:
SEND 'Dumn af' TO DISPLAY
END IF
