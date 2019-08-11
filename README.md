# scanbills
Web application that give an API to scan bills and save results for authorized users. Web form to test added.

** Commands to build in container
curl -L -o master.zip https://github.com/polux2016/scanbills/archive/master.zip && unzip master.zip
dotnet "restore" "scanbills-master/BillScanController/BillScanController.csproj"
dotnet "build" "scanbills-master/BillScanController/BillScanController.csproj"