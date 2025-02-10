
The **notebookutils** package, formerly known as **mssparkutils**, is a built-in package designed to help you easily perform common tasks in **Fabric Notebook**. Here are some key points about its usage and advantages1:

File System Utilities: notebookutils.fs provides utilities for working with various file systems, including Azure Data Lake Storage (ADLS) Gen2 and Azure Blob Storage. You can copy, move, list, create, write, read, append, and remove files or directories.

Environment Variables: You can use notebookutils to get environment variables and chain notebooks together.

Credentials Management: notebookutils.credentials allows you to manage credentials, such as retrieving secrets from Azure Key Vault.

Backward Compatibility: The existing code remains backward compatible, ensuring that your current implementations won't break. However, it is strongly recommended to upgrade to notebookutils to ensure continued support and access to new features.

Integration with Spark: notebookutils is designed to work with Spark 3.4 (Runtime v1.2) and above, making it a powerful tool for data engineering tasks.
