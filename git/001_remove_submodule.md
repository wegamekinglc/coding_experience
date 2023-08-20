Link: https://stackoverflow.com/questions/1260748/how-do-i-remove-a-submodule

* Run git rm <path-to-submodule>, and commit.
* manually delete the submodule's directory in .git/modules/, and remove the submodule's entry in the file .git/config