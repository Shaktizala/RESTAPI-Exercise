Title - Vehicles

Tables - 
1. Vehicles 
{
    id: 1,
    type: car,
    model_no : K23GR4,
    model_type : abcd,
    company : FARARI 
}

2. Buyers 
{
    id: 1,
    vehicle_id : 1,
    full_name: Abcd Demo,
    Contact_no : 9841578985 
}

3. Invoice
{
    id : 1,
    buyer_id : 1,
    invoice_no : 09328,
    amount : 1,50,00000
}

1. Vehicles
GET - Vehicles/{vehicle id}/  - list of vehicles
GET - Vehicles/     - Whole list
POST - Vehicles/
PUT - Vehicles/{vehicle id}/
PATCH - Vehicles/{vehicle id}/
DELETE - Vehicles/{vehicle  id}/

2. Vehicles/Buyers/
GET - Vehicles/{vehicle id}/Buyers/{buyer id}/  - list Buyers with vehicle id
GET - Vehicles/{vehicle id}/Buyers/     - Whole list
POST - Vehicles/{vehicle id}/Buyers/
PUT - Vehicles/{vehicle id}/Buyers/{buyer id}/
PATCH - Vehicles/{vehicle id}/Buyers/{buyer id}/
DELETE - Vehicles/{vehicle id}/Buyers/{buyer id}/

3. Vehicles/Buyers/Invoice
GET - Vehicles/{vehicle id}/Buyers/{buyer id}/Invoice/{invoice id}/  - list Buyers with vehicle id
GET - Vehicles/{vehicle id}/Buyers/{buyer id}/Invoice/     - Whole list
POST - Vehicles/{vehicle id}/Buyers/{buyer id}/Invoice/
PUT - Vehicles/{vehicle id}/Buyers/{buyer id}/{buyer id}/Invoice/{invoice id}/
PATCH - Vehicles/{vehicle id}/Buyers/{buyer id}/{buyer id}/Invoice/{invoice id}/
DELETE - Vehicles/{vehicle id}/Buyers/{buyer id}/{buyer id}/Invoice/{invoice id}/