# template
This repository serves as a template for you to create your own team repository.

## Copying the repository
To duplicate the repository, complete the [following steps](https://help.github.com/articles/duplicating-a-repository/). In a new terminal,

> git clone --bare https://github.com/2019-NEU502b/template.git

Mirror-push to the new repository.

> cd template.git
> git push --mirror https://github.com/2019-NEU502b/team-name.git

Remove the temporary local repository you created in step 1.

> cd ..
> rm -rf old-repository.git

## Installing *fmritools*

To install locally:

> pip install -e .

To install from Github:

> pip install git+https://github.com/2019-NEU502b/team-name

To uninstall:

> pip uninstall fmritools
