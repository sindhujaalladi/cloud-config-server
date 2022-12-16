# cloud-config-server

in order to check whether this cloud config server springboot project has connected to Git hub repository spring-cloud-config-server
u can test via below url
http://localhost:8888/vehicle-service/default

it will show below properties 
{"name":"vehicle-service","profiles":["default"],"label":null,"version":"a1764f46ba9d316bb8eb6a07595271baad2fad20","state":null,"propertySources":[{"name":"https://github.com/sindhujaalladi/spring-cloud-config-server.git/vehicle-service.properties","source":{"eureka.client.register-with-eureka":"true","eureka.client.fetch-registry":"true","eureka.instance.hostname":"localhost","eureka.client.serviceUrl.defaultZone":"http://localhost:8761/eureka/","vehicle.provider.url":"http://localhost:9595/registration/servicetype/VEHICLE-SERVICE","message.vehicle":"hello!! greetings from cloud config from remote git repository","management.health.circuitbreakers.enabled":"true","management.endpoint.health.show-details":"always","management.endpoints.web.exposure.include":"health"}}]}
