use this curl command to check my project:
    
curl -X POST -H \"Content-Type: application\/json; charset=UTF-8\" (optional) --data '{JSON DATA}' http://x.x.x.x:port/method

API:
api_get_time - use POST request without params to get current time

api_get_calculate - use follow JSON format {\"a\": your_data ,\"b\": your_data,\"operation\": operation above digits}
[example: \'{\"a\":\"5\",\"b\":\"10\",\"operation\":\"+\"}\']
 
 api_get_help - use POST request without params to get HELP