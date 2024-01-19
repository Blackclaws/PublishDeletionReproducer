# Reproducer for `dotnet publish` deleting files

When running `dotnet publish -o out` twice in a row, the first time a .dll.config file is copied into the target directory, the second and any subsequent times it is deleted.
