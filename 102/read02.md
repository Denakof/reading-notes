

# git
![img](https://www.codematters.online/wp-content/uploads/2019/09/Git-Logo-2Color.png)
# Seeing Your Remotes
### By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

### By using git remote -v, you can view all the remote URLs next to their corresponding short names.

###### $ _***cd example***_

###### $ _***git remote***_

![img2](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f4/Git_session.svg/1200px-Git_session.svg.png)




###### **remote1 https://github.com/remote1/example (fetch)**

###### **remote1 https://github.com/remote1/example (push)**

###### **remote2 https://github.com/remote2/example (fetch)**

###### **remote2 https://github.com/remote2/example (push)**

###### **remote3 https://github.com/remote3/example (fetch**)

###### **remote3 https://github.com/remote3/example (push)**

# Adding Remotes
### To create a new remote Git repository with a short name, use the following format:

#### git remote add shortname url
Example:

 ###### $ git remote

origin

$ git remote add


###### **js https://github.com/janesmith/project1**

###### _***$ git remote -v***_

###### **origin https://github.com/johndoe/project1 (fetch)**

###### **origin https://github.com/johndoe/project1 (push**)

###### **js     https://github.com/janesmith/project1 (fetch)**

###### **js     https://github.com/janesmith/project1 (push)**


