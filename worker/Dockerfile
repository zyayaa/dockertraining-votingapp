FROM microsoft/dotnet:2.0.0-sdk

COPY . src/Worker
RUN dotnet restore -v minimal src/Worker && dotnet publish -c Release -o "./" "src/Worker"
CMD dotnet src/Worker/Worker.dll