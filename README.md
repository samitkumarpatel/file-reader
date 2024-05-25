# file-reader

It is just a folder which has all the submodule (child repo) details to work for file-reader application.

I have adopted this approach just to apply the good practice between `mono repo` Vs `multi repo`.

If you want to know, Click on this link: [What is git submodule](https://www.freecodecamp.org/news/how-to-use-git-submodules/)

To work on this repo

- Clone this repo it in a directory
```sh
  git clone .....
```
- Initialize the submodule

```sh
git submodule init
```

- Fetch the submodule
```sh
git submodule update
```

- If there is a Chand/ update in the submodule , you can pull the latest by using the same `git submodule update` command
