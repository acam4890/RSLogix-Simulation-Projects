This was primarily for understanding some of the ASCII string control functions in RSLogix. This program is supposed to simulate recieving a barcode scan string, deciphering the barcode scan, and using that to manage the stock of three seperate items.

The barcode strings follow the format of "AAA-BB:C". 

Where AAA = part number (123, 456, and 789)
BB = Quantity of the item in stock (99 max)
C = Direction (1=incoming item; 2=outgoing item)

An incoming item is added to the total stock of that specific item. An outgoing item is subtracted from the total stock of that specific item.
