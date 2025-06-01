# CST8917 Lab 1: Azure Function Apps with Output Bindings

This project contains two Python-based Azure Function Apps demonstrating the use of **output bindings** with:

1. Azure Storage Queue  
2. Azure SQL Database

## 📌 Objective

To implement and deploy serverless functions using Azure Functions with output bindings, enabling integration with external services like queues and databases.

---

## 🛠️ Setup Instructions

### Prerequisites

- Python 3.10+
- [Azure Functions Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- Azure subscription

---

## 📦 Function 1: Azure Storage Queue Output Binding

### Resources Created

- Azure Function App
- Azure Storage Account
- Queue named `my-queue-items`

### Local Setup

```bash
cd storage-queue-function
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
func start
