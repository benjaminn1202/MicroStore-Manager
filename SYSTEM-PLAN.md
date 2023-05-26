## FEATURES
- Inventory management
	- Stock tracking : Record stocks and alert when the stock of certain items are low
	- Expiration date tracking : Record item's expiry date and alert when products are approaching their expiry dates.
	- Product variants : For products that have size, flavors, etc.
	- Product information management : Detailed information about the product such as name, price, supplier
	- PS : Problem sa inventory management. What if bumili si owner ng bagong stocks ng product pero yung lumang stock ay iba ang price sa bagong stock? Pedeng update nalang lahat ng price, bago man or luma (yung mas mataas na presyo susundin) or use batch numbers/codes EVERY item that has their own price.

- Point of sales
	- Sales processing : Allows owners to process transactions accurately and easily. Calculates the amount, change, etc.
	- Debt tracking : Kapag may umutang, record the item bought as a debt. Dapat may debt tracking window, nakalagay pangalan ng customer tapos mga utang niya.
	- Receipt generation
	- Return/exchange handling : If binalik/pinalitan yung product.
	- Sales reporting : Displays daily, weekly, monthly, and yearly sales transactions and summaries. Identify popular products. Note to self: add more sub-features.


## DESIGN

### System design (Windows/Pages)
- Inventory management
	- Stock tracking
		- Stock dashboard : Overview ng stocks (Total ng stocks, low stocks, stocks na malapit na maexpire etc.)
		- Stock entry : Allows user na mag-add ng stocks (Name, price, expiry, puhunan, etc.)
		- Stock list
		- Stock details : Pag pinindot yung product sa stock list, may lalabas na window tapos nakalagay dun yung details.
	- Expiry date tracking
		- Expiry Alert
		- Expiry reports
	- Product variants
		- sakit sa ulo
	- Product information management
		- Update
		- Delete
- Point of sales
	- Sales entry
		- Transaction processing : Calculate things tapos ilagay sa db.
	- Debt tracking
		- Customer debt management window
		- Debt payment : Update pag nagbayad si customer
	- Receipt generation
	- Return/exchange handling
		- Update inventory and sales report.
	- Sales report
		- Sales summary window : Popular product, etc.
		- Sales list
