# sample-service-
Sample service for up the java base application 

--- this is the proccess of write and run services ---

touch service_name.service
write a service script 
systemctl daemon-restart (if change anything in service file must run daemon restart)
enable to service  -  systemctl enable-start service_name.service
services up and running
		
	systemctl status service_name.service   -  check the status
	systemctl start service_name.service   -  start the service
	systemctl restart service_name.service   -  restart the service
