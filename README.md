#Companies House PHP API
This Companies House PHP API wrapper lets you get informations about companies, officers, fillings and everything else that the Companies House makes public for everyone to see.

#Setup
Edit the $_ApiKey from CompaniesHouse.php file to match your Companies House API Key

`private $_ApiKey 	= 	'YOUR_COMPANIES_HOUSE_API_KEY';`

Include the CompaniesHouse.php file

`require_once('CompaniesHouse.php');`

Make a test request

`$CompaniesHouse = new CompaniesHouse;
var_dump($CompaniesHouse->company_profile('10131005'));`

#Wiki
To access the wiki or see more examples access our [Companies House PHP API wiki](https://github.com/GRITnet/Companies-House-PHP-API/wiki)

#Copyright
This Companies House PHP API wrapper is released by [@GRITnet](https://github.com/GRITnet) under a GNU General Public License
