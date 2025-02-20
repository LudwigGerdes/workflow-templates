# n8n Workflow Templates (workflow-templates)

Welcome to my collection of **n8n workflow templates**! This repository is regularly updated with new workflows designed to automate various tasks and streamline your processes.

## 📌 How to Use These Templates

### Importing Workflows into n8n via UI

1. **Clone or Download**  
   - Clone the repository:  
     ```sh
     git clone https://github.com/LudwigGerdes/workflow-templates.git
     ```
   - Or download the specific workflow you need.

2. **Import into n8n**  
   - Open your **n8n instance**.  
   - Navigate to the **workflow editor**.  
   - Click on **Import** (top right corner).  
   - Upload the `.json` file or copy-paste the contents.

3. **Customize the Workflow**  
   - Modify credentials, API keys, and any necessary parameters.  
   - Adjust nodes as needed to fit your specific use case.  

4. **Activate & Use**  
   - Test the workflow with sample data.  
   - Enable it to run manually, on a schedule, or via webhooks.

### Using a Local Fork with the n8n CLI

If you're working with a **local fork** of this repository, you can use the **n8n CLI tool** to import workflows directly:

#### **Importing a Single Workflow**
```sh
n8n import:workflow --input=path/to/workflow.json
```

#### **Importing Multiple Workflows from a Directory**
```sh
n8n import:workflow --separate --input=backups/latest/
```

**Important:**  
- n8n exports workflows with their IDs, meaning that **importing a workflow with the same ID will overwrite an existing one**.  
- To prevent accidental overwrites, **delete or modify the ID** inside the JSON file before importing.  

## 🔍 Finding the Right Workflow

Each workflow has a brief **description** in its filename or comments within the JSON file. For more details, check the documentation or open an issue.

## ✨ Contributing

If you have improvements or new templates to share:
- Fork the repository.
- Make your changes.
- Submit a pull request!

## 📜 Licensing

This repository is licensed under the **[MIT License](LICENSE)**.  
You are free to **use, modify, and distribute** these workflows, but please provide attribution if you share them publicly.

## 💬 Support & Questions

If you encounter issues or have suggestions, feel free to open an **issue** or reach out.

Happy automating! 🚀
