# ZoomPhoneTemplates

notes and things i've learned about Zoom Phone templates

When using the Yealink phones on Zoom, the directory lookup should be LDP but that doesn't get consistantly enabled. for example, the main "directory" button on a t58a will default to local directory and isn't searchign ldap. so in the t58a cfg, we're setting the second softkey to the ldap app and naming it "Directory" so that it works the same as that person icon on the left. I'm also removing the Menu soft key because the app is still in the drop down and the left side app area.

the Recorder, File Manager and someitmes the Gallery seem to have different app names so i haven't figured out how to hide them yet.

ont eh cp960, you cna't mess witht eh softkey 2 like i did on the t58a so thats why i have a seperate cfg file. otherwise the t58a file woould work just fine on a cp960.

i'm testing the t58a file on a t57 as well, i think it'll work too
