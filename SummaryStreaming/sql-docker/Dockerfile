# Use a Microsoft image with Linux MS SQL tools
# https://hub.docker.com/r/microsoft/mssql-tools/
FROM mcr.microsoft.com/mssql-tools

# Set the working directory to /work
WORKDIR /work

# Copy the shell script
ADD run-script.sh /work

# Define environment variables
ENV SCRIPT_URL "Missing script URL"
ENV SQL_SERVER "Server Name missing"
ENV SQL_DB "DB Missing"
ENV SQL_USER_NAME "User Name missing"
ENV SQL_PASSWORD "Password missing"

# Run app.py when the container launches
CMD ["bash", "run-script.sh"]
