# conda_packages
List linked packages in a conda environment. (https://docs.conda.io/projects/conda/en/4.6.0/commands/list.html)

</br>

### List all packages in the current environment:
> conda list

</br>

### List all packages installed into the environment {myenv}:
> conda list -n {myenv}

</br>

### Save packages for future use:
> conda activate {myenv}
>
> conda list –export > package-list.txt

</br>

### Reinstall packages from an export file:
> conda create -n {myenv} –file package-list.txt
