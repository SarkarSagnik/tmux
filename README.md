# A basic “ tmux.conf “ file.

Prerequisites: Install tmux plugin manager from the below link

```https://github.com/tmux-plugins/tpm#key-bindings```

<br/>
<br/>

### Procedure 🔗

After you have followed the steps and installed tmux-plugin manager successfully, you can now make changes to your ```“tmux.conf”``` file.
<br/>


Step1. Open your ```~/.tmux.conf``` file in a text editor: <br/> 
<br/>
```nvim ~/.tmux.conf```

<br/>

Step2. Copy the tmux.conf code from the repository and paste it into your tmux.conf file & exit your editor.

<br/>

Step3. If you are in tmux already(prefered), refresh and apply the script using: <br/>
<br/>
```tmux source-file ~/.tmux.conf```

<br/>


Step4. This way your default tmux keybinding of ``` ‘Ctrl+b’ ```changes to ``` ‘Ctrl+<spacebar>’ ```, now open up the ```tmux.conf``` file again.<br/>

Step5. Now press ``` Ctrl+<spacebar> (leave the keys) + I ``` to install all the plugins into your tmux and now you are ready.

<br/>
<br/>
<br/>
<br/>

NOTE: Your ```leader```  keybinding is now:  ```Ctrl+<spacebar>``` 

<br/>
<br/>
<br/>

### Future Modifications 🔗

You can add all your future modifications to the ```tmux.conf```  file, and install it using  ```<leader> + I``` 
