# API Builder SFDC Bulk API 2 Test

* Using [**https://github.com/msrivastav13/node-sf-bulk2**](https://github.com/msrivastav13/node-sf-bulk2)
* Use account.csv should be un the API Builder root project folder
		* See repo above for a sample account.csv file
* Set username and password environment variables and run
	* e.g. `username=xxxx password=yyyyzzzz npm start`
	* Password is your password concatenated with your security token
* Trigger the process by calling the `/api/fileupload` API (e.g. `GET http://localhost:8080/api/fileupload`)
