# Azure Databricks Utilities

Currently, this repository holds a few utilities for working with Azure Databricks clusters.

## Resources

Generally resources in this repository are jupyter notebooks that can be imported to a databricks cluster workspace. Each notebook's first cell provides information on what the notebook does.

- `rstudio-init-notebook.ipynb`: a notebook that generates an init script to install rstudio and potentially R packages of your choice
- `check-init-logs.ipynb`: a notebook that allows you to view logs from init processes.

## How to Use

To add a notebook to your workspace, proceed to your databricks workspace, click on the `Home` section on the left, and within the appropriate directory, you can right-click in white space, and select `Import`. You can import it directly from github by selecting `URL` and entering the direct URL to the notebook.

e.g. you could do the following to import the `check-init-logs.ipynb` file.

- Launch your workspace
- Navigate to your home directory using the `Home` button on the left side of your workspace.
- In your home directory, click on the downward-pointing arrow next to your name, and select `Create -> Folder`
- Enter a name as in `init-notebooks`
- Click on the folder
- Right click in the white space to the right of the highlighted folder and select `Import`
- Select the `URL` button and enter `https://raw.githubusercontent.com/jreynolds01/Azure-databricks-utils/master/check-init-logs.ipynb` to import the check init logs notebook directly from github.

Alternatively, if you have cloned this repository locally, you can also select the `Files` option to import from your local machine, and navigate to your local file.

## Notes

Please see [NOTICE.TXT](NOTICE.TXT) for license information.