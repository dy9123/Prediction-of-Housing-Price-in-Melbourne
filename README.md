# Prediction-of-Housing-Price-in-Melbourne
In this project. We employed general non-linear regression to predict the housing price of Melbourne.
We followed the following steps.
1. Check the significance of the interaction terms and delete the insignificant terms
2. Check the significance of the remaining variables without interaction effects.
3. Check multicollinearity
4. Regroup categorical variables.
5. Detect outliers by looking at Cook-Distance and leverage.
6. Check normality and perform nonlinear transformation, such as Box-Cox, Box-Tidewell or Spline method.
7. Stepwise regression

We finally achieved R^2 of 0.8 with only 9 attributes. 
The description of data are here.

Some Key Details
====================
Suburb: Suburb

Address: Address

Rooms: Number of rooms

Price: Price in dollars

Method: 
S - property sold; 
SP - property sold prior; 
PI - property passed in; 
PN - sold prior not disclosed; 
SN - sold not disclosed; 
NB - no bid; 
VB - vendor bid; 
W - withdrawn prior to auction; 
SA - sold after auction; 
SS - sold after auction price not disclosed. 
N/A - price or highest bid not available.

Type: 
br - bedroom(s); 
h - house,cottage,villa, semi,terrace; 
u - unit, duplex; 
t - townhouse; 
dev site - development site; 
o res - other residential.

SellerG: Real Estate Agent

Date: Date sold

Distance: Distance from CBD

Regionname: General Region (West, North West, North, North east ...etc)

Propertycount: Number of properties that exist in the suburb.

Bedroom2 : Scraped # of Bedrooms (from different source)

Bathroom: Number of Bathrooms

Car: Number of carspots

Landsize: Land Size

BuildingArea: Building Size

YearBuilt: Year the house was built

CouncilArea: Governing council for the area

Lattitude: Self explanitory

Longtitude: Self explanitory

