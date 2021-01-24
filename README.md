# Cwebpthis
## A cwebp script

Well first of all you have to download the cwebp compressor tool according to your machine(Windows|Linux) from [here][1].
(note that the new versions of the files are descendants) 

Now after extracting the .zip file you have to set the bin folder to variable path.
In order to do this type in your windows search `edit the system environment variables`
Then click on `Environment Variables` in the bottom-right corner, and go to `path - new `
Your new path line should look like this : 
`Path:: C:\Folder_Where_You've_Extracted_.Zip\libwebp\bin`

Open cmd to check if you have done right till now.

 - `cmd> cwebp -version`

[![cwebp- version][2]][2]

Be sure to have python installed on your machine

- `cmd> python --version`

[![python --version][3]][3]

Now go to your python's script folder and copy the .exe so you can run the program everywhere on your pc

After you've done this just go to any directory, type cmd in your file explorer and then write `cwebpthis` 

It should look like this :

[![executed program][4]][4]
   
  [1]: https://storage.googleapis.com/downloads.webmproject.org/releases/webp/index.html
  [2]: https://i.stack.imgur.com/YoL6I.png
  [3]: https://i.stack.imgur.com/etcwW.png
  [4]: https://telegra.ph/file/066582f7f4d8db8c3f08a.png
