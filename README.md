# ResourceAPI
Apigee Resource Api

# Commands for deploying the proxy using maven
To deploy the proxy

/src/gateway/proxy-dir
(run the command from the directory same as child pom)

✔ mvn apigee-enterprise:deploy -P<profile> -Dusername=<username> -Dpassword=<password>

For example:
✔ mvn apigee-enterprise:deploy -P prod -Dusername=admin@toopowerful.com -Dpassword=too\_powerful\_password

# To deploy the proxy and run jmeter tests
✔ mvn install -P <profile_name> -Dusername=<username> -Dpassword=<password>
 
