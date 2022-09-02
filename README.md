# How to Create your First go lang Package
In this project, we will create a go-lang package which is a very simple package.
**Step 1:- ** we will create a new folder which will be of the same name as the package 
```
mkdir calculator
```
**Step 2:- ** Now we create the mod.go file 
```
go mod init github.com/<username>/calculator
```
> You don't have to create the repo know we will do that later.
**Step 3:- ** Now We will create a `main.go` file and paste this code or the code that you want to make a package.

**Step 4:- **  Now is the time we will create the repo that we used at the time of creating the mod file so Go to your GitHub account and then create a new repo with the name `calculator`

**Step 5:- ** Now we will push the code to the GitHub repo that we just create.
```
git init

git remote add origin <repo URL link that we just got>

git add .

git commit -m "first commit"

git push --set-upstream origin main
```
**Step 6:- ** Now we will also add the `Tag` 
```
git tag "v1.0.0"

git push --tags
```
Now you Have your Go lang package that you can use in your every other Project whenever you want.
# How to Use this Go Lang Package
**Step 1:- ** Open Terminal in your Project folder 
```
go get -u github.com/souravsk/calculator
```
**Step 2:- ** Now you can import this GitHub repo into you go lang file 
```
package main

import (
  "github.com/souravsk/calculator"
)

func main(){
  calculator.calu
}
```
That's it Your Go lang Package 
