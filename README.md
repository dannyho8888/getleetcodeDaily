## getleetcodeDaily
This script is built for opening the leetcode daily question url on your chrome browser by the terminal command

## Getting start
Download the file and enter the below command in your terminal (please change the path to your own path). It will open the leetcode daily question on chrome browser.
```sh
  python3 ~/yourOwnPath/getDaily.py
``` 
then go your .zshrc and alias the above command with "leetcode"

```sh
  nano ~/.zshrc 

```
or whatever shell rc file you're using.

Then paste the below command inside the .zshrc file
```sh
  alias leetcode="python3 ~/yourOwnPath/getDaily.py"
```
Finally use source command to activate the .zshrc file
```sh
  source ./zshrc
```

Reopen the terminal and you're already to go
 
If you're not using chrome as your default browser,Please change the command variable to your default browser

```command = "open -a 'Google Chrome'"``` to  ```command = "open -a 'Safari'"```
