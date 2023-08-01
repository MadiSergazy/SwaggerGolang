if you using windows install swagger_windows_amd64.exe
https://github.com/go-swagger/go-swagger/releases/tag/v0.30.5 and pass it inside to => GOPATH/bin

after use:
 swagger generate client -A todo -f ./swagger.yaml
 swagger_windows_amd64 generate server -A todo -f ./swagger.yaml


for help catch errors and ensure your API behaves as expected:
swagger_windows_amd64 validate ./swagger.yaml 