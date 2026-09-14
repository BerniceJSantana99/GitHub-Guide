# Cloning Repositories To Local

Cloning a repositpory to your `Local Folder` allows you to work on it locally prior to pushing any changes to GitHub.
It also serves as a great back up.

## Find `Local Folder`

Using the terminal, ensure you are working from the inside of `Local Folder`.
To do this, type `cd` to call the directory followed by a space and the `Local Folder`'s path.
  
```bash
cd `Path To Local Folder`
```
  
This takes us to where we need to be to clone.

## Retrieving `Clone Web URL`

Now that we are working from the inside of `Local Folder`, we can go ahead and clone the repository to your device.
First, retrieve the `Clone Web URL` by clicking `<> Code` in desired repository on GitHub.
  
> Insert Image
  
Then, find the green `<> Code` that has a drop down arrow and click it.
  
> Insert Image
  
Under `HTTPS`, copy the `Clone Web URL`.
  
> Insert Image
  
That URL is what is used to clone the repository to desired location on your device.

## Cloning To `Local Folder`

Returning to the terminal that is working inside the `Local Folder`, type the following:
  
```bash
git clone "`Clone Web URL`"
```
