#VERIFICATION#

+ Assert the checkout URL: https://staging-belleandkate.netlify.app/checkout/address

1st Case
+ Insert First Name > *Blank* > Alert message is showing "First name can't be blank"
+ Insert Last Name > *Blank* > Alert message is showing "Last name can't be blank"
+ Insert Street Address > *Blank* > Alert message is showing "Street address can't be blank"
+ Insert Phone Number > *Blank* > Alert message is showing "Phone can't be blank"

2nd Case 
+ Insert First Name > Ibnu 
+ Insert Last Name > Aviandi
+ Choose Province > Jawa Barat
+ Choose Town / City > Depok
+ Choose Distict > Cimanggis
+ Choose Sub-District > Cisalak Pasar
+ Insert Street Address > Permata Puri 1 Block C.10 No. 6
+ Insert *INCORRECT* Phone Number > 081211810900 > Alert message is showing "Please enter a valid Indonesian mobile phone number starting with 8xx"
+ Insert *INCORRECT* Phone Number > +6281211810900 > Alert message is showing "Please enter a valid Indonesian mobile phone number starting with 8xx"
+ Insert Phone Number > 81211810900

After click Continue to Shipping
+ Assert the URL: https://staging-belleandkate.netlify.app/checkout/shipment



#AUTOMATION RESULT#

file:///C:/Users/ibnu.aviandi/Katalon%20Studio/BelleandKate/Reports/20230517_235504/TERM%203%20-%20INPUT%20ADDRESS%20-%20WEB/20230517_235505/20230517_235505.html

