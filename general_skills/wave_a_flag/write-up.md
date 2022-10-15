# PicoCTF Write-Up for General Skills challenges:

### Wave A Flag:

For this challenge, we are only provided with one file <em>warm</em>. The file seems like a binary file so lets see if we can make it executable with the following command:

<code>chmod +x warm</code>

Once the binary is coverted to an executable, we can execute the file using

<code>./warm</code>

We get the following output:

```
Hello user! Pass me a -h to learn what I can do!
```

So, let's use the help flag in terminal:

<code>./warm -h</code>

The resulting output contains the flag:

```
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_d6969390}
```
