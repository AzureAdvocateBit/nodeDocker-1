FROM microsoft/aspnetcore:2.0

# Set the Working Directory
WORKDIR /app

# Copy the app
COPY . /app

# Tell .net core which port to expose
ENV ASPNETCORE_URLS=http://*:

# Start the app
ENTRYPOINT dotnet nodeDocker.dll