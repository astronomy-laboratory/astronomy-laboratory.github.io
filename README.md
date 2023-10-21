
# AstroLab website

This is the repository for the [astronomy-laboratory public website](https://astronomy-laboratory.github.io).

## How to contribute (AstroLab members only)

To include your corrections or additions to the website, please follow these steps:
```bash
git clone git@github.com:astronomy-laboratory/astronomy-laboratory.github.io.git astrolab-webpage

cd astrolab-webpage

git checkout -b <your-branch-name>
```
Here you can open any of the `.html` files modify them and then to see the changes offline you can simply open the `.html` file with your favorite web browser. There are other files such as the `.css`, please do not modify these unless you really know what you're doing!

Notice that we have also created a new branch `<your-branch-name>` fill in that with your AstroLab name.

Once you are happy with your changes, you can commit them to the repository and push them to the remote repository:
```bash
git add -u
git push origin <your-branch-name>
```
Then you can open a pull request on GitHub and ask for a review from one of the other AstroLab admin.

The GitHub official documentation is [here](https://docs.github.com/en/pages).