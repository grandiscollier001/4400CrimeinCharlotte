# 4400CrimeinCharlotte
# DATA SOURCING

## Deliverables


### 1. Source Locations

1.   Crime Incidents - https://data.charlottenc.gov/datasets/charlotte::cmpd-incidents-1/about
2.   Violent Crime - https://data.charlottenc.gov/datasets/7b28963ad9564ef7b59cdfdce3cbe9a5_0/explore
3.   Real Estate Information - https://www.realtor.com/apartments/Charlotte_NC





### 2.   Source Explanation


1.   The crime incidents data is being used to identity the trends reported incidents.
2.   The violent crime data is being used to give an additional layer to the trends in crime.
3.   The real estate data will be used to create a relationship between locations and rental unit pricing. (data taken from the past 180 months)




### 3.   Data Dictionary (Google drive) - https://drive.google.com/drive/folders/1T1YYHBezx7n5OckZ6jKtaLMqUxIC7XHi?usp=drive_link
#### Section 1: Incident Reports Data
X

Data Type: float64 Description: X coordinate (possibly geographical or other spatial data). Format/Constraints: Floating point number. Y

Data Type: float64 Description: Y coordinate (possibly geographical or other spatial data). Format/Constraints: Floating point number. YEAR

Data Type: int64 Description: Year when the incident occurred. Format/Constraints: Integer. INCIDENT_REPORT_ID

Data Type: object Description: Unique identifier for each incident report. Format/Constraints: Alphanumeric string. LOCATION

Data Type: object Description: General location description of the incident. Format/Constraints: Text. CITY

Data Type: object Description: City where the incident occurred. Format/Constraints: Text. STATE

Data Type: object Description: State where the incident occurred. Format/Constraints: Text. ZIP

Data Type: object Description: ZIP code of the incident location. Format/Constraints: Text, usually 5 digits. X_COORD_PUBLIC

Data Type: float64 Description: Public X coordinate for geographical data. Format/Constraints: Floating point number. Y_COORD_PUBLIC

Data Type: float64 Description: Public Y coordinate for geographical data. Format/Constraints: Floating point number. LATITUDE_PUBLIC

Data Type: float64 Description: Public latitude of the incident location. Format/Constraints: Floating point number. LONGITUDE_PUBLIC

Data Type: float64 Description: Public longitude of the incident location. Format/Constraints: Floating point number. DIVISION_ID

Data Type: object Description: Identifier for the division handling the incident. Format/Constraints: Alphanumeric string. CMPD_PATROL_DIVISION

Data Type: object Description: Name of the patrol division handling the incident. Format/Constraints: Text. NPA

Data Type: float64 Description: Neighborhood Profile Area identifier. Format/Constraints: Floating point number. DATE_REPORTED

Data Type: object Description: Date when the incident was reported. Format/Constraints: Date in string format (e.g., YYYY-MM-DD). DATE_INCIDENT_BEGAN

Data Type: object Description: Date when the incident began. Format/Constraints: Date in string format (e.g., YYYY-MM-DD). DATE_INCIDENT_END

Data Type: object Description: Date when the incident ended. Format/Constraints: Date in string format (e.g., YYYY-MM-DD). ADDRESS_DESCRIPTION

Data Type: object Description: Description of the address where the incident occurred. Format/Constraints: Text. restored_column

Data Type: int64 Description: Column possibly used for data restoration or versioning. Format/Constraints: Integer.

#### Section 2: Offense Data
ROW_TYPE

Data Type: object Description: Type of row, indicating different data categories or types. Format/Constraints: Text. GEOGRAPHY

Data Type: object Description: Geographical area related to the offense. Format/Constraints: Text. GEOGRAPHY_ID

Data Type: int64 Description: Identifier for the geographical area. Format/Constraints: Integer. CALENDAR_YEAR

Data Type: int64 Description: Calendar year of the offense. Format/Constraints: Integer. CALENDAR_MONTH

Data Type: int64 Description: Calendar month of the offense. Format/Constraints: Integer (1-12). OFFENSE_DESCRIPTION

Data Type: object Description: Description of the offense. Format/Constraints: Text. OFFENSE_COUNT

Data Type: int64 Description: Number of offenses recorded. Format/Constraints: Integer. OBJECTID

Data Type: int64 Description: Unique identifier for the offense record. Format/Constraints: Integer.

#### Section 3: Real Estate Data
property_url

Data Type: object Description: URL of the property listing. Format/Constraints: URL string. mls

Data Type: object Description: Multiple Listing Service (MLS) identifier. Format/Constraints: Alphanumeric string. mls_id

Data Type: object Description: Unique MLS ID for the property. Format/Constraints: Alphanumeric string. status

Data Type: object Description: Current status of the property (e.g., Active, Sold). Format/Constraints: Text. style

Data Type: object Description: Architectural style of the property. Format/Constraints: Text. street

Data Type: object Description: Street address of the property. Format/Constraints: Text. unit

Data Type: object Description: Unit number if applicable. Format/Constraints: Text. city

Data Type: object Description: City where the property is located. Format/Constraints: Text. state

Data Type: object Description: State where the property is located. Format/Constraints: Text. zip_code

Data Type: int64 Description: ZIP code of the property location. Format/Constraints: Integer, usually 5 digits. beds

Data Type: float64 Description: Number of bedrooms in the property. Format/Constraints: Floating point number. full_baths

Data Type: float64 Description: Number of full bathrooms in the property. Format/Constraints: Floating point number. half_baths

Data Type: float64 Description: Number of half bathrooms in the property. Format/Constraints: Floating point number. sqft

Data Type: float64 Description: Square footage of the property. Format/Constraints: Floating point number. year_built

Data Type: float64 Description: Year the property was built. Format/Constraints: Floating point number. days_on_mls

Data Type: int64 Description: Number of days the property has been listed on MLS. Format/Constraints: Integer. list_price

Data Type: float64 Description: Listing price of the property. Format/Constraints: Floating point number. list_date

Data Type: object Description: Date the property was listed. Format/Constraints: Date in string format (e.g., YYYY-MM-DD). sold_price

Data Type: float64 Description: Sold price of the property. Format/Constraints: Floating point number. last_sold_date

Data Type: object Description: Date the property was last sold. Format/Constraints: Date in string format (e.g., YYYY-MM-DD). lot_sqft

Data Type: float64 Description: Square footage of the lot. Format/Constraints: Floating point number. price_per_sqft

Data Type: float64 Description: Price per square foot of the property. Format/Constraints: Floating point number. latitude

Data Type: float64 Description: Latitude of the property location. Format/Constraints: Floating point number. longitude

Data Type: float64 Description: Longitude of the property location. Format/Constraints: Floating point number. stories

Data Type: float64 Description: Number of stories in the property. Format/Constraints: Floating point number. hoa_fee

Data Type: float64 Description: Homeowners Association (HOA) fee. Format/Constraints: Floating point number. parking_garage

Data Type: float64 Description: Parking garage availability. Format/Constraints: Floating point number. primary_photo

Data Type: object Description: URL of the primary photo of the property. Format/Constraints: URL string. alt_photos

Data Type: object Description: URLs of alternative photos of the property. Format/Constraints: URL strings.
