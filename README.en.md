# Türkçe için [buraya](README.md) tıklayın.

If you accidentally deleted the 'file' named web.itu.edu.tr in your SSH server you cannot view your website.

In order to solve this issue follow the steps given below.

Connect to your SSH server either with terminal or your choice of SSH client. Find the console which lets you reach the terminal on the server.

Replace the [ituUserName] with your ITU username. Example: altinpinar18

1. In order to connect to your SSH server via terminal write the following code then enter your ITU password.
```shell
ssh -p 22 [ituUserName]@ssh.itu.edu.tr
```

2. For cleaning your attempts to bring your webpage. Be careful to __NOT put / at the end of the code__.
```shell
rm -r web.itu.edu.tr
```

3. 
```shell
ln -s ../../web.itu.edu.tr/[ituUserName] web.itu.edu.tr
```
