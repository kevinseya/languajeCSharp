# Asp. Net Project
This is a basic C# project with a simple functionality. Below are the steps to set up and run the project.

## Requirements

- .NET SDK (version 7.0 or higher)
- Code editor (e.g., Visual Studio, Visual Studio Code.)

## 1. Clone the repository

Clone the repository or download the source code.
   ```bash
   git clone https://github.com/kevinseya/languajeCSharp.git
   ```
## 2. Install dependencies

Navigate to the project directory and restore the dependencies:
   ```bash
dotnet restore
   ```
## 3. Run the Project Locally

To start the application locally, use the following command:
   ```bash
dotnet run
   ```

### Run the image of Docker Hub

You can pull and run it on any machine that has Docker installed.
```bash
docker pull kevinseya/languaje-csharp-app:latest

docker run -p 80:80 kevinseya/languaje-csharp-app:latest
```
### Usage
Once the application is running, you can access it at http://localhost:8080.

### Deployed in service PAAS Digital Ocean

https://languaje-csharp-pggns.ondigitalocean.app/
