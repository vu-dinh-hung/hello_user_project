# Installation instructions for this cute hello_user script

1. Add execute permission to the script:

```
chmod +x ./hello_user
```

2. Copy the `hello_user` script to `$HOME/bin`

```
mkdir ~/bin

cp ./hello_user $HOME/bin
```

3. Add `$HOME/bin` to your `$PATH`

```
echo PATH="$PATH:$HOME/bin" >> ~/.zshrc
```

4. Profit! Run `hello_user` anywhere!

5. Bonus: Run `hello_user` every time you log into a new shell:

```
echo hello_user >> ~/.zshrc
```
