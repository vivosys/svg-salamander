1. git svn remote (add to .git/config):

    [svn-remote "svn"]
	url = https://svn.java.net/svn/svgsalamander~svn
        fetch = trunk:refs/remotes/trunk
        branches = branches/*:refs/remotes/*
        tags = tags/*:refs/remotes/tags/*


