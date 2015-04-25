To test this example:

curl -sv --compressed -H "Content-Type: application/json" -d '{"method":"HelloService.Say","params":[{"who":"tester"}], "id": 12}' http://localhost:8080/rpc
