# Smart-Billing-Trolley

Though almost everything is available online for purchase, a large number of people still prefer to buy many things by visiting supermarkets and malls. The traditional way of shopping that is still in implementation involves picking the things of their interest and waiting in the queue at the billing counter until it’s their turn. This creates inconvenience and delay especially during festive seasons and holidays when the malls are filled with crowd.
To reduce this hassle, we propose a smart billing trolley which uses RFID technology to detect and bill the products when dropped in the trolley. The product details are updated on the database providing billing details to the system in the billing counter. In this way, the customer can keep track of the bill while he can still make choices to buy and pay the bill at the counter or online while leaving without waiting in the queue.
The hardware consists of an ESP8266 NodeMCU, EM-18 RFID Reader Module, LCD, Weight Sensor and each product must contain an RFID tag. The system also allows the customer to delete a product from the list and generate the total bill. The discounts and offers or coupons that are applicable on the product can be applied and the bill is updated by the system.
The RFID reader scans all the items as and when they are put in the trolley. The record of the items bought is stored in the microcontroller memory along with their individual costs as well as the total expenditure. This information will be displayed on a LCD screen which will also be placed on the trolley for the customer to verify the item bought and to keep a track on the amount spent on each item. At the billing side, the employee can get an itemized bill from each and every trolley just by giving the trolley number as the input to a software which would then print the itemized bill. Data can be erased from the micro controller memory after the bill is printed so as to make that trolley reusable.