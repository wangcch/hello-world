# hello-world
<hr>
## how to use git (basis)

* Run the configure user name and email for the first time

		git config --global user.name "wangcch"<br>
		git config --global user.email "ci713@qq.com"
* Initialize the warehouse

		git init

* Add remote warehouse

		git remote add origin http://...

* Access to the warehuse content updates

		git pull origin master

* Check the local modification and not submitted file

		git status

* Will submit the file information to add to the index in the library

		git add test.txt
		git add *
* Fill in the submission instructions
		
		git commit -m "..."
* Update warehouse content
		
		git push origin master