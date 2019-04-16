# paymentsMovie
visualize geolocated pharma payments over time using D3


# Intent:
Inputs from  file (.csv or json) with fields:
"day" = days since start
"lat" = (for now) lattitude of the centroid of the zip code of the payment recipient
"long" = (for now) longitude of the centroid of the zip code of the payment recipient
"pay" = dollar value of payment

Create:
A map of the US updationg to display 1 day of payments every second, filtering from the input file only payments made on that day

