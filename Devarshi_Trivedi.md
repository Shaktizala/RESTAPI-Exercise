Contains url about nasa space

Three layers 
- NASA
- MISSIONS
- Mission_department
- EMPLOYEES

* GET Request

GET /nasa/mission/list <-give the list of mission
GET /nasa/mission/mission_id

GET /nasa/mission/ms_departments/list
GET /nasa/mission/ms_department/msd_id

GET /nasa/mission/ms_departments/employees/list
GET /nasa/mission/ms_departments/employees/emp_id

GET /nasa/employees/list
GET /nasa/departments/list

* POST Request

POST /nasa/mission/
{
	"id":1,
	"mission_name":"Stellar-Extra-Teresterials-5(SET-5)",
	"mission_departments":[
		{
			"dept_id":1,
			"dept_name":"Extra-TT Observation",
			"employees":300
		},
		{
			"dept_id":2,
			"dept_name":"Signal, Chip and Matter Observation",
			"employees":300
		}
	]
}
	
* PUT Request

PUT /nasa/mission/ms_department/employees/
{
	"id":2,
	"Name":"Josua",
	"Planet":"ETM-3032"
}

* PATCH Request

PATCH /nasa/mission/ms_department/employees/2
{
	"Planet":"ETM-3031"
}

* DELETE Request

DELETE /nasa/mission/ms_department/employees/2
