# 🚀 Azure VM Auto-Shutdown Project

This project uses an Azure Logic App and GitHub Actions to automatically shut down virtual machines every day at a scheduled time.

## 🌐 Features
- Logic App triggered daily (9 PM)
- Stops Azure VM using REST API
- Uses Managed Identity for secure access
- Infrastructure as Code via ARM template
- CI/CD with GitHub Actions

## 📂 Project Structure
- `infra/logicapp/template.json`: Logic App template
- `infra/logicapp/parameters.json`: Deployment parameters
- `.github/workflows/deploy.yml`: CI/CD pipeline

## 🛠️ How to Use
1. Upload to GitHub
2. Add required secrets
3. Push to `main` → Auto deploys via CI/CD

## 📸 Screenshots
_Include any screen captures here (Logic App designer, success logs, etc.)_
